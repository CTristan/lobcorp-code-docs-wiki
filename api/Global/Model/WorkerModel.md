---
uid: Global.WorkerModel
canonical_path: /api/Global/Model/WorkerModel
---

# Class WorkerModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerModel : UnitModel, IObserver, IMouseCommandTargetModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/Global/Model/UnitModel) → WorkerModel

## Derived
[AgentModel](/api/Global/Worker/AgentModel), [OfficerModel](/api/Global/Worker/OfficerModel)

## Implements
[IObserver](/api/Global/Misc/IObserver), [IMouseCommandTargetModel](/api/Global/Model/IMouseCommandTargetModel)

## Inherited Members
[stunCriteria](/api/Global/Model/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/Global/Model/UnitModel#defaultstuneffectsrc), [instanceId](/api/Global/Model/UnitModel#instanceid), [movableNode](/api/Global/Model/UnitModel#movablenode), [shield](/api/Global/Model/UnitModel#shield), [_equipment](/api/Global/Model/UnitModel#equipment), [tempAnim](/api/Global/Model/UnitModel#tempanim), [factionTypeInfo](/api/Global/Model/UnitModel#factiontypeinfo), [stunTimer](/api/Global/Model/UnitModel#stuntimer), [hp](/api/Global/Model/UnitModel#hp), [mental](/api/Global/Model/UnitModel#mental), [baseMaxHp](/api/Global/Model/UnitModel#basemaxhp), [baseMaxMental](/api/Global/Model/UnitModel#basemaxmental), [baseMovement](/api/Global/Model/UnitModel#basemovement), [baseRegeneration](/api/Global/Model/UnitModel#baseregeneration), [baseRegenerationDelay](/api/Global/Model/UnitModel#baseregenerationdelay), [additionalDef](/api/Global/Model/UnitModel#additionaldef), [superArmorMax](/api/Global/Model/UnitModel#superarmormax), [superArmor](/api/Global/Model/UnitModel#superarmor), [superArmorDefense](/api/Global/Model/UnitModel#superarmordefense), [remainMoveDelay](/api/Global/Model/UnitModel#remainmovedelay), [remainAttackDelay](/api/Global/Model/UnitModel#remainattackdelay), [isStun](/api/Global/Model/UnitModel#isstun), [damageTransform](/api/Global/Model/UnitModel#damagetransform), [basePhysicalDefense](/api/Global/Model/UnitModel#basephysicaldefense), [baseMentalDefense](/api/Global/Model/UnitModel#basementaldefense), [encounteredWorker](/api/Global/Model/UnitModel#encounteredworker), [_bufList](/api/Global/Model/UnitModel#buflist), [_statBufList](/api/Global/Model/UnitModel#statbuflist), [_barrierBufList](/api/Global/Model/UnitModel#barrierbuflist), [CanOpenDoor()](/api/Global/Model/UnitModel#canopendoor), [GetUnitName()](/api/Global/Model/UnitModel#getunitname), [OnStopMovableByShield(AgentModel)](/api/Global/Model/UnitModel#onstopmovablebyshield-agentmodel), [GetMovableNode()](/api/Global/Model/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/Global/Model/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/Global/Model/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/Global/Model/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/Global/Model/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/Global/Model/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/Global/Model/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/Global/Model/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/Global/Model/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/Global/Model/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/Global/Model/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/Global/Model/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/Global/Model/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/Global/Model/UnitModel#releasekitcreature-bool), [OnSetWeapon()](/api/Global/Model/UnitModel#onsetweapon), [OnReleaseWeapon()](/api/Global/Model/UnitModel#onreleaseweapon), [OnReleaseArmor()](/api/Global/Model/UnitModel#onreleasearmor), [OnChangeGift()](/api/Global/Model/UnitModel#onchangegift), [OnSetKitCreature()](/api/Global/Model/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/Global/Model/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/Global/Model/UnitModel#getweaponspritesrc), [PrepareWeapon()](/api/Global/Model/UnitModel#prepareweapon), [CancelWeapon()](/api/Global/Model/UnitModel#cancelweapon), [Attack(UnitModel)](/api/Global/Model/UnitModel#attack-unitmodel), [IsAttackState()](/api/Global/Model/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/Global/Model/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/Global/Model/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/Global/Model/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/Global/Model/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/Global/Model/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/Global/Model/UnitModel#onendattackcycle), [EndAttackAnimation()](/api/Global/Model/UnitModel#endattackanimation), [GetEGObonus()](/api/Global/Model/UnitModel#getegobonus), [HasEquipment(int)](/api/Global/Model/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/Global/Model/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/Global/Model/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/Global/Model/UnitModel#takedamage-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/Global/Model/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/Global/Model/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/Global/Model/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/Global/Model/UnitModel#checknearworkerencounting), [IsStunned()](/api/Global/Model/UnitModel#isstunned), [OnSuperArmorBreak()](/api/Global/Model/UnitModel#onsuperarmorbreak), [SetMoveDelay(float)](/api/Global/Model/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/Global/Model/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/Global/Model/UnitModel#setattackdelay-float), [UpdateBufState()](/api/Global/Model/UnitModel#updatebufstate), [GetRiskLevel()](/api/Global/Model/UnitModel#getrisklevel), [GetAttackLevel()](/api/Global/Model/UnitModel#getattacklevel), [GetDefenseLevel()](/api/Global/Model/UnitModel#getdefenselevel), [AddUnitBuf(UnitBuf)](/api/Global/Model/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/Global/Model/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/Global/Model/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/Global/Model/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/Global/Model/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/Global/Model/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/Global/Model/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/Global/Model/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/Global/Model/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/Global/Model/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/Global/Model/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/Global/Model/UnitModel#getmovementscalebybuf), [SetFaction(FactionTypeInfo)](/api/Global/Model/UnitModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/Global/Model/UnitModel#setfaction-string), [GetFaction()](/api/Global/Model/UnitModel#getfaction), [SetFactionForcely(string)](/api/Global/Model/UnitModel#setfactionforcely-string), [OnStunEnd()](/api/Global/Model/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/Global/Model/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/Global/Model/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/Global/Model/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/Global/Model/UnitModel#getunitbuflist), [Equipment](/api/Global/Model/UnitModel#equipment), [radius](/api/Global/Model/UnitModel#radius), [maxHp](/api/Global/Model/UnitModel#maxhp), [maxMental](/api/Global/Model/UnitModel#maxmental), [movement](/api/Global/Model/UnitModel#movement), [regeneration](/api/Global/Model/UnitModel#regeneration), [regenerationDelay](/api/Global/Model/UnitModel#regenerationdelay), [defense](/api/Global/Model/UnitModel#defense), [attackSpeed](/api/Global/Model/UnitModel#attackspeed), [damage](/api/Global/Model/UnitModel#damage), [physicalDefense](/api/Global/Model/UnitModel#physicaldefense), [mentalDefense](/api/Global/Model/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerModel()

```csharp
public WorkerModel()
```

### WorkerModel(int, Sefira)

```csharp
public WorkerModel(int instanceId, Sefira area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instanceId` | `System.Int32` |  |
| `area` | `Global.Sefira` |  |

### WorkerModel(int, string)

```csharp
public WorkerModel(int instanceId, string area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instanceId` | `System.Int32` |  |
| `area` | `System.String` |  |

## Fields

### _attackTargetWorker

```csharp
private WorkerModel _attackTargetWorker
```

#### Field Value

**Type:** Global.WorkerModel

### _currentSefira

```csharp
private string _currentSefira
```

#### Field Value

**Type:** System.String

### _deadType

```csharp
private DeadType _deadType
```

#### Field Value

**Type:** Global.DeadType

### _isDead

```csharp
protected bool _isDead
```

#### Field Value

**Type:** System.Boolean

### _panicData

```csharp
protected PanicData _panicData
```

#### Field Value

**Type:** Global.PanicData

### _recentlyAttacked

```csharp
private CreatureModel _recentlyAttacked
```

#### Field Value

**Type:** Global.CreatureModel

### _revivaledHp

```csharp
protected bool _revivaledHp
```

#### Field Value

**Type:** System.Boolean

### _revivaledMental

```csharp
protected bool _revivaledMental
```

#### Field Value

**Type:** System.Boolean

### _revivalHp

```csharp
protected bool _revivalHp
```

#### Field Value

**Type:** System.Boolean

### _revivalMental

```csharp
protected bool _revivalMental
```

#### Field Value

**Type:** System.Boolean

### _specialDeadScene

```csharp
private bool _specialDeadScene
```

#### Field Value

**Type:** System.Boolean

### animationMessageRecevied

```csharp
public CreatureBase animationMessageRecevied
```

#### Field Value

**Type:** Global.CreatureBase

### blockRecover

```csharp
public bool blockRecover
```

#### Field Value

**Type:** System.Boolean

### commandQueue

```csharp
protected WorkerCommandQueue commandQueue
```

#### Field Value

**Type:** Global.WorkerCommandQueue

### currentPanicAction

```csharp
private PanicAction currentPanicAction
```

#### Field Value

**Type:** Global.PanicAction

### currentSefiraEnum

```csharp
public SefiraEnum currentSefiraEnum
```

#### Field Value

**Type:** Global.SefiraEnum

### deadSceneName

```csharp
protected string deadSceneName
```

#### Field Value

**Type:** System.String

### faceSprite

```csharp
public Sprite faceSprite
```

#### Field Value

**Type:** UnityEngine.Sprite

### gender

```csharp
public string gender
```

#### Field Value

**Type:** System.String

### hairSprite

```csharp
public Sprite hairSprite
```

#### Field Value

**Type:** UnityEngine.Sprite

### haltUpdate

```csharp
public bool haltUpdate
```

#### Field Value

**Type:** System.Boolean

### hasUniqueFace

```csharp
protected bool hasUniqueFace
```

#### Field Value

**Type:** System.Boolean

### invincible

```csharp
public bool invincible
```

#### Field Value

**Type:** System.Boolean

### isChangeableAnimator

```csharp
public bool isChangeableAnimator
```

#### Field Value

**Type:** System.Boolean

### isRealWorker

```csharp
public bool isRealWorker
```

#### Field Value

**Type:** System.Boolean

### lastestMoveTarget

```csharp
public MapNode lastestMoveTarget
```

#### Field Value

**Type:** Global.MapNode

### movementMul

```csharp
public float movementMul
```

#### Field Value

**Type:** System.Single

### name

```csharp
public string name
```

#### Field Value

**Type:** System.String

### OnWorkEndFlag

```csharp
public bool OnWorkEndFlag
```

#### Field Value

**Type:** System.Boolean

### panicValue

```csharp
public int panicValue
```

#### Field Value

**Type:** System.Int32

### puppetChanged

```csharp
public bool puppetChanged
```

#### Field Value

**Type:** System.Boolean

### returnPanic

```csharp
public bool returnPanic
```

#### Field Value

**Type:** System.Boolean

### revivalProb

```csharp
private const float revivalProb = 0.25
```

#### Field Value

**Type:** System.Single

### seperator

```csharp
protected bool seperator
```

#### Field Value

**Type:** System.Boolean

### speechTable

```csharp
public Dictionary<string, string> speechTable
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

### spriteData

```csharp
public WorkerSprite spriteData
```

#### Field Value

**Type:** WorkerSprite.WorkerSprite

### stunEffect

```csharp
public GameObject stunEffect
```

#### Field Value

**Type:** UnityEngine.GameObject

### stunTime

```csharp
public float stunTime
```

#### Field Value

**Type:** System.Single

### target

```csharp
public CreatureModel target
```

#### Field Value

**Type:** Global.CreatureModel

### targetObject

```csharp
public StandingItemModel targetObject
```

#### Field Value

**Type:** Global.StandingItemModel

### targetWorker

```csharp
public WorkerModel targetWorker
```

#### Field Value

**Type:** Global.WorkerModel

### unconAction

```csharp
public UncontrollableAction unconAction
```

#### Field Value

**Type:** Global.UncontrollableAction

### visible

```csharp
public bool visible
```

#### Field Value

**Type:** System.Boolean

### waitTimer

```csharp
public float waitTimer
```

#### Field Value

**Type:** System.Single

### willDead

```csharp
public bool willDead
```

#### Field Value

**Type:** System.Boolean

### workerClass

```csharp
public WorkerClass workerClass
```

#### Field Value

**Type:** Global.WorkerClass

## Properties

### attackTargetWorker

```csharp
public WorkerModel attackTargetWorker { get; }
```

#### Property Value

**Type:** Global.WorkerModel

### CurrentPanicAction

```csharp
public PanicAction CurrentPanicAction { get; set; }
```

#### Property Value

**Type:** Global.PanicAction

### currentSefira

```csharp
public string currentSefira { get; set; }
```

#### Property Value

**Type:** System.String

### DeadType

```csharp
public DeadType DeadType { get; }
```

#### Property Value

**Type:** Global.DeadType

### fortitudeLevel

```csharp
public virtual int fortitudeLevel { get; }
```

#### Property Value

**Type:** System.Int32

### justiceLevel

```csharp
public virtual int justiceLevel { get; }
```

#### Property Value

**Type:** System.Int32

### panicData

```csharp
public virtual PanicData panicData { get; }
```

#### Property Value

**Type:** Global.PanicData

### prudenceLevel

```csharp
public virtual int prudenceLevel { get; }
```

#### Property Value

**Type:** System.Int32

### recentlyAttacked

```csharp
public CreatureModel recentlyAttacked { get; set; }
```

#### Property Value

**Type:** Global.CreatureModel

### specialDeadScene

```csharp
public bool specialDeadScene { get; set; }
```

#### Property Value

**Type:** System.Boolean

### temperanceLevel

```csharp
public virtual int temperanceLevel { get; }
```

#### Property Value

**Type:** System.Int32

### workerAnimator

```csharp
public Animator workerAnimator { get; }
```

#### Property Value

**Type:** UnityEngine.Animator

## Methods

### AfterDeadAnim()

```csharp
public virtual void AfterDeadAnim()
```

### CannotControll()

```csharp
public virtual bool CannotControll()
```

#### Returns

**Type:** System.Boolean

### ChangeHairSprite(SpriteInfo)

```csharp
public virtual void ChangeHairSprite(SpriteInfo spriteInfo)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spriteInfo` | `Global.SpriteInfo` |  |

### ChangePuppet(string)

```csharp
public virtual GameObject ChangePuppet(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject

### ChangePuppetAnimToDie(string)

```csharp
public virtual WorkerDeadScript ChangePuppetAnimToDie(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.WorkerDeadScript

### ChangePuppetAnimToUncon(string)

```csharp
public virtual void ChangePuppetAnimToUncon(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### CheckEGOGift()

```csharp
public virtual void CheckEGOGift()
```

### ClearEffect()

```csharp
public virtual void ClearEffect()
```

### ClearUnconCommand()

```csharp
public virtual void ClearUnconCommand()
```

### CompareByID(WorkerModel, WorkerModel)

```csharp
public static int CompareByID(WorkerModel x, WorkerModel y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `Global.WorkerModel` |  |
| `y` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Int32

### CompareByName(WorkerModel, WorkerModel)

```csharp
public static int CompareByName(WorkerModel x, WorkerModel y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `Global.WorkerModel` |  |
| `y` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Int32

### CompareBySefira(WorkerModel, WorkerModel)

```csharp
public static int CompareBySefira(WorkerModel x, WorkerModel y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `Global.WorkerModel` |  |
| `y` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Int32

### CreateMentalDamagedEffect(float)

```csharp
protected void CreateMentalDamagedEffect(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### CreatePhysicalDamagedEffect(float)

```csharp
protected void CreatePhysicalDamagedEffect(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### Die()

```csharp
public virtual void Die()
```

### EncounterCreature(UnitModel)

```csharp
public virtual void EncounterCreature(UnitModel encounteredCreature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `encounteredCreature` | `Global.UnitModel` |  |

### EncounterStandingItem(StandingItemModel)

```csharp
public virtual void EncounterStandingItem(StandingItemModel standing)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `standing` | `Global.StandingItemModel` |  |

### FollowMovable(MovableObjectNode)

```csharp
public void FollowMovable(MovableObjectNode targetNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MovableObjectNode` |  |

### GetConnectedNode()

```csharp
public MapNode GetConnectedNode()
```

#### Returns

**Type:** Global.MapNode

### GetControl()

```csharp
public virtual void GetControl()
```

### GetCurrentCommand()

```csharp
public WorkerCommand GetCurrentCommand()
```

#### Returns

**Type:** Global.WorkerCommand

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

### GetCurrentSefira()

```csharp
public virtual Sefira GetCurrentSefira()
```

#### Returns

**Type:** Global.Sefira

### GetEdgeDirection()

```csharp
public virtual EdgeDirection GetEdgeDirection()
```

#### Returns

**Type:** Global.EdgeDirection

### GetSaveData()

```csharp
public virtual Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetWeaponSprite()

```csharp
public override Sprite GetWeaponSprite()
```

#### Returns

**Type:** UnityEngine.Sprite

### GetWorkerUnit()

```csharp
public virtual WorkerUnit GetWorkerUnit()
```

#### Returns

**Type:** Global.WorkerUnit

### HaltUpdate()

```csharp
public virtual void HaltUpdate()
```

### InitialEncounteredCreature(RiskLevel)

```csharp
public virtual void InitialEncounteredCreature(RiskLevel level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.RiskLevel` |  |

### InitialEncounteredCreature(UnitModel)

```csharp
public virtual void InitialEncounteredCreature(UnitModel encountered)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `encountered` | `Global.UnitModel` |  |

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

### IsCrazy()

```csharp
public virtual bool IsCrazy()
```

#### Returns

**Type:** System.Boolean

### IsDead()

```csharp
public virtual bool IsDead()
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

### IsInSefira()

```csharp
public virtual bool IsInSefira()
```

#### Returns

**Type:** System.Boolean

### IsPanic()

```csharp
public virtual bool IsPanic()
```

#### Returns

**Type:** System.Boolean

### IsSuppable()

```csharp
public virtual bool IsSuppable()
```

#### Returns

**Type:** System.Boolean

### LoadData(Dictionary<string, object>)

```csharp
public virtual void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### LoseControl()

```csharp
public virtual void LoseControl()
```

### MakeCreatureEffect(CreatureModel)

```csharp
public virtual GameObject MakeCreatureEffect(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeCreatureEffect(long)

```csharp
public virtual GameObject MakeCreatureEffect(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeCreatureEffectHead(CreatureModel)

```csharp
public virtual GameObject MakeCreatureEffectHead(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeCreatureEffectHead(CreatureModel, bool)

```csharp
public virtual GameObject MakeCreatureEffectHead(CreatureModel model, bool addlist)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |
| `addlist` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeSpatteredBlood()

```csharp
public void MakeSpatteredBlood()
```

### MoveFromNullPassage()

```csharp
public void MoveFromNullPassage()
```

### MoveToMovable(MovableObjectNode)

```csharp
public void MoveToMovable(MovableObjectNode targetMovable)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |

### MoveToMovable(MovableObjectNode, bool)

```csharp
public void MoveToMovable(MovableObjectNode targetMovable, bool resetCommand)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |
| `resetCommand` | `System.Boolean` |  |

### MoveToNode(MapNode)

```csharp
public void MoveToNode(MapNode targetNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |

### MoveToNode(MapNode, bool)

```csharp
public void MoveToNode(MapNode targetNode, bool resetCommand)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |
| `resetCommand` | `System.Boolean` |  |

### MoveToNode(string)

```csharp
public void MoveToNode(string targetNodeID)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNodeID` | `System.String` |  |

### OnAttackWorker(WorkerModel)

```csharp
public virtual void OnAttackWorker(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### OnDie()

```csharp
public virtual void OnDie()
```

### OnFixedUpdate()

```csharp
public virtual void OnFixedUpdate()
```

### OnNotice(string, params object[])

```csharp
public virtual void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnResurrect()

```csharp
public virtual void OnResurrect()
```

### OnSetArmor()

```csharp
protected override void OnSetArmor()
```

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

### OnStun(float)

```csharp
public override void OnStun(float stunVal)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `stunVal` | `System.Single` |  |

### OnStunEffectDestroied()

```csharp
public void OnStunEffectDestroied()
```

### Panic()

```csharp
public virtual void Panic()
```

### PanicReadyComplete()

```csharp
public virtual void PanicReadyComplete()
```

### PlayAttackAnimation(string)

```csharp
protected override void PlayAttackAnimation(string animationName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animationName` | `System.String` |  |

### ProcessAction()

```csharp
public virtual void ProcessAction()
```

### PursueUnconAgent(UnitModel)

```csharp
public virtual void PursueUnconAgent(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### RecentlyAttackedCreature(CreatureModel)

```csharp
public virtual void RecentlyAttackedCreature(CreatureModel creatureModel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureModel` | `Global.CreatureModel` |  |

### RecoverHP(float)

```csharp
public virtual void RecoverHP(float amount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `amount` | `System.Single` |  |

### RecoverMental(float)

```csharp
public virtual void RecoverMental(float amount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `amount` | `System.Single` |  |

### ReleaseUpdate()

```csharp
public virtual void ReleaseUpdate()
```

### ResetAnimator()

```csharp
public virtual void ResetAnimator()
```

### ResetSpecialDeadScene()

```csharp
public void ResetSpecialDeadScene()
```

### ResetSprite()

```csharp
public virtual void ResetSprite()
```

### ReturnToSefira()

```csharp
public virtual void ReturnToSefira()
```

### SetAgentCommand(WorkerCommand)

```csharp
public void SetAgentCommand(WorkerCommand command)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `command` | `Global.WorkerCommand` |  |

### SetCurrentNode(MapNode)

```csharp
public virtual void SetCurrentNode(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### SetCustsomCommand(WorkerCommand)

```csharp
public virtual void SetCustsomCommand(WorkerCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.WorkerCommand` |  |

### SetDeadType(DeadType)

```csharp
public void SetDeadType(DeadType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.DeadType` |  |

### SetInvincible(bool)

```csharp
public virtual void SetInvincible(bool b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `System.Boolean` |  |

### SetPanicAnim(bool)

```csharp
public void SetPanicAnim(bool b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `System.Boolean` |  |

### SetSpecialDeadScene(string)

```csharp
public void SetSpecialDeadScene(string deadSceneName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `deadSceneName` | `System.String` |  |

### SetSpecialDeadScene(string, bool)

```csharp
public void SetSpecialDeadScene(string deadSceneName, bool seperator)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `deadSceneName` | `System.String` |  |
| `seperator` | `System.Boolean` |  |

### SetSpecialDeadScene(string, bool, bool)

```csharp
public void SetSpecialDeadScene(string deadSceneName, bool seperator, bool hasUniqueFace)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `deadSceneName` | `System.String` |  |
| `seperator` | `System.Boolean` |  |
| `hasUniqueFace` | `System.Boolean` |  |

### SetUncontrollableAction(UncontrollableAction)

```csharp
public virtual void SetUncontrollableAction(UncontrollableAction uncon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `uncon` | `Global.UncontrollableAction` |  |

### SetWorkerFaceType(WorkerFaceType)

```csharp
public void SetWorkerFaceType(WorkerFaceType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `WorkerSprite.WorkerFaceType` |  |

### ShowCreatureActionSpeech(long, string)

```csharp
public virtual void ShowCreatureActionSpeech(long creatureID, string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureID` | `System.Int64` |  |
| `key` | `System.String` |  |

### ShowSpeech(string)

```csharp
public virtual void ShowSpeech(string txt)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `txt` | `System.String` |  |

### ShowUnconSpeech(string)

```csharp
public virtual void ShowUnconSpeech(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

### SpecialAttackDamage(TrackEntry, Event)

```csharp
public void SpecialAttackDamage(TrackEntry trackEntry, Event e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackEntry` | `Spine.TrackEntry` |  |
| `e` | `Spine.Event` |  |

### SpecialAttackEnd(TrackEntry)

```csharp
public void SpecialAttackEnd(TrackEntry trackEntry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackEntry` | `Spine.TrackEntry` |  |

### StopAction()

```csharp
public virtual void StopAction()
```

### StopPanic()

```csharp
public virtual void StopPanic()
```

### StopPanicWithoutStun()

```csharp
public virtual void StopPanicWithoutStun()
```

### StopStun()

```csharp
public virtual void StopStun()
```

### Stun(float)

```csharp
public virtual void Stun(float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

### TakeDamage(UnitModel, DamageInfo)

```csharp
public override void TakeDamage(UnitModel actor, DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### TakeDamageWithoutEffect(UnitModel, DamageInfo)

```csharp
public override void TakeDamageWithoutEffect(UnitModel actor, DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### TakeMentalDamage(float)

```csharp
public void TakeMentalDamage(float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Single` |  |

### TakeMentalDamage(float, MentalDamageOption)

```csharp
public virtual void TakeMentalDamage(float damage, MentalDamageOption option)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Single` |  |
| `option` | `Global.MentalDamageOption` |  |

### TryGetValue<T>(Dictionary<string, object>, string, ref T)

```csharp
public static bool TryGetValue<T>(Dictionary<string, object> dic, string name, ref T field)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `name` | `System.String` |  |
| `field` | `{T}` |  |

#### Returns

**Type:** System.Boolean
