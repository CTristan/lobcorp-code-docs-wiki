---
uid: Global.EventCreatureModel
canonical_path: /api/Global/Creature/EventCreatureModel
---

# Class EventCreatureModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EventCreatureModel : CreatureModel, IObserver, ISerializablePlayData, IMouseCommandTargetModel
```

Represents a creature spawned by an event.

... Which is to say, by [Apocalypse Bird](/api/Global/Misc/BossBird).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/Global/Model/UnitModel) → [CreatureModel](/api/Global/Model/CreatureModel) → EventCreatureModel

## Implements
[IObserver](/api/Global/Misc/IObserver), [ISerializablePlayData](/api/Global/Misc/ISerializablePlayData), [IMouseCommandTargetModel](/api/Global/Model/IMouseCommandTargetModel)

## Inherited Members
[regionName](/api/Global/Model/CreatureModel#regionname), [careTakingRegion](/api/Global/Model/CreatureModel#caretakingregion), [commandQueue](/api/Global/Model/CreatureModel#commandqueue), [canBeSuppressed](/api/Global/Model/CreatureModel#canbesuppressed), [metaInfo](/api/Global/Model/CreatureModel#metainfo), [metadataId](/api/Global/Model/CreatureModel#metadataid), [script](/api/Global/Model/CreatureModel#script), [observeInfo](/api/Global/Model/CreatureModel#observeinfo), [narrationList](/api/Global/Model/CreatureModel#narrationlist), [_state](/api/Global/Model/CreatureModel#state), [feelingState](/api/Global/Model/CreatureModel#feelingstate), [feelingStateRemainTime](/api/Global/Model/CreatureModel#feelingstateremaintime), [_currentSkill](/api/Global/Model/CreatureModel#currentskill), [suppressReturnTimer](/api/Global/Model/CreatureModel#suppressreturntimer), [sefiraNum](/api/Global/Model/CreatureModel#sefiranum), [sefira](/api/Global/Model/CreatureModel#sefira), [sefiraOrigin](/api/Global/Model/CreatureModel#sefiraorigin), [specialSkillPos](/api/Global/Model/CreatureModel#specialskillpos), [basePosition](/api/Global/Model/CreatureModel#baseposition), [entryNodeId](/api/Global/Model/CreatureModel#entrynodeid), [entryNode](/api/Global/Model/CreatureModel#entrynode), [workspaceNode](/api/Global/Model/CreatureModel#workspacenode), [roomNode](/api/Global/Model/CreatureModel#roomnode), [customNode](/api/Global/Model/CreatureModel#customnode), [isolateRoomData](/api/Global/Model/CreatureModel#isolateroomdata), [defenseId](/api/Global/Model/CreatureModel#defenseid), [_unit](/api/Global/Model/CreatureModel#unit), [<InstanceID>k__BackingField](Global.CreatureModel.html#CreatureModel__InstanceID_k__BackingField), [movementScale](/api/Global/Model/CreatureModel#movementscale), [workCount](/api/Global/Model/CreatureModel#workcount), [_qliphothCounter](/api/Global/Model/CreatureModel#qliphothcounter), [_probReductionCounter](/api/Global/Model/CreatureModel#probreductioncounter), [_probReductionValue](/api/Global/Model/CreatureModel#probreductionvalue), [overloadLevel](/api/Global/Model/CreatureModel#overloadlevel), [isOverloaded](/api/Global/Model/CreatureModel#isoverloaded), [overloadType](/api/Global/Model/CreatureModel#overloadtype), [currentOverloadMaxTime](/api/Global/Model/CreatureModel#currentoverloadmaxtime), [overloadTimer](/api/Global/Model/CreatureModel#overloadtimer), [overloadTime](/api/Global/Model/CreatureModel#overloadtime), [kitEquipOwner](/api/Global/Model/CreatureModel#kitequipowner), [childs](/api/Global/Model/CreatureModel#childs), [childInst](/api/Global/Model/CreatureModel#childinst), [_activated](/api/Global/Model/CreatureModel#activated), [counter](/api/Global/Model/CreatureModel#counter), [GetSaveData()](/api/Global/Model/CreatureModel#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Model/CreatureModel#loaddata-dictionary-string-object), [WorkParamInit()](/api/Global/Model/CreatureModel#workparaminit), [OnGameInit()](/api/Global/Model/CreatureModel#ongameinit), [OnStageEnd()](/api/Global/Model/CreatureModel#onstageend), [GetUnitName(CreatureTypeInfo, CreatureObserveInfoModel)](/api/Global/Model/CreatureModel#getunitname-creaturetypeinfo-creatureobserveinfomodel), [GetUnitName()](/api/Global/Model/CreatureModel#getunitname), [GetFeelingState()](/api/Global/Model/CreatureModel#getfeelingstate), [CopyNodeData(CreatureModel)](/api/Global/Model/CreatureModel#copynodedata-creaturemodel), [SetRoomNode(MapNode)](/api/Global/Model/CreatureModel#setroomnode-mapnode), [SetCustomNode(MapNode)](/api/Global/Model/CreatureModel#setcustomnode-mapnode), [SetCurrentNode(MapNode)](/api/Global/Model/CreatureModel#setcurrentnode-mapnode), [GetCurrentNode()](/api/Global/Model/CreatureModel#getcurrentnode), [GetCurrentEdge()](/api/Global/Model/CreatureModel#getcurrentedge), [SetWorkspaceNode(MapNode)](/api/Global/Model/CreatureModel#setworkspacenode-mapnode), [GetWorkspaceNode()](/api/Global/Model/CreatureModel#getworkspacenode), [GetEntryNode()](/api/Global/Model/CreatureModel#getentrynode), [GetCustomNode()](/api/Global/Model/CreatureModel#getcustomnode), [GetRoomNode()](/api/Global/Model/CreatureModel#getroomnode), [GetDirection()](/api/Global/Model/CreatureModel#getdirection), [IsWorkingState()](/api/Global/Model/CreatureModel#isworkingstate), [IsEscaped()](/api/Global/Model/CreatureModel#isescaped), [IsEscapedOnlyEscape()](/api/Global/Model/CreatureModel#isescapedonlyescape), [GetConnectedUnitModel()](/api/Global/Model/CreatureModel#getconnectedunitmodel), [PlayAttackAnimation(string)](/api/Global/Model/CreatureModel#playattackanimation-string), [AddWorkCount()](/api/Global/Model/CreatureModel#addworkcount), [ResetWorkCount()](/api/Global/Model/CreatureModel#resetworkcount), [GetMaxWorkCount()](/api/Global/Model/CreatureModel#getmaxworkcount), [GetMaxWorkCountView()](/api/Global/Model/CreatureModel#getmaxworkcountview), [IsWorkCountFull()](/api/Global/Model/CreatureModel#isworkcountfull), [AddProbReductionCounter()](/api/Global/Model/CreatureModel#addprobreductioncounter), [ResetProbReductionCounter()](/api/Global/Model/CreatureModel#resetprobreductioncounter), [GetRedusedWorkProbByCounter()](/api/Global/Model/CreatureModel#getredusedworkprobbycounter), [OnChangeProbReduectionCounter()](/api/Global/Model/CreatureModel#onchangeprobreduectioncounter), [OnActivateAgentDeadPenalty()](/api/Global/Model/CreatureModel#onactivateagentdeadpenalty), [ActivateOverload(int, float, OverloadType)](/api/Global/Model/CreatureModel#activateoverload-int-float-overloadtype), [ExplodeOverload()](/api/Global/Model/CreatureModel#explodeoverload), [ClearProbReduction()](/api/Global/Model/CreatureModel#clearprobreduction), [CancelOverload()](/api/Global/Model/CreatureModel#canceloverload), [GetNearWorkerEncounted()](/api/Global/Model/CreatureModel#getnearworkerencounted), [OnEscapeUpdate()](/api/Global/Model/CreatureModel#onescapeupdate), [OnNotice(string, params object[])](/api/Global/Model/CreatureModel#onnotice-string-params-object), [ShowTextOutside(CreatureOutsideTextLayout, string)](/api/Global/Model/CreatureModel#showtextoutside-creatureoutsidetextlayout-string), [ShowNarrationText(string, params string[])](/api/Global/Model/CreatureModel#shownarrationtext-string-params-string), [ShowNarrationText(string, bool, params string[])](/api/Global/Model/CreatureModel#shownarrationtext-string-bool-params-string), [ShowNarrationForcely(string)](/api/Global/Model/CreatureModel#shownarrationforcely-string), [ShowProcessNarrationText(string, params string[])](/api/Global/Model/CreatureModel#showprocessnarrationtext-string-params-string), [EscapeWithoutIsolateRoom()](/api/Global/Model/CreatureModel#escapewithoutisolateroom), [ResetAttackDelay()](/api/Global/Model/CreatureModel#resetattackdelay), [ResetAttackDelay(float)](/api/Global/Model/CreatureModel#resetattackdelay-float), [TakeDamage(UnitModel, DamageInfo)](/api/Global/Model/CreatureModel#takedamage-unitmodel-damageinfo), [Suppressed()](/api/Global/Model/CreatureModel#suppressed), [OnSuperArmorBreak()](/api/Global/Model/CreatureModel#onsuperarmorbreak), [IsAttackTargetable()](/api/Global/Model/CreatureModel#isattacktargetable), [GetRiskLevel()](/api/Global/Model/CreatureModel#getrisklevel), [GetAttackLevel()](/api/Global/Model/CreatureModel#getattacklevel), [GetDefenseLevel()](/api/Global/Model/CreatureModel#getdefenselevel), [SetFeelingStateInWork(CreatureFeelingState)](/api/Global/Model/CreatureModel#setfeelingstateinwork-creaturefeelingstate), [ClearCommand()](/api/Global/Model/CreatureModel#clearcommand), [MoveToNode(MapNode)](/api/Global/Model/CreatureModel#movetonode-mapnode), [MoveToMovable(MovableObjectNode)](/api/Global/Model/CreatureModel#movetomovable-movableobjectnode), [PursueWorker(WorkerModel)](/api/Global/Model/CreatureModel#pursueworker-workermodel), [AttackTarget(AttackCommand_creature)](/api/Global/Model/CreatureModel#attacktarget-attackcommand-creature), [PursueWorkerAlter(WorkerModel, float)](/api/Global/Model/CreatureModel#pursueworkeralter-workermodel-float), [PursueWorkerAlter(WorkerModel, RwbpType, int, int)](/api/Global/Model/CreatureModel#pursueworkeralter-workermodel-rwbptype-int-int), [SetPursueWorkerCommand(WorkerModel, CreatureCommand)](/api/Global/Model/CreatureModel#setpursueworkercommand-workermodel-creaturecommand), [FinishReturn()](/api/Global/Model/CreatureModel#finishreturn), [SendAnimMessage(string)](/api/Global/Model/CreatureModel#sendanimmessage-string), [SetMoveAnimState(bool)](/api/Global/Model/CreatureModel#setmoveanimstate-bool), [GetAnimScript()](/api/Global/Model/CreatureModel#getanimscript), [InteractWithDoor(DoorObjectModel)](/api/Global/Model/CreatureModel#interactwithdoor-doorobjectmodel), [OnStopMovableByShield(AgentModel)](/api/Global/Model/CreatureModel#onstopmovablebyshield-agentmodel), [GetFeelingPercent()](/api/Global/Model/CreatureModel#getfeelingpercent), [AddObservationLevel()](/api/Global/Model/CreatureModel#addobservationlevel), [OnObservationLevelChanged()](/api/Global/Model/CreatureModel#onobservationlevelchanged), [AddCreatureSuccessCube(int)](/api/Global/Model/CreatureModel#addcreaturesuccesscube-int), [SubCreatureSuccessCube(int)](/api/Global/Model/CreatureModel#subcreaturesuccesscube-int), [GetObservationConditionPoint()](/api/Global/Model/CreatureModel#getobservationconditionpoint), [GetNeedObservePoint()](/api/Global/Model/CreatureModel#getneedobservepoint), [GetCreatureCurrentCmd()](/api/Global/Model/CreatureModel#getcreaturecurrentcmd), [SetUnit(CreatureUnit)](/api/Global/Model/CreatureModel#setunit-creatureunit), [ShowCreatureSpeech(string)](/api/Global/Model/CreatureModel#showcreaturespeech-string), [ShowCreatureSpeech(string, float)](/api/Global/Model/CreatureModel#showcreaturespeech-string-float), [ShowCreatureSpeechDirect(string)](/api/Global/Model/CreatureModel#showcreaturespeechdirect-string), [ShowCreatureSpeechDirect(string, float)](/api/Global/Model/CreatureModel#showcreaturespeechdirect-string-float), [SpecialSkillActivated()](/api/Global/Model/CreatureModel#specialskillactivated), [OnPhysicsAttackInWork()](/api/Global/Model/CreatureModel#onphysicsattackinwork), [OnMentalAttackInWork()](/api/Global/Model/CreatureModel#onmentalattackinwork), [OnComplexAttackInWork()](/api/Global/Model/CreatureModel#oncomplexattackinwork), [ConvertNarrationCodeIDToName()](/api/Global/Model/CreatureModel#convertnarrationcodeidtoname), [ConvertCodeIDToName(string)](/api/Global/Model/CreatureModel#convertcodeidtoname-string), [ConvertCodeIDToNameForcely(string)](/api/Global/Model/CreatureModel#convertcodeidtonameforcely-string), [OnRevealSpecialSkillTip(string, params object[])](/api/Global/Model/CreatureModel#onrevealspecialskilltip-string-params-object), [MakeSpatteredBlood()](/api/Global/Model/CreatureModel#makespatteredblood), [GetWorkSuccessProb(AgentModel, SkillTypeInfo)](/api/Global/Model/CreatureModel#getworksuccessprob-agentmodel-skilltypeinfo), [GetCubeSpeed()](/api/Global/Model/CreatureModel#getcubespeed), [isPrevMaxObserve()](/api/Global/Model/CreatureModel#isprevmaxobserve), [ChangePos(CreatureModel)](/api/Global/Model/CreatureModel#changepos-creaturemodel), [AddChildCreatureModel()](/api/Global/Model/CreatureModel#addchildcreaturemodel), [AddChildCreatureModel(string, string)](/api/Global/Model/CreatureModel#addchildcreaturemodel-string-string), [GetChildCreatureModel(long)](/api/Global/Model/CreatureModel#getchildcreaturemodel-long), [GetAliveChilds()](/api/Global/Model/CreatureModel#getalivechilds), [DeleteChildCreatureModel(long)](/api/Global/Model/CreatureModel#deletechildcreaturemodel-long), [GetCurrentCommand()](/api/Global/Model/CreatureModel#getcurrentcommand), [SetFaction(FactionTypeInfo)](/api/Global/Model/CreatureModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/Global/Model/CreatureModel#setfaction-string), [SetActivatedState(bool)](/api/Global/Model/CreatureModel#setactivatedstate-bool), [ForcelyCancelSuppress()](/api/Global/Model/CreatureModel#forcelycancelsuppress), [SetDefenseId(string)](/api/Global/Model/CreatureModel#setdefenseid-string), [ResetQliphothCounter()](/api/Global/Model/CreatureModel#resetqliphothcounter), [SubQliphothCounter()](/api/Global/Model/CreatureModel#subqliphothcounter), [AddQliphothCounter()](/api/Global/Model/CreatureModel#addqliphothcounter), [SetQliphothCounter(int)](/api/Global/Model/CreatureModel#setqliphothcounter-int), [UpdateQliphothCounter()](/api/Global/Model/CreatureModel#updateqliphothcounter), [GetCurrentCumlatvieCube()](/api/Global/Model/CreatureModel#getcurrentcumlatviecube), [CanPurhcase(int)](/api/Global/Model/CreatureModel#canpurhcase-int), [TransactionCube(int)](/api/Global/Model/CreatureModel#transactioncube-int), [GetObservationLevel()](/api/Global/Model/CreatureModel#getobservationlevel), [OnFixedUpdateInKitEquip(AgentModel)](/api/Global/Model/CreatureModel#onfixedupdateinkitequip-agentmodel), [GetObserveBonusProb()](/api/Global/Model/CreatureModel#getobservebonusprob), [GetObserveBonusSpeed()](/api/Global/Model/CreatureModel#getobservebonusspeed), [state](/api/Global/Model/CreatureModel#state), [radius](/api/Global/Model/CreatureModel#radius), [currentSkill](/api/Global/Model/CreatureModel#currentskill), [Unit](/api/Global/Model/CreatureModel#unit), [InstanceID](/api/Global/Model/CreatureModel#instanceid), [defense](/api/Global/Model/CreatureModel#defense), [qliphothCounter](/api/Global/Model/CreatureModel#qliphothcounter), [probReductionCounter](/api/Global/Model/CreatureModel#probreductioncounter), [ProbReductionValue](/api/Global/Model/CreatureModel#probreductionvalue), [activated](/api/Global/Model/CreatureModel#activated), [stunCriteria](/api/Global/Model/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/Global/Model/UnitModel#defaultstuneffectsrc), [instanceId](/api/Global/Model/UnitModel#instanceid), [movableNode](/api/Global/Model/UnitModel#movablenode), [shield](/api/Global/Model/UnitModel#shield), [_equipment](/api/Global/Model/UnitModel#equipment), [tempAnim](/api/Global/Model/UnitModel#tempanim), [factionTypeInfo](/api/Global/Model/UnitModel#factiontypeinfo), [stunTimer](/api/Global/Model/UnitModel#stuntimer), [hp](/api/Global/Model/UnitModel#hp), [mental](/api/Global/Model/UnitModel#mental), [baseMaxHp](/api/Global/Model/UnitModel#basemaxhp), [baseMaxMental](/api/Global/Model/UnitModel#basemaxmental), [baseMovement](/api/Global/Model/UnitModel#basemovement), [baseRegeneration](/api/Global/Model/UnitModel#baseregeneration), [baseRegenerationDelay](/api/Global/Model/UnitModel#baseregenerationdelay), [additionalDef](/api/Global/Model/UnitModel#additionaldef), [superArmorMax](/api/Global/Model/UnitModel#superarmormax), [superArmor](/api/Global/Model/UnitModel#superarmor), [superArmorDefense](/api/Global/Model/UnitModel#superarmordefense), [remainMoveDelay](/api/Global/Model/UnitModel#remainmovedelay), [remainAttackDelay](/api/Global/Model/UnitModel#remainattackdelay), [isStun](/api/Global/Model/UnitModel#isstun), [damageTransform](/api/Global/Model/UnitModel#damagetransform), [basePhysicalDefense](/api/Global/Model/UnitModel#basephysicaldefense), [baseMentalDefense](/api/Global/Model/UnitModel#basementaldefense), [encounteredWorker](/api/Global/Model/UnitModel#encounteredworker), [_bufList](/api/Global/Model/UnitModel#buflist), [_statBufList](/api/Global/Model/UnitModel#statbuflist), [_barrierBufList](/api/Global/Model/UnitModel#barrierbuflist), [CanOpenDoor()](/api/Global/Model/UnitModel#canopendoor), [GetMovableNode()](/api/Global/Model/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/Global/Model/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/Global/Model/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/Global/Model/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/Global/Model/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/Global/Model/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/Global/Model/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/Global/Model/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/Global/Model/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/Global/Model/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/Global/Model/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/Global/Model/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/Global/Model/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/Global/Model/UnitModel#releasekitcreature-bool), [OnSetWeapon()](/api/Global/Model/UnitModel#onsetweapon), [OnReleaseWeapon()](/api/Global/Model/UnitModel#onreleaseweapon), [OnSetArmor()](/api/Global/Model/UnitModel#onsetarmor), [OnReleaseArmor()](/api/Global/Model/UnitModel#onreleasearmor), [OnChangeGift()](/api/Global/Model/UnitModel#onchangegift), [OnSetKitCreature()](/api/Global/Model/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/Global/Model/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/Global/Model/UnitModel#getweaponspritesrc), [GetWeaponSprite()](/api/Global/Model/UnitModel#getweaponsprite), [PrepareWeapon()](/api/Global/Model/UnitModel#prepareweapon), [CancelWeapon()](/api/Global/Model/UnitModel#cancelweapon), [Attack(UnitModel)](/api/Global/Model/UnitModel#attack-unitmodel), [IsAttackState()](/api/Global/Model/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/Global/Model/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/Global/Model/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/Global/Model/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/Global/Model/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/Global/Model/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/Global/Model/UnitModel#onendattackcycle), [EndAttackAnimation()](/api/Global/Model/UnitModel#endattackanimation), [GetEGObonus()](/api/Global/Model/UnitModel#getegobonus), [HasEquipment(int)](/api/Global/Model/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/Global/Model/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/Global/Model/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/Global/Model/UnitModel#takedamage-damageinfo), [TakeDamageWithoutEffect(UnitModel, DamageInfo)](/api/Global/Model/UnitModel#takedamagewithouteffect-unitmodel-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/Global/Model/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/Global/Model/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/Global/Model/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/Global/Model/UnitModel#checknearworkerencounting), [IsStunned()](/api/Global/Model/UnitModel#isstunned), [SetMoveDelay(float)](/api/Global/Model/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/Global/Model/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/Global/Model/UnitModel#setattackdelay-float), [UpdateBufState()](/api/Global/Model/UnitModel#updatebufstate), [AddUnitBuf(UnitBuf)](/api/Global/Model/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/Global/Model/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/Global/Model/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/Global/Model/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/Global/Model/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/Global/Model/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/Global/Model/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/Global/Model/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/Global/Model/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/Global/Model/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/Global/Model/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/Global/Model/UnitModel#getmovementscalebybuf), [GetFaction()](/api/Global/Model/UnitModel#getfaction), [SetFactionForcely(string)](/api/Global/Model/UnitModel#setfactionforcely-string), [OnStun(float)](/api/Global/Model/UnitModel#onstun-float), [OnStunEnd()](/api/Global/Model/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/Global/Model/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/Global/Model/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/Global/Model/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/Global/Model/UnitModel#getunitbuflist), [Equipment](/api/Global/Model/UnitModel#equipment), [maxHp](/api/Global/Model/UnitModel#maxhp), [maxMental](/api/Global/Model/UnitModel#maxmental), [movement](/api/Global/Model/UnitModel#movement), [regeneration](/api/Global/Model/UnitModel#regeneration), [regenerationDelay](/api/Global/Model/UnitModel#regenerationdelay), [attackSpeed](/api/Global/Model/UnitModel#attackspeed), [damage](/api/Global/Model/UnitModel#damage), [physicalDefense](/api/Global/Model/UnitModel#physicaldefense), [mentalDefense](/api/Global/Model/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EventCreatureModel(long)

```csharp
public EventCreatureModel(long instanceId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instanceId` | `System.Int64` |  |

## Fields

### _eventBase

```csharp
private EventBase _eventBase
```
#INC


#### Field Value

**Type:** Global.EventBase

## Properties

### eventBase

```csharp
public EventBase eventBase { get; private set; }
```

#### Property Value

**Type:** Global.EventBase

## Methods

### Escape()

```csharp
public override void Escape()
```
#INC
#code-generated


### IsHostile(UnitModel)

```csharp
public override bool IsHostile(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### OnDestroy()

```csharp
public void OnDestroy()
```
#INC


### OnFixedUpdate()

```csharp
public override void OnFixedUpdate()
```
#INC


### OnStageRelease()

```csharp
public override void OnStageRelease()
```
#INC


### OnStageStart()

```csharp
public override void OnStageStart()
```
#INC


### SetEventBase(EventBase)

```csharp
public void SetEventBase(EventBase _event)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_event` | `Global.EventBase` |  |
