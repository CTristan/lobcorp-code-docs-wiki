---
uid: Global.StandingItemModel
canonical_path: /api/Global/Model/StandingItemModel
---

# Class StandingItemModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StandingItemModel : UnitModel
```

#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/Global/Model/UnitModel) → StandingItemModel

## Inherited Members
[stunCriteria](/api/Global/Model/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/Global/Model/UnitModel#defaultstuneffectsrc), [instanceId](/api/Global/Model/UnitModel#instanceid), [movableNode](/api/Global/Model/UnitModel#movablenode), [shield](/api/Global/Model/UnitModel#shield), [_equipment](/api/Global/Model/UnitModel#equipment), [tempAnim](/api/Global/Model/UnitModel#tempanim), [factionTypeInfo](/api/Global/Model/UnitModel#factiontypeinfo), [stunTimer](/api/Global/Model/UnitModel#stuntimer), [hp](/api/Global/Model/UnitModel#hp), [mental](/api/Global/Model/UnitModel#mental), [baseMaxHp](/api/Global/Model/UnitModel#basemaxhp), [baseMaxMental](/api/Global/Model/UnitModel#basemaxmental), [baseMovement](/api/Global/Model/UnitModel#basemovement), [baseRegeneration](/api/Global/Model/UnitModel#baseregeneration), [baseRegenerationDelay](/api/Global/Model/UnitModel#baseregenerationdelay), [additionalDef](/api/Global/Model/UnitModel#additionaldef), [superArmorMax](/api/Global/Model/UnitModel#superarmormax), [superArmor](/api/Global/Model/UnitModel#superarmor), [superArmorDefense](/api/Global/Model/UnitModel#superarmordefense), [remainMoveDelay](/api/Global/Model/UnitModel#remainmovedelay), [remainAttackDelay](/api/Global/Model/UnitModel#remainattackdelay), [isStun](/api/Global/Model/UnitModel#isstun), [damageTransform](/api/Global/Model/UnitModel#damagetransform), [basePhysicalDefense](/api/Global/Model/UnitModel#basephysicaldefense), [baseMentalDefense](/api/Global/Model/UnitModel#basementaldefense), [encounteredWorker](/api/Global/Model/UnitModel#encounteredworker), [_bufList](/api/Global/Model/UnitModel#buflist), [_statBufList](/api/Global/Model/UnitModel#statbuflist), [_barrierBufList](/api/Global/Model/UnitModel#barrierbuflist), [CanOpenDoor()](/api/Global/Model/UnitModel#canopendoor), [GetUnitName()](/api/Global/Model/UnitModel#getunitname), [InteractWithDoor(DoorObjectModel)](/api/Global/Model/UnitModel#interactwithdoor-doorobjectmodel), [OnStopMovableByShield(AgentModel)](/api/Global/Model/UnitModel#onstopmovablebyshield-agentmodel), [GetMovableNode()](/api/Global/Model/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/Global/Model/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/Global/Model/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/Global/Model/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/Global/Model/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/Global/Model/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/Global/Model/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/Global/Model/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/Global/Model/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/Global/Model/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/Global/Model/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/Global/Model/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/Global/Model/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/Global/Model/UnitModel#releasekitcreature-bool), [OnSetWeapon()](/api/Global/Model/UnitModel#onsetweapon), [OnReleaseWeapon()](/api/Global/Model/UnitModel#onreleaseweapon), [OnSetArmor()](/api/Global/Model/UnitModel#onsetarmor), [OnReleaseArmor()](/api/Global/Model/UnitModel#onreleasearmor), [OnChangeGift()](/api/Global/Model/UnitModel#onchangegift), [OnSetKitCreature()](/api/Global/Model/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/Global/Model/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/Global/Model/UnitModel#getweaponspritesrc), [GetWeaponSprite()](/api/Global/Model/UnitModel#getweaponsprite), [PrepareWeapon()](/api/Global/Model/UnitModel#prepareweapon), [CancelWeapon()](/api/Global/Model/UnitModel#cancelweapon), [Attack(UnitModel)](/api/Global/Model/UnitModel#attack-unitmodel), [IsAttackState()](/api/Global/Model/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/Global/Model/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/Global/Model/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/Global/Model/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/Global/Model/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/Global/Model/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/Global/Model/UnitModel#onendattackcycle), [PlayAttackAnimation(string)](/api/Global/Model/UnitModel#playattackanimation-string), [EndAttackAnimation()](/api/Global/Model/UnitModel#endattackanimation), [GetEGObonus()](/api/Global/Model/UnitModel#getegobonus), [HasEquipment(int)](/api/Global/Model/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/Global/Model/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/Global/Model/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/Global/Model/UnitModel#takedamage-damageinfo), [TakeDamage(UnitModel, DamageInfo)](/api/Global/Model/UnitModel#takedamage-unitmodel-damageinfo), [TakeDamageWithoutEffect(UnitModel, DamageInfo)](/api/Global/Model/UnitModel#takedamagewithouteffect-unitmodel-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/Global/Model/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/Global/Model/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/Global/Model/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/Global/Model/UnitModel#checknearworkerencounting), [IsStunned()](/api/Global/Model/UnitModel#isstunned), [OnSuperArmorBreak()](/api/Global/Model/UnitModel#onsuperarmorbreak), [IsHostile(UnitModel)](/api/Global/Model/UnitModel#ishostile-unitmodel), [SetMoveDelay(float)](/api/Global/Model/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/Global/Model/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/Global/Model/UnitModel#setattackdelay-float), [UpdateBufState()](/api/Global/Model/UnitModel#updatebufstate), [GetRiskLevel()](/api/Global/Model/UnitModel#getrisklevel), [GetAttackLevel()](/api/Global/Model/UnitModel#getattacklevel), [GetDefenseLevel()](/api/Global/Model/UnitModel#getdefenselevel), [AddUnitBuf(UnitBuf)](/api/Global/Model/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/Global/Model/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/Global/Model/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/Global/Model/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/Global/Model/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/Global/Model/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/Global/Model/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/Global/Model/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/Global/Model/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/Global/Model/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/Global/Model/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/Global/Model/UnitModel#getmovementscalebybuf), [SetFaction(FactionTypeInfo)](/api/Global/Model/UnitModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/Global/Model/UnitModel#setfaction-string), [GetFaction()](/api/Global/Model/UnitModel#getfaction), [SetFactionForcely(string)](/api/Global/Model/UnitModel#setfactionforcely-string), [OnStun(float)](/api/Global/Model/UnitModel#onstun-float), [OnStunEnd()](/api/Global/Model/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/Global/Model/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/Global/Model/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/Global/Model/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/Global/Model/UnitModel#getunitbuflist), [Equipment](/api/Global/Model/UnitModel#equipment), [radius](/api/Global/Model/UnitModel#radius), [maxHp](/api/Global/Model/UnitModel#maxhp), [maxMental](/api/Global/Model/UnitModel#maxmental), [movement](/api/Global/Model/UnitModel#movement), [regeneration](/api/Global/Model/UnitModel#regeneration), [regenerationDelay](/api/Global/Model/UnitModel#regenerationdelay), [defense](/api/Global/Model/UnitModel#defense), [attackSpeed](/api/Global/Model/UnitModel#attackspeed), [damage](/api/Global/Model/UnitModel#damage), [physicalDefense](/api/Global/Model/UnitModel#physicaldefense), [mentalDefense](/api/Global/Model/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StandingItemModel(UnitModel, MapNode)

```csharp
public StandingItemModel(UnitModel owner, MapNode position)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.UnitModel` |  |
| `position` | `Global.MapNode` |  |

## Fields

### blockActionUpdate

```csharp
public bool blockActionUpdate
```
#INC


#### Field Value

**Type:** System.Boolean

### blockPosition

```csharp
public bool blockPosition
```
#INC


#### Field Value

**Type:** System.Boolean

### blockScaling

```csharp
public bool blockScaling
```
#INC


#### Field Value

**Type:** System.Boolean

### commandQueue

```csharp
private StandingCommandQueue commandQueue
```
#INC


#### Field Value

**Type:** Global.StandingCommandQueue

### currentNode

```csharp
protected MapNode currentNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### currentSefira

