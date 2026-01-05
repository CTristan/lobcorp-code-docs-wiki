# Class StageTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StageTypeInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StageTypeInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### StageTypeInfo()

```csharp
public StageTypeInfo()
```

## Fields

### allocateAgent

```csharp
public int[] allocateAgent
```

#### Field Value

**Type:** System.Int32[]

### energyVal

```csharp
public int[] energyVal
```

#### Field Value

**Type:** System.Int32[]

### goal

```csharp
public int goal
```

#### Field Value

**Type:** System.Int32

### stageTime

```csharp
public int[] stageTime
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

#### Returns

**Type:** System.Single
