# Class EquipmentScriptBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EquipmentScriptBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EquipmentScriptBase

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### EquipmentScriptBase()

```csharp
public EquipmentScriptBase()
```

## Fields

### MAX_REINFORCEMENT_LEVEL

```csharp
protected const int MAX_REINFORCEMENT_LEVEL = 4
```

#### Field Value

**Type:** System.Int32

## Properties

### model

```csharp
public EquipmentModel model { get; }
```

#### Property Value

**Type:** Global.EquipmentModel

### reinforcementLevel

```csharp
public int reinforcementLevel { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### AddReinforcementLevel(int)

```csharp
public void AddReinforcementLevel(int lv)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lv` | `System.Int32` |  |

### GetBonus(UnitModel)

```csharp
public virtual EGObonusInfo GetBonus(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.EGObonusInfo

### GetDamage(UnitModel)

```csharp
public virtual DamageInfo GetDamage(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.DamageInfo

### GetDamageFactor()

```csharp
public virtual float GetDamageFactor()
```

#### Returns

**Type:** System.Single

### GetDefense(UnitModel)

```csharp
public virtual DefenseInfo GetDefense(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.DefenseInfo

### GetReinforcementDmg()

```csharp
public float GetReinforcementDmg()
```

#### Returns

**Type:** System.Single

### GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)

```csharp
public virtual float GetWorkProbSpecialBonus(UnitModel actor, SkillTypeInfo skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `skill` | `Global.SkillTypeInfo` |  |

#### Returns

**Type:** System.Single

### OnAttackEnd(UnitModel, UnitModel)

```csharp
public virtual void OnAttackEnd(UnitModel actor, UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |

### OnAttackStart(UnitModel, UnitModel)

```csharp
public virtual EquipmentScriptBase.WeaponDamageInfo OnAttackStart(UnitModel actor, UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.EquipmentScriptBase.WeaponDamageInfo

### OnCancelWeapon(UnitModel)

```csharp
public virtual void OnCancelWeapon(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnEquip(UnitModel)

```csharp
public virtual void OnEquip(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnFixedUpdate()

```csharp
public virtual void OnFixedUpdate()
```

### OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)

```csharp
public virtual bool OnGiveDamage(UnitModel actor, UnitModel target, ref DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean

### OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)

```csharp
public virtual void OnGiveDamageAfter(UnitModel actor, UnitModel target, DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### OnKillMainTarget(UnitModel, UnitModel)

```csharp
public virtual void OnKillMainTarget(UnitModel actor, UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |

### OnPrepareWeapon(UnitModel)

```csharp
public virtual void OnPrepareWeapon(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnRelease()

```csharp
public virtual void OnRelease()
```

### OnStageRelease()

```csharp
public virtual void OnStageRelease()
```

### OnStageStart()

```csharp
public virtual void OnStageStart()
```

### OnTakeDamage(UnitModel, ref DamageInfo)

```csharp
public virtual bool OnTakeDamage(UnitModel actor, ref DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean

### OnTakeDamage_After(float, RwbpType)

```csharp
public virtual bool OnTakeDamage_After(float value, RwbpType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |
| `type` | `Global.RwbpType` |  |

#### Returns

**Type:** System.Boolean

### OwnerHeal(bool, ref float)

```csharp
public virtual void OwnerHeal(bool isMental, ref float amount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isMental` | `System.Boolean` |  |
| `amount` | `System.Single` |  |

### SetModel(EquipmentModel)

```csharp
public void SetModel(EquipmentModel m)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `m` | `Global.EquipmentModel` |  |
