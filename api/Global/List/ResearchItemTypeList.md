---
uid: Global.ResearchItemTypeList
canonical_path: /api/Global/List/ResearchItemTypeList
---

# Class ResearchItemTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResearchItemTypeList
```
Loads and holds [types of research](/api/Global/Info/ResearchItemTypeInfo).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ResearchItemTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ResearchItemTypeList()

```csharp
private ResearchItemTypeList()
```
#INC
#code-generated


## Fields

### _dic

```csharp
private Dictionary<int, ResearchItemTypeInfo> _dic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,ResearchItemTypeInfo}

### _instance

```csharp
private static ResearchItemTypeList _instance
```
#INC


#### Field Value

**Type:** Global.ResearchItemTypeList

### _list

```csharp
private List<ResearchItemTypeInfo> _list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{ResearchItemTypeInfo}

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
public static ResearchItemTypeList instance { get; }
```

#### Property Value

**Type:** Global.ResearchItemTypeList

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetData(int)

```csharp
public ResearchItemTypeInfo GetData(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.ResearchItemTypeInfo

### GetDataBySefira(string)

```csharp
public List<ResearchItemTypeInfo> GetDataBySefira(string sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

#### Returns

**Type:** System.Collections.Generic.List{ResearchItemTypeInfo}

### GetList()

```csharp
public ReadOnlyCollection<ResearchItemTypeInfo> GetList()
```
#INC


#### Returns

**Type:** System.Collections.ObjectModel.ReadOnlyCollection{ResearchItemTypeInfo}

### Init(ReadOnlyCollection<ResearchItemTypeInfo>)

```csharp
public void Init(ReadOnlyCollection<ResearchItemTypeInfo> list)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.ObjectModel.ReadOnlyCollection{ResearchItemTypeInfo}` |  |
