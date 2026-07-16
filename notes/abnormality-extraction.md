---
title: abnormality extraction - notes
description: 
published: true
date: 2026-07-16T01:17:34.382Z
tags: notes
editor: markdown
dateCreated: 2026-07-16T01:17:34.382Z
---

## Notes
```CreatureGenerateInfoManager::LoadStaticData
ON STARTUP
-Loads xml/CreatureGenInfo into dayGenInfoDic
	Each day except fifth days and days after 45
	-Contains 1, 2, or 3 doors
		-ONLY and REMOVE instructions
		-Probabilities for each risk level
        
CreatureDataLoader::Load
ON STARTUP
-loads xml/CreatureList into CreatureTypeList
    -Will come back to this, it's a lot
-loads xml/creatureStats/<abno>_stat.txt into CreatureTypeList
    -Will come back to this too, it's less but still a lot


CreatureSelectUI
--> Awake
    -If there is already an instance of this object, destroy it.
    -Make the instance this (for singleton pattern)
    -Disable the preview textbox

ENTRY POINT NORMALLY
--> Start()
	-reset tiperethRunned (used to track if this is the first or section selection today)
	-reset reExtracted (used to allow re-extracting once when that research is done)
	-reset threshold (used for preventing CheckYinAndYang recursion later)
	-load etc file if it exists with GlobalGameManager::LoadEtcFile(saveEtcFileName)
        -saveEtcFileName is `Application.persistentDataPath` + "/etc170808.dat"`
        -SaveUtil::ReadSerializableFile
            -Important for another time but reads a file into a Dictionary<string, object>
        -Try to get "waitingCreature" from the file data and if it's not queued already, queue it (PlayerModel::AddWaitingCreature)
	CreatureSelectUI::Init()

    Init
	// Initialize UI
	-Activate/deactivate the re-extraction controller as needed (including if already used)
	-CheckUIActivateCondition: checks if we need to do something today, returns a bool
		// Using the actual day (If you don't know why this clarification is needed, see CreatureGenerateInfoManager::CalculateDay later.)
		-False if we hit a keter gameover
		-False if day<0 (as a fall-back, queues BIG BIRD from a debug array)
		-False if this day never has a selection:
			-False on every fifth day, except Day 15, Day 30, and Day 40 (when two departments can be open)
			-(?!) False on every Day 52 and later
			-False on every Day 51 or later
		-False on Days 19 and 34 unless one of the current departments has open level (?)exactly 3, and so can accept a new abno today.
		-False if there's enough abnos in the queue:
			PlayerModel::IsWaitingCreatureExist
			-(? Shouldn't ever happen.) On days 21-25 and 46-50, returns true when there are at least two abnos in the queue.
			-On every other day, returns true if there is at least one abno in queue (e.g., if you maxed out a department on Days 15, 30, or 40)
		-False if we're transitioning to the true ending (gameMode == GameMode.HIDDEN)
	-If false do OnUIActionEnd and return, otherwise continue
		CreatureSelectUI::OnUIActionEnd
			-Disable this ui
			-save Etc data
			-start story
	-Reset effectRunned (flag which is set when a door is chosen to make the UI non-interactable)
	-Enable visual filter
	-Enable all door units and tell them to play the Exit animation (Exit_Normal.anim)
	-Set the animator to run "Open" (which runs UIOpen.anim)

	// Populate doors
	-GetCreatureList: Get the creatures for the day
		-Clear pre-existing data
		-CreatureGenerateInfoManager::CalculateDay: Calculate the effect day for the generation
			-Just choose the current day ALMOST ALWAYS
			-If the current day is a multiple of 5 and we're still trying, use whatever the next day is instead
			// May run if we do the abnormality storage bug
			-(?!) Otherwise, if there are more abnormalities than there are supposed to be, use whatever the next day is
		-CheckKitGeneration: sets a flag indicating tool or no tool
            -For days < 21, set flag to true when day is 4 modulo 5 (every fourth of five days)
            -For 21 to 26, set it to false unless this is the second extraction on days 21 and 23
            -For days 26 to 50, set flag to true when day is 4 modulo 5 (every fourth of five days)
            -If we set the flag to true but there are no more tool abnormalities, set it to false // shouldn't ever run
		-CreatureGenerateInfoManager::OnDayChanged:
			-Update the ActivateStateLists (which stores abnos of each risk level and whether they can be chosen)
				DayUpdate
				-For each ActivateStateModel in this thing's list:
					-Flag as not removed
					-If this abno is not already flagged as used, and it's either in the facility or queued to be added to facility, mark it as used
				CheckUsableState
				-Set the Usable abnormalities to those which are:
					-not queued, used, or removed
					-are tools if today is a tool day
						-but aren't yang unless yin is present
					-are not non-tools if today isn't a tool day
						-but aren't PD unless WN isn't in the facility
					-are not WN
		-Clear the current abnos
		-IF setEmpty is true, initialize slots to abno -1L
		-CreatureGenerateInfoManager::GetCreature(): Get the list of 3 random abnos
			-Get today's probabilities for each door from dayGenInfoDic using the generation day (see CreatureGenerateInfoManager::CalculateDay above for when this is not the same as the actual day)
			-If there is no data for the day, return a null list. Otherwise continue
			-CreatureGenerateModel::SetCreature():
				-Execute actions on each door
				-Set all doors to have an abno with CreatureGenerateDoor::SetCreature:
					CheckProb()
						-Flags all enabled risk levels as being enabled
					-Gets a random risk level
						-Calculates the total probability based on the enabled risk levels
						-Chooses a random float between 0 and the total
						-Chooses the lowest risk level that meets or exceeds that random number
					-Gets the ActivateStateList with that risk level ActivateStateList::GetList(int)
                        -CreatureGenerateInfoManager::GetCreatureState((RiskLevel)i, out list)
                            -Gets the list from activateStateDic with that risk level
					-Picks a random abno from that list and make it this door's abno ActivateStatemodel::GetRandomCreature
                        -If this risk level is disabled return null
                        -Return a random entry from `Usable`
					-Remove that abno from that ActivateStateList
					
				-Add all doors with non-null abnos
			-If the error ProbCheckExeption is thrown (?!which it can't be, nothing throws it), try again with day -2 as a backup
			-Return the list of the abnos in the doors
		-If the list is null:
			-panic and logerror "null removed +  " + (day % 5 == 3)
			-Use the list of all abnormalities except tools
		-If the list is empty:
			-panic and logerror "Could not make Creature"


		// This is for days without probabilities
		-? Make a list (list2) of all non-tool abnormalities and remove all creatures in the facility, with special treatment of PD/WN
		-make a new list (list3)
		-Three times:
			-Stop if we ran out of candidates and already found at least one

			// This conditional can't run
			-? If list and list 3 are empty, get all abnos in the facility, and remove them from list2... again. With special treatment of PD/WN. Then set list to list2
			
			// Shuffle?
			-get a random abno from the list
			-add that abno to list 3
			-remove that abno from the list
		-Add the abnos in list3 to CurrentCreatures
		-CheckYinAndYang()
			-Increment a threshold and if its at least 3 return (to prevent infinite recursion, for after day 48 yin-present, yang-absent, "not enough abnos" behaviour)
			-Check if Yin and/or Yang are present
			-If both are present, or Yin is absent, return (nothing special happens)
			-If Yin is present but Yang is not:
			-? If the day is at least 48
				(?!) If there are 0 or 1 abnos in the list:
				// Try again??? I Guess???
				-(?!) go back to GetCreatureList with setEmpty false, and otherwise just remove Yin from the queue.
				If there are at least 2 abnos:
				-(?!) Remove Yin from the queue (but it's already in the facility??)

			// Make Yang the only choice if all the right conditions are met
			-If the day is 47 or earlier, today is a tool day, and Yang isn't queued:
				-Clear the current abnos
				-Add back Yang
               

	// Update doors to reflect the abnormalities we found
	-If there's only one abno, disable all doors except the middle one, and initialize it with CreatureSelectUnit::Init:
        -If re-extraction is happening, save the current id and return (to be used at the end of the re-extract animation)
        -If the abno is PD and has already advented, set id to WN
        -If id is -1, CreatureSelectUnit::SetDisabled:
            -disable this game object and quit
        -Enable this game object
        -Reset the TransSelected flag, used to track whether we've already selected an abno
        -Store the data of this abno
        -CreatureSelectUnit::SetEnabled (empty)
        -Set the text to the name with GetName:
            -If there's no abno data, return empty string
            -If there's any observation info for this abno, return CreatureModel::GetUnitName
            -Otherwise return the code id
        -Start the DullTimer (shaky anomation) and set the controller to speed .2
        -Disable all sprites in the frame
        -Enable/disable the backer/normal abno frame or vice versa

	// does not run normally!!!
	-If there are no abnos, get all non-tool abnos that are not already in the facility and choose 3 at random to initialize (?! no safety for yin/yang/pd/wn) without replacement. Uses CreatureSelectUnit::Init as above

	// Shuffle again from the list...
	-If there are 2 or 3 abnos:
		-Populate each unit with a random choice of the 3(? assumes not 2) abnos and initialize them with CreatureSelectUnit::Init as above

	// Finalize
	-Play the background music
	-? If there's a duplicate abno, disable the one in the later door. // shouldn't ever run
	-Show or Hide the re-extraction controller

FixedUpdate
    -If the music fadeout effect has started, change the volume
    -If the timer has run out, mute the music

OnUIActionEnd
	-Disable this ui
	-save Etc data
	-start story
    
CheckCreatureExisting
    -If id is PD return true if either PD or WN is in the facility
    -Otherwise return true if the abno with the given id is in the facility

HOVERING OVER DOOR
-->CreatureSelectUnit::OnPointerEnter
    -If the UI is not interactable or doing re-extraction, do nothing. Otherwise, continue
    -Change the animation speed of DullAnimCTRL (speed up the idle shaking when hovered over?)
    -CreatureSelectUnit::OnEnter:
        -Set the transition animation to "Enter"
        -CreatureSelectUI::OnEnterUnit(CreatureSelectUnit unit)
            -If any doors are TransSelected, return immediately (already selecting an abno)
            -Show Block (the grey filter over everything except the selected box)
            -Show and populate the preview text box with the abno opening text of the selected door
            -Adjust all doors' transforms (reparent the selected one to Index_Select and all others to Index_Normal
    -Enable all sprites for this door (***may need to be verified, enables every Image in Frame)
    -Set the pointer flag (used to speed up DullFreq, which presumably controls idle spinning)

-->CreatureSelectUnit::OnPointerExit
    -If the UI is not interactable or doing re-extraction, do nothing. Otherwise continue
    -Change the animation speed of DullAnimCTRL (shaking slows after not being hovered over)
    -CreatureSelectUnit::OnExit:
        -If not TransSelected, set the transition animation trigger to "Exit" (already selecting an abno)
        -Disable all sprites (***may need to be verified, disables every Image in Frame)
        -CreatureSelectUI::OnExitUnit(this):
            -Hide Block (the grey filter over everything except the selected box)
            -Hide the preview text box
            -If none of the doors have been selected yet (all have TransSelected false), reparent their transform to Index_Normal
    -Change the pointer flag (used to change the speed of "DullFreq", which presumably controls how fast they idly spin)       
    
-->CreatureSelectUnit::OnPointerClick
    -If the UI is not interactable or doing re-extraction, do nothing. Otherwise continue
    -Set the TransSelected flag (we have selected an abno)
    -CreatureSelectUI::OnClickUnit(this)
        -If the effectRunned flag is false, set it to true (indicating a door has been selected)
        -Queue the selected abno (or PD if it's WN)
        -CreatureGenerateInfoManager::OnUsed(abno id)
            -Get the data for this abno with CreatureTypeList::GetData(abno id):
                -Iterate over the CreatureTypeInfo list until you find this abno, then return it
            -Find whichever ActivateStateList this belongs to and mark it as used with ActivateStateList::OnUsed(id):
                -Find this abno and set isUsed to true
        -Set the UI animation to Close
            -This contains a callback to CreatureSelectUI::OnCalled
                -If today is 21-24 or 46-50 and we haven't done the second extraction yet:
                    -Set tipherethRunned, the flag that tracks if we've gotten to the second extraction
                    -Set re-extraction to false (we can re-extract again the second time)
                    -CreatureSelectUI::Init
                -Otherwise
                    -Start the animation GlobalClose
                        -This contains a callback to OnCalled(0)
                            -CreatureSelectUI::OnUIActionEnd
                    -Set story music fade in (StoryBgm::SetFadeIn(2f))
                    -Move to the story
        -CreatureSelectUnit::FadeoutEffect
            -Start a timer to fade out the music
    -Start the transition animation OnClick

(ReExtract -> Button)'s On Click
-->CreatureSelectUI::OnClickReExtract
    -Return immediately if the re-extract research hasn't been completed
    -CreatureSelectUI::GetCreatureList with setEmpty false
    -Call CreatureSelectUnit::OnChange for each door:
        -Set the isChanging flag
        -Start the transition animation Change (CreatureChange.anim)
            -On finish this calls OnChangeCompleted
                -Reset isChanging
                -CreatureSelectUnit::LateInit
                    -If the id is valid (not -1) re-run Init with the saved id
                    -Reset the saved id to -1
    -If we only found 1 abno, disable two of the doors to reflect that
    -If we found none, get all non-tools, remove all abnos in the facility, and choose 3 at random without replacement
    -If we found 2 or 3, (?!) assume we found 3 and shuffle them
    -If there are duplicates disable the duplicate door
    -If we haven't re-extracted (?) enable the re-extraction controller
    
    
CreatureGenerateInfoManager::Init
    -CreatureGenerateInfoManager::InitCreatureList:
        -Clear the creature list
        -Get a list of all types of abnormalities from `CreatureTypeList::GetList`
            -Returns `_list` as an array (loaded by `CreatureDataLoader`)
        -For each abnormality:
            -If `CreatureList` doesn't have its risk level, add a new list with that risk level `CreatureTypeInfo::GetRiskLevel`:
                -`CreatureTypeInfo::GetRiskLevelStringToEnum(riskLevelForce)`
                    -Converts a string to the risk level with `RiskLevel.ZAYIN` as the default.
                -Note that riskLevelForce is a get-only property with a WEIRD definition:
                    -Get the `CreatureDataList` `riskLevel` from the `dataTable`
                    -`riskLevel.GetDataTemp`:
                        -Iterates over `CreatureData` in the list and returns the first non-null value
                    -If null then return `"Unknown"`
                    -Return that data casted to string...
            -Add this abnormality to the list of its risk level
    -Clear `activateStateDic`
    -Set the `_isInitiated` flag
    -Get all abnormalities with `CreatureGenerateInfo::GetAll`
        -ew!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
        -Make a list of all abnormalities (excluding backer abnormalities if `GlobalGameManager::dlcCreatureOn` is false)
            -The list of backer abnormalities is hard-coded as `creditCreatures`
            -The list of all abnormalities is hard-coded as `all`
        -If `removeTool` is set, removes all tools from the list
            -The list of tool abnormalities is hard-coded as `kitCreature`
        -Removes Apocalypse Bird (`100038L`) from the list
        -Returns the list as an array
    -For each abnormality:
        -Get its data with `CreatureTypeList::GetData(id)`
            -Returns the `CreatureTypeInfo` in the list with id `id`, or else returns `null`
        -Get its risk level `CreatureTypeInfo::GetRiskLevel`
            -See above
        -Check if its used `CreatureGenerateInfoManager::IsUsedCreature`
            -? Returns `CreatureManager::IsCreatureActivated`
                -Returns true if the `creatureList` has the same id as `metaId`... Hm.
        -Make a new `ActivateStateModel` for this abnormality
        -Store it in an `ActivateStateList` if it exists and `continue`
        -Otherwise make a new one for this risk level and add it to that, then add the list to `activateStateDic`
    -CheckCreatureUseState:
        -For each `ActivateStateList`:
            DayUpdate
				-For each ActivateStateModel in this thing's list:
					-Flag as not removed
					-If this abno is not already flagged as used, and it's either in the facility or queued to be added to facility, mark it as used
            CheckUsableState
            -Set the Usable abnormalities to those which are:
                -not queued, used, or removed
                -are tools if today is a tool day
                    -but aren't yang unless yin is present
                -are not non-tools if today isn't a tool day
                    -but aren't PD unless WN isn't in the facility
                -are not WN
    -If the day is loaded, log that, then `Print`:
        -Do nothing
    -Otherwise log the error `"Load Fail"````