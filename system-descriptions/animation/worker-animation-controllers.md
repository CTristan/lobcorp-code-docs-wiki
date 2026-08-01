---
title: Worker Animation Controllers
description: List of animation controllers used by agents and clerks
published: true
date: 2026-08-01T23:02:45.762Z
tags: 
editor: markdown
dateCreated: 2026-08-01T23:02:45.762Z
---

# Worker Animation Controllers

Agents and clerks, by default, use the `skeleton_Controller1.controller` animation controller (at `Assets/AnimatorController/skeleton_Controller1.controller`). However, in a number of different circumstances, this animator will be changed from the default. This page hosts a complete list of alternative animator controllers by the method used to change it.


## Default Animator
The methods `WorkerUnit::ChangeAnimatorDefault()` and  `WorkerAnimatorChanger::ChangeAnimator()` reset the worker to use their default animator controller. When a worker has a `SPECIAL` type weapon,  `WorkerUnit::UpdateAnimatorChange` can also do this.

## Special Weapon Animators
When a worker has a `SPECIAL` type weapon, `WorkerUnit::UpdateAnimatorChange` can change the animator to use the special weapon animator specified in `xml/Equipment/Equipment`.
#### List
- HelperWeapon
- GreedWeapon
- LongBirdWeapon
- SilentOrchestraWeapon
- NothingWeapon
- SamuraiWeapon
- FetusWeapon
- KnightOfDespairWeapon
- DangoCreatureWeapon
- FreischutzWeapon
- BlackSwanWeapon
- ButterflyWeapon
- CensoredWeapon
- PorccuWeapon
- BlueStarWeapon
- RedHoodWeapon
- BigBadWolfWeapon
- SakuraWeapon
- BakuWeapon
- MagicalGirlWeapon
- YinWeapon
- FireBirdWeapon
- DeathAngelWeapon
- LookAtMeWeapon
- FengYunWeapon
- SharkWeapon
- PianoWeapon
- SlimeGirlWeapon
- PinkCorpsWeapon

## Tool Abnormality Use
The method `WorkerUnit::ChangeAnimatorForcely(string, bool, bool)` is used only by abnormalities which specify the `workAnim` animation controller in their data (`Resources/xml/creaturestats/{abno}_stat.txt`). The only abnormalities that have these present are the tool abnormalities.
#### List
(without `uniqueFace`)
- BigTreeSapUse
- KitEquipCreatureUse (ResetMirror, YouMustHappy, Shelter, default if not specified)

(with `uniqueFace` (always the string `"unique"`))
- TheresiaUse (HellTrain, IronMaiden, OtherWorldPortrait, ProphecyOfSkin, Theresia; see also `WorkerAnimatorChanger::ChangeAnimatorWithUniqueFace`)
- MeatIdolUse (MeatIdol, see also `WorkerAnimatorChanger::ChangeAnimatorWithUniqueFace`)
- PromiseAndFaithUse
- ReverseClockUse

## AgentModel::OnDie and OfficerModel::OnDie (deadSceneName)
The methods `AgentModel::OnDie` and `OfficerModel::OnDie` use the animator controller specified by `deadSceneName` when a worker dies.

This value can be changed by the following methods.
### SetSpecialDeadScene(string)
#### List
- LongBirdAgentDead (by LongBird)
- AlriuneAgentDead
- OrchestraAgentDead
- dmg.specialDeadSceneName (see `WorkerModel::TakeDamageWithoutEffect` and `WorkerModel::TakeDamage` later)
### SetSpecialDeadScene(string, bool)
#### List
- BigBirdAgentDead
### SetSpecialDeadScene(string, bool, bool)
#### List
- BlueStarAgentDead
- LongBirdAgentDead (`BossBird`)
- ButterflyAgentDead
- FairyAgentDead
- KnightOfDespairDead
- RedShoesAgentDead
- SnowWhiteAgentDead
- AlriuneAgentDead

## WorkerAnimatorChanger::ChangeAnimator(string)
The method `WorkerAnimatorChanger::ChangeAnimator(string)` changes the animator to the animation controller with the given name.
#### List
- SpiderMomAgentDead
- ArmorCreatureDead
- HealthBraceletDead
- OtherWorldPortraitDead
- MeatIdolUse (by OneGoodManyBad or work type 6; see also Tool Abnormality Use)
- WorkerUnit::ChangeAnimatorForcely(string, bool, bool) (from UseSkill.InitUseSkillAction, see Tool Abnormality use)

## WorkerAnimatorChanger::ChangeAnimator(string, bool)
The method `WorkerAnimatorChanger::ChangeAnimator(string, bool)` changes the animator to the animation controller with the given name, and with separator disabled^[What does this do?].
#### List
- deadSceneName (see `AgentModel::OnDie` and `OfficerModel::OnDie` (deadSceneName))
- specialWeaponAnim (see `Special Weapon Animators`)
- PlagueDoctorAgentCTRL
- AgentPanic
- BlackCorpsAgentCTRL
- SingingMachineAttackerAgentCTRL
- SingingMachineDieAgentCTRL

## WorkerAnimatorChanger::ChangeAnimatorWithUniqueFace(string, bool)
The method `WorkerAnimatorChanger::ChangeAnimator(string, bool)` changes the animator to the animation controller with the given name, and with separator disabled^[What does this do?]. It also sets the face to a unique face.
#### List
- deadSceneName (see `AgentModel::OnDie` and `OfficerModel::OnDie` (deadSceneName))
- ScytheApostleDead
- WandApostleDead
- SpearApostleDead
- BakuAgentDead
- BeautyBeastAgentDead
- BirdBirdAgentDead
- ScarecrowAgentDead (by `Scarecrow`, `BugMidnight`, `Censored`)
- NamelessFetusAgentDead (by `NamelessFetus`, `Censored`)
- FireBirdAgentDead (by `FireBird`, `SnowQueen`)
- HappyTeddyAgentDead
- JusticeReceiverAgentDead
- PianoAgentCTRL
- PianoAgentDead
- PinkCorpsAgentCTRL
- PorccuAgentDead
- ProphecyOfSkinDead
- SakuraAgentDead
- SlimeGirlAgentDead
- SnowQueenAgentCTRL
- WellcheersAgentCTRL
- YggdrasilAgentCTRL
- YggdrasilAgentDead
- YoungPrinceAgentDead
- TheresiaUse (YoungPrince, see also Tool Abnormality Use)
- RedShoesAgentCTRL
- ViscusSnakeAgentDead

## WorkerModel::TakeDamageWithoutEffect and WorkerModel::TakeDamage (specialDeadSceneName)
The methods `WorkerModel::TakeDamageWithoutEffect` and `WorkerModel::TakeDamage` use the value of `dmg.specialDeadSceneName` to set a special death scene. This is only used by [Green Dawn](/api/Global/Abnormalities/Ordeals/Green-Ordeals/Green-Dawn/MachineDawn).
#### List
- MachineDawnAgentDead