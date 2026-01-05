# Class DelaunayTriangle

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DelaunayTriangle
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DelaunayTriangle

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DelaunayTriangle(TriangulationPoint, TriangulationPoint, TriangulationPoint)

```csharp
public DelaunayTriangle(TriangulationPoint p1, TriangulationPoint p2, TriangulationPoint p3)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p1` | `Poly2Tri.TriangulationPoint` |  |
| `p2` | `Poly2Tri.TriangulationPoint` |  |
| `p3` | `Poly2Tri.TriangulationPoint` |  |

## Fields

### EdgeIsDelaunay

```csharp
public FixedBitArray3 EdgeIsDelaunay
```

#### Field Value

**Type:** Poly2Tri.FixedBitArray3

### Neighbors

```csharp
public FixedArray3<DelaunayTriangle> Neighbors
```

#### Field Value

**Type:** Poly2Tri.FixedArray3{Poly2Tri.DelaunayTriangle}

### Points

```csharp
public FixedArray3<TriangulationPoint> Points
```

#### Field Value

**Type:** Poly2Tri.FixedArray3{Poly2Tri.TriangulationPoint}

## Properties

### EdgeIsConstrained

```csharp
public FixedBitArray3 EdgeIsConstrained { get; }
```

#### Property Value

**Type:** Poly2Tri.FixedBitArray3

### IsInterior

```csharp
public bool IsInterior { get; set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### Area()

```csharp
public double Area()
```

#### Returns

**Type:** System.Double

### Centroid()

```csharp
public TriangulationPoint Centroid()
```

#### Returns

**Type:** Poly2Tri.TriangulationPoint

### Clear()

```csharp
public void Clear()
```

### ClearNeighbor(DelaunayTriangle)

```csharp
public void ClearNeighbor(DelaunayTriangle triangle)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `triangle` | `Poly2Tri.DelaunayTriangle` |  |

### ClearNeighbors()

```csharp
public void ClearNeighbors()
```

### Contains(TriangulationPoint)

