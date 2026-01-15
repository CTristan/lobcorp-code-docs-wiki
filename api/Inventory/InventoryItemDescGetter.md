---
uid: Inventory.InventoryItemDescGetter
canonical_path: /api/Inventory/InventoryItemDescGetter
---

# Class InventoryItemDescGetter

**Namespace:** [Inventory](/api/Inventory)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class InventoryItemDescGetter
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → InventoryItemDescGetter

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Fields

### AttackRangeKey

```csharp
public static string[] AttackRangeKey
```

#### Field Value

**Type:** System.String[]

### AttackSpeedKey

```csharp
public static string[] AttackSpeedKey
```

#### Field Value

**Type:** System.String[]

## Methods

### GetText(string)

```csharp
public static string GetText(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### GetWeaponDesc(EquipmentTypeInfo, out string, out string)

```csharp
public static void GetWeaponDesc(EquipmentTypeInfo model, out string attackSpeed, out string attackRange)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EquipmentTypeInfo` |  |
| `attackSpeed` | `System.String` |  |
| `attackRange` | `System.String` |  |

### GetWeaponDesc(WeaponModel, out string, out string)

```csharp
public static void GetWeaponDesc(WeaponModel model, out string attackSpeed, out string attackRange)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WeaponModel` |  |
| `attackSpeed` | `System.String` |  |
| `attackRange` | `System.String` |  |
