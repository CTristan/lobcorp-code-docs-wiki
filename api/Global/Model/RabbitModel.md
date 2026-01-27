---
uid: Global.RabbitModel
canonical_path: /api/Global/Model/RabbitModel
---

# Class RabbitModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitModel : UnitModel, IMouseCommandTargetModel
```

A rabbit, abstractly. Managed by [RabbitManager](/api/Global/Misc/RabbitManager).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/Global/Model/UnitModel) → RabbitModel

## Implements
[IMouseCommandTargetModel](/api/Global/Model/IMouseCommandTargetModel)

## Inherited Members
[stunCriteria](/api/Global/Model/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/Global/Model/UnitModel#defaultstuneffectsrc), [instanceId](/api/Global/Model/UnitModel#instanceid), [movableNode](/api/Global/Model/UnitModel#movablenode), [shield](/api/Global/Model/UnitModel#shield), [_equipment](/api/Global/Model/UnitModel#equipment), [tempAnim](/api/Global/Model/UnitModel#tempanim), [factionTypeInfo](/api/Global/Model/UnitModel#factiontypeinfo), [stunTimer](/api/Global/Model/UnitModel#stuntimer), [hp](/api/Global/Model/UnitModel#hp), [mental](/api/Global/Model/UnitModel#mental), [baseMaxHp](/api/Global/Model/UnitModel#basemaxhp), [baseMaxMental](/api/Global/Model/UnitModel#basemaxmental), [baseMovement](/api/Global/Model/UnitModel#basemovement), [baseRegeneration](/api/Global/Model/UnitModel#baseregeneration), [baseRegenerationDelay](/api/Global/Model/UnitModel#baseregenerationdelay), [additionalDef](/api/Global/Model/UnitModel#additionaldef), [superArmorMax](/api/Global/Model/UnitModel#superarmormax), [superArmor](/api/Global/Model/UnitModel#superarmor), [superArmorDefense](/api/Global/Model/UnitModel#superarmordefense), [remainMoveDelay](/api/Global/Model/UnitModel#remainmovedelay), [remainAttackDelay](/api/Global/Model/UnitModel#remainattackdelay), [isStun](/api/Global/Model/UnitModel#isstun), [damageTransform](/api/Global/Model/UnitModel#damagetransform), [basePhysicalDefense](/api/Global/Model/UnitModel#basephysicaldefense), [baseMentalDefense](/api/Global/Model/UnitModel#basementaldefense), [encounteredWorker](/api/Global/Model/UnitModel#encounteredworker), [_bufList](/api/Global/Model/UnitModel#buflist), [_statBufList](/api/Global/Model/UnitModel#statbuflist), [_barrierBufList](/api/Global/Model/UnitModel#barrierbuflist), [CanOpenDoor()](/api/Global/Model/UnitModel#canopendoor), [GetUnitName()](/api/Global/Model/UnitModel#getunitname), [InteractWithDoor(DoorObjectModel)](/api/Global/Model/UnitModel#interactwithdoor-doorobjectmodel), [OnStopMovableByShield(AgentModel)](/api/Global/Model/UnitModel#onstopmovablebyshield-agentmodel), [GetMovableNode()](/api/Global/Model/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/Global/Model/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/Global/Model/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/Global/Model/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/Global/Model/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/Global/Model/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/Global/Model/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/Global/Model/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/Global/Model/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/Global/Model/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/Global/Model/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/Global/Model/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/Global/Model/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/Global/Model/UnitModel#releasekitcreature-bool), [OnSetWeapon()](/api/Global/Model/UnitModel#onsetweapon), [OnReleaseWeapon()](/api/Global/Model/UnitModel#onreleaseweapon), [OnSetArmor()](/api/Global/Model/UnitModel#onsetarmor), [OnReleaseArmor()](/api/Global/Model/UnitModel#onreleasearmor), [OnChangeGift()](/api/Global/Model/UnitModel#onchangegift), [OnSetKitCreature()](/api/Global/Model/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/Global/Model/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/Global/Model/UnitModel#getweaponspritesrc), [GetWeaponSprite()](/api/Global/Model/UnitModel#getweaponsprite), [PrepareWeapon()](/api/Global/Model/UnitModel#prepareweapon), [CancelWeapon()](/api/Global/Model/UnitModel#cancelweapon), [IsAttackState()](/api/Global/Model/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/Global/Model/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/Global/Model/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/Global/Model/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/Global/Model/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/Global/Model/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/Global/Model/UnitModel#onendattackcycle), [EndAttackAnimation()](/api/Global/Model/UnitModel#endattackanimation), [GetEGObonus()](/api/Global/Model/UnitModel#getegobonus), [HasEquipment(int)](/api/Global/Model/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/Global/Model/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/Global/Model/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/Global/Model/UnitModel#takedamage-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/Global/Model/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/Global/Model/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/Global/Model/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/Global/Model/UnitModel#checknearworkerencounting), [IsStunned()](/api/Global/Model/UnitModel#isstunned), [OnSuperArmorBreak()](/api/Global/Model/UnitModel#onsuperarmorbreak), [SetMoveDelay(float)](/api/Global/Model/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/Global/Model/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/Global/Model/UnitModel#setattackdelay-float), [UpdateBufState()](/api/Global/Model/UnitModel#updatebufstate), [AddUnitBuf(UnitBuf)](/api/Global/Model/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/Global/Model/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/Global/Model/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/Global/Model/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/Global/Model/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/Global/Model/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/Global/Model/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/Global/Model/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/Global/Model/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/Global/Model/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/Global/Model/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/Global/Model/UnitModel#getmovementscalebybuf), [SetFaction(FactionTypeInfo)](/api/Global/Model/UnitModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/Global/Model/UnitModel#setfaction-string), [GetFaction()](/api/Global/Model/UnitModel#getfaction), [SetFactionForcely(string)](/api/Global/Model/UnitModel#setfactionforcely-string), [OnStun(float)](/api/Global/Model/UnitModel#onstun-float), [OnStunEnd()](/api/Global/Model/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/Global/Model/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/Global/Model/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/Global/Model/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/Global/Model/UnitModel#getunitbuflist), [Equipment](/api/Global/Model/UnitModel#equipment), [radius](/api/Global/Model/UnitModel#radius), [maxHp](/api/Global/Model/UnitModel#maxhp), [maxMental](/api/Global/Model/UnitModel#maxmental), [movement](/api/Global/Model/UnitModel#movement), [regeneration](/api/Global/Model/UnitModel#regeneration), [regenerationDelay](/api/Global/Model/UnitModel#regenerationdelay), [defense](/api/Global/Model/UnitModel#defense), [attackSpeed](/api/Global/Model/UnitModel#attackspeed), [damage](/api/Global/Model/UnitModel#damage), [physicalDefense](/api/Global/Model/UnitModel#physicaldefense), [mentalDefense](/api/Global/Model/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RabbitModel(RwbpType)

```csharp
public RabbitModel(RwbpType rwbpType)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rwbpType` | `Global.RwbpType` |  |

## Fields

### _activated

```csharp
private bool _activated
```
#INC


#### Field Value

**Type:** System.Boolean

### _commandQueue

```csharp
private RabbitCommandQueue _commandQueue
```
#INC


#### Field Value

**Type:** Global.RabbitCommandQueue

### _currentWeapon

```csharp
private RabbitWeaponEnum _currentWeapon
```
#INC


#### Field Value

**Type:** Global.RabbitWeaponEnum

### _encounterClearTimer

```csharp
private Timer _encounterClearTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _isDead

