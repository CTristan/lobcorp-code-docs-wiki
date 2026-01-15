---
uid: Poly2Tri.PolygonPoint
canonical_path: /api/Poly2Tri/PolygonPoint
---

# Class PolygonPoint

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PolygonPoint : TriangulationPoint, IComparable<Point2D>
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Point2D](/api/Poly2Tri/Point2D) → [TriangulationPoint](/api/Poly2Tri/TriangulationPoint) → PolygonPoint

## Implements
[IComparable<Point2D>](https://learn.microsoft.com/dotnet/api/system.icomparable-1)

## Inherited Members
[kVertexCodeDefaultPrecision](/api/Poly2Tri/TriangulationPoint#kvertexcodedefaultprecision), [mVertexCode](/api/Poly2Tri/TriangulationPoint#mvertexcode), [<Edges>k__BackingField](Poly2Tri.TriangulationPoint.html#Poly2Tri_TriangulationPoint__Edges_k__BackingField), [ToString()](/api/Poly2Tri/TriangulationPoint#tostring), [GetHashCode()](/api/Poly2Tri/TriangulationPoint#gethashcode), [Equals(object)](/api/Poly2Tri/TriangulationPoint#equals-object), [Set(double, double)](/api/Poly2Tri/TriangulationPoint#set-double-double), [CreateVertexCode(double, double, double)](/api/Poly2Tri/TriangulationPoint#createvertexcode-double-double-double), [AddEdge(DTSweepConstraint)](/api/Poly2Tri/TriangulationPoint#addedge-dtsweepconstraint), [HasEdge(TriangulationPoint)](/api/Poly2Tri/TriangulationPoint#hasedge-triangulationpoint), [GetEdge(TriangulationPoint, out DTSweepConstraint)](/api/Poly2Tri/TriangulationPoint#getedge-triangulationpoint-out-dtsweepconstraint), [ToPoint2D(TriangulationPoint)](/api/Poly2Tri/TriangulationPoint#topoint2d-triangulationpoint), [X](/api/Poly2Tri/TriangulationPoint#x), [Y](/api/Poly2Tri/TriangulationPoint#y), [VertexCode](/api/Poly2Tri/TriangulationPoint#vertexcode), [Edges](/api/Poly2Tri/TriangulationPoint#edges), [HasEdges](/api/Poly2Tri/TriangulationPoint#hasedges), [mX](/api/Poly2Tri/Point2D#mx), [mY](/api/Poly2Tri/Point2D#my), [Equals(Point2D)](/api/Poly2Tri/Point2D#equals-point2d), [Equals(Point2D, double)](/api/Poly2Tri/Point2D#equals-point2d-double), [CompareTo(Point2D)](/api/Poly2Tri/Point2D#compareto-point2d), [Set(Point2D)](/api/Poly2Tri/Point2D#set-point2d), [Add(Point2D)](/api/Poly2Tri/Point2D#add-point2d), [Add(double)](/api/Poly2Tri/Point2D#add-double), [Subtract(Point2D)](/api/Poly2Tri/Point2D#subtract-point2d), [Subtract(double)](/api/Poly2Tri/Point2D#subtract-double), [Multiply(Point2D)](/api/Poly2Tri/Point2D#multiply-point2d), [Multiply(double)](/api/Poly2Tri/Point2D#multiply-double), [Divide(Point2D)](/api/Poly2Tri/Point2D#divide-point2d), [Divide(double)](/api/Poly2Tri/Point2D#divide-double), [Negate()](/api/Poly2Tri/Point2D#negate), [Magnitude()](/api/Poly2Tri/Point2D#magnitude), [MagnitudeSquared()](/api/Poly2Tri/Point2D#magnitudesquared), [MagnitudeReciprocal()](/api/Poly2Tri/Point2D#magnitudereciprocal), [Normalize()](/api/Poly2Tri/Point2D#normalize), [Dot(Point2D)](/api/Poly2Tri/Point2D#dot-point2d), [Cross(Point2D)](/api/Poly2Tri/Point2D#cross-point2d), [Clamp(Point2D, Point2D)](/api/Poly2Tri/Point2D#clamp-point2d-point2d), [Abs()](/api/Poly2Tri/Point2D#abs), [Reciprocal()](/api/Poly2Tri/Point2D#reciprocal), [Translate(Point2D)](/api/Poly2Tri/Point2D#translate-point2d), [Translate(double, double)](/api/Poly2Tri/Point2D#translate-double-double), [Scale(Point2D)](/api/Poly2Tri/Point2D#scale-point2d), [Scale(double)](/api/Poly2Tri/Point2D#scale-double), [Scale(double, double)](/api/Poly2Tri/Point2D#scale-double-double), [Rotate(double)](/api/Poly2Tri/Point2D#rotate-double), [RotateDegrees(double)](/api/Poly2Tri/Point2D#rotatedegrees-double), [Dot(Point2D, Point2D)](/api/Poly2Tri/Point2D#dot-point2d-point2d), [Cross(Point2D, Point2D)](/api/Poly2Tri/Point2D#cross-point2d-point2d), [Clamp(Point2D, Point2D, Point2D)](/api/Poly2Tri/Point2D#clamp-point2d-point2d-point2d), [Min(Point2D, Point2D)](/api/Poly2Tri/Point2D#min-point2d-point2d), [Max(Point2D, Point2D)](/api/Poly2Tri/Point2D#max-point2d-point2d), [Abs(Point2D)](/api/Poly2Tri/Point2D#abs-point2d), [Reciprocal(Point2D)](/api/Poly2Tri/Point2D#reciprocal-point2d), [Perpendicular(Point2D, double)](/api/Poly2Tri/Point2D#perpendicular-point2d-double), [Perpendicular(double, Point2D)](/api/Poly2Tri/Point2D#perpendicular-double-point2d), [Xf](/api/Poly2Tri/Point2D#xf), [Yf](/api/Poly2Tri/Point2D#yf), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PolygonPoint(double, double)

```csharp
public PolygonPoint(double x, double y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |

## Properties

### Next

```csharp
public PolygonPoint Next { get; set; }
```

#### Property Value

**Type:** Poly2Tri.PolygonPoint

### Previous

```csharp
public PolygonPoint Previous { get; set; }
```

#### Property Value

**Type:** Poly2Tri.PolygonPoint

## Methods

### ToBasePoint(PolygonPoint)

```csharp
public static Point2D ToBasePoint(PolygonPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.PolygonPoint` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### ToTriangulationPoint(PolygonPoint)

```csharp
public static TriangulationPoint ToTriangulationPoint(PolygonPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.PolygonPoint` |  |

#### Returns

**Type:** Poly2Tri.TriangulationPoint
