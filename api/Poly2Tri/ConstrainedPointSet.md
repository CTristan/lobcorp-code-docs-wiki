---
uid: Poly2Tri.ConstrainedPointSet
canonical_path: /api/Poly2Tri/ConstrainedPointSet
---

# Class ConstrainedPointSet

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ConstrainedPointSet : PointSet, IList<Point2D>, ICollection<Point2D>, IEnumerable<Point2D>, ITriangulatable, IList<TriangulationPoint>, ICollection<TriangulationPoint>, IEnumerable<TriangulationPoint>, IEnumerable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Point2DList](/api/Poly2Tri/Point2DList) → [PointSet](/api/Poly2Tri/PointSet) → ConstrainedPointSet

## Implements
[IList<Point2D>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ilist-1), [ICollection<Point2D>](https://learn.microsoft.com/dotnet/api/system.collections.generic.icollection-1), [IEnumerable<Point2D>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable-1), [ITriangulatable](/api/Poly2Tri/ITriangulatable), [IList<TriangulationPoint>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ilist-1), [ICollection<TriangulationPoint>](https://learn.microsoft.com/dotnet/api/system.collections.generic.icollection-1), [IEnumerable<TriangulationPoint>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable-1), [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.ienumerable)

## Inherited Members
[mPointMap](/api/Poly2Tri/PointSet#mpointmap), [<Triangles>k__BackingField](Poly2Tri.PointSet.html#Poly2Tri_PointSet__Triangles_k__BackingField), [<FileName>k__BackingField](Poly2Tri.PointSet.html#Poly2Tri_PointSet__FileName_k__BackingField), [<DisplayFlipX>k__BackingField](Poly2Tri.PointSet.html#Poly2Tri_PointSet__DisplayFlipX_k__BackingField), [<DisplayFlipY>k__BackingField](Poly2Tri.PointSet.html#Poly2Tri_PointSet__DisplayFlipY_k__BackingField), [<DisplayRotate>k__BackingField](Poly2Tri.PointSet.html#Poly2Tri_PointSet__DisplayRotate_k__BackingField), [mPrecision](/api/Poly2Tri/PointSet#mprecision), [IEnumerable<TriangulationPoint>.GetEnumerator()](/api/Poly2Tri/PointSet#ienumerable-triangulationpoint-getenumerator), [IndexOf(TriangulationPoint)](/api/Poly2Tri/PointSet#indexof-triangulationpoint), [Add(Point2D, int, bool)](/api/Poly2Tri/PointSet#add-point2d-int-bool), [Add(TriangulationPoint, int, bool)](/api/Poly2Tri/PointSet#add-triangulationpoint-int-bool), [AddRange(IEnumerator<Point2D>, WindingOrderType)](/api/Poly2Tri/PointSet#addrange-ienumerator-point2d-windingordertype), [TryGetPoint(double, double, out TriangulationPoint)](/api/Poly2Tri/PointSet#trygetpoint-double-double-out-triangulationpoint), [Insert(int, TriangulationPoint)](/api/Poly2Tri/PointSet#insert-int-triangulationpoint), [Remove(Point2D)](/api/Poly2Tri/PointSet#remove-point2d), [Remove(TriangulationPoint)](/api/Poly2Tri/PointSet#remove-triangulationpoint), [RemoveAt(int)](/api/Poly2Tri/PointSet#removeat-int), [Contains(TriangulationPoint)](/api/Poly2Tri/PointSet#contains-triangulationpoint), [CopyTo(TriangulationPoint[], int)](/api/Poly2Tri/PointSet#copyto-triangulationpoint-int), [ConstrainPointToBounds(Point2D)](/api/Poly2Tri/PointSet#constrainpointtobounds-point2d), [ConstrainPointToBounds(TriangulationPoint)](/api/Poly2Tri/PointSet#constrainpointtobounds-triangulationpoint), [AddTriangles(IEnumerable<DelaunayTriangle>)](/api/Poly2Tri/PointSet#addtriangles-ienumerable-delaunaytriangle), [ClearTriangles()](/api/Poly2Tri/PointSet#cleartriangles), [Points](/api/Poly2Tri/PointSet#points), [Triangles](/api/Poly2Tri/PointSet#triangles), [FileName](/api/Poly2Tri/PointSet#filename), [DisplayFlipX](/api/Poly2Tri/PointSet#displayflipx), [DisplayFlipY](/api/Poly2Tri/PointSet#displayflipy), [DisplayRotate](/api/Poly2Tri/PointSet#displayrotate), [Precision](/api/Poly2Tri/PointSet#precision), [MinX](/api/Poly2Tri/PointSet#minx), [MaxX](/api/Poly2Tri/PointSet#maxx), [MinY](/api/Poly2Tri/PointSet#miny), [MaxY](/api/Poly2Tri/PointSet#maxy), [Bounds](/api/Poly2Tri/PointSet#bounds), [this[int]](/api/Poly2Tri/PointSet#this-int), [kMaxPolygonVertices](/api/Poly2Tri/Point2DList#kmaxpolygonvertices), [kLinearSlop](/api/Poly2Tri/Point2DList#klinearslop), [kAngularSlop](/api/Poly2Tri/Point2DList#kangularslop), [mPoints](/api/Poly2Tri/Point2DList#mpoints), [mBoundingBox](/api/Poly2Tri/Point2DList#mboundingbox), [mWindingOrder](/api/Poly2Tri/Point2DList#mwindingorder), [mEpsilon](/api/Poly2Tri/Point2DList#mepsilon), [ToString()](/api/Poly2Tri/Point2DList#tostring), [IEnumerable.GetEnumerator()](/api/Poly2Tri/Point2DList#ienumerable-getenumerator), [IEnumerable<Point2D>.GetEnumerator()](/api/Poly2Tri/Point2DList#ienumerable-point2d-getenumerator), [Clear()](/api/Poly2Tri/Point2DList#clear), [IndexOf(Point2D)](/api/Poly2Tri/Point2DList#indexof-point2d), [AddRange(Point2DList)](/api/Poly2Tri/Point2DList#addrange-point2dlist), [Insert(int, Point2D)](/api/Poly2Tri/Point2DList#insert-int-point2d), [RemoveRange(int, int)](/api/Poly2Tri/Point2DList#removerange-int-int), [Contains(Point2D)](/api/Poly2Tri/Point2DList#contains-point2d), [CopyTo(Point2D[], int)](/api/Poly2Tri/Point2DList#copyto-point2d-int), [CalculateBounds()](/api/Poly2Tri/Point2DList#calculatebounds), [CalculateEpsilon()](/api/Poly2Tri/Point2DList#calculateepsilon), [CalculateWindingOrder()](/api/Poly2Tri/Point2DList#calculatewindingorder), [NextIndex(int)](/api/Poly2Tri/Point2DList#nextindex-int), [PreviousIndex(int)](/api/Poly2Tri/Point2DList#previousindex-int), [GetSignedArea()](/api/Poly2Tri/Point2DList#getsignedarea), [GetArea()](/api/Poly2Tri/Point2DList#getarea), [GetCentroid()](/api/Poly2Tri/Point2DList#getcentroid), [Translate(Point2D)](/api/Poly2Tri/Point2DList#translate-point2d), [Scale(Point2D)](/api/Poly2Tri/Point2DList#scale-point2d), [Rotate(double)](/api/Poly2Tri/Point2DList#rotate-double), [IsDegenerate()](/api/Poly2Tri/Point2DList#isdegenerate), [IsConvex()](/api/Poly2Tri/Point2DList#isconvex), [IsSimple()](/api/Poly2Tri/Point2DList#issimple), [CheckPolygon()](/api/Poly2Tri/Point2DList#checkpolygon), [GetErrorString(PolygonError)](/api/Poly2Tri/Point2DList#geterrorstring-polygonerror), [RemoveDuplicateNeighborPoints()](/api/Poly2Tri/Point2DList#removeduplicateneighborpoints), [Simplify()](/api/Poly2Tri/Point2DList#simplify), [Simplify(double)](/api/Poly2Tri/Point2DList#simplify-double), [MergeParallelEdges(double)](/api/Poly2Tri/Point2DList#mergeparalleledges-double), [ProjectToAxis(Point2D, out double, out double)](/api/Poly2Tri/Point2DList#projecttoaxis-point2d-out-double-out-double), [BoundingBox](/api/Poly2Tri/Point2DList#boundingbox), [WindingOrder](/api/Poly2Tri/Point2DList#windingorder), [Epsilon](/api/Poly2Tri/Point2DList#epsilon), [Count](/api/Poly2Tri/Point2DList#count), [IsReadOnly](/api/Poly2Tri/Point2DList#isreadonly), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ConstrainedPointSet(List<TriangulationPoint>)

```csharp
public ConstrainedPointSet(List<TriangulationPoint> bounds)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bounds` | `System.Collections.Generic.List{Poly2Tri.TriangulationPoint}` |  |

### ConstrainedPointSet(List<TriangulationPoint>, int[])

```csharp
public ConstrainedPointSet(List<TriangulationPoint> bounds, int[] indices)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bounds` | `System.Collections.Generic.List{Poly2Tri.TriangulationPoint}` |  |
| `indices` | `System.Int32[]` |  |

### ConstrainedPointSet(List<TriangulationPoint>, List<TriangulationConstraint>)

```csharp
public ConstrainedPointSet(List<TriangulationPoint> bounds, List<TriangulationConstraint> constraints)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bounds` | `System.Collections.Generic.List{Poly2Tri.TriangulationPoint}` |  |
| `constraints` | `System.Collections.Generic.List{Poly2Tri.TriangulationConstraint}` |  |

## Fields

### mConstraintMap

```csharp
protected Dictionary<uint, TriangulationConstraint> mConstraintMap
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.UInt32,Poly2Tri.TriangulationConstraint}

### mHoles

```csharp
protected List<Contour> mHoles
```

#### Field Value

**Type:** System.Collections.Generic.List{Poly2Tri.Contour}

## Properties

### TriangulationMode

```csharp
public override TriangulationMode TriangulationMode { get; }
```

#### Property Value

**Type:** Poly2Tri.TriangulationMode

## Methods

### Add(Point2D)

```csharp
public override void Add(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

### Add(TriangulationPoint)

```csharp
public override void Add(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

### AddBoundaryConstraints()

```csharp
protected void AddBoundaryConstraints()
```

### AddConstraint(TriangulationConstraint)

```csharp
public bool AddConstraint(TriangulationConstraint tc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tc` | `Poly2Tri.TriangulationConstraint` |  |

#### Returns

**Type:** System.Boolean

### AddConstraints(List<TriangulationConstraint>)

```csharp
public bool AddConstraints(List<TriangulationConstraint> constraints)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraints` | `System.Collections.Generic.List{Poly2Tri.TriangulationConstraint}` |  |

#### Returns

**Type:** System.Boolean

### AddHole(List<TriangulationPoint>, string)

```csharp
public bool AddHole(List<TriangulationPoint> points, string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `points` | `System.Collections.Generic.List{Poly2Tri.TriangulationPoint}` |  |
| `name` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### AddRange(List<TriangulationPoint>)

```csharp
public override bool AddRange(List<TriangulationPoint> points)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `points` | `System.Collections.Generic.List{Poly2Tri.TriangulationPoint}` |  |

#### Returns

**Type:** System.Boolean

### AddTriangle(DelaunayTriangle)

```csharp
public override void AddTriangle(DelaunayTriangle t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `Poly2Tri.DelaunayTriangle` |  |

### GetActualHoles(out List<Contour>)

```csharp
public int GetActualHoles(out List<Contour> holes)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `holes` | `System.Collections.Generic.List{Poly2Tri.Contour}` |  |

#### Returns

**Type:** System.Int32

### GetConstraintEnumerator()

```csharp
public Dictionary<uint, TriangulationConstraint>.Enumerator GetConstraintEnumerator()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.UInt32,Poly2Tri.TriangulationConstraint}.Enumerator

### GetHole(int)

```csharp
public Contour GetHole(int idx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `idx` | `System.Int32` |  |

#### Returns

**Type:** Poly2Tri.Contour

### GetNumConstraints()

```csharp
public int GetNumConstraints()
```

#### Returns

**Type:** System.Int32

### GetNumHoles()

```csharp
public int GetNumHoles()
```

#### Returns

**Type:** System.Int32

### Initialize()

```csharp
public override bool Initialize()
```

#### Returns

**Type:** System.Boolean

### InitializeHoles()

```csharp
protected void InitializeHoles()
```

### Prepare(TriangulationContext)

```csharp
public override void Prepare(TriangulationContext tcx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.TriangulationContext` |  |

### TryGetConstraint(uint, out TriangulationConstraint)

```csharp
public bool TryGetConstraint(uint constraintCode, out TriangulationConstraint tc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraintCode` | `System.UInt32` |  |
| `tc` | `Poly2Tri.TriangulationConstraint` |  |

#### Returns

**Type:** System.Boolean