```csharp
private bool _isDead
```
#INC


#### Field Value

**Type:** System.Boolean

### _remainFireDelay

```csharp
private float _remainFireDelay
```
#INC


#### Field Value

**Type:** System.Single

### _rwbpType

```csharp
private RwbpType _rwbpType
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _unit

```csharp
private RabbitUnit _unit
```
#INC


#### Field Value

**Type:** Global.RabbitUnit

### encountClearFreq

```csharp
private float encountClearFreq
```
#INC


#### Field Value

**Type:** System.Single

### encountered

```csharp
private List<UnitModel> encountered
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

## Properties

### name

```csharp
public string name { get; }
```

#### Property Value

**Type:** System.String

### rwbpType

```csharp
public RwbpType rwbpType { get; }
```

#### Property Value

**Type:** Global.RwbpType

### Unit

```csharp
public RabbitUnit Unit { get; }
```

#### Property Value

**Type:** Global.RabbitUnit

## Methods

### Attack(UnitModel)

```csharp
public override void Attack(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### CheckNear()

```csharp
public void CheckNear()
```
#INC


### ClearOperation()

```csharp
public void ClearOperation()
```
#INC


### Fire()

```csharp
public void Fire()
```
#INC


### GetAttackLevel()

```csharp
public override int GetAttackLevel()
```
#INC


#### Returns

**Type:** System.Int32

### GetCurrentCommand()

```csharp
public UnitCommand GetCurrentCommand()
```
#INC


#### Returns

**Type:** Global.UnitCommand

### GetDefenseLevel()

```csharp
public override int GetDefenseLevel()
```
#INC


#### Returns

**Type:** System.Int32

### GetRiskLevel()

```csharp
public override int GetRiskLevel()
```
#INC


#### Returns

**Type:** System.Int32

### IsAttackTargetable()

```csharp
public override bool IsAttackTargetable()
```
#INC
#code-generated


#### Returns

**Type:** System.Boolean

### IsDead()

```csharp
public bool IsDead()
```
#INC


#### Returns

**Type:** System.Boolean

### IsFireState()

```csharp
public bool IsFireState()
```
#INC


#### Returns

**Type:** System.Boolean

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

### MakeSound(string)

```csharp
public SoundEffectPlayer MakeSound(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### OnAnimEventCalled(int)

```csharp
public void OnAnimEventCalled(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnClearProtocol()

```csharp
public void OnClearProtocol()
```
#INC


### OnDie()

```csharp
public void OnDie()
```
#INC


### OnDieByMental()

```csharp
public void OnDieByMental()
```
#INC


### OnEndCycle()

```csharp
public void OnEndCycle()
```
#INC


### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```
#INC


### OnGiveDamage()

```csharp
public void OnGiveDamage()
```
#INC


### OnGiveDamageByRifle()

```csharp
private void OnGiveDamageByRifle()
```
#INC


### PlayAttackAnimation(string)

```csharp
protected override void PlayAttackAnimation(string animationName)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animationName` | `System.String` |  |

### SetCommand(UnitCommand)

```csharp
public void SetCommand(UnitCommand cmd)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.UnitCommand` |  |

### SetUnit(RabbitUnit)

```csharp
public void SetUnit(RabbitUnit unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.RabbitUnit` |  |

### SetUnitState(bool)

```csharp
public void SetUnitState(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### TakeDamage(UnitModel, DamageInfo)

```csharp
public override void TakeDamage(UnitModel actor, DamageInfo dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### TakeDamageWithoutEffect(UnitModel, DamageInfo)

```csharp
public override void TakeDamageWithoutEffect(UnitModel actor, DamageInfo dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |
