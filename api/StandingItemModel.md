# Class StandingItemModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StandingItemModel : UnitModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/UnitModel) → StandingItemModel

## Inherited Members
[stunCriteria](/api/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/UnitModel#defaultstuneffectsrc), [instanceId](/api/UnitModel#instanceid), [movableNode](/api/UnitModel#movablenode), [shield](/api/UnitModel#shield), [_equipment](/api/UnitModel#equipment), [tempAnim](/api/UnitModel#tempanim), [factionTypeInfo](/api/UnitModel#factiontypeinfo), [stunTimer](/api/UnitModel#stuntimer), [hp](/api/UnitModel#hp), [mental](/api/UnitModel#mental), [baseMaxHp](/api/UnitModel#basemaxhp), [baseMaxMental](/api/UnitModel#basemaxmental), [baseMovement](/api/UnitModel#basemovement), [baseRegeneration](/api/UnitModel#baseregeneration), [baseRegenerationDelay](/api/UnitModel#baseregenerationdelay), [additionalDef](/api/UnitModel#additionaldef), [superArmorMax](/api/UnitModel#superarmormax), [superArmor](/api/UnitModel#superarmor), [superArmorDefense](/api/UnitModel#superarmordefense), [remainMoveDelay](/api/UnitModel#remainmovedelay), [remainAttackDelay](/api/UnitModel#remainattackdelay), [isStun](/api/UnitModel#isstun), [damageTransform](/api/UnitModel#damagetransform), [basePhysicalDefense](/api/UnitModel#basephysicaldefense), [baseMentalDefense](/api/UnitModel#basementaldefense), [encounteredWorker](/api/UnitModel#encounteredworker), [_bufList](/api/UnitModel#buflist), [_statBufList](/api/UnitModel#statbuflist), [_barrierBufList](/api/UnitModel#barrierbuflist), [CanOpenDoor()](/api/UnitModel#canopendoor), [GetUnitName()](/api/UnitModel#getunitname), [InteractWithDoor(DoorObjectModel)](/api/UnitModel#interactwithdoor-doorobjectmodel), [OnStopMovableByShield(AgentModel)](/api/UnitModel#onstopmovablebyshield-agentmodel), [GetMovableNode()](/api/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/UnitModel#releasekitcreature-bool), [OnSetWeapon()](/api/UnitModel#onsetweapon), [OnReleaseWeapon()](/api/UnitModel#onreleaseweapon), [OnSetArmor()](/api/UnitModel#onsetarmor), [OnReleaseArmor()](/api/UnitModel#onreleasearmor), [OnChangeGift()](/api/UnitModel#onchangegift), [OnSetKitCreature()](/api/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/UnitModel#getweaponspritesrc), [GetWeaponSprite()](/api/UnitModel#getweaponsprite), [PrepareWeapon()](/api/UnitModel#prepareweapon), [CancelWeapon()](/api/UnitModel#cancelweapon), [Attack(UnitModel)](/api/UnitModel#attack-unitmodel), [IsAttackState()](/api/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/UnitModel#onendattackcycle), [PlayAttackAnimation(string)](/api/UnitModel#playattackanimation-string), [EndAttackAnimation()](/api/UnitModel#endattackanimation), [GetEGObonus()](/api/UnitModel#getegobonus), [HasEquipment(int)](/api/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/UnitModel#takedamage-damageinfo), [TakeDamage(UnitModel, DamageInfo)](/api/UnitModel#takedamage-unitmodel-damageinfo), [TakeDamageWithoutEffect(UnitModel, DamageInfo)](/api/UnitModel#takedamagewithouteffect-unitmodel-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/UnitModel#checknearworkerencounting), [IsStunned()](/api/UnitModel#isstunned), [OnSuperArmorBreak()](/api/UnitModel#onsuperarmorbreak), [IsHostile(UnitModel)](/api/UnitModel#ishostile-unitmodel), [SetMoveDelay(float)](/api/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/UnitModel#setattackdelay-float), [UpdateBufState()](/api/UnitModel#updatebufstate), [GetRiskLevel()](/api/UnitModel#getrisklevel), [GetAttackLevel()](/api/UnitModel#getattacklevel), [GetDefenseLevel()](/api/UnitModel#getdefenselevel), [AddUnitBuf(UnitBuf)](/api/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/UnitModel#getmovementscalebybuf), [SetFaction(FactionTypeInfo)](/api/UnitModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/UnitModel#setfaction-string), [GetFaction()](/api/UnitModel#getfaction), [SetFactionForcely(string)](/api/UnitModel#setfactionforcely-string), [OnStun(float)](/api/UnitModel#onstun-float), [OnStunEnd()](/api/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/UnitModel#getunitbuflist), [Equipment](/api/UnitModel#equipment), [radius](/api/UnitModel#radius), [maxHp](/api/UnitModel#maxhp), [maxMental](/api/UnitModel#maxmental), [movement](/api/UnitModel#movement), [regeneration](/api/UnitModel#regeneration), [regenerationDelay](/api/UnitModel#regenerationdelay), [defense](/api/UnitModel#defense), [attackSpeed](/api/UnitModel#attackspeed), [damage](/api/UnitModel#damage), [physicalDefense](/api/UnitModel#physicaldefense), [mentalDefense](/api/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### StandingItemModel(UnitModel, MapNode)

```csharp
public StandingItemModel(UnitModel owner, MapNode position)
```

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

#### Field Value

**Type:** System.Boolean

### blockPosition

```csharp
public bool blockPosition
```

#### Field Value

**Type:** System.Boolean

### blockScaling

```csharp
public bool blockScaling
```

#### Field Value

**Type:** System.Boolean

### currentNode

```csharp
protected MapNode currentNode
```

#### Field Value

**Type:** Global.MapNode

### currentSefira

```csharp
protected Sefira currentSefira
```

#### Field Value

**Type:** Global.Sefira

### data

```csharp
public ItemObjectData data
```

#### Field Value

**Type:** Global.ItemObjectData

### owner

```csharp
public UnitModel owner
```

#### Field Value

**Type:** Global.UnitModel

### script

```csharp
public StandingItemScriptBase script
```

#### Field Value

**Type:** Global.StandingItemScriptBase

### speedMult

```csharp
public float speedMult
```

#### Field Value

**Type:** System.Single

### unit

```csharp
public StandingItemUnit unit
```

#### Field Value

**Type:** Global.StandingItemUnit

### useGlobalPosition

```csharp
public bool useGlobalPosition
```

#### Field Value

**Type:** System.Boolean

## Methods

### BuildScript(string)

```csharp
public void BuildScript(string scriptName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `scriptName` | `System.String` |  |

### CheckRange(UnitModel, float)

```csharp
public bool CheckRange(UnitModel target, float range)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### DestroyUnit()

```csharp
public void DestroyUnit()
```

### GetCurrentCmd()

```csharp
public StandingCommand GetCurrentCmd()
```

#### Returns

**Type:** Global.StandingCommand

### GetSefira()

```csharp
public Sefira GetSefira()
```

#### Returns

**Type:** Global.Sefira

### GetState()

```csharp
public StandingItemScriptBase.StandingItemState GetState()
```

#### Returns

**Type:** Global.StandingItemScriptBase.StandingItemState

### GiveDamage(UnitModel, float)

```csharp
public void GiveDamage(UnitModel target, float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `System.Single` |  |

### IsAttackTargetable()

```csharp
public override bool IsAttackTargetable()
```

#### Returns

**Type:** System.Boolean

### LoadData(long)

```csharp
public void LoadData(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

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

### MoveToMovable(MovableObjectNode, bool, OnCommandEnd)

```csharp
public void MoveToMovable(MovableObjectNode targetMovable, bool resetCommand, StandingCommand.OnCommandEnd end)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |
| `end` | `Global.StandingCommand.OnCommandEnd` |  |

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

### MoveToNode(MapNode, bool, OnCommandEnd)

```csharp
public void MoveToNode(MapNode targetNode, bool resetCommand, StandingCommand.OnCommandEnd end)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |
| `end` | `Global.StandingCommand.OnCommandEnd` |  |

### OnBreakDown()

```csharp
public virtual void OnBreakDown()
```

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```

### OnTryAttack()

```csharp
public virtual bool OnTryAttack()
```

#### Returns

**Type:** System.Boolean

### ProcessAction()

```csharp
public void ProcessAction()
```

### Reset()

```csharp
public virtual void Reset()
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### SetSpeedMult()

```csharp
public void SetSpeedMult()
```

### SetSpeedMult(float)

```csharp
public void SetSpeedMult(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### SetUnit(StandingItemUnit)

```csharp
public void SetUnit(StandingItemUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.StandingItemUnit` |  |

### StopCommand()

```csharp
public void StopCommand()
```
