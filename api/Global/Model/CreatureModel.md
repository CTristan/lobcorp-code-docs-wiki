---
uid: Global.CreatureModel
canonical_path: /api/Global/Model/CreatureModel
---

# Class CreatureModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureModel : UnitModel, IObserver, ISerializablePlayData, IMouseCommandTargetModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/Global/Model/UnitModel) → CreatureModel

## Derived
[ChildCreatureModel](/api/Global/Creature/ChildCreatureModel), [EventCreatureModel](/api/Global/Creature/EventCreatureModel), [OrdealCreatureModel](/api/Global/Creature/OrdealCreatureModel), [SefiraBossCreatureModel](/api/Global/Creature/SefiraBossCreatureModel)

## Implements
[IObserver](/api/Global/Misc/IObserver), [ISerializablePlayData](/api/Global/Misc/ISerializablePlayData), [IMouseCommandTargetModel](/api/Global/Model/IMouseCommandTargetModel)

## Inherited Members
[stunCriteria](/api/Global/Model/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/Global/Model/UnitModel#defaultstuneffectsrc), [instanceId](/api/Global/Model/UnitModel#instanceid), [movableNode](/api/Global/Model/UnitModel#movablenode), [shield](/api/Global/Model/UnitModel#shield), [_equipment](/api/Global/Model/UnitModel#equipment), [tempAnim](/api/Global/Model/UnitModel#tempanim), [factionTypeInfo](/api/Global/Model/UnitModel#factiontypeinfo), [stunTimer](/api/Global/Model/UnitModel#stuntimer), [hp](/api/Global/Model/UnitModel#hp), [mental](/api/Global/Model/UnitModel#mental), [baseMaxHp](/api/Global/Model/UnitModel#basemaxhp), [baseMaxMental](/api/Global/Model/UnitModel#basemaxmental), [baseMovement](/api/Global/Model/UnitModel#basemovement), [baseRegeneration](/api/Global/Model/UnitModel#baseregeneration), [baseRegenerationDelay](/api/Global/Model/UnitModel#baseregenerationdelay), [additionalDef](/api/Global/Model/UnitModel#additionaldef), [superArmorMax](/api/Global/Model/UnitModel#superarmormax), [superArmor](/api/Global/Model/UnitModel#superarmor), [superArmorDefense](/api/Global/Model/UnitModel#superarmordefense), [remainMoveDelay](/api/Global/Model/UnitModel#remainmovedelay), [remainAttackDelay](/api/Global/Model/UnitModel#remainattackdelay), [isStun](/api/Global/Model/UnitModel#isstun), [damageTransform](/api/Global/Model/UnitModel#damagetransform), [basePhysicalDefense](/api/Global/Model/UnitModel#basephysicaldefense), [baseMentalDefense](/api/Global/Model/UnitModel#basementaldefense), [encounteredWorker](/api/Global/Model/UnitModel#encounteredworker), [_bufList](/api/Global/Model/UnitModel#buflist), [_statBufList](/api/Global/Model/UnitModel#statbuflist), [_barrierBufList](/api/Global/Model/UnitModel#barrierbuflist), [CanOpenDoor()](/api/Global/Model/UnitModel#canopendoor), [GetMovableNode()](/api/Global/Model/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/Global/Model/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/Global/Model/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/Global/Model/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/Global/Model/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/Global/Model/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/Global/Model/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/Global/Model/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/Global/Model/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/Global/Model/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/Global/Model/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/Global/Model/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/Global/Model/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/Global/Model/UnitModel#releasekitcreature-bool), [OnSetWeapon()](/api/Global/Model/UnitModel#onsetweapon), [OnReleaseWeapon()](/api/Global/Model/UnitModel#onreleaseweapon), [OnSetArmor()](/api/Global/Model/UnitModel#onsetarmor), [OnReleaseArmor()](/api/Global/Model/UnitModel#onreleasearmor), [OnChangeGift()](/api/Global/Model/UnitModel#onchangegift), [OnSetKitCreature()](/api/Global/Model/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/Global/Model/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/Global/Model/UnitModel#getweaponspritesrc), [GetWeaponSprite()](/api/Global/Model/UnitModel#getweaponsprite), [PrepareWeapon()](/api/Global/Model/UnitModel#prepareweapon), [CancelWeapon()](/api/Global/Model/UnitModel#cancelweapon), [Attack(UnitModel)](/api/Global/Model/UnitModel#attack-unitmodel), [IsAttackState()](/api/Global/Model/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/Global/Model/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/Global/Model/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/Global/Model/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/Global/Model/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/Global/Model/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/Global/Model/UnitModel#onendattackcycle), [EndAttackAnimation()](/api/Global/Model/UnitModel#endattackanimation), [GetEGObonus()](/api/Global/Model/UnitModel#getegobonus), [HasEquipment(int)](/api/Global/Model/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/Global/Model/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/Global/Model/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/Global/Model/UnitModel#takedamage-damageinfo), [TakeDamageWithoutEffect(UnitModel, DamageInfo)](/api/Global/Model/UnitModel#takedamagewithouteffect-unitmodel-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/Global/Model/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/Global/Model/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/Global/Model/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/Global/Model/UnitModel#checknearworkerencounting), [IsStunned()](/api/Global/Model/UnitModel#isstunned), [SetMoveDelay(float)](/api/Global/Model/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/Global/Model/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/Global/Model/UnitModel#setattackdelay-float), [UpdateBufState()](/api/Global/Model/UnitModel#updatebufstate), [AddUnitBuf(UnitBuf)](/api/Global/Model/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/Global/Model/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/Global/Model/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/Global/Model/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/Global/Model/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/Global/Model/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/Global/Model/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/Global/Model/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/Global/Model/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/Global/Model/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/Global/Model/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/Global/Model/UnitModel#getmovementscalebybuf), [GetFaction()](/api/Global/Model/UnitModel#getfaction), [SetFactionForcely(string)](/api/Global/Model/UnitModel#setfactionforcely-string), [OnStun(float)](/api/Global/Model/UnitModel#onstun-float), [OnStunEnd()](/api/Global/Model/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/Global/Model/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/Global/Model/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/Global/Model/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/Global/Model/UnitModel#getunitbuflist), [Equipment](/api/Global/Model/UnitModel#equipment), [maxHp](/api/Global/Model/UnitModel#maxhp), [maxMental](/api/Global/Model/UnitModel#maxmental), [movement](/api/Global/Model/UnitModel#movement), [regeneration](/api/Global/Model/UnitModel#regeneration), [regenerationDelay](/api/Global/Model/UnitModel#regenerationdelay), [attackSpeed](/api/Global/Model/UnitModel#attackspeed), [damage](/api/Global/Model/UnitModel#damage), [physicalDefense](/api/Global/Model/UnitModel#physicaldefense), [mentalDefense](/api/Global/Model/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureModel(long)

```csharp
public CreatureModel(long instanceId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instanceId` | `System.Int64` |  |

## Fields

### _activated

```csharp
private bool _activated
```

#### Field Value

**Type:** System.Boolean

### _currentSkill

```csharp
private UseSkill _currentSkill
```

#### Field Value

**Type:** Global.UseSkill

### _probReductionCounter

```csharp
private int _probReductionCounter
```

#### Field Value

**Type:** System.Int32

### _probReductionValue

```csharp
private int _probReductionValue
```

#### Field Value

**Type:** System.Int32

### _qliphothCounter

```csharp
private int _qliphothCounter
```

#### Field Value

**Type:** System.Int32

### _state

```csharp
protected CreatureState _state
```

#### Field Value

**Type:** Global.CreatureState

### _unit

```csharp
protected CreatureUnit _unit
```

#### Field Value

**Type:** Global.CreatureUnit

### basePosition

```csharp
public Vector2 basePosition
```

#### Field Value

**Type:** UnityEngine.Vector2

### canBeSuppressed

```csharp
public bool canBeSuppressed
```

#### Field Value

**Type:** System.Boolean

### careTakingRegion

```csharp
public static string[] careTakingRegion
```

#### Field Value

**Type:** System.String[]

### childInst

```csharp
private long childInst
```

#### Field Value

**Type:** System.Int64

### childs

```csharp
private List<ChildCreatureModel> childs
```

#### Field Value

**Type:** System.Collections.Generic.List{ChildCreatureModel}

### commandQueue

```csharp
public CreatureCommandQueue commandQueue
```

#### Field Value

**Type:** Global.CreatureCommandQueue

### counter

```csharp
private static int counter
```

#### Field Value

**Type:** System.Int32

### currentOverloadMaxTime

```csharp
public float currentOverloadMaxTime
```

#### Field Value

**Type:** System.Single

### customNode

```csharp
private MapNode customNode
```

#### Field Value

**Type:** Global.MapNode

### defenseId

```csharp
private string defenseId
```

#### Field Value

**Type:** System.String

### entryNode

```csharp
public MapNode entryNode
```

#### Field Value

**Type:** Global.MapNode

### entryNodeId

```csharp
public string entryNodeId
```

#### Field Value

**Type:** System.String

### feelingState

```csharp
public CreatureFeelingState feelingState
```

#### Field Value

**Type:** Global.CreatureFeelingState

### feelingStateRemainTime

```csharp
public float feelingStateRemainTime
```

#### Field Value

**Type:** System.Single

### isolateRoomData

```csharp
public SefiraIsolate isolateRoomData
```

#### Field Value

**Type:** Global.SefiraIsolate

### isOverloaded

```csharp
public bool isOverloaded
```

#### Field Value

**Type:** System.Boolean

### kitEquipOwner

```csharp
public AgentModel kitEquipOwner
```

#### Field Value

**Type:** Global.AgentModel

### metadataId

```csharp
public long metadataId
```

#### Field Value

**Type:** System.Int64

### metaInfo

```csharp
public CreatureTypeInfo metaInfo
```

#### Field Value

**Type:** Global.CreatureTypeInfo

### movementScale

```csharp
public float movementScale
```

#### Field Value

**Type:** System.Single

### narrationList

```csharp
public List<string> narrationList
```

#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### observeInfo

```csharp
public CreatureObserveInfoModel observeInfo
```

#### Field Value

**Type:** Global.CreatureObserveInfoModel

### overloadLevel

```csharp
public int overloadLevel
```

#### Field Value

**Type:** System.Int32

### overloadTime

```csharp
public const float overloadTime = 60
```

#### Field Value

**Type:** System.Single

### overloadTimer

```csharp
public float overloadTimer
```

#### Field Value

**Type:** System.Single

### overloadType

```csharp
public OverloadType overloadType
```

#### Field Value

**Type:** Global.OverloadType

### regionName

```csharp
public static string[] regionName
```

#### Field Value

**Type:** System.String[]

### roomNode

```csharp
public MapNode roomNode
```

#### Field Value

**Type:** Global.MapNode

### script

```csharp
public CreatureBase script
```

#### Field Value

**Type:** Global.CreatureBase

### sefira

```csharp
public Sefira sefira
```

#### Field Value

**Type:** Global.Sefira

### sefiraNum

```csharp
public string sefiraNum
```

#### Field Value

**Type:** System.String

### sefiraOrigin

```csharp
public Sefira sefiraOrigin
```

#### Field Value

**Type:** Global.Sefira

### specialSkillPos

```csharp
public IsolatePos specialSkillPos
```

#### Field Value

**Type:** Global.IsolatePos

### suppressReturnTimer

```csharp
public float suppressReturnTimer
```

#### Field Value

**Type:** System.Single

### workCount

```csharp
public int workCount
```

#### Field Value

**Type:** System.Int32

### workspaceNode

```csharp
private MapNode workspaceNode
```

#### Field Value

**Type:** Global.MapNode

## Properties

### activated

```csharp
public bool activated { get; }
```

#### Property Value

**Type:** System.Boolean

### currentSkill

```csharp
public UseSkill currentSkill { get; set; }
```

#### Property Value

**Type:** Global.UseSkill

### defense

```csharp
public override DefenseInfo defense { get; }
```

#### Property Value

**Type:** Global.DefenseInfo

### InstanceID

```csharp
public Guid InstanceID { get; private set; }
```

#### Property Value

**Type:** System.Guid

### probReductionCounter

```csharp
public int probReductionCounter { get; }
```

#### Property Value

**Type:** System.Int32

### ProbReductionValue

```csharp
public int ProbReductionValue { get; set; }
```

#### Property Value

**Type:** System.Int32

### qliphothCounter

```csharp
public int qliphothCounter { get; }
```

#### Property Value

**Type:** System.Int32

### radius

```csharp
public override float radius { get; }
```

#### Property Value

**Type:** System.Single

### state

```csharp
public CreatureState state { get; set; }
```

#### Property Value

**Type:** Global.CreatureState

### Unit

```csharp
public CreatureUnit Unit { get; }
```

#### Property Value

**Type:** Global.CreatureUnit

## Methods

### ActivateOverload(int, float, OverloadType)

```csharp
public void ActivateOverload(int level, float iOverloadTime = 60, OverloadType overloadType = OverloadType.DEFAULT)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |
| `iOverloadTime` | `System.Single` |  |
| `overloadType` | `Global.OverloadType` |  |

### AddChildCreatureModel()

```csharp
public long AddChildCreatureModel()
```

#### Returns

**Type:** System.Int64

### AddChildCreatureModel(string, string)

```csharp
public long AddChildCreatureModel(string childScriptBase, string childPrefab)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `childScriptBase` | `System.String` |  |
| `childPrefab` | `System.String` |  |

#### Returns

**Type:** System.Int64

### AddCreatureSuccessCube(int)

```csharp
public void AddCreatureSuccessCube(int count)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `count` | `System.Int32` |  |

### AddObservationLevel()

```csharp
public void AddObservationLevel()
```

### AddProbReductionCounter()

```csharp
public void AddProbReductionCounter()
```

### AddQliphothCounter()

```csharp
public void AddQliphothCounter()
```

### AddWorkCount()

```csharp
public void AddWorkCount()
```

### AttackTarget(AttackCommand_creature)

```csharp
public void AttackTarget(AttackCommand_creature cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.AttackCommand_creature` |  |

### CancelOverload()

```csharp
public void CancelOverload()
```

### CanPurhcase(int)

```csharp
public bool CanPurhcase(int cost)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cost` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### ChangePos(CreatureModel)

```csharp
public void ChangePos(CreatureModel changed)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `changed` | `Global.CreatureModel` |  |

### ClearCommand()

```csharp
public void ClearCommand()
```

### ClearProbReduction()

```csharp
public void ClearProbReduction()
```

### ConvertCodeIDToName(string)

```csharp
public string ConvertCodeIDToName(string origin)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |

#### Returns

**Type:** System.String

### ConvertCodeIDToNameForcely(string)

```csharp
public string ConvertCodeIDToNameForcely(string origin)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |

#### Returns

**Type:** System.String

### ConvertNarrationCodeIDToName()

```csharp
public void ConvertNarrationCodeIDToName()
```

### CopyNodeData(CreatureModel)

```csharp
public void CopyNodeData(CreatureModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |

### DeleteChildCreatureModel(long)

```csharp
public void DeleteChildCreatureModel(long instId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instId` | `System.Int64` |  |

### Escape()

```csharp
public virtual void Escape()
```

### EscapeWithoutIsolateRoom()

```csharp
public virtual void EscapeWithoutIsolateRoom()
```

### ExplodeOverload()

```csharp
public void ExplodeOverload()
```

### FinishReturn()

```csharp
public void FinishReturn()
```

### ForcelyCancelSuppress()

```csharp
public void ForcelyCancelSuppress()
```

### GetAliveChilds()

```csharp
public List<ChildCreatureModel> GetAliveChilds()
```

#### Returns

**Type:** System.Collections.Generic.List{ChildCreatureModel}

### GetAnimScript()

```csharp
public CreatureAnimScript GetAnimScript()
```

#### Returns

**Type:** Global.CreatureAnimScript

### GetAttackLevel()

```csharp
public override int GetAttackLevel()
```

#### Returns

**Type:** System.Int32

### GetChildCreatureModel(long)

```csharp
public ChildCreatureModel GetChildCreatureModel(long instID)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instID` | `System.Int64` |  |

#### Returns

**Type:** Global.ChildCreatureModel

### GetConnectedUnitModel()

```csharp
public UnitModel GetConnectedUnitModel()
```

#### Returns

**Type:** Global.UnitModel

### GetCreatureCurrentCmd()

```csharp
public CreatureCommand GetCreatureCurrentCmd()
```

#### Returns

**Type:** Global.CreatureCommand

### GetCubeSpeed()

```csharp
public float GetCubeSpeed()
```

#### Returns

**Type:** System.Single

### GetCurrentCommand()

```csharp
public virtual CreatureCommand GetCurrentCommand()
```

#### Returns

**Type:** Global.CreatureCommand

### GetCurrentCumlatvieCube()

```csharp
public int GetCurrentCumlatvieCube()
```

#### Returns

**Type:** System.Int32

### GetCurrentEdge()

```csharp
public virtual MapEdge GetCurrentEdge()
```

#### Returns

**Type:** Global.MapEdge

### GetCurrentNode()

```csharp
public virtual MapNode GetCurrentNode()
```

#### Returns

**Type:** Global.MapNode

### GetCustomNode()

```csharp
public MapNode GetCustomNode()
```

#### Returns

**Type:** Global.MapNode

### GetDefenseLevel()

```csharp
public override int GetDefenseLevel()
```

#### Returns

**Type:** System.Int32

### GetDirection()

```csharp
public UnitDirection GetDirection()
```

#### Returns

**Type:** Global.UnitDirection

### GetEntryNode()

```csharp
public MapNode GetEntryNode()
```

#### Returns

**Type:** Global.MapNode

### GetFeelingPercent()

```csharp
public float GetFeelingPercent()
```

#### Returns

**Type:** System.Single

### GetFeelingState()

```csharp
public CreatureFeelingState GetFeelingState()
```

#### Returns

**Type:** Global.CreatureFeelingState

### GetMaxWorkCount()

```csharp
public int GetMaxWorkCount()
```

#### Returns

**Type:** System.Int32

### GetMaxWorkCountView()

```csharp
public int GetMaxWorkCountView()
```

#### Returns

**Type:** System.Int32

### GetNearWorkerEncounted()

```csharp
public List<WorkerModel> GetNearWorkerEncounted()
```

#### Returns

**Type:** System.Collections.Generic.List{WorkerModel}

### GetNeedObservePoint()

```csharp
public int GetNeedObservePoint()
```

#### Returns

**Type:** System.Int32

### GetObservationConditionPoint()

```csharp
public int GetObservationConditionPoint()
```

#### Returns

**Type:** System.Int32

### GetObservationLevel()

```csharp
public int GetObservationLevel()
```

#### Returns

**Type:** System.Int32

### GetObserveBonusProb()

```csharp
public int GetObserveBonusProb()
```

#### Returns

**Type:** System.Int32

### GetObserveBonusSpeed()

```csharp
public int GetObserveBonusSpeed()
```

#### Returns

**Type:** System.Int32

### GetRedusedWorkProbByCounter()

```csharp
public int GetRedusedWorkProbByCounter()
```

#### Returns

**Type:** System.Int32

### GetRiskLevel()

```csharp
public override int GetRiskLevel()
```

#### Returns

**Type:** System.Int32

### GetRoomNode()

```csharp
public MapNode GetRoomNode()
```

#### Returns

**Type:** Global.MapNode

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetUnitName()

```csharp
public override string GetUnitName()
```

#### Returns

**Type:** System.String

### GetUnitName(CreatureTypeInfo, CreatureObserveInfoModel)

```csharp
public static string GetUnitName(CreatureTypeInfo metaInfo, CreatureObserveInfoModel observeInfo)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metaInfo` | `Global.CreatureTypeInfo` |  |
| `observeInfo` | `Global.CreatureObserveInfoModel` |  |

#### Returns

**Type:** System.String

### GetWorkspaceNode()

```csharp
public MapNode GetWorkspaceNode()
```

#### Returns

**Type:** Global.MapNode

### GetWorkSuccessProb(AgentModel, SkillTypeInfo)

```csharp
public float GetWorkSuccessProb(AgentModel actor, SkillTypeInfo skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |
| `skill` | `Global.SkillTypeInfo` |  |

#### Returns

**Type:** System.Single

### InteractWithDoor(DoorObjectModel)

```csharp
public override void InteractWithDoor(DoorObjectModel door)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `door` | `Global.DoorObjectModel` |  |

### IsAttackTargetable()

```csharp
public override bool IsAttackTargetable()
```

#### Returns

**Type:** System.Boolean

### IsEscaped()

```csharp
public bool IsEscaped()
```

#### Returns

**Type:** System.Boolean

### IsEscapedOnlyEscape()

```csharp
public bool IsEscapedOnlyEscape()
```

#### Returns

**Type:** System.Boolean

### IsHostile(UnitModel)

```csharp
public override bool IsHostile(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### isPrevMaxObserve()

```csharp
public bool isPrevMaxObserve()
```

#### Returns

**Type:** System.Boolean

### IsWorkCountFull()

```csharp
public bool IsWorkCountFull()
```

#### Returns

**Type:** System.Boolean

### IsWorkingState()

```csharp
public bool IsWorkingState()
```

#### Returns

**Type:** System.Boolean

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### MakeSpatteredBlood()

```csharp
public void MakeSpatteredBlood()
```

### MoveToMovable(MovableObjectNode)

```csharp
public void MoveToMovable(MovableObjectNode movable)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `movable` | `Global.MovableObjectNode` |  |

### MoveToNode(MapNode)

```csharp
public void MoveToNode(MapNode mapNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mapNode` | `Global.MapNode` |  |

### OnActivateAgentDeadPenalty()

```csharp
public void OnActivateAgentDeadPenalty()
```

### OnChangeProbReduectionCounter()

```csharp
private void OnChangeProbReduectionCounter()
```

### OnComplexAttackInWork()

```csharp
public void OnComplexAttackInWork()
```

### OnEscapeUpdate()

```csharp
public virtual void OnEscapeUpdate()
```

### OnFixedUpdate()

```csharp
public virtual void OnFixedUpdate()
```

### OnFixedUpdateInKitEquip(AgentModel)

```csharp
public void OnFixedUpdateInKitEquip(AgentModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

### OnGameInit()

```csharp
public virtual void OnGameInit()
```

### OnMentalAttackInWork()

```csharp
public void OnMentalAttackInWork()
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

### OnObservationLevelChanged()

```csharp
public void OnObservationLevelChanged()
```

### OnPhysicsAttackInWork()

```csharp
public void OnPhysicsAttackInWork()
```

### OnRevealSpecialSkillTip(string, params object[])

```csharp
public void OnRevealSpecialSkillTip(string key, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageEnd()

```csharp
public virtual void OnStageEnd()
```

### OnStageRelease()

```csharp
public virtual void OnStageRelease()
```

### OnStageStart()

```csharp
public virtual void OnStageStart()
```

### OnStopMovableByShield(AgentModel)

```csharp
public override void OnStopMovableByShield(AgentModel shielder)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `shielder` | `Global.AgentModel` |  |

### OnSuperArmorBreak()

```csharp
public override void OnSuperArmorBreak()
```

### PlayAttackAnimation(string)

```csharp
protected override void PlayAttackAnimation(string animationName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animationName` | `System.String` |  |

### PursueWorker(WorkerModel)

```csharp
public virtual void PursueWorker(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### PursueWorkerAlter(WorkerModel, float)

```csharp
public virtual void PursueWorkerAlter(WorkerModel target, float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `damage` | `System.Single` |  |

### PursueWorkerAlter(WorkerModel, RwbpType, int, int)

```csharp
public virtual void PursueWorkerAlter(WorkerModel target, RwbpType dmgType, int dmgMin, int dmgMax)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `dmgType` | `Global.RwbpType` |  |
| `dmgMin` | `System.Int32` |  |
| `dmgMax` | `System.Int32` |  |

### ResetAttackDelay()

```csharp
public void ResetAttackDelay()
```

### ResetAttackDelay(float)

```csharp
public void ResetAttackDelay(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### ResetProbReductionCounter()

```csharp
public void ResetProbReductionCounter()
```

### ResetQliphothCounter()

```csharp
public void ResetQliphothCounter()
```

### ResetWorkCount()

```csharp
public void ResetWorkCount()
```

### SendAnimMessage(string)

```csharp
public virtual void SendAnimMessage(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

### SetActivatedState(bool)

```csharp
public void SetActivatedState(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetCurrentNode(MapNode)

```csharp
public virtual void SetCurrentNode(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### SetCustomNode(MapNode)

```csharp
public void SetCustomNode(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### SetDefenseId(string)

```csharp
public void SetDefenseId(string id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

### SetFaction(FactionTypeInfo)

```csharp
public override void SetFaction(FactionTypeInfo type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.FactionTypeInfo` |  |

### SetFaction(string)

```csharp
public override void SetFaction(string factionCode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factionCode` | `System.String` |  |

### SetFeelingStateInWork(CreatureFeelingState)

```csharp
public void SetFeelingStateInWork(CreatureFeelingState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.CreatureFeelingState` |  |

### SetMoveAnimState(bool)

```csharp
public virtual void SetMoveAnimState(bool b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `System.Boolean` |  |

### SetPursueWorkerCommand(WorkerModel, CreatureCommand)

```csharp
public virtual void SetPursueWorkerCommand(WorkerModel target, CreatureCommand pursueCommand)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `pursueCommand` | `Global.CreatureCommand` |  |

### SetQliphothCounter(int)

```csharp
public void SetQliphothCounter(int value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Int32` |  |

### SetRoomNode(MapNode)

```csharp
public void SetRoomNode(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### SetUnit(CreatureUnit)

```csharp
public void SetUnit(CreatureUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### SetWorkspaceNode(MapNode)

```csharp
public void SetWorkspaceNode(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### ShowCreatureSpeech(string)

```csharp
public void ShowCreatureSpeech(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

### ShowCreatureSpeech(string, float)

```csharp
public void ShowCreatureSpeech(string key, float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |
| `time` | `System.Single` |  |

### ShowCreatureSpeechDirect(string)

```csharp
public void ShowCreatureSpeechDirect(string desc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `desc` | `System.String` |  |

### ShowCreatureSpeechDirect(string, float)

```csharp
public void ShowCreatureSpeechDirect(string desc, float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `desc` | `System.String` |  |
| `time` | `System.Single` |  |

### ShowNarrationForcely(string)

```csharp
public void ShowNarrationForcely(string desc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `desc` | `System.String` |  |

### ShowNarrationText(string, bool, params string[])

```csharp
public string ShowNarrationText(string narrationKey, bool roomEffect, params string[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `narrationKey` | `System.String` |  |
| `roomEffect` | `System.Boolean` |  |
| `param` | `System.String[]` |  |

#### Returns

**Type:** System.String

### ShowNarrationText(string, params string[])

```csharp
public string ShowNarrationText(string narrationKey, params string[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `narrationKey` | `System.String` |  |
| `param` | `System.String[]` |  |

#### Returns

**Type:** System.String

### ShowProcessNarrationText(string, params string[])

```csharp
public void ShowProcessNarrationText(string narrationKey, params string[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `narrationKey` | `System.String` |  |
| `param` | `System.String[]` |  |

### ShowTextOutside(CreatureOutsideTextLayout, string)

```csharp
public void ShowTextOutside(CreatureOutsideTextLayout layoutType, string textKey)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `layoutType` | `Global.CreatureOutsideTextLayout` |  |
| `textKey` | `System.String` |  |

### SpecialSkillActivated()

```csharp
public void SpecialSkillActivated()
```

### SubCreatureSuccessCube(int)

```csharp
public void SubCreatureSuccessCube(int count)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `count` | `System.Int32` |  |

### SubQliphothCounter()

```csharp
public void SubQliphothCounter()
```

### Suppressed()

```csharp
public virtual void Suppressed()
```

### TakeDamage(UnitModel, DamageInfo)

```csharp
public override void TakeDamage(UnitModel actor, DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### TransactionCube(int)

```csharp
public bool TransactionCube(int cost)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cost` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### UpdateQliphothCounter()

```csharp
private void UpdateQliphothCounter()
```

### WorkParamInit()

```csharp
public void WorkParamInit()
```
