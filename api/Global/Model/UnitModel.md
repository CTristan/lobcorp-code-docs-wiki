---
uid: Global.UnitModel
canonical_path: /api/Global/Model/UnitModel
---

# Class UnitModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnitModel
```
Represents a unit on the screen, such as workers, rabbits, or abnormalities.

#INC (This one will be worth going through completely, I think.)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → UnitModel

## Derived
[Butterfly.ButterflyEffect](/api/Global/Effect/ButterflyButterflyEffect), [CreatureModel](/api/Global/Model/CreatureModel), [ProjectileModel](/api/Global/Model/ProjectileModel), [RabbitModel](/api/Global/Model/RabbitModel), [SnowWhite.VineArea](/api/Global/Misc/SnowWhiteVineArea), [StandingItemModel](/api/Global/Model/StandingItemModel), [WorkerModel](/api/Global/Model/WorkerModel), [YoungPrinceFriend.Spore](/api/Global/Misc/YoungPrinceFriendSpore)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UnitModel()

```csharp
public UnitModel()
```

## Fields

### _barrierBufList

```csharp
protected List<BarrierBuf> _barrierBufList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{BarrierBuf}

### _bufList

```csharp
protected List<UnitBuf> _bufList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnitBuf}

### _equipment

```csharp
protected UnitEquipSpace _equipment
```
#INC


#### Field Value

**Type:** Global.UnitEquipSpace

### _statBufList

```csharp
protected List<UnitStatBuf> _statBufList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnitStatBuf}

### additionalDef

```csharp
public DefenseInfo additionalDef
```
#INC


#### Field Value

**Type:** Global.DefenseInfo

### baseMaxHp

```csharp
public int baseMaxHp
```
#INC


#### Field Value

**Type:** System.Int32

### baseMaxMental

```csharp
public int baseMaxMental
```
#INC


#### Field Value

**Type:** System.Int32

### baseMentalDefense

```csharp
public int baseMentalDefense
```
#INC


#### Field Value

**Type:** System.Int32

### baseMovement

```csharp
public float baseMovement
```
#INC


#### Field Value

**Type:** System.Single

### basePhysicalDefense

```csharp
public int basePhysicalDefense
```
#INC


#### Field Value

**Type:** System.Int32

### baseRegeneration

```csharp
public int baseRegeneration
```
#INC


#### Field Value

**Type:** System.Int32

### baseRegenerationDelay

```csharp
public float baseRegenerationDelay
```
#INC


#### Field Value

**Type:** System.Single

### damageTransform

```csharp
public StatTransform damageTransform
```
#INC


#### Field Value

**Type:** Global.StatTransform

### defaultStunEffectSrc

```csharp
public const string defaultStunEffectSrc = "Effect/Stun"
```
#INC


#### Field Value

**Type:** System.String

### encounteredWorker

