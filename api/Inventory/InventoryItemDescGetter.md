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
Turns the attack speed and range into text (e.g., 'fast', 'slow', 'long', 'short'...)

Used by the [abnormality information screen](/api/Global/Misc/CreatureInfoWindow) (see [WeaponSlot](/api/CreatureInfo/WeaponSlot)) and the [E.G.O List screen](/api/Inventory/InventoryUI) (see [InventoryWeaponSlot](/api/Inventory/InventoryWeaponSlot)).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → InventoryItemDescGetter

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Fields

### AttackRangeKey

```csharp
public static string[] AttackRangeKey
```
#INC


#### Field Value

**Type:** System.String[]

### AttackSpeedKey

```csharp
public static string[] AttackSpeedKey
```
#INC


#### Field Value

**Type:** System.String[]

## Methods

### GetText(string)

```csharp
public static string GetText(string key)
```
#INC


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
#INC
#code-generated


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WeaponModel` |  |
| `attackSpeed` | `System.String` |  |
| `attackRange` | `System.String` |  |