```csharp
public bool Contains(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean

### EdgeIndex(TriangulationPoint, TriangulationPoint)

```csharp
public int EdgeIndex(TriangulationPoint p1, TriangulationPoint p2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p1` | `Poly2Tri.TriangulationPoint` |  |
| `p2` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Int32

### GetConstrainedEdgeAcross(TriangulationPoint)

```csharp
public bool GetConstrainedEdgeAcross(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean

### GetConstrainedEdgeCCW(TriangulationPoint)

```csharp
public bool GetConstrainedEdgeCCW(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean

### GetConstrainedEdgeCW(TriangulationPoint)

```csharp
public bool GetConstrainedEdgeCW(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean

### GetDelaunayEdgeAcross(TriangulationPoint)

```csharp
public bool GetDelaunayEdgeAcross(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean

### GetDelaunayEdgeCCW(TriangulationPoint)

```csharp
public bool GetDelaunayEdgeCCW(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean

### GetDelaunayEdgeCW(TriangulationPoint)

```csharp
public bool GetDelaunayEdgeCW(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean

### GetEdge(int, out DTSweepConstraint)

```csharp
public bool GetEdge(int idx, out DTSweepConstraint edge)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `idx` | `System.Int32` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |

#### Returns

**Type:** System.Boolean

### GetEdgeAcross(TriangulationPoint, out DTSweepConstraint)

```csharp
public bool GetEdgeAcross(TriangulationPoint p, out DTSweepConstraint edge)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |

#### Returns

**Type:** System.Boolean

### GetEdgeCCW(TriangulationPoint, out DTSweepConstraint)

```csharp
public bool GetEdgeCCW(TriangulationPoint p, out DTSweepConstraint edge)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |

#### Returns

**Type:** System.Boolean

### GetEdgeCW(TriangulationPoint, out DTSweepConstraint)

```csharp
public bool GetEdgeCW(TriangulationPoint p, out DTSweepConstraint edge)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |

#### Returns

**Type:** System.Boolean

### IndexCCWFrom(TriangulationPoint)

```csharp
public int IndexCCWFrom(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Int32

### IndexCWFrom(TriangulationPoint)

```csharp
public int IndexCWFrom(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Int32

### IndexOf(TriangulationPoint)

```csharp
public int IndexOf(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Int32

### Legalize(TriangulationPoint, TriangulationPoint)

```csharp
public void Legalize(TriangulationPoint oPoint, TriangulationPoint nPoint)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `oPoint` | `Poly2Tri.TriangulationPoint` |  |
| `nPoint` | `Poly2Tri.TriangulationPoint` |  |

### MarkConstrainedEdge(DTSweepConstraint)

```csharp
public void MarkConstrainedEdge(DTSweepConstraint edge)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |

### MarkConstrainedEdge(int)

```csharp
public void MarkConstrainedEdge(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### MarkConstrainedEdge(TriangulationPoint, TriangulationPoint)

```csharp
public void MarkConstrainedEdge(TriangulationPoint p, TriangulationPoint q)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `q` | `Poly2Tri.TriangulationPoint` |  |

### MarkEdge(DelaunayTriangle)

```csharp
public void MarkEdge(DelaunayTriangle triangle)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `triangle` | `Poly2Tri.DelaunayTriangle` |  |

### MarkEdge(List<DelaunayTriangle>)

```csharp
public void MarkEdge(List<DelaunayTriangle> tList)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tList` | `System.Collections.Generic.List{Poly2Tri.DelaunayTriangle}` |  |

### MarkNeighbor(DelaunayTriangle)

```csharp
public void MarkNeighbor(DelaunayTriangle t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `Poly2Tri.DelaunayTriangle` |  |

### MarkNeighborEdges()

```csharp
public void MarkNeighborEdges()
```

### NeighborAcrossFrom(TriangulationPoint)

```csharp
public DelaunayTriangle NeighborAcrossFrom(TriangulationPoint point)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `point` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** Poly2Tri.DelaunayTriangle

### NeighborCCWFrom(TriangulationPoint)

```csharp
public DelaunayTriangle NeighborCCWFrom(TriangulationPoint point)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `point` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** Poly2Tri.DelaunayTriangle

### NeighborCWFrom(TriangulationPoint)

```csharp
public DelaunayTriangle NeighborCWFrom(TriangulationPoint point)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `point` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** Poly2Tri.DelaunayTriangle

### OppositePoint(DelaunayTriangle, TriangulationPoint)

```csharp
public TriangulationPoint OppositePoint(DelaunayTriangle t, TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `Poly2Tri.DelaunayTriangle` |  |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** Poly2Tri.TriangulationPoint

### PointCCWFrom(TriangulationPoint)

```csharp
public TriangulationPoint PointCCWFrom(TriangulationPoint point)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `point` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** Poly2Tri.TriangulationPoint

### PointCWFrom(TriangulationPoint)

```csharp
public TriangulationPoint PointCWFrom(TriangulationPoint point)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `point` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** Poly2Tri.TriangulationPoint

### SetConstrainedEdge(int, bool)

```csharp
protected void SetConstrainedEdge(int idx, bool ce)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `idx` | `System.Int32` |  |
| `ce` | `System.Boolean` |  |

### SetConstrainedEdgeAcross(TriangulationPoint, bool)

```csharp
public void SetConstrainedEdgeAcross(TriangulationPoint p, bool ce)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `ce` | `System.Boolean` |  |

### SetConstrainedEdgeCCW(TriangulationPoint, bool)

```csharp
public void SetConstrainedEdgeCCW(TriangulationPoint p, bool ce)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `ce` | `System.Boolean` |  |

### SetConstrainedEdgeCW(TriangulationPoint, bool)

```csharp
public void SetConstrainedEdgeCW(TriangulationPoint p, bool ce)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `ce` | `System.Boolean` |  |

### SetDelaunayEdgeAcross(TriangulationPoint, bool)

```csharp
public void SetDelaunayEdgeAcross(TriangulationPoint p, bool ce)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `ce` | `System.Boolean` |  |

### SetDelaunayEdgeCCW(TriangulationPoint, bool)

```csharp
public void SetDelaunayEdgeCCW(TriangulationPoint p, bool ce)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `ce` | `System.Boolean` |  |

### SetDelaunayEdgeCW(TriangulationPoint, bool)

```csharp
public void SetDelaunayEdgeCW(TriangulationPoint p, bool ce)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `ce` | `System.Boolean` |  |

### SharedEdge(TriangulationPoint, TriangulationPoint)

```csharp
public bool SharedEdge(TriangulationPoint p1, TriangulationPoint p2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p1` | `Poly2Tri.TriangulationPoint` |  |
| `p2` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
