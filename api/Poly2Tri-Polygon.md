# Class Polygon

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Polygon : Point2DList, IList<Point2D>, ICollection<Point2D>, IEnumerable<Point2D>, ITriangulatable, IList<TriangulationPoint>, ICollection<TriangulationPoint>, IEnumerable<TriangulationPoint>, IEnumerable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Point2DList](/api/Poly2Tri-Point2DList) → Polygon

## Inherited Members
[kMaxPolygonVertices](/api/Poly2Tri-Point2DList#kmaxpolygonvertices), [kLinearSlop](/api/Poly2Tri-Point2DList#klinearslop), [kAngularSlop](/api/Poly2Tri-Point2DList#kangularslop), [mPoints](/api/Poly2Tri-Point2DList#mpoints), [mBoundingBox](/api/Poly2Tri-Point2DList#mboundingbox), [mWindingOrder](/api/Poly2Tri-Point2DList#mwindingorder), [mEpsilon](/api/Poly2Tri-Point2DList#mepsilon), [ToString()](/api/Poly2Tri-Point2DList#tostring), [Clear()](/api/Poly2Tri-Point2DList#clear), [IndexOf(Point2D)](/api/Poly2Tri-Point2DList#indexof-point2d), [AddRange(Point2DList)](/api/Poly2Tri-Point2DList#addrange-point2dlist), [AddRange(IEnumerator<Point2D>, WindingOrderType)](/api/Poly2Tri-Point2DList#addrange-ienumerator-point2d-windingordertype), [Insert(int, Point2D)](/api/Poly2Tri-Point2DList#insert-int-point2d), [Remove(Point2D)](/api/Poly2Tri-Point2DList#remove-point2d), [RemoveAt(int)](/api/Poly2Tri-Point2DList#removeat-int), [RemoveRange(int, int)](/api/Poly2Tri-Point2DList#removerange-int-int), [Contains(Point2D)](/api/Poly2Tri-Point2DList#contains-point2d), [CopyTo(Point2D[], int)](/api/Poly2Tri-Point2DList#copyto-point2d-int), [CalculateBounds()](/api/Poly2Tri-Point2DList#calculatebounds), [CalculateEpsilon()](/api/Poly2Tri-Point2DList#calculateepsilon), [CalculateWindingOrder()](/api/Poly2Tri-Point2DList#calculatewindingorder), [NextIndex(int)](/api/Poly2Tri-Point2DList#nextindex-int), [PreviousIndex(int)](/api/Poly2Tri-Point2DList#previousindex-int), [GetSignedArea()](/api/Poly2Tri-Point2DList#getsignedarea), [GetArea()](/api/Poly2Tri-Point2DList#getarea), [GetCentroid()](/api/Poly2Tri-Point2DList#getcentroid), [Translate(Point2D)](/api/Poly2Tri-Point2DList#translate-point2d), [Scale(Point2D)](/api/Poly2Tri-Point2DList#scale-point2d), [Rotate(double)](/api/Poly2Tri-Point2DList#rotate-double), [IsDegenerate()](/api/Poly2Tri-Point2DList#isdegenerate), [IsConvex()](/api/Poly2Tri-Point2DList#isconvex), [IsSimple()](/api/Poly2Tri-Point2DList#issimple), [CheckPolygon()](/api/Poly2Tri-Point2DList#checkpolygon), [GetErrorString(PolygonError)](/api/Poly2Tri-Point2DList#geterrorstring-polygonerror), [RemoveDuplicateNeighborPoints()](/api/Poly2Tri-Point2DList#removeduplicateneighborpoints), [Simplify()](/api/Poly2Tri-Point2DList#simplify), [Simplify(double)](/api/Poly2Tri-Point2DList#simplify-double), [MergeParallelEdges(double)](/api/Poly2Tri-Point2DList#mergeparalleledges-double), [ProjectToAxis(Point2D, out double, out double)](/api/Poly2Tri-Point2DList#projecttoaxis-point2d-out-double-out-double), [BoundingBox](/api/Poly2Tri-Point2DList#boundingbox), [WindingOrder](/api/Poly2Tri-Point2DList#windingorder), [Epsilon](/api/Poly2Tri-Point2DList#epsilon), [Count](/api/Poly2Tri-Point2DList#count), [IsReadOnly](/api/Poly2Tri-Point2DList#isreadonly), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Polygon(IEnumerable<PolygonPoint>)

```csharp
public Polygon(IEnumerable<PolygonPoint> points)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `points` | `System.Collections.Generic.IEnumerable{Poly2Tri.PolygonPoint}` |  |

### Polygon(IList<PolygonPoint>)

```csharp
public Polygon(IList<PolygonPoint> points)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `points` | `System.Collections.Generic.IList{Poly2Tri.PolygonPoint}` |  |

### Polygon(params PolygonPoint[])

```csharp
public Polygon(params PolygonPoint[] points)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `points` | `Poly2Tri.PolygonPoint[]` |  |

## Fields

### _last

```csharp
protected PolygonPoint _last
```

#### Field Value

**Type:** Poly2Tri.PolygonPoint

### mHoles

```csharp
protected List<Polygon> mHoles
```

#### Field Value

**Type:** System.Collections.Generic.List{Poly2Tri.Polygon}

### mPointMap

```csharp
protected Dictionary<uint, TriangulationPoint> mPointMap
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.UInt32,Poly2Tri.TriangulationPoint}

