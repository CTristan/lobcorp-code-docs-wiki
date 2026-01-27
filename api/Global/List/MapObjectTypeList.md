---
uid: Global.MapObjectTypeList
canonical_path: /api/Global/List/MapObjectTypeList
---

# Class MapObjectTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MapObjectTypeList
```
Manager for a list with one item: a [MapObject](/api/Global/Object/MapObject) prefab.

#unused #maybe_unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MapObjectTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MapObjectTypeList()

```csharp
private MapObjectTypeList()
```
#INC
#code-generated


## Fields

### _instance

```csharp
private static MapObjectTypeList _instance
```
#INC


#### Field Value

**Type:** Global.MapObjectTypeList

### _list

```csharp
private List<MapObjectTypeInfo> _list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MapObjectTypeInfo}

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
public static MapObjectTypeList instance { get; }
```

#### Property Value

**Type:** Global.MapObjectTypeList

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetData(long)

```csharp
public MapObjectTypeInfo GetData(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.MapObjectTypeInfo

### GetList()

```csharp
public MapObjectTypeInfo[] GetList()
```
#INC


#### Returns

**Type:** Global.MapObjectTypeInfo[]

### Init(MapObjectTypeInfo[])

```csharp
public void Init(MapObjectTypeInfo[] list)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `Global.MapObjectTypeInfo[]` |  |
