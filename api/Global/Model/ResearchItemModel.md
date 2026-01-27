---
uid: Global.ResearchItemModel
canonical_path: /api/Global/Model/ResearchItemModel
---

# Class ResearchItemModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResearchItemModel
```
A research.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ResearchItemModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ResearchItemModel()

```csharp
public ResearchItemModel()
```

## Fields

### curLevel

```csharp
public int curLevel
```
#INC


#### Field Value

**Type:** System.Int32

### info

```csharp
public ResearchItemTypeInfo info
```
#INC


#### Field Value

**Type:** Global.ResearchItemTypeInfo

## Methods

### CompareById(ResearchItemModel, ResearchItemModel)

```csharp
public static int CompareById(ResearchItemModel a, ResearchItemModel b)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Global.ResearchItemModel` |  |
| `b` | `Global.ResearchItemModel` |  |

#### Returns

**Type:** System.Int32

### GetCurrentUpgradeInfo()

```csharp
public ResearchUpgradeInfo GetCurrentUpgradeInfo()
```
#INC


#### Returns

**Type:** Global.ResearchUpgradeInfo

### GetNextUpgradeInfo()

```csharp
public ResearchUpgradeInfo GetNextUpgradeInfo()
```
#INC


#### Returns

**Type:** Global.ResearchUpgradeInfo

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```
#INC
#code-generated


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
