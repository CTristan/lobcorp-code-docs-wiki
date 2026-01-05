# Class ChildCreatureModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChildCreatureModel : CreatureModel, IMouseCommandTargetModel, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/UnitModel) → [CreatureModel](/api/CreatureModel) → ChildCreatureModel

## Inherited Members
[regionName](/api/CreatureModel#regionname), [careTakingRegion](/api/CreatureModel#caretakingregion), [commandQueue](/api/CreatureModel#commandqueue), [canBeSuppressed](/api/CreatureModel#canbesuppressed), [metaInfo](/api/CreatureModel#metainfo), [metadataId](/api/CreatureModel#metadataid), [script](/api/CreatureModel#script), [observeInfo](/api/CreatureModel#observeinfo), [narrationList](/api/CreatureModel#narrationlist), [_state](/api/CreatureModel#state), [feelingState](/api/CreatureModel#feelingstate), [feelingStateRemainTime](/api/CreatureModel#feelingstateremaintime), [suppressReturnTimer](/api/CreatureModel#suppressreturntimer), [sefiraNum](/api/CreatureModel#sefiranum), [sefira](/api/CreatureModel#sefira), [sefiraOrigin](/api/CreatureModel#sefiraorigin), [specialSkillPos](/api/CreatureModel#specialskillpos), [basePosition](/api/CreatureModel#baseposition), [entryNodeId](/api/CreatureModel#entrynodeid), [entryNode](/api/CreatureModel#entrynode), [roomNode](/api/CreatureModel#roomnode), [isolateRoomData](/api/CreatureModel#isolateroomdata), [_unit](/api/CreatureModel#unit), [movementScale](/api/CreatureModel#movementscale), [workCount](/api/CreatureModel#workcount), [overloadLevel](/api/CreatureModel#overloadlevel), [isOverloaded](/api/CreatureModel#isoverloaded), [overloadType](/api/CreatureModel#overloadtype), [currentOverloadMaxTime](/api/CreatureModel#currentoverloadmaxtime), [overloadTimer](/api/CreatureModel#overloadtimer), [overloadTime](/api/CreatureModel#overloadtime), [kitEquipOwner](/api/CreatureModel#kitequipowner), [GetSaveData()](/api/CreatureModel#getsavedata), [LoadData(Dictionary<string, object>)](/api/CreatureModel#loaddata-dictionary-string-object), [WorkParamInit()](/api/CreatureModel#workparaminit), [OnGameInit()](/api/CreatureModel#ongameinit), [OnStageStart()](/api/CreatureModel#onstagestart), [OnStageEnd()](/api/CreatureModel#onstageend), [GetUnitName(CreatureTypeInfo, CreatureObserveInfoModel)](/api/CreatureModel#getunitname-creaturetypeinfo-creatureobserveinfomodel), [GetFeelingState()](/api/CreatureModel#getfeelingstate), [CopyNodeData(CreatureModel)](/api/CreatureModel#copynodedata-creaturemodel), [SetRoomNode(MapNode)](/api/CreatureModel#setroomnode-mapnode), [SetCustomNode(MapNode)](/api/CreatureModel#setcustomnode-mapnode), [SetCurrentNode(MapNode)](/api/CreatureModel#setcurrentnode-mapnode), [GetCurrentNode()](/api/CreatureModel#getcurrentnode), [GetCurrentEdge()](/api/CreatureModel#getcurrentedge), [SetWorkspaceNode(MapNode)](/api/CreatureModel#setworkspacenode-mapnode), [GetWorkspaceNode()](/api/CreatureModel#getworkspacenode), [GetEntryNode()](/api/CreatureModel#getentrynode), [GetCustomNode()](/api/CreatureModel#getcustomnode), [GetRoomNode()](/api/CreatureModel#getroomnode), [GetDirection()](/api/CreatureModel#getdirection), [IsWorkingState()](/api/CreatureModel#isworkingstate), [IsEscaped()](/api/CreatureModel#isescaped), [IsEscapedOnlyEscape()](/api/CreatureModel#isescapedonlyescape), [GetConnectedUnitModel()](/api/CreatureModel#getconnectedunitmodel), [PlayAttackAnimation(string)](/api/CreatureModel#playattackanimation-string), [AddWorkCount()](/api/CreatureModel#addworkcount), [ResetWorkCount()](/api/CreatureModel#resetworkcount), [GetMaxWorkCount()](/api/CreatureModel#getmaxworkcount), [GetMaxWorkCountView()](/api/CreatureModel#getmaxworkcountview), [IsWorkCountFull()](/api/CreatureModel#isworkcountfull), [AddProbReductionCounter()](/api/CreatureModel#addprobreductioncounter), [ResetProbReductionCounter()](/api/CreatureModel#resetprobreductioncounter), [GetRedusedWorkProbByCounter()](/api/CreatureModel#getredusedworkprobbycounter), [OnActivateAgentDeadPenalty()](/api/CreatureModel#onactivateagentdeadpenalty), [ActivateOverload(int, float, OverloadType)](/api/CreatureModel#activateoverload-int-float-overloadtype), [ExplodeOverload()](/api/CreatureModel#explodeoverload), [ClearProbReduction()](/api/CreatureModel#clearprobreduction), [CancelOverload()](/api/CreatureModel#canceloverload), [GetNearWorkerEncounted()](/api/CreatureModel#getnearworkerencounted), [ShowTextOutside(CreatureOutsideTextLayout, string)](/api/CreatureModel#showtextoutside-creatureoutsidetextlayout-string), [ShowNarrationText(string, params string[])](/api/CreatureModel#shownarrationtext-string-params-string), [ShowNarrationText(string, bool, params string[])](/api/CreatureModel#shownarrationtext-string-bool-params-string), [ShowNarrationForcely(string)](/api/CreatureModel#shownarrationforcely-string), [ShowProcessNarrationText(string, params string[])](/api/CreatureModel#showprocessnarrationtext-string-params-string), [EscapeWithoutIsolateRoom()](/api/CreatureModel#escapewithoutisolateroom), [ResetAttackDelay()](/api/CreatureModel#resetattackdelay), [ResetAttackDelay(float)](/api/CreatureModel#resetattackdelay-float), [TakeDamage(UnitModel, DamageInfo)](/api/CreatureModel#takedamage-unitmodel-damageinfo), [OnSuperArmorBreak()](/api/CreatureModel#onsuperarmorbreak), [IsHostile(UnitModel)](/api/CreatureModel#ishostile-unitmodel), [GetAttackLevel()](/api/CreatureModel#getattacklevel), [GetDefenseLevel()](/api/CreatureModel#getdefenselevel), [SetFeelingStateInWork(CreatureFeelingState)](/api/CreatureModel#setfeelingstateinwork-creaturefeelingstate), [ClearCommand()](/api/CreatureModel#clearcommand), [MoveToNode(MapNode)](/api/CreatureModel#movetonode-mapnode), [MoveToMovable(MovableObjectNode)](/api/CreatureModel#movetomovable-movableobjectnode), [AttackTarget(AttackCommand_creature)](/api/CreatureModel#attacktarget-attackcommand-creature), [PursueWorkerAlter(WorkerModel, float)](/api/CreatureModel#pursueworkeralter-workermodel-float), [PursueWorkerAlter(WorkerModel, RwbpType, int, int)](/api/CreatureModel#pursueworkeralter-workermodel-rwbptype-int-int), [SetPursueWorkerCommand(WorkerModel, CreatureCommand)](/api/CreatureModel#setpursueworkercommand-workermodel-creaturecommand), [FinishReturn()](/api/CreatureModel#finishreturn), [GetAnimScript()](/api/CreatureModel#getanimscript), [InteractWithDoor(DoorObjectModel)](/api/CreatureModel#interactwithdoor-doorobjectmodel), [OnStopMovableByShield(AgentModel)](/api/CreatureModel#onstopmovablebyshield-agentmodel), [GetFeelingPercent()](/api/CreatureModel#getfeelingpercent), [AddObservationLevel()](/api/CreatureModel#addobservationlevel), [OnObservationLevelChanged()](/api/CreatureModel#onobservationlevelchanged), [AddCreatureSuccessCube(int)](/api/CreatureModel#addcreaturesuccesscube-int), [SubCreatureSuccessCube(int)](/api/CreatureModel#subcreaturesuccesscube-int), [GetObservationConditionPoint()](/api/CreatureModel#getobservationconditionpoint), [GetNeedObservePoint()](/api/CreatureModel#getneedobservepoint), [GetCreatureCurrentCmd()](/api/CreatureModel#getcreaturecurrentcmd), [SetUnit(CreatureUnit)](/api/CreatureModel#setunit-creatureunit), [ShowCreatureSpeech(string)](/api/CreatureModel#showcreaturespeech-string), [ShowCreatureSpeech(string, float)](/api/CreatureModel#showcreaturespeech-string-float), [ShowCreatureSpeechDirect(string)](/api/CreatureModel#showcreaturespeechdirect-string), [ShowCreatureSpeechDirect(string, float)](/api/CreatureModel#showcreaturespeechdirect-string-float), [SpecialSkillActivated()](/api/CreatureModel#specialskillactivated), [OnPhysicsAttackInWork()](/api/CreatureModel#onphysicsattackinwork), [OnMentalAttackInWork()](/api/CreatureModel#onmentalattackinwork), [OnComplexAttackInWork()](/api/CreatureModel#oncomplexattackinwork), [ConvertNarrationCodeIDToName()](/api/CreatureModel#convertnarrationcodeidtoname), [ConvertCodeIDToName(string)](/api/CreatureModel#convertcodeidtoname-string), [ConvertCodeIDToNameForcely(string)](/api/CreatureModel#convertcodeidtonameforcely-string), [OnRevealSpecialSkillTip(string, params object[])](/api/CreatureModel#onrevealspecialskilltip-string-params-object), [MakeSpatteredBlood()](/api/CreatureModel#makespatteredblood), [GetWorkSuccessProb(AgentModel, SkillTypeInfo)](/api/CreatureModel#getworksuccessprob-agentmodel-skilltypeinfo), [GetCubeSpeed()](/api/CreatureModel#getcubespeed), [isPrevMaxObserve()](/api/CreatureModel#isprevmaxobserve), [ChangePos(CreatureModel)](/api/CreatureModel#changepos-creaturemodel), [AddChildCreatureModel()](/api/CreatureModel#addchildcreaturemodel), [AddChildCreatureModel(string, string)](/api/CreatureModel#addchildcreaturemodel-string-string), [GetChildCreatureModel(long)](/api/CreatureModel#getchildcreaturemodel-long), [GetAliveChilds()](/api/CreatureModel#getalivechilds), [DeleteChildCreatureModel(long)](/api/CreatureModel#deletechildcreaturemodel-long), [GetCurrentCommand()](/api/CreatureModel#getcurrentcommand), [SetFaction(FactionTypeInfo)](/api/CreatureModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/CreatureModel#setfaction-string), [SetActivatedState(bool)](/api/CreatureModel#setactivatedstate-bool), [ForcelyCancelSuppress()](/api/CreatureModel#forcelycancelsuppress), [SetDefenseId(string)](/api/CreatureModel#setdefenseid-string), [ResetQliphothCounter()](/api/CreatureModel#resetqliphothcounter), [SubQliphothCounter()](/api/CreatureModel#subqliphothcounter), [AddQliphothCounter()](/api/CreatureModel#addqliphothcounter), [SetQliphothCounter(int)](/api/CreatureModel#setqliphothcounter-int), [GetCurrentCumlatvieCube()](/api/CreatureModel#getcurrentcumlatviecube), [CanPurhcase(int)](/api/CreatureModel#canpurhcase-int), [TransactionCube(int)](/api/CreatureModel#transactioncube-int), [GetObservationLevel()](/api/CreatureModel#getobservationlevel), [OnFixedUpdateInKitEquip(AgentModel)](/api/CreatureModel#onfixedupdateinkitequip-agentmodel), [GetObserveBonusProb()](/api/CreatureModel#getobservebonusprob), [GetObserveBonusSpeed()](/api/CreatureModel#getobservebonusspeed), [state](/api/CreatureModel#state), [radius](/api/CreatureModel#radius), [currentSkill](/api/CreatureModel#currentskill), [InstanceID](/api/CreatureModel#instanceid), [defense](/api/CreatureModel#defense), [qliphothCounter](/api/CreatureModel#qliphothcounter), [probReductionCounter](/api/CreatureModel#probreductioncounter), [ProbReductionValue](/api/CreatureModel#probreductionvalue), [activated](/api/CreatureModel#activated), [stunCriteria](/api/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/UnitModel#defaultstuneffectsrc), [instanceId](/api/UnitModel#instanceid), [movableNode](/api/UnitModel#movablenode), [shield](/api/UnitModel#shield), [_equipment](/api/UnitModel#equipment), [tempAnim](/api/UnitModel#tempanim), [factionTypeInfo](/api/UnitModel#factiontypeinfo), [stunTimer](/api/UnitModel#stuntimer), [hp](/api/UnitModel#hp), [mental](/api/UnitModel#mental), [baseMaxHp](/api/UnitModel#basemaxhp), [baseMaxMental](/api/UnitModel#basemaxmental), [baseMovement](/api/UnitModel#basemovement), [baseRegeneration](/api/UnitModel#baseregeneration), [baseRegenerationDelay](/api/UnitModel#baseregenerationdelay), [additionalDef](/api/UnitModel#additionaldef), [superArmorMax](/api/UnitModel#superarmormax), [superArmor](/api/UnitModel#superarmor), [superArmorDefense](/api/UnitModel#superarmordefense), [remainMoveDelay](/api/UnitModel#remainmovedelay), [remainAttackDelay](/api/UnitModel#remainattackdelay), [isStun](/api/UnitModel#isstun), [damageTransform](/api/UnitModel#damagetransform), [basePhysicalDefense](/api/UnitModel#basephysicaldefense), [baseMentalDefense](/api/UnitModel#basementaldefense), [encounteredWorker](/api/UnitModel#encounteredworker), [_bufList](/api/UnitModel#buflist), [_statBufList](/api/UnitModel#statbuflist), [_barrierBufList](/api/UnitModel#barrierbuflist), [CanOpenDoor()](/api/UnitModel#canopendoor), [GetMovableNode()](/api/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/UnitModel#releasekitcreature-bool), [OnSetWeapon()](/api/UnitModel#onsetweapon), [OnReleaseWeapon()](/api/UnitModel#onreleaseweapon), [OnSetArmor()](/api/UnitModel#onsetarmor), [OnReleaseArmor()](/api/UnitModel#onreleasearmor), [OnChangeGift()](/api/UnitModel#onchangegift), [OnSetKitCreature()](/api/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/UnitModel#getweaponspritesrc), [GetWeaponSprite()](/api/UnitModel#getweaponsprite), [PrepareWeapon()](/api/UnitModel#prepareweapon), [CancelWeapon()](/api/UnitModel#cancelweapon), [Attack(UnitModel)](/api/UnitModel#attack-unitmodel), [IsAttackState()](/api/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/UnitModel#onendattackcycle), [EndAttackAnimation()](/api/UnitModel#endattackanimation), [GetEGObonus()](/api/UnitModel#getegobonus), [HasEquipment(int)](/api/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/UnitModel#takedamage-damageinfo), [TakeDamageWithoutEffect(UnitModel, DamageInfo)](/api/UnitModel#takedamagewithouteffect-unitmodel-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/UnitModel#clearworkerencounting), [IsStunned()](/api/UnitModel#isstunned), [SetMoveDelay(float)](/api/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/UnitModel#setattackdelay-float), [UpdateBufState()](/api/UnitModel#updatebufstate), [AddUnitBuf(UnitBuf)](/api/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/UnitModel#getmovementscalebybuf), [GetFaction()](/api/UnitModel#getfaction), [SetFactionForcely(string)](/api/UnitModel#setfactionforcely-string), [OnStun(float)](/api/UnitModel#onstun-float), [OnStunEnd()](/api/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/UnitModel#getunitbuflist), [Equipment](/api/UnitModel#equipment), [maxHp](/api/UnitModel#maxhp), [maxMental](/api/UnitModel#maxmental), [movement](/api/UnitModel#movement), [regeneration](/api/UnitModel#regeneration), [regenerationDelay](/api/UnitModel#regenerationdelay), [attackSpeed](/api/UnitModel#attackspeed), [damage](/api/UnitModel#damage), [physicalDefense](/api/UnitModel#physicaldefense), [mentalDefense](/api/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ChildCreatureModel(long)

```csharp
public ChildCreatureModel(long instanceId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instanceId` | `System.Int64` |  |

## Fields

### activateState

```csharp
public bool activateState
```

#### Field Value

**Type:** System.Boolean

### animAutoSet

```csharp
public bool animAutoSet
```

#### Field Value

**Type:** System.Boolean

### destroied

```csharp
public bool destroied
```

#### Field Value

**Type:** System.Boolean

### PortraitSrc

```csharp
public string PortraitSrc
```

#### Field Value

**Type:** System.String

### RiskLevel

```csharp
public RiskLevel RiskLevel
```

#### Field Value

**Type:** Global.RiskLevel

## Properties

### childMetaInfo

```csharp
public ChildCreatureTypeInfo childMetaInfo { get; }
```

#### Property Value

**Type:** Global.ChildCreatureTypeInfo

### parent

```csharp
public CreatureModel parent { get; }
```

#### Property Value

**Type:** Global.CreatureModel

### Unit

```csharp
public ChildCreatureUnit Unit { get; }
```

#### Property Value

**Type:** Global.ChildCreatureUnit

## Methods

### CheckNearWorkerEncounting()

```csharp
public List<WorkerModel> CheckNearWorkerEncounting()
```

#### Returns

**Type:** System.Collections.Generic.List{WorkerModel}

### ChildInitialEncounter(WorkerModel)

```csharp
public void ChildInitialEncounter(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### Escape()

```csharp
public override void Escape()
```

### GenCreatureUnit(string)

```csharp
public ChildCreatureUnit GenCreatureUnit(string prefabSrc = null)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `prefabSrc` | `System.String` |  |

#### Returns

**Type:** Global.ChildCreatureUnit

### GetBaseMetaInfo()

```csharp
public CreatureTypeInfo GetBaseMetaInfo()
```

#### Returns

**Type:** Global.CreatureTypeInfo

### GetRiskLevel()

```csharp
public override int GetRiskLevel()
```

#### Returns

**Type:** System.Int32

### GetUnitName()

```csharp
public override string GetUnitName()
```

#### Returns

**Type:** System.String

### IsAttackTargetable()

```csharp
public override bool IsAttackTargetable()
```

#### Returns

**Type:** System.Boolean

### LoadCustom(ChildCreatureUnit, string)

```csharp
public void LoadCustom(ChildCreatureUnit component, string Src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `component` | `Global.ChildCreatureUnit` |  |
| `Src` | `System.String` |  |

### OnDeleted()

```csharp
public void OnDeleted()
```

### OnEscapeUpdate()

```csharp
public override void OnEscapeUpdate()
```

### OnFixedUpdate()

```csharp
public override void OnFixedUpdate()
```

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageRelease()

```csharp
public override void OnStageRelease()
```

### PursueWorker(WorkerModel)

```csharp
public override void PursueWorker(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### SelfDestroy()

```csharp
public void SelfDestroy()
```

### SendAnimMessage(string)

```csharp
public override void SendAnimMessage(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

### SetMoveAnimState(bool)

```csharp
public override void SetMoveAnimState(bool b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `System.Boolean` |  |

### SetParent(CreatureModel)

```csharp
public void SetParent(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### SetParent(CreatureModel, string, string)

```csharp
public void SetParent(CreatureModel creature, string childScriptSrc, string childPrefab)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `childScriptSrc` | `System.String` |  |
| `childPrefab` | `System.String` |  |

### SetSpeed(float)

```csharp
public void SetSpeed(float speed = -1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `speed` | `System.Single` |  |

### Suppressed()

```csharp
public override void Suppressed()
```
