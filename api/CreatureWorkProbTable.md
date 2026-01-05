# Class CreatureWorkProbTable

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureWorkProbTable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureWorkProbTable

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreatureWorkProbTable()

```csharp
public CreatureWorkProbTable()
```

## Methods

### GetWorkProb(RwbpType, int)

```csharp
public float GetWorkProb(RwbpType type, int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.Single

### SetWorkProb(RwbpType, int, float)

```csharp
public void SetWorkProb(RwbpType type, int level, float prob)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `level` | `System.Int32` |  |
| `prob` | `System.Single` |  |
