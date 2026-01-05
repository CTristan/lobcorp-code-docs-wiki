# Class EquipmentModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EquipmentModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EquipmentModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### EquipmentModel()

```csharp
public EquipmentModel()
```

## Fields

### currentTarget

```csharp
public UnitModel currentTarget
```

#### Field Value

**Type:** Global.UnitModel

### instanceId

```csharp
public long instanceId
```

#### Field Value

**Type:** System.Int64

### metaInfo

```csharp
public EquipmentTypeInfo metaInfo
```

#### Field Value

**Type:** Global.EquipmentTypeInfo

### script

```csharp
public EquipmentScriptBase script
```

#### Field Value

**Type:** Global.EquipmentScriptBase

## Properties

### owner

```csharp
public UnitModel owner { get; }
```

#### Property Value

**Type:** Global.UnitModel

## Methods

### CheckRequire(UnitModel)

```csharp
public bool CheckRequire(UnitModel unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### GetBonus(UnitModel)

```csharp
public EGObonusInfo GetBonus(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.EGObonusInfo

### GetDamageFactor()

```csharp
public float GetDamageFactor()
```

#### Returns

**Type:** System.Single

### GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)

```csharp
public float GetWorkProbSpecialBonus(UnitModel actor, SkillTypeInfo skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `skill` | `Global.SkillTypeInfo` |  |

#### Returns

**Type:** System.Single

### OnCancelWeapon(UnitModel)

```csharp
public void OnCancelWeapon(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnEquip(UnitModel)

```csharp
public void OnEquip(UnitModel newOwner)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `newOwner` | `Global.UnitModel` |  |

### OnFixedUpdate()

```csharp
public virtual void OnFixedUpdate()
```

### OnPrepareWeapon(UnitModel)

```csharp
public void OnPrepareWeapon(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnRelease()

```csharp
public void OnRelease()
```

### OnTakeDamage(UnitModel, ref DamageInfo)

```csharp
public void OnTakeDamage(UnitModel actor, ref DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### OnTakeDamage_After(float, RwbpType)

```csharp
public void OnTakeDamage_After(float value, RwbpType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |
| `type` | `Global.RwbpType` |  |
