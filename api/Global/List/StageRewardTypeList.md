---
uid: Global.StageRewardTypeList
canonical_path: /api/Global/List/StageRewardTypeList
---

# Class StageRewardTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StageRewardTypeList
```
Stores the LOB point reward for each day as a [StageRewardTypeInfo](/api/Global/Info/StageRewardTypeInfo).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StageRewardTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StageRewardTypeList()

```csharp
private StageRewardTypeList()
```
#INC
#code-generated


## Fields

### _instance

```csharp
private static StageRewardTypeList _instance
```
#INC


#### Field Value

**Type:** Global.StageRewardTypeList

### _list

```csharp
private List<StageRewardTypeInfo> _list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{StageRewardTypeInfo}

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
public static StageRewardTypeList instance { get; }
```

#### Property Value

**Type:** Global.StageRewardTypeList

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetData(int)

```csharp
public StageRewardTypeInfo GetData(int day)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

#### Returns

**Type:** Global.StageRewardTypeInfo

### GetList()

```csharp
public StageRewardTypeInfo[] GetList()
```
#INC


#### Returns

**Type:** Global.StageRewardTypeInfo[]

### Init(StageRewardTypeInfo[])

```csharp
public void Init(StageRewardTypeInfo[] list)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `Global.StageRewardTypeInfo[]` |  |
