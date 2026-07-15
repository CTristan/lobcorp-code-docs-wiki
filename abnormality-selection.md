---
title: Abnormality Selection
description: How abnormalities are chosen and presented before each day
published: true
date: 2026-07-15T23:26:37.781Z
tags: 
editor: markdown
dateCreated: 2026-07-14T21:52:51.447Z
---

# Abnormality Extraction


The abnormality extraction screen ([`CreatureSelectUI`](/api/Global/Abnormality-Extraction/CreatureSelectUI)) is the screen which allows the player to pick an abnormality before most days. This page describes how this screen works and how abnormalities are selected.

<img 
    style="display: block;
           margin-left: auto;
           margin-right: auto;
           width: 80%;"
    src="/abnormality-extraction/creatureselectui_diagram_2.svg" 
    alt="CreatureSelectUI Diagram 2">
</img>

## Abnormality Selection Overview
There are three doors. Each of these selects an abnormality in order, then the selected abnormalities are shuffled before being presented to the player. At the end of selection, if there is only one abnormality available for the day, only one door is shown.

Abnormalities are selected by first choosing a random risk level, then choosing a random available abnormality of that risk level. Each door has a different probabilities depending on the day. For example, on Day 2, the first door has a `50%` chance to choose a `ZAYIN` abnormality and a `50%` chance to choose a `TETH` abnormality. These are read from `Assets/Resources/xml/CreatureGenInfo.txt`. A table of the probabilities for each day can be found at the [Day Info V3 sheet](https://docs.google.com/spreadsheets/d/1ZCfaw51PIZk93opHr8hkLNVxPvHHU8_xyq7IRV0R2uk/edit?gid=0#gid=0). Note that there is odd behavior on certain days, particularly Day 15, Day 30, and Day 40; see [`CreatureGenerateInfoManager::CalculateDay`](/api/CreatureGenerate/CreatureGenerateInfoManager#calculateday) for details.

Some days have instructions for which abnormalities are exclusively allowed (`ONLY`) or disallowed (`REMOVE`). The only day that exclusively allows certain abnormalities is Day 1, on which only [One Sin and Hundreds of Good Deeds](/api/Global/Abnormalities/One-Sin-and-Thousands-of-Good-Deeds/OneBadManyGood) can be selected. Some other days have abnormalities removed; for example, [Army in Black](/api/Global/Abnormalities/Army-in-Black/PinkCorps) can never be selected on Day 2, even though its risk level is technically `ZAYIN`.

Every fourth extraction is a tool abnormality. See [`CreatureSelectUI::CheckKitGeneration`](/api/Global/Abnormality-Extraction/CreatureSelectUI#checkkitgeneration) for details on how this is determined. These extractions can only select tool abnormalities (except Yang), but otherwise follow the same selection behaviour as normal abnormalities. On every day except Day 49, if [Yin](/api/Global/Abnormalities/Yin-and-Yang/Yin/Yin) is in the facility but [Yang](/api/Global/Abnormalities/Yin-and-Yang/Yang/Yang) is not yet, the only tool abnormality available is Yang. See [`CreatureSelectUI::CheckYinAndYang`](/api/Global/Abnormality-Extraction/CreatureSelectUI#checkyinandyang) for more details.

The player is never presented with an abnormality already in their facility or two of the same abnormality at the same time. However, due to an error^[where?]^, the player can receive two of the same abnormality in a row on days with two extractions.

On days with no data for probabilities (most notably Day 46-49), three abnormalities are chosen from all non-tool abnormalities (except Yang) not currently in the facility. This does not use risk level. See [`CreatureSelectUI::GetCreatureList(bool)`](/api/Global/Abnormality-Extraction/CreatureSelectUI#getcreaturelistbool) for details.


## From Initialization

### Before Extraction
Before the extraction scene is loaded^[when?]^, [`CreatureGenerateInfoManager`](/api/CreatureGenerate/CreatureGenerateInfoManager) is initialized.

When [`CreatureGenerateInfoManager`](/api/CreatureGenerate/CreatureGenerateInfoManager) is initialized, it creates a list of all abnormalities by risk level and stores it in [`CreatureGenerateInfoManager::CreatureList`](/api/CreatureGenerate/CreatureGenerateInfoManager#creaturelist). Then, it constructs a new list which matches each risk level to an [`ActivateStateList`](/api/CreatureGenerate/ActivateStateList). Each `ActivateStateList` contains a list of [`ActivateStateModels`](/api/CreatureGenerate/ActivateStateModel), which holds an abnormality ID and some flags relating to how it should be generated.

Each `ActivateStateModel` stores whether an abnormality is:
- currently in the facility,
- removed from the current day's pool, and
- a tool abnormality.

Each `ActivateStateList` represents all abnormalities of some risk level, and maintains a list of the "usable" abnormalities (those which can be selected).


<table border=1
       style="display: block;
           margin-left: auto;
           margin-right: auto;
           width: 80%;">
  <tr>
    <td colspan=5>
      <b> <center> activateStateDic (ActivateStateLists) </center> </b>
    </td>
  </tr>
  <tr>
    <td>
      <b> <center> ZAYIN </center> </b>
    </td>
    <td>
      <b> <center> TETH </center> </b>
    </td>
    <td>
      <b> <center> HE </center> </b>
    </td>
    <td>
      <b> <center> WAW </center> </b>
    </td>
    <td>
      <b> <center> ALEPH </center> </b>
    </td>
  </tr>
  <tr>
    <td>
      <table style="width: 100%; margin-left: auto; margin-right: auto;">
        <tr>
          <td colspan=3>
            <b>ActivateStateModel</b>
          </td>
        </tr>
        <tr>
          <td colspan=3>
            One Sin and Hundreds of Good Deeds
          </td>
        </tr>
        <tr>
          <td>
            In facility?
          </td>
          <td>
            True
          </td>
        </tr>
        <tr>
          <td>
            Removed today?
          </td>
          <td>
            False
          </td>
        </tr>
        <tr>
          <td>
            Tool abnormality?
          </td>
          <td>
            False
          </td>
        </tr>
      </table>
      <table style="width: 100%; margin-left: auto; margin-right: auto;">
        <tr>
          <td colspan=3>
            <b>ActivateStateModel</b>
          </td>
        </tr>
        <tr>
          <td colspan=3>
            Fairy Festival
          </td>
        </tr>
        <tr>
          <td>
            In facility?
          </td>
          <td>
            False
          </td>
        </tr>
        <tr>
          <td>
            Removed today?
          </td>
          <td>
            False
          </td>
        </tr>
        <tr>
          <td>
            Tool abnormality?
          </td>
          <td>
            False
          </td>
        </tr>
      </table>
      <center> ⋮ </center>
    </td>
    <td>
      <center> ⋮ </center>
    </td>
    <td>
      <center> ⋮ </center>
    </td>
    <td>
      <center> ⋮ </center>
    </td>
    <td>
      <center> ⋮ </center>
    </td>
  </tr>
</table>

Finally, if it has not been loaded previously, the file `Assets/Resources/xml/CreatureGenInfo.txt` is loaded into [`CreatureGenerateInfoManager::dayGenInfoDic`](/api/CreatureGenerate/CreatureGenerateInfoManager#dayGenInfoDic). This stores the probabilities for each risk level and exceptions (the `ONLY` and `REMOVE` commands) for each day. The data for each day is stored as a [`CreatureGenerateModel`](/api/CreatureGenerate/CreatureGenerateModel), which contains the day it belongs to and three [`CreatureGenerateDoors`](/api/CreatureGenerate/CreatureGenerateDoor) with their respective probabilities. See [`CreatureGenerateInfoManager::LoadStaticData`](/api/CreatureGenerate/CreatureGenerateInfoManager#loadstaticdata) for more information.

Note that there is no data in this table for every fifth day or any day after Day 45, even if an abnormality can be selected on that day. Under normal conditions, if a fifth day has an extraction (e.g. Day 15, Day 30, and Day 40), it will use the data for the next day. Every day after Day 45 instead chooses from all non-tool abnormalities not currently in the facility, and does not use risk level.

### Extraction Scene Start
Everything starts with the script [`CreatureSelectUI`](/api/Global/Abnormality-Extraction/CreatureSelectUI) and continues into the `CreatureGenerate` namespace. This UI script is always loaded before the story after every day, regardless of whether there is an extraction today.

When the scene is first loaded, [`CreatureSelectUI::Awake`](/api/Global/Abnormality-Extraction/CreatureSelectUI#awake) and [`CreatureSelectUI::Start`](/api/Global/Abnormality-Extraction/CreatureSelectUI#start) are called. These mainly reset flags and prepare the class for choosing the abnormality.

Once the class is prepared, [`CreatureSelectUI::Init`](/api/Global/Abnormality-Extraction/CreatureSelectUI#init) does some final important things: it enables or disables the re-extraction button, checks if there should be an extraction today (see [`CreatureSelectUI::CheckUIActivateCondition`](/api/Global/Abnormality-Extraction/CreatureSelectUI#checkuiactivatecondition) for details), and enables the [doors](/api/CreatureSelect/CreatureSelectUnit). It then moves on to actually selecting the abnormalities for the day.

### Abnormality Selection
While [`CreatureSelectUI`](/api/Global/Abnormality-Extraction/CreatureSelectUI) is initializing, it makes a call to [`CreatureSelectUI::GetCreatureList`](/api/Global/Abnormality-Extraction/CreatureSelectUI#getcreaturelist) to select three abnormalities for the day. First, [it calculates what day to use for extraction](/api/CreatureGenerate/CreatureGenerateInfoManager#calculateday), [whether or not there should be a tool abnormality on this extraction](/api/Global/Abnormality-Extraction/CreatureSelectUI#checkkitgeneration), and finally [updates `CreatureGenerateInfoManager`](/api/CreatureGenerate/CreatureGenerateInfoManager#ondaychanged) to reflect the current day and facility status. Then, it clears any pre-existing data in the doors and [gets new abnormalities for the day](/api/CreatureGenerate/CreatureGenerateInfoManager#getcreature). If the resulting list is `null` (i.e., there are no valid abnormalities for the day, or no data for today) it instead chooses from all non-tool abnormalities not currently in the facility, and does not use risk level. If there are *still* no available abnormalities, it logs the error `"Could not make Creature"` and stops.

Then, it shuffles the abnormalities and puts the shuffled list into [`CreatureSelectUI::CurrentCreatures`](/api/Global/Abnormality-Extraction/CreatureSelectUI#currentcreatures).

Finally, it [checks if Yang should be the only option today](/api/Global/Abnormality-Extraction/CreatureSelectUI#checkyinandyang).

### Presenting Doors
If there are three abnormalities in the selection, [`CreatureSelectUI::Init`](/api/Global/Abnormality-Extraction/CreatureSelectUI#init) [initializes all of them in a random order](/api/CreatureSelect/CreatureSelectUnit#initlong).

If there is only one abnormality in the selection, [`CreatureSelectUI::Init`](/api/Global/Abnormality-Extraction/CreatureSelectUI#init) will disable all doors except the middle one, and initialize that one with that abnormality.

If there are duplicate abnormalities in the selection (which should not happen normally), those doors will be disabled from right to left.

### Other Initialization Effects
[`CreatureSelectUI::Init`](/api/Global/Abnormality-Extraction/CreatureSelectUI#init) also enables the visual filter, triggers an animation to play on the UI (`UIOpen.anim`) and on each door (`Exit_Normal.anim`), starts the music, and displays the re-extraction button.

## Selecting An Abnormality
meow

## Re-Extraction
meow meow
