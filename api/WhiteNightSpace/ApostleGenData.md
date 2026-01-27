---
uid: WhiteNightSpace.ApostleGenData
canonical_path: /api/WhiteNightSpace/ApostleGenData
---

# Class ApostleGenData

**Namespace:** [WhiteNightSpace](/api/WhiteNightSpace)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ApostleGenData
```
Data for making an apostle from an agent, maybe?
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ApostleGenData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ApostleGenData(WorkerModel, ApostleData, int)

```csharp
public ApostleGenData(WorkerModel worker, ApostleData data, int index)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |
| `data` | `WhiteNightSpace.ApostleData` |  |
| `index` | `System.Int32` |  |

## Fields

### AposlteModel

```csharp
public ChildCreatureModel AposlteModel
```
#INC


#### Field Value

**Type:** Global.ChildCreatureModel

### data

```csharp
public ApostleData data
```
#INC


#### Field Value

**Type:** WhiteNightSpace.ApostleData

### index

```csharp
public int index
```
#INC


#### Field Value

**Type:** System.Int32

### target

```csharp
public WorkerModel target
```
#INC


#### Field Value

**Type:** Global.WorkerModel

## Methods

### Compare(ApostleGenData, ApostleGenData)

```csharp
public static int Compare(ApostleGenData a, ApostleGenData b)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `WhiteNightSpace.ApostleGenData` |  |
| `b` | `WhiteNightSpace.ApostleGenData` |  |

#### Returns

**Type:** System.Int32