```csharp
public List<WorkerModel> encounteredWorker
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

### factionTypeInfo

```csharp
protected FactionTypeInfo factionTypeInfo
```
#INC


#### Field Value

**Type:** Global.FactionTypeInfo

### hp

```csharp
public float hp
```
#INC


#### Field Value

**Type:** System.Single

### instanceId

```csharp
public long instanceId
```
#INC


#### Field Value

**Type:** System.Int64

### isStun

```csharp
protected bool isStun
```
#INC


#### Field Value

**Type:** System.Boolean

### mental

```csharp
public float mental
```
#INC


#### Field Value

**Type:** System.Single

### movableNode

```csharp
protected MovableObjectNode movableNode
```
#INC


#### Field Value

**Type:** Global.MovableObjectNode

### remainAttackDelay

```csharp
public float remainAttackDelay
```
#INC


#### Field Value

**Type:** System.Single

### remainMoveDelay

```csharp
public float remainMoveDelay
```
#INC


#### Field Value

**Type:** System.Single

### shield

```csharp
public UnitShieldEquipment shield
```
#INC


#### Field Value

**Type:** Global.UnitShieldEquipment

### stunCriteria

```csharp
public const float stunCriteria = 2
```
#INC


#### Field Value

**Type:** System.Single

### stunTimer

```csharp
protected AutoTimer stunTimer
```
#INC


#### Field Value

**Type:** Global.AutoTimer

### superArmor

```csharp
public float superArmor
```
#INC


#### Field Value

**Type:** System.Single

### superArmorDefense

```csharp
public float superArmorDefense
```
#INC


#### Field Value

**Type:** System.Single

### superArmorMax

```csharp
public float superArmorMax
```
#INC


#### Field Value

**Type:** System.Single

### tempAnim

```csharp
public DummyAttackAnimator tempAnim
```

#### Field Value

**Type:** Global.DummyAttackAnimator

## Properties

### attackSpeed

```csharp
public virtual float attackSpeed { get; }
```

#### Property Value

**Type:** System.Single

### damage

```csharp
public virtual float damage { get; }
```

#### Property Value

**Type:** System.Single

### defense

```csharp
public virtual DefenseInfo defense { get; }
```

#### Property Value

**Type:** Global.DefenseInfo

### Equipment

```csharp
public UnitEquipSpace Equipment { get; }
```

#### Property Value

**Type:** Global.UnitEquipSpace

### maxHp

```csharp
public virtual int maxHp { get; }
```

#### Property Value

**Type:** System.Int32

### maxMental

```csharp
public virtual int maxMental { get; }
```

#### Property Value

**Type:** System.Int32

### mentalDefense

```csharp
public virtual int mentalDefense { get; }
```

#### Property Value

**Type:** System.Int32

### movement

```csharp
public virtual float movement { get; }
```

#### Property Value

**Type:** System.Single

### physicalDefense

```csharp
public virtual int physicalDefense { get; }
```

#### Property Value

**Type:** System.Int32

### radius

```csharp
public virtual float radius { get; }
```

#### Property Value

**Type:** System.Single

### regeneration

```csharp
public virtual int regeneration { get; }
```

#### Property Value

**Type:** System.Int32

### regenerationDelay

```csharp
public virtual float regenerationDelay { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### AddSuperArmorMax(float)

```csharp
public void AddSuperArmorMax(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### AddUnitBuf(UnitBuf)

```csharp
public UnitBuf AddUnitBuf(UnitBuf buf)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `buf` | `Global.UnitBuf` |  |

#### Returns

**Type:** Global.UnitBuf

### AttachEGOgift(EGOgiftModel)

```csharp
public void AttachEGOgift(EGOgiftModel gift)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `gift` | `Global.EGOgiftModel` |  |

### Attack(UnitModel)

```csharp
public virtual void Attack(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### CancelWeapon()

```csharp
public virtual void CancelWeapon()
```
#INC


### CanOpenDoor()

```csharp
public virtual bool CanOpenDoor()
```
#INC
#code-generated


#### Returns

**Type:** System.Boolean

### CheckNearWorkerEncounting()

```csharp
public void CheckNearWorkerEncounting()
```
#INC


### ClearWorkerEncounting()

```csharp
public void ClearWorkerEncounting()
```
#INC


### EndAttackAnimation()

```csharp
protected virtual void EndAttackAnimation()
```
#INC


### GetAttackLevel()

```csharp
public virtual int GetAttackLevel()
```
#INC


#### Returns

**Type:** System.Int32

### GetAttackSpeedBuf()

```csharp
public float GetAttackSpeedBuf()
```
#INC


#### Returns

**Type:** System.Single

### GetBufDamageMultiplier(UnitModel, DamageInfo)

```csharp
public virtual float GetBufDamageMultiplier(UnitModel attacker, DamageInfo damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `damage` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Single

### GetCubeSpeedBuf()

```csharp
public int GetCubeSpeedBuf()
```
#INC


#### Returns

**Type:** System.Int32

### GetCurrentViewPosition()

```csharp
public virtual Vector3 GetCurrentViewPosition()
```
#INC


#### Returns

**Type:** UnityEngine.Vector3

### GetDamageFactorByEquipment()

```csharp
public float GetDamageFactorByEquipment()
```
#INC


#### Returns

**Type:** System.Single

### GetDamageFactorBySefiraAbility()

```csharp
public virtual float GetDamageFactorBySefiraAbility()
```
#INC


#### Returns

**Type:** System.Single

### GetDefenseLevel()

```csharp
public virtual int GetDefenseLevel()
```
#INC


#### Returns

**Type:** System.Int32

### GetDmgMultiplierByEgoLevel(int, int)

```csharp
public static float GetDmgMultiplierByEgoLevel(int attackLevel, int defenseLevel)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attackLevel` | `System.Int32` |  |
| `defenseLevel` | `System.Int32` |  |

#### Returns

**Type:** System.Single

### GetEGObonus()

```csharp
public EGObonusInfo GetEGObonus()
```
#INC


#### Returns

**Type:** Global.EGObonusInfo

### GetFaction()

```csharp
public FactionTypeInfo GetFaction()
```
#INC


#### Returns

**Type:** Global.FactionTypeInfo

### GetGiftDisplayState(EGOgiftModel)

```csharp
public bool GetGiftDisplayState(EGOgiftModel gift)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `gift` | `Global.EGOgiftModel` |  |

#### Returns

**Type:** System.Boolean

### GetMaxHpBuf()

```csharp
public int GetMaxHpBuf()
```
#INC


#### Returns

**Type:** System.Int32

### GetMaxMentalBuf()

```csharp
public int GetMaxMentalBuf()
```
#INC


#### Returns

**Type:** System.Int32

### GetMovableNode()

```csharp
public virtual MovableObjectNode GetMovableNode()
```
#INC


#### Returns

**Type:** Global.MovableObjectNode

### GetMovementBuf()

```csharp
public float GetMovementBuf()
```
#INC


#### Returns

**Type:** System.Single

### GetMovementScaleByBuf()

```csharp
public float GetMovementScaleByBuf()
```
#INC


#### Returns

**Type:** System.Single

### GetPrimaryStatBuf()

```csharp
public WorkerPrimaryStatBonus GetPrimaryStatBuf()
```
#INC


#### Returns

**Type:** Global.WorkerPrimaryStatBonus

### GetRiskLevel()

```csharp
public virtual int GetRiskLevel()
```
#INC


#### Returns

**Type:** System.Int32

### GetUnitBufByName(string)

```csharp
public UnitBuf GetUnitBufByName(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** Global.UnitBuf

### GetUnitBufByType(UnitBufType)

```csharp
public UnitBuf GetUnitBufByType(UnitBufType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.UnitBufType` |  |

#### Returns

**Type:** Global.UnitBuf

### GetUnitBufList()

```csharp
public List<UnitBuf> GetUnitBufList()
```

#### Returns

**Type:** System.Collections.Generic.List{UnitBuf}

### GetUnitName()

```csharp
public virtual string GetUnitName()
```
#INC


#### Returns

**Type:** System.String

### GetWeaponSprite()

```csharp
public virtual Sprite GetWeaponSprite()
```
#INC


#### Returns

**Type:** UnityEngine.Sprite

### GetWeaponSpriteSrc()

```csharp
public string GetWeaponSpriteSrc()
```
#INC


#### Returns

**Type:** System.String

### GetWorkProbBuf()

```csharp
public int GetWorkProbBuf()
```
#INC


#### Returns

**Type:** System.Int32

### HasEquipment(int)

```csharp
public bool HasEquipment(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### HasUnitBuf(UnitBufType)

```csharp
public bool HasUnitBuf(UnitBufType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.UnitBufType` |  |

#### Returns

**Type:** System.Boolean

### InteractWithDoor(DoorObjectModel)

```csharp
public virtual void InteractWithDoor(DoorObjectModel door)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `door` | `Global.DoorObjectModel` |  |

### InWeaponRange(UnitModel)

```csharp
public virtual bool InWeaponRange(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### IsAttackState()

```csharp
public virtual bool IsAttackState()
```
#INC


#### Returns

**Type:** System.Boolean

### IsAttackTargetable()

```csharp
public virtual bool IsAttackTargetable()
```
#INC


#### Returns

**Type:** System.Boolean

### IsHostile(UnitModel)

```csharp
public virtual bool IsHostile(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### IsStunned()

```csharp
public virtual bool IsStunned()
```
#INC


#### Returns

**Type:** System.Boolean

### MakeDamageEffect(RwbpType, float, Type)

```csharp
public virtual void MakeDamageEffect(RwbpType type, float value, DefenseInfo.Type defense)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `value` | `System.Single` |  |
| `defense` | `Global.DefenseInfo.Type` |  |

### OnChangeGift()

```csharp
protected virtual void OnChangeGift()
```
#INC


### OnEndAttackCycle()

```csharp
public void OnEndAttackCycle()
```
#INC


### OnGiveDamageByWeapon()

```csharp
public void OnGiveDamageByWeapon()
```
#INC


### OnReleaseArmor()

```csharp
protected virtual void OnReleaseArmor()
```
#INC


### OnReleaseKitCreature()

```csharp
protected virtual void OnReleaseKitCreature()
```
#INC


### OnReleaseWeapon()

```csharp
protected virtual void OnReleaseWeapon()
```
#INC


### OnSetArmor()

```csharp
protected virtual void OnSetArmor()
```
#INC


### OnSetKitCreature()

```csharp
protected virtual void OnSetKitCreature()
```
#INC


### OnSetWeapon()

```csharp
protected virtual void OnSetWeapon()
```
#INC


### OnStopMovableByShield(AgentModel)

```csharp
public virtual void OnStopMovableByShield(AgentModel shielder)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `shielder` | `Global.AgentModel` |  |

### OnStun(float)

```csharp
public virtual void OnStun(float stunVal)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `stunVal` | `System.Single` |  |

### OnStunEnd()

```csharp
public virtual void OnStunEnd()
```
#INC


### OnSuperArmorBreak()

```csharp
public virtual void OnSuperArmorBreak()
```
#INC


### PlayAttackAnimation(string)

```csharp
protected virtual void PlayAttackAnimation(string animationName)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animationName` | `System.String` |  |

### PrepareWeapon()

```csharp
public virtual void PrepareWeapon()
```
#INC


### ReleaseArmor()

```csharp
public void ReleaseArmor()
```
#INC


### ReleaseEGOgift(EGOgiftModel)

```csharp
public void ReleaseEGOgift(EGOgiftModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EGOgiftModel` |  |

### ReleaseEGOGift(int)

```csharp
public bool ReleaseEGOGift(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### ReleaseKitCreature(bool)

```csharp
public void ReleaseKitCreature(bool stageEnd)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `stageEnd` | `System.Boolean` |  |

### ReleaseWeaponV2()

```csharp
public void ReleaseWeaponV2()
```
#INC


### RemoveUnitBuf(UnitBuf)

```csharp
public void RemoveUnitBuf(UnitBuf buf)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `buf` | `Global.UnitBuf` |  |

### SetArmor(ArmorModel)

```csharp
public void SetArmor(ArmorModel armor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `armor` | `Global.ArmorModel` |  |

### SetAttackDelay()

```csharp
public void SetAttackDelay()
```
#INC


### SetAttackDelay(float)

```csharp
public void SetAttackDelay(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### SetFaction(FactionTypeInfo)

```csharp
public virtual void SetFaction(FactionTypeInfo type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.FactionTypeInfo` |  |

### SetFaction(string)

```csharp
public virtual void SetFaction(string factionCode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factionCode` | `System.String` |  |

### SetFactionForcely(string)

```csharp
public void SetFactionForcely(string factionCode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factionCode` | `System.String` |  |

### SetGiftDisplayState(EGOgiftModel, bool)

```csharp
public void SetGiftDisplayState(EGOgiftModel model, bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EGOgiftModel` |  |
| `state` | `System.Boolean` |  |

### SetGiftLockState(EGOgiftModel, bool)

```csharp
public void SetGiftLockState(EGOgiftModel model, bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EGOgiftModel` |  |
| `state` | `System.Boolean` |  |

### SetKitCreature(CreatureModel)

```csharp
public void SetKitCreature(CreatureModel kitCreature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `kitCreature` | `Global.CreatureModel` |  |

### SetMoveDelay(float)

```csharp
public void SetMoveDelay(float moveDelay)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `moveDelay` | `System.Single` |  |

### SetWeapon(WeaponModel)

```csharp
public void SetWeapon(WeaponModel weapon)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `weapon` | `Global.WeaponModel` |  |

### StopAttack()

```csharp
public void StopAttack()
```
#INC


### SubSuperArmorMax(float)

```csharp
public void SubSuperArmorMax(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### TakeDamage(DamageInfo)

```csharp
public void TakeDamage(DamageInfo dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dmg` | `Global.DamageInfo` |  |

### TakeDamage(UnitModel, DamageInfo)

```csharp
public virtual void TakeDamage(UnitModel actor, DamageInfo dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### TakeDamageWithoutEffect(UnitModel, DamageInfo)

```csharp
public virtual void TakeDamageWithoutEffect(UnitModel actor, DamageInfo dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### UnderAttack(UnitModel)

```csharp
public virtual void UnderAttack(UnitModel attacker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |

### UpdateBufState()

```csharp
public virtual void UpdateBufState()
```
#INC

