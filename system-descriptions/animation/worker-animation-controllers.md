---
title: Worker Animation Controllers
description: List of animation controllers used by agents and clerks
published: true
date: 2026-08-02T19:47:13.283Z
tags: 
editor: markdown
dateCreated: 2026-08-01T23:02:45.762Z
---

# Worker Animation Controllers

Agents and clerks, by default, use the `skeleton_Controller1.controller` animation controller (at `Assets/AnimatorController/skeleton_Controller1.controller`). However, in a number of different circumstances, this animator will be changed from the default. This page hosts a complete list of alternative animator controllers by the method used to change it.

Each animation controller has a key associated with a skeleton controller file and a skeleton data file (the pairings can be found in the original file at `Resources/xml/worker/WorkerUniqueAnim.txt`). In addition to their key, they have an id, which appears unused but is included here for completeness.


## Default Animator
The methods `WorkerUnit::ChangeAnimatorDefault()` and  `WorkerAnimatorChanger::ChangeAnimator()` reset the worker to use their default animator controller. When a worker has a `SPECIAL` type weapon,  `WorkerUnit::UpdateAnimatorChange` can also do this.

## Special Weapon Animators
When a worker has a `SPECIAL` type weapon, `WorkerUnit::UpdateAnimatorChange` can change the animator to use the special weapon animator specified in `xml/Equipment/Equipment`.