```csharp
protected Sefira currentSefira
```
#INC


#### Field Value

**Type:** Global.Sefira

### damageEvent

```csharp
private StandingItemModel.TakeDamageEvent damageEvent
```

#### Field Value

**Type:** Global.StandingItemModel.TakeDamageEvent

### data

```csharp
public ItemObjectData data
```
#INC


#### Field Value

**Type:** Global.ItemObjectData

### defaultMovement

```csharp
private const float defaultMovement = 1
```
#INC


#### Field Value

**Type:** System.Single

### owner

```csharp
public UnitModel owner
```
#INC


#### Field Value

**Type:** Global.UnitModel

### script

```csharp
public StandingItemScriptBase script
```
#INC


#### Field Value

**Type:** Global.StandingItemScriptBase

### speedMult

```csharp
public float speedMult
```
#INC


#### Field Value

**Type:** System.Single

### unit

```csharp
public StandingItemUnit unit
```
#INC


#### Field Value

**Type:** Global.StandingItemUnit

### useGlobalPosition

```csharp
public bool useGlobalPosition
```
#INC


#### Field Value

**Type:** System.Boolean

## Methods

### BuildScript(string)

```csharp
public void BuildScript(string scriptName)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `scriptName` | `System.String` |  |

### CheckRange(UnitModel, float)

```csharp
public bool CheckRange(UnitModel target, float range)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### CommonGenerator()

