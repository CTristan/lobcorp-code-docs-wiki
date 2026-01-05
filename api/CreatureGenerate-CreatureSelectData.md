# Class CreatureSelectData

**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureSelectData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureSelectData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreatureSelectData(int)

```csharp
public CreatureSelectData(int day)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

## Fields

### zeroAry

```csharp
public static float[] zeroAry
```

#### Field Value

**Type:** System.Single[]

## Properties

### Day

```csharp
public int Day { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### GetCreature()

```csharp
public List<long> GetCreature()
```

#### Returns

**Type:** System.Collections.Generic.List{System.Int64}

### SetActionType(GenerateCommonAction, params long[])

```csharp
public void SetActionType(GenerateCommonAction action, params long[] ids)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `CreatureGenerate.GenerateCommonAction` |  |
| `ids` | `System.Int64[]` |  |

### SetProb(List<float>, List<float>, List<float>)

```csharp
public void SetProb(List<float> d1, List<float> d2, List<float> d3)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `d1` | `System.Collections.Generic.List{System.Single}` |  |
| `d2` | `System.Collections.Generic.List{System.Single}` |  |
| `d3` | `System.Collections.Generic.List{System.Single}` |  |