Until `CensoredWeapon` (ID `12`) the skeleton controller is `SpineData/SpineUniqueWeapon/{key}Anim/{key}_Controller` and the skeleton data is `SpineData/SpineUniqueWeapon/{key}Anim/{key}_SkeletonData`. Starting with `CensoredWeapon`, the skeleton controller is `SpineData/SpineUniqueWeapon/{key}Anim/skeleton_Controller` and the skeleton data is `SpineData/SpineUniqueWeapon/{key}Anim/skeleton_SkeletonData` starting at `CensoredWeapon` (ID `12`).
#### List
|Id | Key | Skeleton Controller | Skeleton Data |
| --- | --- | --- | --- |
| 0| GreedWeapon | SpineData/SpineUniqueWeapon/GreedyWeaponAnim/GreedWeapon_Controller | SpineData/SpineUniqueWeapon/GreedyWeaponAnim/GreedWeapon_SkeletonData|
| 1 | HelperWeapon | SpineData/SpineUniqueWeapon/HelperWeaponAnim/HelperWeapon_Controller |  SpineData/SpineUniqueWeapon/HelperWeaponAnim/HelperWeapon_SkeletonData |
| 2| LongBirdWeapon | SpineData/SpineUniqueWeapon/LongBirdWeaponAnim/LongBirdWeapon_Controller | SpineData/SpineUniqueWeapon/LongBirdWeaponAnim/LongBirdWeapon_SkeletonData |
| 3| SilentOrchestraWeapon | SpineData/SpineUniqueWeapon/OrchestraWeaponAnim/OrchestraWeapon_Controller | SpineData/SpineUniqueWeapon/OrchestraWeaponAnim/OrchestraWeapon_SkeletonData |
| 4| FetusWeapon | SpineData/SpineUniqueWeapon/FetusWeaponAnim/FetusWeapon_Controller | SpineData/SpineUniqueWeapon/FetusWeaponAnim/FetusWeapon_SkeletonData |
| 5| NothingWeapon | SpineData/SpineUniqueWeapon/NothingWeaponAnim/NothingWeapon_Controller | SpineData/SpineUniqueWeapon/NothingWeaponAnim/NothingWeapon_SkeletonData
| 6| SamuraiWeapon | SpineData/SpineUniqueWeapon/SamuraiWeaponAnim/SamuraiWeapon_Controller | SpineData/SpineUniqueWeapon/SamuraiWeaponAnim/SamuraiWeapon_SkeletonData
| 7| KnightOfDespairWeapon | SpineData/SpineUniqueWeapon/KnightOfDespairWeaponAnim/KnightOfDespairWeapon_Controller | SpineData/SpineUniqueWeapon/KnightOfDespairWeaponAnim/KnightOfDespairWeapon_SkeletonData
| 8| DangoCreatureWeapon | SpineData/SpineUniqueWeapon/DangoCreatureWeaponAnim/DangoCreatureWeapon_Controller | SpineData/SpineUniqueWeapon/DangoCreatureWeaponAnim/DangoCreatureWeapon_SkeletonData
| 9| FreischutzWeapon | SpineData/SpineUniqueWeapon/FreischutzWeaponAnim/FreischutzWeapon_Controller | SpineData/SpineUniqueWeapon/FreischutzWeaponAnim/FreischutzWeapon_SkeletonData
| 10| BlackSwanWeapon | SpineData/SpineUniqueWeapon/BlackSwanWeaponAnim/BlackSwanWeapon_Controller | SpineData/SpineUniqueWeapon/BlackSwanWeaponAnim/BlackSwanWeapon_SkeletonData
| 11| ButterflyWeapon | SpineData/SpineUniqueWeapon/ButterflyWeaponAnim/ButterflyWeapon_Controller | SpineData/SpineUniqueWeapon/ButterflyWeaponAnim/ButterflyWeapon_SkeletonData
| 12| CensoredWeapon | SpineData/SpineUniqueWeapon/CensoredWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/CensoredWeaponAnim/skeleton_SkeletonData
| 13| PorccuWeapon | SpineData/SpineUniqueWeapon/PorccuWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/PorccuWeaponAnim/skeleton_SkeletonData
| 14| BlueStarWeapon | SpineData/SpineUniqueWeapon/BlueStarWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/BlueStarWeaponAnim/skeleton_SkeletonData
| 15| RedHoodWeapon | SpineData/SpineUniqueWeapon/RedHoodWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/RedHoodWeaponAnim/skeleton_SkeletonData
| 16| BigBadWolfWeapon | SpineData/SpineUniqueWeapon/BigBadWolfWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/BigBadWolfWeaponAnim/skeleton_SkeletonData
| 17| BossBirdWeapon | SpineData/SpineUniqueWeapon/BossBirdWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/BossBirdWeaponAnim/skeleton_SkeletonData
| 18| SakuraWeapon | SpineData/SpineUniqueWeapon/SakuraWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/SakuraWeaponAnim/skeleton_SkeletonData
| 19| BakuWeapon | SpineData/SpineUniqueWeapon/BakuWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/BakuWeaponAnim/skeleton_SkeletonData
| 20| MagicalGirlWeapon | SpineData/SpineUniqueWeapon/MagicalGirlWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/MagicalGirlWeaponAnim/skeleton_SkeletonData
| 21| FireBirdWeapon | SpineData/SpineUniqueWeapon/FireBirdWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/FireBirdWeaponAnim/skeleton_SkeletonData
| 22| YinWeapon | SpineData/SpineUniqueWeapon/YinWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/YinWeaponAnim/skeleton_SkeletonData
| 23| DeathAngelWeapon | SpineData/SpineUniqueWeapon/DeathAngelWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/DeathAngelWeaponAnim/skeleton_SkeletonData
| 24| FengYunWeapon | SpineData/SpineUniqueWeapon/FengYunWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/FengYunWeaponAnim/skeleton_SkeletonData
| 25| SlimeGirlWeapon | SpineData/SpineUniqueWeapon/SlimeGirlWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/SlimeGirlWeaponAnim/skeleton_SkeletonData
| 26| SharkWeapon | SpineData/SpineUniqueWeapon/SharkWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/SharkWeaponAnim/skeleton_SkeletonData
| 27| LookAtMeWeapon | SpineData/SpineUniqueWeapon/LookAtMeWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/LookAtMeWeaponAnim/skeleton_SkeletonData
| 28| PinkCorpsWeapon | SpineData/SpineUniqueWeapon/PinkCorpsWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/PinkCorpsWeaponAnim/skeleton_SkeletonData
| 29| PianoWeapon | SpineData/SpineUniqueWeapon/PianoWeaponAnim/skeleton_Controller | SpineData/SpineUniqueWeapon/PianoWeaponAnim/skeleton_SkeletonData

