# Class P2T

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class P2T
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → P2T

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Methods

### CreateContext(TriangulationAlgorithm)

```csharp
public static TriangulationContext CreateContext(TriangulationAlgorithm algorithm)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `algorithm` | `Poly2Tri.TriangulationAlgorithm` |  |

#### Returns

**Type:** Poly2Tri.TriangulationContext

### Triangulate(ConstrainedPointSet)

```csharp
public static void Triangulate(ConstrainedPointSet cps)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cps` | `Poly2Tri.ConstrainedPointSet` |  |

### Triangulate(PointSet)

```csharp
public static void Triangulate(PointSet ps)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ps` | `Poly2Tri.PointSet` |  |

### Triangulate(Polygon)

```csharp
public static void Triangulate(Polygon p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Polygon` |  |

### Triangulate(PolygonSet)

```csharp
public static void Triangulate(PolygonSet ps)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ps` | `Poly2Tri.PolygonSet` |  |

### Triangulate(TriangulationAlgorithm, ITriangulatable)

```csharp
public static void Triangulate(TriangulationAlgorithm algorithm, ITriangulatable t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `algorithm` | `Poly2Tri.TriangulationAlgorithm` |  |
| `t` | `Poly2Tri.ITriangulatable` |  |

### Triangulate(TriangulationContext)

```csharp
public static void Triangulate(TriangulationContext tcx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.TriangulationContext` |  |

### Warmup()

```csharp
public static void Warmup()
```
