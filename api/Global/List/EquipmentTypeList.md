---
uid: Global.EquipmentTypeList
canonical_path: /api/Global/List/EquipmentTypeList
---

# Class EquipmentTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EquipmentTypeList
```
List of all [EGO](/api/Global/List/EquipmentTypeList). Loaded by [EquipmentDataLoader](/api/Global/Loader/EquipmentDataLoader).
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EquipmentTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EquipmentTypeList()

```csharp
private EquipmentTypeList()
```
#INC
#code-generated


## Fields

### _dic

```csharp
private Dictionary<int, EquipmentTypeInfo> _dic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,EquipmentTypeInfo}

### _instance

```csharp
private static EquipmentTypeList _instance
```
#INC


#### Field Value

**Type:** Global.EquipmentTypeList

### _loaded

```csharp
private bool _loaded
```
#INC


#### Field Value

**Type:** System.Boolean

## Properties

### instance

```csharp
public static EquipmentTypeList instance { get; }
```

#### Property Value

**Type:** Global.EquipmentTypeList

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetAllData()

```csharp
public List<EquipmentTypeInfo> GetAllData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{EquipmentTypeInfo}

### GetData(int)

```csharp
public EquipmentTypeInfo GetData(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.EquipmentTypeInfo

### Init(Dictionary<int, EquipmentTypeInfo>)

```csharp
public void Init(Dictionary<int, EquipmentTypeInfo> info)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `System.Collections.Generic.Dictionary{System.Int32,EquipmentTypeInfo}` |  |
