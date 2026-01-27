---
uid: Global.ShieldTypeList
canonical_path: /api/Global/List/ShieldTypeList
---

# Class ShieldTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ShieldTypeList
```
#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ShieldTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ShieldTypeList()

```csharp
private ShieldTypeList()
```
#INC
#code-generated


## Fields

### _dic

```csharp
private Dictionary<int, ShieldTypeInfo> _dic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,ShieldTypeInfo}

### _instance

```csharp
private static ShieldTypeList _instance
```
#INC


#### Field Value

**Type:** Global.ShieldTypeList

### _list

```csharp
private List<ShieldTypeInfo> _list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{ShieldTypeInfo}

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
public static ShieldTypeList instance { get; }
```

#### Property Value

**Type:** Global.ShieldTypeList

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetData(int)

```csharp
public ShieldTypeInfo GetData(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.ShieldTypeInfo

### GetList()

```csharp
public ReadOnlyCollection<ShieldTypeInfo> GetList()
```
#INC


#### Returns

**Type:** System.Collections.ObjectModel.ReadOnlyCollection{ShieldTypeInfo}

### Init(ReadOnlyCollection<ShieldTypeInfo>)

```csharp
public void Init(ReadOnlyCollection<ShieldTypeInfo> list)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.ObjectModel.ReadOnlyCollection{ShieldTypeInfo}` |  |