## Tool Abnormality Use
The method `WorkerUnit::ChangeAnimatorForcely(string, bool, bool)` is used only by abnormalities which specify the `workAnim` animation controller in their data (`Resources/xml/creaturestats/{abno}_stat.txt`). The only abnormalities that have these present are the tool abnormalities.
#### List
|Id | Key | Skeleton Controller | Skeleton Data | uniqueFace | Used By |
| --- | --- | --- | --- | --- | --- |
| 300000 | KitEquipCreatureUse | SpineData/SpineWorkAnim/KitEquipCreatureUse/KitEquipCreatureUse_Controller | SpineData/SpineWorkAnim/KitEquipCreatureUse/KitEquipCreatureUse_SkeletonData| (none) | ResetMirror, YouMustHappy, Shelter, default if not specified |
| 300003 | TheresiaUse | SpineData/SpineWorkAnim/TheresiaUse/TheresiaUse_Controller | SpineData/SpineWorkAnim/TheresiaUse/TheresiaUse_SkeletonData| "unique" | HellTrain, IronMaiden, OtherWorldPortrait, ProphecyOfSkin, Theresia; see also `WorkerAnimatorChanger:: ChangeAnimatorWithUniqueFace` |
| 300004 | MeatIdolUse | SpineData/SpineWorkAnim/MeatIdolUse/MeatIdolUse_Controller | SpineData/SpineWorkAnim/MeatIdolUse/MeatIdolUse_SkeletonData | "unique" | MeatIdol; see also `WorkerAnimatorChanger:: ChangeAnimatorWithUniqueFace` |
| 300005 | BigTreeSapUse | SpineData/SpineWorkAnim/BigTreeSapUse/BigTreeSapUse_Controller | SpineData/SpineWorkAnim/BigTreeSapUse/BigTreeSapUse_SkeletonData| (none) | BigTreeSap |
| 300006 | PromiseAndFaithUse | SpineData/SpineWorkAnim/PromiseAndFaithUse/skeleton_Controller | SpineData/SpineWorkAnim/PromiseAndFaithUse/skeleton_SkeletonData | "unique" | PromiseAndFaith |
| 300007 | ReverseClockUse | SpineData/SpineWorkAnim/ReverseClockUse/agnet_Controller^[sic]^ | SpineData/SpineWorkAnim/ReverseClockUse/agnet_SkeletonData^[sic]^ | "unique" | ReverseClock |

## AgentModel::OnDie and OfficerModel::OnDie (deadSceneName)
The methods `AgentModel::OnDie` and `OfficerModel::OnDie` use the animator controller specified by `deadSceneName` when a worker dies.

This value can be changed by the following methods.
### SetSpecialDeadScene(string)
#### List
|Id | Key | Skeleton Controller | Skeleton Data | Used By |
| --- | --- | --- | --- | --- |
| 10002 | LongBirdAgentDead | SpineData/SpineDeadScene/longBirdAgentDead/longBirdAgentDead_Controller | SpineData/SpineDeadScene/longBirdAgentDead/longBirdAgentDead_SkeletonData| LongBird |
| 10007 | AlriuneAgentDead | SpineData/SpineDeadScene/alriuneAgentDead/alriuneAgentDead_Controller | SpineData/SpineDeadScene/alriuneAgentDead/alriuneAgentDead_SkeletonData| Alriune |
See also `WorkerModel::TakeDamageWithoutEffect` and `WorkerModel::TakeDamage` for a unique use case.
### SetSpecialDeadScene(string, bool)
#### List
|Id | Key | Skeleton Controller | Skeleton Data | Used By |
| --- | --- | --- | --- | --- |
| 100 | AgentPanic | SpineData/AgentCTRL/panicAgentCTRL/AgentPanic_CTRL | SpineData/AgentCTRL/panicAgentCTRL/AgentPanic_SkeletonData | Yggdrasil (Uncontrollable_Yggdrasil_Fake_Panic), PanicAgentMoveTutorial, PanicOpenIsolate, PanicRoaming, PanicSuicideExecutor |
| 10022 | BigBirdAgentDead | SpineData/SpineDeadScene/BigBirdAgentDead/skeleton_Controller | SpineData/SpineDeadScene/BigBirdAgentDead/skeleton_SkeletonData | BigBird |
### SetSpecialDeadScene(string, bool, bool)
#### List
|Id | Key | Skeleton Controller | Skeleton Data | Used By |
| --- | --- | --- | --- | --- |
| 10002 | LongBirdAgentDead | SpineData/SpineDeadScene/longBirdAgentDead/longBirdAgentDead_Controller | SpineData/SpineDeadScene/longBirdAgentDead/longBirdAgentDead_SkeletonData| BossBird |
| 10004 | RedShoesAgentDead | SpineData/SpineDeadScene/redShoesAgentDead/redShoesAgentDead_Controller | SpineData/SpineDeadScene/redShoesAgentDead/redShoesAgentDead_SkeletonData| RedShoes |
| 10006 | SnowWhiteAgentDead | SpineData/SpineDeadScene/snowWhiteAgentDead/snowWhiteAgentDead_Controller | SpineData/SpineDeadScene/snowWhiteAgentDead/snowWhiteAgentDead_SkeletonData| SnowWhite |
| 10007 | AlriuneAgentDead | SpineData/SpineDeadScene/alriuneAgentDead/alriuneAgentDead_Controller | SpineData/SpineDeadScene/alriuneAgentDead/alriuneAgentDead_SkeletonData| Alriune |
| 10011 | ButterflyAgentDead | SpineData/SpineDeadScene/butterflyAgentDead/butterflyAgentDead_Controller | SpineData/SpineDeadScene/butterflyAgentDead/butterflyAgentDead_SkeletonData | Butterfly |
| 10012 | KnightOfDespairDead | SpineData/SpineDeadScene/KnightOfDespairAgentDead/KnightOfDespairDead_Controller | SpineData/SpineDeadScene/KnightOfDespairAgentDead/KnightOfDespairDead_SkeletonData | KnightOfDespair |
| 10014 | FairyAgentDead | SpineData/SpineDeadScene/fairyAgentDead/fairyAgentDead_Controller | SpineData/SpineDeadScene/fairyAgentDead/fairyAgentDead_SkeletonData | Fairy |
| 10015 | BlueStarAgentDead | SpineData/SpineDeadScene/blueStarAgentDead/blueStarAgentDead_Controller | SpineData/SpineDeadScene/blueStarAgentDead/blueStarAgentDead_SkeletonData | BlueStar |

