---
uid: Poly2Tri.DTSweep
canonical_path: /api/Poly2Tri/DTSweep
---

# Class DTSweep

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class DTSweep
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DTSweep

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Fields

### PI_3div4

```csharp
private const double PI_3div4 = 2.356194490192345
```

#### Field Value

**Type:** System.Double

### PI_div2

```csharp
private const double PI_div2 = 1.5707963267948966
```

#### Field Value

**Type:** System.Double

## Methods

### BasinAngle(AdvancingFrontNode)

```csharp
private static double BasinAngle(AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

#### Returns

**Type:** System.Double

### EdgeEvent(DTSweepContext, DTSweepConstraint, AdvancingFrontNode)

```csharp
private static void EdgeEvent(DTSweepContext tcx, DTSweepConstraint edge, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### EdgeEvent(DTSweepContext, TriangulationPoint, TriangulationPoint, DelaunayTriangle, TriangulationPoint)

```csharp
private static void EdgeEvent(DTSweepContext tcx, TriangulationPoint ep, TriangulationPoint eq, DelaunayTriangle triangle, TriangulationPoint point)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `ep` | `Poly2Tri.TriangulationPoint` |  |
| `eq` | `Poly2Tri.TriangulationPoint` |  |
| `triangle` | `Poly2Tri.DelaunayTriangle` |  |
| `point` | `Poly2Tri.TriangulationPoint` |  |

### Fill(DTSweepContext, AdvancingFrontNode)

```csharp
private static void Fill(DTSweepContext tcx, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### FillAdvancingFront(DTSweepContext, AdvancingFrontNode)

```csharp
private static void FillAdvancingFront(DTSweepContext tcx, AdvancingFrontNode n)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `n` | `Poly2Tri.AdvancingFrontNode` |  |

### FillBasin(DTSweepContext, AdvancingFrontNode)

```csharp
private static void FillBasin(DTSweepContext tcx, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### FillBasinReq(DTSweepContext, AdvancingFrontNode)

```csharp
private static void FillBasinReq(DTSweepContext tcx, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### FillEdgeEvent(DTSweepContext, DTSweepConstraint, AdvancingFrontNode)

```csharp
private static void FillEdgeEvent(DTSweepContext tcx, DTSweepConstraint edge, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### FillLeftAboveEdgeEvent(DTSweepContext, DTSweepConstraint, AdvancingFrontNode)

```csharp
private static void FillLeftAboveEdgeEvent(DTSweepContext tcx, DTSweepConstraint edge, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### FillLeftBelowEdgeEvent(DTSweepContext, DTSweepConstraint, AdvancingFrontNode)

```csharp
private static void FillLeftBelowEdgeEvent(DTSweepContext tcx, DTSweepConstraint edge, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### FillLeftConcaveEdgeEvent(DTSweepContext, DTSweepConstraint, AdvancingFrontNode)

```csharp
private static void FillLeftConcaveEdgeEvent(DTSweepContext tcx, DTSweepConstraint edge, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### FillLeftConvexEdgeEvent(DTSweepContext, DTSweepConstraint, AdvancingFrontNode)

```csharp
private static void FillLeftConvexEdgeEvent(DTSweepContext tcx, DTSweepConstraint edge, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### FillRightAboveEdgeEvent(DTSweepContext, DTSweepConstraint, AdvancingFrontNode)

```csharp
private static void FillRightAboveEdgeEvent(DTSweepContext tcx, DTSweepConstraint edge, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### FillRightBelowEdgeEvent(DTSweepContext, DTSweepConstraint, AdvancingFrontNode)

```csharp
private static void FillRightBelowEdgeEvent(DTSweepContext tcx, DTSweepConstraint edge, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### FillRightConcaveEdgeEvent(DTSweepContext, DTSweepConstraint, AdvancingFrontNode)

```csharp
private static void FillRightConcaveEdgeEvent(DTSweepContext tcx, DTSweepConstraint edge, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### FillRightConvexEdgeEvent(DTSweepContext, DTSweepConstraint, AdvancingFrontNode)

```csharp
private static void FillRightConvexEdgeEvent(DTSweepContext tcx, DTSweepConstraint edge, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### FinalizationConstraints(DTSweepContext)

```csharp
private static void FinalizationConstraints(DTSweepContext tcx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |

### FinalizationConvexHull(DTSweepContext)

```csharp
private static void FinalizationConvexHull(DTSweepContext tcx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |

### FinalizationPolygon(DTSweepContext)

```csharp
private static void FinalizationPolygon(DTSweepContext tcx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |

### FixupConstrainedEdges(DTSweepContext)

```csharp
private static void FixupConstrainedEdges(DTSweepContext tcx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |

### FlipEdgeEvent(DTSweepContext, TriangulationPoint, TriangulationPoint, DelaunayTriangle, TriangulationPoint)

```csharp
private static void FlipEdgeEvent(DTSweepContext tcx, TriangulationPoint ep, TriangulationPoint eq, DelaunayTriangle t, TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `ep` | `Poly2Tri.TriangulationPoint` |  |
| `eq` | `Poly2Tri.TriangulationPoint` |  |
| `t` | `Poly2Tri.DelaunayTriangle` |  |
| `p` | `Poly2Tri.TriangulationPoint` |  |

### FlipScanEdgeEvent(DTSweepContext, TriangulationPoint, TriangulationPoint, DelaunayTriangle, DelaunayTriangle, TriangulationPoint)

```csharp
private static void FlipScanEdgeEvent(DTSweepContext tcx, TriangulationPoint ep, TriangulationPoint eq, DelaunayTriangle flipTriangle, DelaunayTriangle t, TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `ep` | `Poly2Tri.TriangulationPoint` |  |
| `eq` | `Poly2Tri.TriangulationPoint` |  |
| `flipTriangle` | `Poly2Tri.DelaunayTriangle` |  |
| `t` | `Poly2Tri.DelaunayTriangle` |  |
| `p` | `Poly2Tri.TriangulationPoint` |  |

### HoleAngle(AdvancingFrontNode)

```csharp
private static double HoleAngle(AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

#### Returns

**Type:** System.Double

### IsEdgeSideOfTriangle(DelaunayTriangle, TriangulationPoint, TriangulationPoint)

```csharp
private static bool IsEdgeSideOfTriangle(DelaunayTriangle triangle, TriangulationPoint ep, TriangulationPoint eq)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `triangle` | `Poly2Tri.DelaunayTriangle` |  |
| `ep` | `Poly2Tri.TriangulationPoint` |  |
| `eq` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean

### IsShallow(DTSweepContext, AdvancingFrontNode)

```csharp
private static bool IsShallow(DTSweepContext tcx, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

#### Returns

**Type:** System.Boolean

### Legalize(DTSweepContext, DelaunayTriangle)

```csharp
private static bool Legalize(DTSweepContext tcx, DelaunayTriangle t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `t` | `Poly2Tri.DelaunayTriangle` |  |

#### Returns

**Type:** System.Boolean

### NewFrontTriangle(DTSweepContext, TriangulationPoint, AdvancingFrontNode)

```csharp
private static AdvancingFrontNode NewFrontTriangle(DTSweepContext tcx, TriangulationPoint point, AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `point` | `Poly2Tri.TriangulationPoint` |  |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

#### Returns

**Type:** Poly2Tri.AdvancingFrontNode

### NextFlipPoint(TriangulationPoint, TriangulationPoint, DelaunayTriangle, TriangulationPoint, out TriangulationPoint)

```csharp
private static bool NextFlipPoint(TriangulationPoint ep, TriangulationPoint eq, DelaunayTriangle ot, TriangulationPoint op, out TriangulationPoint newP)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ep` | `Poly2Tri.TriangulationPoint` |  |
| `eq` | `Poly2Tri.TriangulationPoint` |  |
| `ot` | `Poly2Tri.DelaunayTriangle` |  |
| `op` | `Poly2Tri.TriangulationPoint` |  |
| `newP` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean

### NextFlipTriangle(DTSweepContext, Orientation, DelaunayTriangle, DelaunayTriangle, TriangulationPoint, TriangulationPoint)

```csharp
private static DelaunayTriangle NextFlipTriangle(DTSweepContext tcx, Orientation o, DelaunayTriangle t, DelaunayTriangle ot, TriangulationPoint p, TriangulationPoint op)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `o` | `Poly2Tri.Orientation` |  |
| `t` | `Poly2Tri.DelaunayTriangle` |  |
| `ot` | `Poly2Tri.DelaunayTriangle` |  |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `op` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** Poly2Tri.DelaunayTriangle

### PointEvent(DTSweepContext, TriangulationPoint)

```csharp
private static AdvancingFrontNode PointEvent(DTSweepContext tcx, TriangulationPoint point)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `point` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** Poly2Tri.AdvancingFrontNode

### RotateTrianglePair(DelaunayTriangle, TriangulationPoint, DelaunayTriangle, TriangulationPoint)

```csharp
private static void RotateTrianglePair(DelaunayTriangle t, TriangulationPoint p, DelaunayTriangle ot, TriangulationPoint op)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `Poly2Tri.DelaunayTriangle` |  |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `ot` | `Poly2Tri.DelaunayTriangle` |  |
| `op` | `Poly2Tri.TriangulationPoint` |  |

### Sweep(DTSweepContext)

```csharp
private static void Sweep(DTSweepContext tcx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |

### Triangulate(DTSweepContext)

```csharp
public static void Triangulate(DTSweepContext tcx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |

### TurnAdvancingFrontConvex(DTSweepContext, AdvancingFrontNode, AdvancingFrontNode)

```csharp
private static void TurnAdvancingFrontConvex(DTSweepContext tcx, AdvancingFrontNode b, AdvancingFrontNode c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |
| `b` | `Poly2Tri.AdvancingFrontNode` |  |
| `c` | `Poly2Tri.AdvancingFrontNode` |  |
