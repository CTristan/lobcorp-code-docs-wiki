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

#### Field Value

**Type:** System.Collections.Generic.List{BarrierBuf}

### _bufList

```csharp
protected List<UnitBuf> _bufList
```

#### Field Value

**Type:** System.Collections.Generic.List{UnitBuf}

### _equipment

```csharp
protected UnitEquipSpace _equipment
```

#### Field Value

**Type:** Global.UnitEquipSpace

### _statBufList

```csharp
protected List<UnitStatBuf> _statBufList
```

#### Field Value

**Type:** System.Collections.Generic.List{UnitStatBuf}

### additionalDef

```csharp
public DefenseInfo additionalDef
```

#### Field Value

**Type:** Global.DefenseInfo

### baseMaxHp

```csharp
public int baseMaxHp
```

#### Field Value

**Type:** System.Int32

### baseMaxMental

```csharp
public int baseMaxMental
```

#### Field Value

**Type:** System.Int32

### baseMentalDefense

```csharp
public int baseMentalDefense
```

#### Field Value

**Type:** System.Int32

### baseMovement

```csharp
public float baseMovement
```

#### Field Value

**Type:** System.Single

### basePhysicalDefense

```csharp
public int basePhysicalDefense
```

#### Field Value

**Type:** System.Int32

### baseRegeneration

```csharp
public int baseRegeneration
```

#### Field Value

**Type:** System.Int32

### baseRegenerationDelay

```csharp
public float baseRegenerationDelay
```

#### Field Value

**Type:** System.Single

### damageTransform

```csharp
public StatTransform damageTransform
```

#### Field Value

**Type:** Global.StatTransform

### defaultStunEffectSrc

```csharp
public const string defaultStunEffectSrc = "Effect/Stun"
```

#### Field Value

**Type:** System.String

### encounteredWorker

```csharp
public List<WorkerModel> encounteredWorker
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

### factionTypeInfo

```csharp
protected FactionTypeInfo factionTypeInfo
```

#### Field Value

**Type:** Global.FactionTypeInfo

### hp

```csharp
public float hp
```

#### Field Value

**Type:** System.Single

### instanceId

```csharp
public long instanceId
```

#### Field Value

**Type:** System.Int64

### isStun

```csharp
protected bool isStun
```

#### Field Value

**Type:** System.Boolean

### mental

```csharp
public float mental
```

#### Field Value

**Type:** System.Single

### movableNode

```csharp
protected MovableObjectNode movableNode
```

#### Field Value

**Type:** Global.MovableObjectNode

### remainAttackDelay

```csharp
public float remainAttackDelay
```

#### Field Value

**Type:** System.Single

### remainMoveDelay

```csharp
public float remainMoveDelay
```

#### Field Value

**Type:** System.Single

### shield

```csharp
public UnitShieldEquipment shield
```

#### Field Value

**Type:** Global.UnitShieldEquipment

### stunCriteria

```csharp
public const float stunCriteria = 2
```

#### Field Value

**Type:** System.Single

### stunTimer

```csharp
protected AutoTimer stunTimer
```

#### Field Value

**Type:** Global.AutoTimer

### superArmor

```csharp
public float superArmor
```

#### Field Value

**Type:** System.Single

### superArmorDefense

```csharp
public float superArmorDefense
```

#### Field Value

**Type:** System.Single

### superArmorMax

```csharp
public float superArmorMax
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### AddUnitBuf(UnitBuf)

