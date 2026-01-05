# Class RabbitModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitModel : UnitModel, IMouseCommandTargetModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/UnitModel) → RabbitModel

## Inherited Members
[stunCriteria](/api/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/UnitModel#defaultstuneffectsrc), [instanceId](/api/UnitModel#instanceid), [movableNode](/api/UnitModel#movablenode), [shield](/api/UnitModel#shield), [_equipment](/api/UnitModel#equipment), [tempAnim](/api/UnitModel#tempanim), [factionTypeInfo](/api/UnitModel#factiontypeinfo), [stunTimer](/api/UnitModel#stuntimer), [hp](/api/UnitModel#hp), [mental](/api/UnitModel#mental), [baseMaxHp](/api/UnitModel#basemaxhp), [baseMaxMental](/api/UnitModel#basemaxmental), [baseMovement](/api/UnitModel#basemovement), [baseRegeneration](/api/UnitModel#baseregeneration), [baseRegenerationDelay](/api/UnitModel#baseregenerationdelay), [additionalDef](/api/UnitModel#additionaldef), [superArmorMax](/api/UnitModel#superarmormax), [superArmor](/api/UnitModel#superarmor), [superArmorDefense](/api/UnitModel#superarmordefense), [remainMoveDelay](/api/UnitModel#remainmovedelay), [remainAttackDelay](/api/UnitModel#remainattackdelay), [isStun](/api/UnitModel#isstun), [damageTransform](/api/UnitModel#damagetransform), [basePhysicalDefense](/api/UnitModel#basephysicaldefense), [baseMentalDefense](/api/UnitModel#basementaldefense), [encounteredWorker](/api/UnitModel#encounteredworker), [_bufList](/api/UnitModel#buflist), [_statBufList](/api/UnitModel#statbuflist), [_barrierBufList](/api/UnitModel#barrierbuflist), [CanOpenDoor()](/api/UnitModel#canopendoor), [GetUnitName()](/api/UnitModel#getunitname), [InteractWithDoor(DoorObjectModel)](/api/UnitModel#interactwithdoor-doorobjectmodel), [OnStopMovableByShield(AgentModel)](/api/UnitModel#onstopmovablebyshield-agentmodel), [GetMovableNode()](/api/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/UnitModel#releasekitcreature-bool), [OnSetWeapon()](/api/UnitModel#onsetweapon), [OnReleaseWeapon()](/api/UnitModel#onreleaseweapon), [OnSetArmor()](/api/UnitModel#onsetarmor), [OnReleaseArmor()](/api/UnitModel#onreleasearmor), [OnChangeGift()](/api/UnitModel#onchangegift), [OnSetKitCreature()](/api/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/UnitModel#getweaponspritesrc), [GetWeaponSprite()](/api/UnitModel#getweaponsprite), [PrepareWeapon()](/api/UnitModel#prepareweapon), [CancelWeapon()](/api/UnitModel#cancelweapon), [IsAttackState()](/api/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/UnitModel#onendattackcycle), [EndAttackAnimation()](/api/UnitModel#endattackanimation), [GetEGObonus()](/api/UnitModel#getegobonus), [HasEquipment(int)](/api/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/UnitModel#takedamage-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/UnitModel#checknearworkerencounting), [IsStunned()](/api/UnitModel#isstunned), [OnSuperArmorBreak()](/api/UnitModel#onsuperarmorbreak), [SetMoveDelay(float)](/api/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/UnitModel#setattackdelay-float), [UpdateBufState()](/api/UnitModel#updatebufstate), [AddUnitBuf(UnitBuf)](/api/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/UnitModel#getmovementscalebybuf), [SetFaction(FactionTypeInfo)](/api/UnitModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/UnitModel#setfaction-string), [GetFaction()](/api/UnitModel#getfaction), [SetFactionForcely(string)](/api/UnitModel#setfactionforcely-string), [OnStun(float)](/api/UnitModel#onstun-float), [OnStunEnd()](/api/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/UnitModel#getunitbuflist), [Equipment](/api/UnitModel#equipment), [radius](/api/UnitModel#radius), [maxHp](/api/UnitModel#maxhp), [maxMental](/api/UnitModel#maxmental), [movement](/api/UnitModel#movement), [regeneration](/api/UnitModel#regeneration), [regenerationDelay](/api/UnitModel#regenerationdelay), [defense](/api/UnitModel#defense), [attackSpeed](/api/UnitModel#attackspeed), [damage](/api/UnitModel#damage), [physicalDefense](/api/UnitModel#physicaldefense), [mentalDefense](/api/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### RabbitModel(RwbpType)

```csharp
public RabbitModel(RwbpType rwbpType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rwbpType` | `Global.RwbpType` |  |

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### CheckNear()

```csharp
public void CheckNear()
```

### ClearOperation()

```csharp
public void ClearOperation()
```

### Fire()

```csharp
public void Fire()
```

### GetAttackLevel()

```csharp
public override int GetAttackLevel()
```

#### Returns

**Type:** System.Int32

### GetCurrentCommand()

```csharp
public UnitCommand GetCurrentCommand()
```

#### Returns

**Type:** Global.UnitCommand

### GetDefenseLevel()

```csharp
public override int GetDefenseLevel()
```

#### Returns

**Type:** System.Int32

### GetRiskLevel()

```csharp
public override int GetRiskLevel()
```

#### Returns

**Type:** System.Int32

### IsAttackTargetable()

```csharp
public override bool IsAttackTargetable()
```

#### Returns

**Type:** System.Boolean

### IsDead()

```csharp
public bool IsDead()
```

#### Returns

**Type:** System.Boolean

### IsFireState()

```csharp
public bool IsFireState()
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

### MakeSound(string)

```csharp
public SoundEffectPlayer MakeSound(string src)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnClearProtocol()

```csharp
public void OnClearProtocol()
```

### OnDie()

```csharp
public void OnDie()
```

### OnDieByMental()

```csharp
public void OnDieByMental()
```

### OnEndCycle()

```csharp
public void OnEndCycle()
```

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```

### OnGiveDamage()

```csharp
public void OnGiveDamage()
```

### PlayAttackAnimation(string)

```csharp
protected override void PlayAttackAnimation(string animationName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animationName` | `System.String` |  |

### SetCommand(UnitCommand)

```csharp
public void SetCommand(UnitCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.UnitCommand` |  |

### SetUnit(RabbitUnit)

```csharp
public void SetUnit(RabbitUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.RabbitUnit` |  |

### SetUnitState(bool)

```csharp
public void SetUnitState(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

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