## WorkerAnimatorChanger::ChangeAnimator(string)
The method `WorkerAnimatorChanger::ChangeAnimator(string)` changes the animator to the animation controller with the given name.
#### List
|Id | Key | Skeleton Controller | Skeleton Data | Used By |
| --- | --- | --- | --- | --- |
| 10005 | SpiderMomAgentDead | SpineData/SpineDeadScene/spiderMomAgentDead/spiderMomAgentDead_Controller | SpineData/SpineDeadScene/spiderMomAgentDead/spiderMomAgentDead_SkeletonData | SpiderMom |
| 10010 | ArmorCreatureDead | SpineData/SpineDeadScene/ArmorCreatureDead/skeleton_Controller | SpineData/SpineDeadScene/ArmorCreatureDead/skeleton_SkeletonData | ArmorCreature |
| 10018 | OtherWorldPortraitDead | SpineData/SpineDeadScene/OtherWorldPortraitDead/skeleton_Controller | SpineData/SpineDeadScene/OtherWorldPortraitDead/skeleton_SkeletonData | OtherWorldPortrait |
| 10020 | HealthBraceletDead | SpineData/SpineDeadScene/HealthBraceletDead/skeleton_Controller | SpineData/SpineDeadScene/HealthBraceletDead/skeleton_SkeletonData | HealthBracelet |
| 300004 | MeatIdolUse | SpineData/SpineWorkAnim/MeatIdolUse/MeatIdolUse_Controller | SpineData/SpineWorkAnim/MeatIdolUse/MeatIdolUse_SkeletonData | OneGoodManyBad for work type 6; see also Tool Abnormality Use |

Also used by `WorkerUnit::ChangeAnimatorForcely(string, bool, bool)` from `UseSkill::InitUseSkillAction`, see Tool Abnormality Use above.

## WorkerAnimatorChanger::ChangeAnimator(string, bool)
The method `WorkerAnimatorChanger::ChangeAnimator(string, bool)` changes the animator to the animation controller with the given name, and with separator disabled^[What does this do?].
#### List
|Id | Key | Skeleton Controller | Skeleton Data | Used By |
| --- | --- | --- | --- | --- |
| 1004 | SingingMachineDieAgentCTRL | SpineData/AgentCTRL/SingingMachineAgentCTRL/SingingMachine_AgentDie_CTRL | SpineData/AgentCTRL/SingingMachineAgentCTRL/SingingMachine_AgentDie^[sic]^ | SingingMachine |
| 1005 | SingingMachineAttackerAgentCTRL | SpineData/AgentCTRL/SingingMachineAgentCTRL/SingingMachine_AgentAttacker_CTRL | SpineData/AgentCTRL/SingingMachineAgentCTRL/SingingMachine_AgentAttacker^[sic]^ | SingingMachine |
| 1006 | PlagueDoctorAgentCTRL | SpineData/AgentCTRL/plagueDoctorCTRL/PlagueDoctorAgentCTRL | SpineData/AgentCTRL/plagueDoctorCTRL/PlagueDoctorAgentSkeletonData | PlagueDoctor |
| 1010 | BlackCorpsAgentCTRL | SpineData/AgentCTRL/blackWorkerCTRL/skeleton_Controller | SpineData/AgentCTRL/blackWorkerCTRL/skeleton_SkeletonData | PinkCorps (BlackLovePanicReady) |

