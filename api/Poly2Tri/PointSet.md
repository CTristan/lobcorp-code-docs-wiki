---
uid: Poly2Tri.PointSet
canonical_path: /api/Poly2Tri/PointSet
---

# Class PointSet

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PointSet : Point2DList, IList<Point2D>, ICollection<Point2D>, IEnumerable<Point2D>, ITriangulatable, IList<TriangulationPoint>, ICollection<TriangulationPoint>, IEnumerable<TriangulationPoint>, IEnumerable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Point2DList](/api/Poly2Tri/Point2DList) → PointSet

## Derived
[ConstrainedPointSet](/api/Poly2Tri/ConstrainedPointSet)

## Implements
[IList<Point2D>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ilist-1), [ICollection<Point2D>](https://learn.microsoft.com/dotnet/api/system.collections.generic.icollection-1), [IEnumerable<Point2D>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable-1), [ITriangulatable](/api/Poly2Tri/ITriangulatable), [IList<TriangulationPoint>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ilist-1), [ICollection<TriangulationPoint>](https://learn.microsoft.com/dotnet/api/system.collections.generic.icollection-1), [IEnumerable<TriangulationPoint>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable-1), [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.ienumerable)

## Inherited Members
[kMaxPolygonVertices](/api/Poly2Tri/Point2DList#kmaxpolygonvertices), [kLinearSlop](/api/Poly2Tri/Point2DList#klinearslop), [kAngularSlop](/api/Poly2Tri/Point2DList#kangularslop), [mPoints](/api/Poly2Tri/Point2DList#mpoints), [mBoundingBox](/api/Poly2Tri/Point2DList#mboundingbox), [mWindingOrder](/api/Poly2Tri/Point2DList#mwindingorder), [mEpsilon](/api/Poly2Tri/Point2DList#mepsilon), [ToString()](/api/Poly2Tri/Point2DList#tostring), [IEnumerable.GetEnumerator()](/api/Poly2Tri/Point2DList#ienumerable-getenumerator), [IEnumerable<Point2D>.GetEnumerator()](/api/Poly2Tri/Point2DList#ienumerable-point2d-getenumerator), [Clear()](/api/Poly2Tri/Point2DList#clear), [IndexOf(Point2D)](/api/Poly2Tri/Point2DList#indexof-point2d), [AddRange(Point2DList)](/api/Poly2Tri/Point2DList#addrange-point2dlist), [Insert(int, Point2D)](/api/Poly2Tri/Point2DList#insert-int-point2d), [RemoveRange(int, int)](/api/Poly2Tri/Point2DList#removerange-int-int), [Contains(Point2D)](/api/Poly2Tri/Point2DList#contains-point2d), [CopyTo(Point2D[], int)](/api/Poly2Tri/Point2DList#copyto-point2d-int), [CalculateBounds()](/api/Poly2Tri/Point2DList#calculatebounds), [CalculateEpsilon()](/api/Poly2Tri/Point2DList#calculateepsilon), [CalculateWindingOrder()](/api/Poly2Tri/Point2DList#calculatewindingorder), [NextIndex(int)](/api/Poly2Tri/Point2DList#nextindex-int), [PreviousIndex(int)](/api/Poly2Tri/Point2DList#previousindex-int), [GetSignedArea()](/api/Poly2Tri/Point2DList#getsignedarea), [GetArea()](/api/Poly2Tri/Point2DList#getarea), [GetCentroid()](/api/Poly2Tri/Point2DList#getcentroid), [Translate(Point2D)](/api/Poly2Tri/Point2DList#translate-point2d), [Scale(Point2D)](/api/Poly2Tri/Point2DList#scale-point2d), [Rotate(double)](/api/Poly2Tri/Point2DList#rotate-double), [IsDegenerate()](/api/Poly2Tri/Point2DList#isdegenerate), [IsConvex()](/api/Poly2Tri/Point2DList#isconvex), [IsSimple()](/api/Poly2Tri/Point2DList#issimple), [CheckPolygon()](/api/Poly2Tri/Point2DList#checkpolygon), [GetErrorString(PolygonError)](/api/Poly2Tri/Point2DList#geterrorstring-polygonerror), [RemoveDuplicateNeighborPoints()](/api/Poly2Tri/Point2DList#removeduplicateneighborpoints), [Simplify()](/api/Poly2Tri/Point2DList#simplify), [Simplify(double)](/api/Poly2Tri/Point2DList#simplify-double), [MergeParallelEdges(double)](/api/Poly2Tri/Point2DList#mergeparalleledges-double), [ProjectToAxis(Point2D, out double, out double)](/api/Poly2Tri/Point2DList#projecttoaxis-point2d-out-double-out-double), [BoundingBox](/api/Poly2Tri/Point2DList#boundingbox), [WindingOrder](/api/Poly2Tri/Point2DList#windingorder), [Epsilon](/api/Poly2Tri/Point2DList#epsilon), [Count](/api/Poly2Tri/Point2DList#count), [IsReadOnly](/api/Poly2Tri/Point2DList#isreadonly), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PointSet(List<TriangulationPoint>)

```csharp
public PointSet(List<TriangulationPoint> bounds)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bounds` | `System.Collections.Generic.List{Poly2Tri.TriangulationPoint}` |  |

## Fields

### mPointMap

```csharp
protected Dictionary<uint, TriangulationPoint> mPointMap
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.UInt32,Poly2Tri.TriangulationPoint}

### mPrecision

```csharp
protected double mPrecision
```

#### Field Value

**Type:** System.Double

## Properties

### Bounds

```csharp
public Rect2D Bounds { get; }
```

#### Property Value

**Type:** Poly2Tri.Rect2D

### DisplayFlipX

```csharp
public bool DisplayFlipX { get; set; }
```

#### Property Value

**Type:** System.Boolean

### DisplayFlipY

```csharp
public bool DisplayFlipY { get; set; }
```

#### Property Value

**Type:** System.Boolean

### DisplayRotate

```csharp
public float DisplayRotate { get; set; }
```

#### Property Value

**Type:** System.Single

### FileName

```csharp
public string FileName { get; set; }
```

#### Property Value

**Type:** System.String

### MaxX

```csharp
public double MaxX { get; }
```

#### Property Value

**Type:** System.Double

### MaxY

```csharp
public double MaxY { get; }
```

#### Property Value

**Type:** System.Double

### MinX

```csharp
public double MinX { get; }
```

#### Property Value

**Type:** System.Double

### MinY

```csharp
public double MinY { get; }
```

#### Property Value

**Type:** System.Double

### Points

```csharp
public IList<TriangulationPoint> Points { get; private set; }
```

#### Property Value

**Type:** System.Collections.Generic.IList{Poly2Tri.TriangulationPoint}

### Precision

```csharp
public double Precision { get; set; }
```

#### Property Value

**Type:** System.Double

### this[int]

```csharp
public TriangulationPoint this[int index] { get; set; }
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Property Value

**Type:** Poly2Tri.TriangulationPoint

### Triangles

```csharp
public IList<DelaunayTriangle> Triangles { get; private set; }
```

#### Property Value

**Type:** System.Collections.Generic.IList{Poly2Tri.DelaunayTriangle}

### TriangulationMode

```csharp
public virtual TriangulationMode TriangulationMode { get; }
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

### Add(Point2D, int, bool)

```csharp
protected override void Add(Point2D p, int idx, bool constrainToBounds)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |
| `idx` | `System.Int32` |  |
| `constrainToBounds` | `System.Boolean` |  |

### Add(TriangulationPoint)

```csharp
public virtual void Add(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

### Add(TriangulationPoint, int, bool)

```csharp
protected bool Add(TriangulationPoint p, int idx, bool constrainToBounds)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `idx` | `System.Int32` |  |
| `constrainToBounds` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean

### AddRange(IEnumerator<Point2D>, WindingOrderType)

```csharp
public override void AddRange(IEnumerator<Point2D> iter, Point2DList.WindingOrderType windingOrder)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `iter` | `System.Collections.Generic.IEnumerator{Poly2Tri.Point2D}` |  |
| `windingOrder` | `Poly2Tri.Point2DList.WindingOrderType` |  |

### AddRange(List<TriangulationPoint>)

```csharp
public virtual bool AddRange(List<TriangulationPoint> points)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `points` | `System.Collections.Generic.List{Poly2Tri.TriangulationPoint}` |  |

#### Returns

**Type:** System.Boolean

### AddTriangle(DelaunayTriangle)

```csharp
public virtual void AddTriangle(DelaunayTriangle t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `Poly2Tri.DelaunayTriangle` |  |

### AddTriangles(IEnumerable<DelaunayTriangle>)

```csharp
public void AddTriangles(IEnumerable<DelaunayTriangle> list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.Generic.IEnumerable{Poly2Tri.DelaunayTriangle}` |  |

### ClearTriangles()

```csharp
public void ClearTriangles()
```

### ConstrainPointToBounds(Point2D)

```csharp
protected bool ConstrainPointToBounds(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean

### ConstrainPointToBounds(TriangulationPoint)

```csharp
protected bool ConstrainPointToBounds(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean

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

### CopyTo(TriangulationPoint[], int)

```csharp
public void CopyTo(TriangulationPoint[] array, int arrayIndex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `array` | `Poly2Tri.TriangulationPoint[]` |  |
| `arrayIndex` | `System.Int32` |  |

### IEnumerable<TriangulationPoint>.GetEnumerator()

```csharp
IEnumerator<TriangulationPoint> IEnumerable<TriangulationPoint>.GetEnumerator()
```

#### Returns

**Type:** System.Collections.Generic.IEnumerator{Poly2Tri.TriangulationPoint}

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

### Initialize()

```csharp
public virtual bool Initialize()
```

#### Returns

**Type:** System.Boolean

### Insert(int, TriangulationPoint)

```csharp
public void Insert(int idx, TriangulationPoint item)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `idx` | `System.Int32` |  |
| `item` | `Poly2Tri.TriangulationPoint` |  |

### Prepare(TriangulationContext)

```csharp
public virtual void Prepare(TriangulationContext tcx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.TriangulationContext` |  |

### Remove(Point2D)

```csharp
public override bool Remove(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean

### Remove(TriangulationPoint)

```csharp
public bool Remove(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean

### RemoveAt(int)

```csharp
public override void RemoveAt(int idx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `idx` | `System.Int32` |  |

### TryGetPoint(double, double, out TriangulationPoint)

```csharp
public bool TryGetPoint(double x, double y, out TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean
