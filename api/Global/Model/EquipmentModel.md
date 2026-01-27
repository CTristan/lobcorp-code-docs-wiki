---
uid: Global.EquipmentModel
canonical_path: /api/Global/Model/EquipmentModel
---

# Class EquipmentModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EquipmentModel
```
Represents EGO.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EquipmentModel

## Derived
[ArmorModel](/api/Global/Model/ArmorModel), [EGOgiftModel](/api/Global/Model/EGOgiftModel), [WeaponModel](/api/Global/Model/WeaponModel)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EquipmentModel()

```csharp
public EquipmentModel()
```

## Fields

### _owner

```csharp
private UnitModel _owner
```
#INC


#### Field Value

**Type:** Global.UnitModel

### currentTarget

```csharp
public UnitModel currentTarget
```
#INC


#### Field Value

**Type:** Global.UnitModel

### instanceId

```csharp
public long instanceId
```
#INC


#### Field Value

**Type:** System.Int64

### metaInfo

```csharp
public EquipmentTypeInfo metaInfo
```
#INC


#### Field Value

**Type:** Global.EquipmentTypeInfo

### script

```csharp
public EquipmentScriptBase script
```
#INC


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
#INC


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
#INC


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
#INC


#### Returns

**Type:** System.Single

### GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)

```csharp
public float GetWorkProbSpecialBonus(UnitModel actor, SkillTypeInfo skill)
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnEquip(UnitModel)

```csharp
public void OnEquip(UnitModel newOwner)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `newOwner` | `Global.UnitModel` |  |

### OnFixedUpdate()

```csharp
public virtual void OnFixedUpdate()
```
#INC
#code-generated


### OnPrepareWeapon(UnitModel)

```csharp
public void OnPrepareWeapon(UnitModel actor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnRelease()

```csharp
public void OnRelease()
```
#INC


### OnTakeDamage(UnitModel, ref DamageInfo)

```csharp
public void OnTakeDamage(UnitModel actor, ref DamageInfo dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### OnTakeDamage_After(float, RwbpType)

```csharp
public void OnTakeDamage_After(float value, RwbpType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |
| `type` | `Global.RwbpType` |  |
