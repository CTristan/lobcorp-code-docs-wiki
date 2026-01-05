# Class PointGenerator

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PointGenerator
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PointGenerator

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### PointGenerator()

```csharp
public PointGenerator()
```

## Methods

### UniformDistribution(int, double)

```csharp
public static List<TriangulationPoint> UniformDistribution(int n, double scale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `n` | `System.Int32` |  |
| `scale` | `System.Double` |  |

#### Returns

**Type:** System.Collections.Generic.List{Poly2Tri.TriangulationPoint}

### UniformGrid(int, double)

```csharp
public static List<TriangulationPoint> UniformGrid(int n, double scale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `n` | `System.Int32` |  |
| `scale` | `System.Double` |  |

#### Returns

**Type:** System.Collections.Generic.List{Poly2Tri.TriangulationPoint}