Also used with the value of `deadSceneName` (see `AgentModel::OnDie` and `OfficerModel::OnDie` (deadSceneName) above) and `specialWeaponAnim` (see `Special Weapon Animators` above).

## WorkerAnimatorChanger::ChangeAnimatorWithUniqueFace(string, bool)
The method `WorkerAnimatorChanger::ChangeAnimator(string, bool)` changes the animator to the animation controller with the given name, and with separator disabled^[What does this do?]. It also sets the face to a unique face.
#### List
|Id | Key | Skeleton Controller | Skeleton Data | Used By |
| --- | --- | --- | --- | --- |
| 1000 | RedShoesAgentCTRL | SpineData/AgentCTRL/redShoesAgentCTRL/redShoesAgentCTRL_Controller | SpineData/AgentCTRL/redShoesAgentCTRL/redShoesAgentCTRL_SkeletonData | RedShoes |
| 1001 | WellcheersAgentCTRL | SpineData/AgentCTRL/wellcheersAgentCTRL/wellcheersAgentCTRL_Controller | SpineData/AgentCTRL/wellcheersAgentCTRL/wellcheersAgentCTRL_SkeletonData | Wellcheers |
| 1002 | SnowQueenAgentCTRL | SpineData/AgentCTRL/snowqueenAgentCTRL/skeleton_Controller | SpineData/AgentCTRL/snowqueenAgentCTRL/skeleton_SkeletonData | SnowQueen |
| 1003 | ViscusSnakeAgentCTRL | SpineData/AgentCTRL/viscusSnakeAgentCTRL/viscusAgent_Controller | SpineData/AgentCTRL/viscusSnakeAgentCTRL/viscusAgent_SkeletonData | ViscusSnake |
| 1007 | YggdrasilAgentCTRL | SpineData/AgentCTRL/YggdrasilAgentCTRL/skeleton_Controller | SpineData/AgentCTRL/YggdrasilAgentCTRL/skeleton_SkeletonData | Yggdrasil |
| 1008 | PianoAgentCTRL | SpineData/AgentCTRL/PianoAgentCTRL/skeleton_Controller | SpineData/AgentCTRL/PianoAgentCTRL/skeleton_SkeletonData | Piano |
| 1009 | PinkCorpsAgentCTRL | SpineData/AgentCTRL/PianoAgentCTRL/skeleton_Controller | SpineData/AgentCTRL/PianoAgentCTRL/skeleton_SkeletonData | PinkCorps |
| 10000 | BeautyBeastAgentDead | SpineData/SpineDeadScene/beautyBeastAgentDead/beautyBeastAgentDead_Controller | SpineData/SpineDeadScene/beautyBeastAgentDead/beautyBeastAgentDead_SkeletonData| BeautyBeast |
| 10001 | HappyTeddyAgentDead | SpineData/SpineDeadScene/happyTeddyAgentDead/happyTeddyAgentDead_Controller | SpineData/SpineDeadScene/happyTeddyAgentDead/happyTeddyAgentDead_SkeletonData| HappyTeddy |
| 10009 | NamelessFetusAgentDead | SpineData/SpineDeadScene/namelessFetusAgentDead/namelessFetusAgentDead_Controller | SpineData/SpineDeadScene/namelessFetusAgentDead/namelessFetusAgentDead_SkeletonData | NamelessFetus, Censored |
| 10013 | ScarecrowAgentDead | SpineData/SpineDeadScene/ScarecrowAgentDead/ScarecrowAgentDead_Controller | SpineData/SpineDeadScene/ScarecrowAgentDead/ScarecrowAgentDead_SkeletonData | Scarecrow, BugMidnight, Censored |
| 10016 | ProphecyOfSkinDead | SpineData/SpineDeadScene/ProphecyOfSkinDead/ProphecyOfSkinDead_Controller | SpineData/SpineDeadScene/ProphecyOfSkinDead/ProphecyOfSkinDead_SkeletonData | ProphecyOfSkin |
| 10017 | PorccuAgentDead | SpineData/SpineDeadScene/porccuAgentDead/skeleton_Controller | SpineData/SpineDeadScene/porccuAgentDead/skeleton_SkeletonData | Porccu |
| 10019 | YoungPrinceAgentDead | SpineData/SpineDeadScene/youngPrinceAgentDead/skeleton_Controller | SpineData/SpineDeadScene/youngPrinceAgentDead/skeleton_SkeletonData | YoungPrince |
| 10021 | JusticeReceiverAgentDead | SpineData/SpineDeadScene/JusticeReceiverAgentDead/skeleton_Controller | SpineData/SpineDeadScene/JusticeReceiverAgentDead/skeleton_SkeletonData | JusticeReceiver |
| 10022 | BigBirdAgentDead | SpineData/SpineDeadScene/BigBirdAgentDead/skeleton_Controller | SpineData/SpineDeadScene/BigBirdAgentDead/skeleton_SkeletonData | BigBird |
| 10023 | SakuraAgentDead | SpineData/SpineDeadScene/SakuraAgentDead/Agent_Controller | SpineData/SpineDeadScene/SakuraAgentDead/Agent_SkeletonData | Sakura |
| 10024 | BakuAgentDead | SpineData/SpineDeadScene/BakuAgentDead/skeleton_Controller | SpineData/SpineDeadScene/BakuAgentDead/skeleton_SkeletonData | Baku |
| 10025 | FireBirdAgentDead | SpineData/SpineDeadScene/FireBirdAgentDead/skeleton_Controller | SpineData/SpineDeadScene/FireBirdAgentDead/skeleton_SkeletonData | FireBird, SnowQueen^[Hidden interaction when sending an agent with FireBird's armor into SnowQueen's room.] |
| 10026 | ScytheApostleDead | SpineData/SpineDeadScene/ApostleDead/ScytheApostleWorkerDead/ScytheApostleWorkerDeadCTRL | SpineData/SpineDeadScene/ApostleDead/ScytheApostleWorkerDead/ScytheApostleWorkerDeadSkeletonData | DeathAngel |
| 10027 | WandApostleDead | SpineData/SpineDeadScene/ApostleDead/WandApostleWorkerDead/WandApostleWorkerDeadCTRL | SpineData/SpineDeadScene/ApostleDead/WandApostleWorkerDead/WandApostleWorkerDeadSkeletonData | DeathAngel |
| 10028 | SpearApostleDead | SpineData/SpineDeadScene/ApostleDead/SpearApostleWorkerDead/SpearApostleWorkerDeadCTRL | SpineData/SpineDeadScene/ApostleDead/SpearApostleWorkerDead/SpearApostleWorkerDeadSkeletonData | DeathAngel |
| 10029 | YggdrasilAgentDead | SpineData/SpineDeadScene/YggdrasilAgentDead/skeleton_Controller | SpineData/SpineDeadScene/YggdrasilAgentDead/skeleton_SkeletonData | Yggdrasil |
| 10030 | SlimeGirlAgentDead | SpineData/SpineDeadScene/SlimeGirlAgentDead/skeleton_Controller | SpineData/SpineDeadScene/SlimeGirlAgentDead/skeleton_SkeletonData | SlimeGirl |
| 10031 | PianoAgentDead | SpineData/SpineDeadScene/PianoAgentDead/skeleton_Controlle | SpineData/SpineDeadScene/PianoAgentDead/skeleton_SkeletonData| Piano |
| 300003 | TheresiaUse | SpineData/SpineWorkAnim/TheresiaUse/TheresiaUse_Controller | SpineData/SpineWorkAnim/TheresiaUse/TheresiaUse_SkeletonData| YoungPrince; see also Tool Abnormality Use|

Also used with the value of `deadSceneName` (see `AgentModel::OnDie` and `OfficerModel::OnDie` (deadSceneName) above).

## WorkerModel::TakeDamageWithoutEffect and WorkerModel::TakeDamage (specialDeadSceneName)
The methods `WorkerModel::TakeDamageWithoutEffect` and `WorkerModel::TakeDamage` use the value of `dmg.specialDeadSceneName` to set a special death scene. This is only used by [Green Dawn](/api/Global/Abnormalities/Ordeals/Green-Ordeals/Green-Dawn/MachineDawn).
#### List
|Id | Key | Skeleton Controller | Skeleton Data | Used By |
| --- | --- | --- | --- | --- |
| 10008 | MachineDawnAgentDead | SpineData/SpineDeadScene/MachineDawnAgentDead/MachineDawnAgentDead_Controller | SpineData/SpineDeadScene/MachineDawnAgentDead/MachineDawnAgentDead_SkeletonData | MachineDawn |