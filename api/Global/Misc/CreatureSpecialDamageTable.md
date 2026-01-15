---
uid: Global.CreatureSpecialDamageTable
canonical_path: /api/Global/Misc/CreatureSpecialDamageTable
---

# Class CreatureSpecialDamageTable

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureSpecialDamageTable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureSpecialDamageTable

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureSpecialDamageTable()

```csharp
public CreatureSpecialDamageTable()
```

## Fields

### _specialWeaponInfos

```csharp
private Dictionary<string, EquipmentTypeInfo> _specialWeaponInfos
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,EquipmentTypeInfo}

## Methods

### GetList()

```csharp
public List<DamageInfo> GetList()
```

#### Returns

**Type:** System.Collections.Generic.List{DamageInfo}

### GetSpecialDamage(string)

```csharp
public DamageInfo GetSpecialDamage(string id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns

**Type:** Global.DamageInfo

### GetSpecialWeapon(string)

```csharp
public EquipmentTypeInfo GetSpecialWeapon(string id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns

**Type:** Global.EquipmentTypeInfo

### Init(Dictionary<string, EquipmentTypeInfo>)

```csharp
public void Init(Dictionary<string, EquipmentTypeInfo> infos)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `infos` | `System.Collections.Generic.Dictionary{System.String,EquipmentTypeInfo}` |  |