```csharp
public UnitBuf AddUnitBuf(UnitBuf buf)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `gift` | `Global.EGOgiftModel` |  |

### Attack(UnitModel)

```csharp
public virtual void Attack(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### CancelWeapon()

```csharp
public virtual void CancelWeapon()
```

### CanOpenDoor()

```csharp
public virtual bool CanOpenDoor()
```

#### Returns

**Type:** System.Boolean

### CheckNearWorkerEncounting()

```csharp
public void CheckNearWorkerEncounting()
```

### ClearWorkerEncounting()

```csharp
public void ClearWorkerEncounting()
```

### EndAttackAnimation()

```csharp
protected virtual void EndAttackAnimation()
```

### GetAttackLevel()

```csharp
public virtual int GetAttackLevel()
```

#### Returns

**Type:** System.Int32

### GetAttackSpeedBuf()

```csharp
public float GetAttackSpeedBuf()
```

#### Returns

**Type:** System.Single

### GetBufDamageMultiplier(UnitModel, DamageInfo)

```csharp
public virtual float GetBufDamageMultiplier(UnitModel attacker, DamageInfo damage)
```

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

#### Returns

**Type:** System.Int32

### GetCurrentViewPosition()

```csharp
public virtual Vector3 GetCurrentViewPosition()
```

#### Returns

**Type:** UnityEngine.Vector3

### GetDamageFactorByEquipment()

```csharp
public float GetDamageFactorByEquipment()
```

#### Returns

**Type:** System.Single

### GetDamageFactorBySefiraAbility()

```csharp
public virtual float GetDamageFactorBySefiraAbility()
```

#### Returns

**Type:** System.Single

### GetDefenseLevel()

```csharp
public virtual int GetDefenseLevel()
```

#### Returns

**Type:** System.Int32

### GetDmgMultiplierByEgoLevel(int, int)

```csharp
public static float GetDmgMultiplierByEgoLevel(int attackLevel, int defenseLevel)
```

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

#### Returns

**Type:** Global.EGObonusInfo

### GetFaction()

```csharp
public FactionTypeInfo GetFaction()
```

#### Returns

**Type:** Global.FactionTypeInfo

### GetGiftDisplayState(EGOgiftModel)

```csharp
public bool GetGiftDisplayState(EGOgiftModel gift)
```

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

#### Returns

**Type:** System.Int32

### GetMaxMentalBuf()

```csharp
public int GetMaxMentalBuf()
```

#### Returns

**Type:** System.Int32

### GetMovableNode()

```csharp
public virtual MovableObjectNode GetMovableNode()
```

#### Returns

**Type:** Global.MovableObjectNode

### GetMovementBuf()

```csharp
public float GetMovementBuf()
```

#### Returns

**Type:** System.Single

### GetMovementScaleByBuf()

```csharp
public float GetMovementScaleByBuf()
```

#### Returns

**Type:** System.Single

### GetPrimaryStatBuf()

```csharp
public WorkerPrimaryStatBonus GetPrimaryStatBuf()
```

#### Returns

**Type:** Global.WorkerPrimaryStatBonus

### GetRiskLevel()

```csharp
public virtual int GetRiskLevel()
```

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

#### Returns

**Type:** System.String

### GetWeaponSprite()

```csharp
public virtual Sprite GetWeaponSprite()
```

#### Returns

**Type:** UnityEngine.Sprite

### GetWeaponSpriteSrc()

```csharp
public string GetWeaponSpriteSrc()
```

#### Returns

**Type:** System.String

### GetWorkProbBuf()

```csharp
public int GetWorkProbBuf()
```

#### Returns

**Type:** System.Int32

### HasEquipment(int)

```csharp
public bool HasEquipment(int id)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `door` | `Global.DoorObjectModel` |  |

### InWeaponRange(UnitModel)

```csharp
public virtual bool InWeaponRange(UnitModel target)
```

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

#### Returns

**Type:** System.Boolean

### IsAttackTargetable()

```csharp
public virtual bool IsAttackTargetable()
```

#### Returns

**Type:** System.Boolean

### IsHostile(UnitModel)

```csharp
public virtual bool IsHostile(UnitModel target)
```

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

#### Returns

**Type:** System.Boolean

### MakeDamageEffect(RwbpType, float, Type)

```csharp
public virtual void MakeDamageEffect(RwbpType type, float value, DefenseInfo.Type defense)
```

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

### OnEndAttackCycle()

```csharp
public void OnEndAttackCycle()
```

### OnGiveDamageByWeapon()

```csharp
public void OnGiveDamageByWeapon()
```

### OnReleaseArmor()

```csharp
protected virtual void OnReleaseArmor()
```

### OnReleaseKitCreature()

```csharp
protected virtual void OnReleaseKitCreature()
```

### OnReleaseWeapon()

```csharp
protected virtual void OnReleaseWeapon()
```

### OnSetArmor()

```csharp
protected virtual void OnSetArmor()
```

### OnSetKitCreature()

```csharp
protected virtual void OnSetKitCreature()
```

### OnSetWeapon()

```csharp
protected virtual void OnSetWeapon()
```

### OnStopMovableByShield(AgentModel)

```csharp
public virtual void OnStopMovableByShield(AgentModel shielder)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `shielder` | `Global.AgentModel` |  |

### OnStun(float)

```csharp
public virtual void OnStun(float stunVal)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `stunVal` | `System.Single` |  |

### OnStunEnd()

```csharp
public virtual void OnStunEnd()
```

### OnSuperArmorBreak()

```csharp
public virtual void OnSuperArmorBreak()
```

### PlayAttackAnimation(string)

```csharp
protected virtual void PlayAttackAnimation(string animationName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animationName` | `System.String` |  |

### PrepareWeapon()

```csharp
public virtual void PrepareWeapon()
```

### ReleaseArmor()

```csharp
public void ReleaseArmor()
```

### ReleaseEGOgift(EGOgiftModel)

```csharp
public void ReleaseEGOgift(EGOgiftModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EGOgiftModel` |  |

### ReleaseEGOGift(int)

```csharp
public bool ReleaseEGOGift(int id)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `stageEnd` | `System.Boolean` |  |

### ReleaseWeaponV2()

```csharp
public void ReleaseWeaponV2()
```

### RemoveUnitBuf(UnitBuf)

```csharp
public void RemoveUnitBuf(UnitBuf buf)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `buf` | `Global.UnitBuf` |  |

### SetArmor(ArmorModel)

```csharp
public void SetArmor(ArmorModel armor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `armor` | `Global.ArmorModel` |  |

### SetAttackDelay()

```csharp
public void SetAttackDelay()
```

### SetAttackDelay(float)

```csharp
public void SetAttackDelay(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### SetFaction(FactionTypeInfo)

```csharp
public virtual void SetFaction(FactionTypeInfo type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.FactionTypeInfo` |  |

### SetFaction(string)

```csharp
public virtual void SetFaction(string factionCode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factionCode` | `System.String` |  |

### SetFactionForcely(string)

```csharp
public void SetFactionForcely(string factionCode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factionCode` | `System.String` |  |

### SetGiftDisplayState(EGOgiftModel, bool)

```csharp
public void SetGiftDisplayState(EGOgiftModel model, bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EGOgiftModel` |  |
| `state` | `System.Boolean` |  |

### SetGiftLockState(EGOgiftModel, bool)

```csharp
public void SetGiftLockState(EGOgiftModel model, bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EGOgiftModel` |  |
| `state` | `System.Boolean` |  |

### SetKitCreature(CreatureModel)

```csharp
public void SetKitCreature(CreatureModel kitCreature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `kitCreature` | `Global.CreatureModel` |  |

### SetMoveDelay(float)

```csharp
public void SetMoveDelay(float moveDelay)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `moveDelay` | `System.Single` |  |

### SetWeapon(WeaponModel)

```csharp
public void SetWeapon(WeaponModel weapon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `weapon` | `Global.WeaponModel` |  |

### StopAttack()

```csharp
public void StopAttack()
```

### SubSuperArmorMax(float)

```csharp
public void SubSuperArmorMax(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### TakeDamage(DamageInfo)

```csharp
public void TakeDamage(DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dmg` | `Global.DamageInfo` |  |

### TakeDamage(UnitModel, DamageInfo)

```csharp
public virtual void TakeDamage(UnitModel actor, DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### TakeDamageWithoutEffect(UnitModel, DamageInfo)

```csharp
public virtual void TakeDamageWithoutEffect(UnitModel actor, DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### UnderAttack(UnitModel)

```csharp
public virtual void UnderAttack(UnitModel attacker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |

### UpdateBufState()

```csharp
public virtual void UpdateBufState()
```