```csharp
private void CommonGenerator()
```
#INC


### DestroyUnit()

```csharp
public void DestroyUnit()
```
#INC


### GetCurrentCmd()

```csharp
public StandingCommand GetCurrentCmd()
```
#INC


#### Returns

**Type:** Global.StandingCommand

### GetSefira()

```csharp
public Sefira GetSefira()
```
#INC


#### Returns

**Type:** Global.Sefira

### GetState()

```csharp
public StandingItemScriptBase.StandingItemState GetState()
```
#INC


#### Returns

**Type:** Global.StandingItemScriptBase.StandingItemState

### GiveDamage(UnitModel, float)

```csharp
public void GiveDamage(UnitModel target, float damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `System.Single` |  |

### IsAttackTargetable()

```csharp
public override bool IsAttackTargetable()
```
#INC
#code-generated


#### Returns

**Type:** System.Boolean

### LoadData(long)

```csharp
public void LoadData(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### MoveToMovable(MovableObjectNode)

```csharp
public void MoveToMovable(MovableObjectNode targetMovable)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |

### MoveToMovable(MovableObjectNode, bool)

```csharp
public void MoveToMovable(MovableObjectNode targetMovable, bool resetCommand)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |
| `resetCommand` | `System.Boolean` |  |

### MoveToMovable(MovableObjectNode, bool, OnCommandEnd)

```csharp
public void MoveToMovable(MovableObjectNode targetMovable, bool resetCommand, StandingCommand.OnCommandEnd end)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |
| `resetCommand` | `System.Boolean` |  |
| `end` | `Global.StandingCommand.OnCommandEnd` |  |

### MoveToMovable(MovableObjectNode, OnCommandEnd)

```csharp
public void MoveToMovable(MovableObjectNode targetMovable, StandingCommand.OnCommandEnd end)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |
| `end` | `Global.StandingCommand.OnCommandEnd` |  |

### MoveToNode(MapNode)

```csharp
public void MoveToNode(MapNode targetNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |

### MoveToNode(MapNode, bool)

```csharp
public void MoveToNode(MapNode targetNode, bool resetCommand)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |
| `resetCommand` | `System.Boolean` |  |

### MoveToNode(MapNode, bool, OnCommandEnd)

```csharp
public void MoveToNode(MapNode targetNode, bool resetCommand, StandingCommand.OnCommandEnd end)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |
| `resetCommand` | `System.Boolean` |  |
| `end` | `Global.StandingCommand.OnCommandEnd` |  |

### MoveToNode(MapNode, OnCommandEnd)

```csharp
public void MoveToNode(MapNode targetNode, StandingCommand.OnCommandEnd end)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |
| `end` | `Global.StandingCommand.OnCommandEnd` |  |

### OnBreakDown()

```csharp
public virtual void OnBreakDown()
```
#INC


### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```
#INC


### OnTryAttack()

```csharp
public virtual bool OnTryAttack()
```
#INC


#### Returns

**Type:** System.Boolean

### ProcessAction()

```csharp
public void ProcessAction()
```
#INC


### Reset()

```csharp
public virtual void Reset()
```
#INC


### SetDamageEvent(TakeDamageEvent)

```csharp
public void SetDamageEvent(StandingItemModel.TakeDamageEvent e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StandingItemModel.TakeDamageEvent` |  |

### SetPosition(MapNode)

```csharp
public void SetPosition(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### SetSpeedMult()

```csharp
public void SetSpeedMult()
```
#INC


### SetSpeedMult(float)

```csharp
public void SetSpeedMult(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### SetUnit(StandingItemUnit)

```csharp
public void SetUnit(StandingItemUnit unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.StandingItemUnit` |  |

### StopCommand()

```csharp
public void StopCommand()
```
#INC

