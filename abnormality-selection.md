---
title: Abnormality Selection
description: How abnormalities are chosen and presented before each day
published: true
date: 2026-07-15T20:20:49.685Z
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

On days with no data (for example, Day 46-49), three abnormalities are chosen from all non-tool abnormalities (except Yang) not currently in the facility. This does not use risk level. See [`CreatureSelectUI::GetCreatureList(bool)`](/api/Global/Abnormality-Extraction/CreatureSelectUI#getcreaturelistbool) for details.

### Code Structure



## Initialization
Everything starts with the script [`CreatureSelectUI`](/api/Global/Abnormality-Extraction/CreatureSelectUI) and continues in the `CreatureGenerate` namespace. This scene is always loaded before the story after every day, regardless of if there is an extraction today.

When the scene is first loaded, [`CreatureSelectUI::Awake`](/api/Global/Abnormality-Extraction/CreatureSelectUI#awake) and [`CreatureSelectUI::Start`](/api/Global/Abnormality-Extraction/CreatureSelectUI#start) are called. These mainly reset flags and prepare the class for choosing the abnormality.

Once the class is prepared, [`CreatureSelectUI::Init`](/api/Global/Abnormality-Extraction/CreatureSelectUI#init) does some final important things: it enables or disables the re-extraction button, checks if there should be an extraction today (see [`CreatureSelectUI::CheckUIActivateCondition`](/api/Global/Abnormality-Extraction/CreatureSelectUI#checkuiactivatecondition) for details), and enables the [doors](/api/CreatureSelect/CreatureSelectUnit). It then moves on to actually selecting the abnormalities for the day, as described above.