### mSteinerPoints

```csharp
protected List<TriangulationPoint> mSteinerPoints
```

#### Field Value

**Type:** System.Collections.Generic.List{Poly2Tri.TriangulationPoint}

### mTriangles

```csharp
protected List<DelaunayTriangle> mTriangles
```

#### Field Value

**Type:** System.Collections.Generic.List{Poly2Tri.DelaunayTriangle}

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

### Holes

```csharp
public IList<Polygon> Holes { get; }
```

#### Property Value

**Type:** System.Collections.Generic.IList{Poly2Tri.Polygon}

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
public IList<TriangulationPoint> Points { get; }
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
public IList<DelaunayTriangle> Triangles { get; }
```

#### Property Value

**Type:** System.Collections.Generic.IList{Poly2Tri.DelaunayTriangle}

### TriangulationMode

```csharp
public TriangulationMode TriangulationMode { get; }
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
protected override void Add(Point2D p, int idx, bool bCalcWindingOrderAndEpsilon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |
| `idx` | `System.Int32` |  |
| `bCalcWindingOrderAndEpsilon` | `System.Boolean` |  |

### Add(PolygonPoint)

```csharp
public void Add(PolygonPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.PolygonPoint` |  |

### Add(TriangulationPoint)

```csharp
public void Add(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

### AddHole(Polygon)

```csharp
public void AddHole(Polygon poly)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `poly` | `Poly2Tri.Polygon` |  |

### AddRange(IList<PolygonPoint>, WindingOrderType)

```csharp
public void AddRange(IList<PolygonPoint> points, Point2DList.WindingOrderType windingOrder)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `points` | `System.Collections.Generic.IList{Poly2Tri.PolygonPoint}` |  |
| `windingOrder` | `Poly2Tri.Point2DList.WindingOrderType` |  |

### AddRange(IList<TriangulationPoint>, WindingOrderType)

```csharp
public void AddRange(IList<TriangulationPoint> points, Point2DList.WindingOrderType windingOrder)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `points` | `System.Collections.Generic.IList{Poly2Tri.TriangulationPoint}` |  |
| `windingOrder` | `Poly2Tri.Point2DList.WindingOrderType` |  |

### AddSteinerPoint(TriangulationPoint)

```csharp
public void AddSteinerPoint(TriangulationPoint point)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `point` | `Poly2Tri.TriangulationPoint` |  |

### AddSteinerPoints(List<TriangulationPoint>)

```csharp
public void AddSteinerPoints(List<TriangulationPoint> points)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `points` | `System.Collections.Generic.List{Poly2Tri.TriangulationPoint}` |  |

### AddTriangle(DelaunayTriangle)

```csharp
public void AddTriangle(DelaunayTriangle t)
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

### ClearSteinerPoints()

```csharp
public void ClearSteinerPoints()
```

### ClearTriangles()

```csharp
public void ClearTriangles()
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

### CopyTo(TriangulationPoint[], int)

```csharp
public void CopyTo(TriangulationPoint[] array, int arrayIndex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `array` | `Poly2Tri.TriangulationPoint[]` |  |
| `arrayIndex` | `System.Int32` |  |

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

### Insert(int, TriangulationPoint)

```csharp
public void Insert(int idx, TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `idx` | `System.Int32` |  |
| `p` | `Poly2Tri.TriangulationPoint` |  |

### IsPointInside(TriangulationPoint)

```csharp
public bool IsPointInside(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean

### Prepare(TriangulationContext)

```csharp
public void Prepare(TriangulationContext tcx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.TriangulationContext` |  |

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

### RemovePoint(PolygonPoint)

```csharp
public void RemovePoint(PolygonPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.PolygonPoint` |  |
