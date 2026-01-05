# Class DistanceUnitUtil

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DistanceUnitUtil
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DistanceUnitUtil

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DistanceUnitUtil()

```csharp
public DistanceUnitUtil()
```

## Fields

### distanceScale

```csharp
public const float distanceScale = 1.3333334
```

#### Field Value

**Type:** System.Single

## Methods

### GameToUnity(float)

```csharp
public static float GameToUnity(float v)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `v` | `System.Single` |  |

#### Returns

**Type:** System.Single

### SelectNearestUnit(UnitModel, List<UnitModel>)

```csharp
public static UnitModel SelectNearestUnit(UnitModel model, List<UnitModel> list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |
| `list` | `System.Collections.Generic.List{UnitModel}` |  |

#### Returns

**Type:** Global.UnitModel

### UnityToGame(float)

```csharp
public static float UnityToGame(float v)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `v` | `System.Single` |  |

#### Returns

**Type:** System.Single
