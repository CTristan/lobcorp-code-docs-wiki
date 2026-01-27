---
uid: Global.StageTypeInfo
canonical_path: /api/Global/Info/StageTypeInfo
---

# Class StageTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StageTypeInfo
```
Stores information about this work day, including the energy value needed.

Also stores how many agents can be allocated to a department of with a certain opened level... #verify 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StageTypeInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StageTypeInfo()

```csharp
public StageTypeInfo()
```

## Fields

### _instance

```csharp
private static StageTypeInfo _instance
```
#INC


#### Field Value

**Type:** Global.StageTypeInfo

### allocateAgent

```csharp
public int[] allocateAgent
```
#INC


#### Field Value

**Type:** System.Int32[]

### energyVal

```csharp
public int[] energyVal
```
#INC


#### Field Value

**Type:** System.Int32[]

### goal

```csharp
public int goal
```
#INC


#### Field Value

**Type:** System.Int32

### stageTime

```csharp
public int[] stageTime
```
#INC


#### Field Value

**Type:** System.Int32[]

## Properties

### instnace

```csharp
public static StageTypeInfo instnace { get; }
```

#### Property Value

**Type:** Global.StageTypeInfo

## Methods

### EndRank(int, float)

```csharp
public int EndRank(int day, float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |
| `time` | `System.Single` |  |

#### Returns

**Type:** System.Int32

### GetEnergyNeed(int)

```csharp
public float GetEnergyNeed(int day)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

#### Returns

**Type:** System.Single

### GetEnergyNeedInUnlimitMode(int)

```csharp
private float GetEnergyNeedInUnlimitMode(int day)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

#### Returns

**Type:** System.Single
