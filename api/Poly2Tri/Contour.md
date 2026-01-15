---
uid: Poly2Tri.Contour
canonical_path: /api/Poly2Tri/Contour
---

# Class Contour

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Contour : Point2DList, IList<Point2D>, ICollection<Point2D>, IEnumerable<Point2D>, ITriangulatable, IList<TriangulationPoint>, ICollection<TriangulationPoint>, IEnumerable<TriangulationPoint>, IEnumerable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Point2DList](/api/Poly2Tri/Point2DList) → Contour

## Implements
[IList<Point2D>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ilist-1), [ICollection<Point2D>](https://learn.microsoft.com/dotnet/api/system.collections.generic.icollection-1), [IEnumerable<Point2D>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable-1), [ITriangulatable](/api/Poly2Tri/ITriangulatable), [IList<TriangulationPoint>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ilist-1), [ICollection<TriangulationPoint>](https://learn.microsoft.com/dotnet/api/system.collections.generic.icollection-1), [IEnumerable<TriangulationPoint>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable-1), [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.ienumerable)

## Inherited Members
[kMaxPolygonVertices](/api/Poly2Tri/Point2DList#kmaxpolygonvertices), [kLinearSlop](/api/Poly2Tri/Point2DList#klinearslop), [kAngularSlop](/api/Poly2Tri/Point2DList#kangularslop), [mPoints](/api/Poly2Tri/Point2DList#mpoints), [mBoundingBox](/api/Poly2Tri/Point2DList#mboundingbox), [mWindingOrder](/api/Poly2Tri/Point2DList#mwindingorder), [mEpsilon](/api/Poly2Tri/Point2DList#mepsilon), [IEnumerable.GetEnumerator()](/api/Poly2Tri/Point2DList#ienumerable-getenumerator), [IEnumerable<Point2D>.GetEnumerator()](/api/Poly2Tri/Point2DList#ienumerable-point2d-getenumerator), [Clear()](/api/Poly2Tri/Point2DList#clear), [IndexOf(Point2D)](/api/Poly2Tri/Point2DList#indexof-point2d), [Add(Point2D)](/api/Poly2Tri/Point2DList#add-point2d), [AddRange(Point2DList)](/api/Poly2Tri/Point2DList#addrange-point2dlist), [Insert(int, Point2D)](/api/Poly2Tri/Point2DList#insert-int-point2d), [Remove(Point2D)](/api/Poly2Tri/Point2DList#remove-point2d), [RemoveAt(int)](/api/Poly2Tri/Point2DList#removeat-int), [RemoveRange(int, int)](/api/Poly2Tri/Point2DList#removerange-int-int), [Contains(Point2D)](/api/Poly2Tri/Point2DList#contains-point2d), [CopyTo(Point2D[], int)](/api/Poly2Tri/Point2DList#copyto-point2d-int), [CalculateBounds()](/api/Poly2Tri/Point2DList#calculatebounds), [CalculateEpsilon()](/api/Poly2Tri/Point2DList#calculateepsilon), [CalculateWindingOrder()](/api/Poly2Tri/Point2DList#calculatewindingorder), [NextIndex(int)](/api/Poly2Tri/Point2DList#nextindex-int), [PreviousIndex(int)](/api/Poly2Tri/Point2DList#previousindex-int), [GetSignedArea()](/api/Poly2Tri/Point2DList#getsignedarea), [GetArea()](/api/Poly2Tri/Point2DList#getarea), [GetCentroid()](/api/Poly2Tri/Point2DList#getcentroid), [Translate(Point2D)](/api/Poly2Tri/Point2DList#translate-point2d), [Scale(Point2D)](/api/Poly2Tri/Point2DList#scale-point2d), [Rotate(double)](/api/Poly2Tri/Point2DList#rotate-double), [IsDegenerate()](/api/Poly2Tri/Point2DList#isdegenerate), [IsConvex()](/api/Poly2Tri/Point2DList#isconvex), [IsSimple()](/api/Poly2Tri/Point2DList#issimple), [CheckPolygon()](/api/Poly2Tri/Point2DList#checkpolygon), [GetErrorString(PolygonError)](/api/Poly2Tri/Point2DList#geterrorstring-polygonerror), [RemoveDuplicateNeighborPoints()](/api/Poly2Tri/Point2DList#removeduplicateneighborpoints), [Simplify()](/api/Poly2Tri/Point2DList#simplify), [Simplify(double)](/api/Poly2Tri/Point2DList#simplify-double), [MergeParallelEdges(double)](/api/Poly2Tri/Point2DList#mergeparalleledges-double), [ProjectToAxis(Point2D, out double, out double)](/api/Poly2Tri/Point2DList#projecttoaxis-point2d-out-double-out-double), [BoundingBox](/api/Poly2Tri/Point2DList#boundingbox), [WindingOrder](/api/Poly2Tri/Point2DList#windingorder), [Epsilon](/api/Poly2Tri/Point2DList#epsilon), [Count](/api/Poly2Tri/Point2DList#count), [IsReadOnly](/api/Poly2Tri/Point2DList#isreadonly), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Contour(ITriangulatable)

```csharp
public Contour(ITriangulatable parent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `parent` | `Poly2Tri.ITriangulatable` |  |

### Contour(ITriangulatable, IList<TriangulationPoint>, WindingOrderType)

```csharp
public Contour(ITriangulatable parent, IList<TriangulationPoint> points, Point2DList.WindingOrderType windingOrder)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `parent` | `Poly2Tri.ITriangulatable` |  |
| `points` | `System.Collections.Generic.IList{Poly2Tri.TriangulationPoint}` |  |
| `windingOrder` | `Poly2Tri.Point2DList.WindingOrderType` |  |

## Fields

### mHoles

```csharp
private List<Contour> mHoles
```

#### Field Value

**Type:** System.Collections.Generic.List{Poly2Tri.Contour}

### mName

```csharp
private string mName
```

#### Field Value

**Type:** System.String

### mParent

```csharp
private ITriangulatable mParent
```

#### Field Value

**Type:** Poly2Tri.ITriangulatable

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

### Name

```csharp
public string Name { get; set; }
```

#### Property Value

**Type:** System.String

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
public TriangulationMode TriangulationMode { get; }
```

#### Property Value

**Type:** Poly2Tri.TriangulationMode

## Methods

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

### Add(TriangulationPoint)

```csharp
public void Add(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

### AddHole(Contour)

```csharp
protected void AddHole(Contour c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `Poly2Tri.Contour` |  |

### AddRange(IEnumerator<Point2D>, WindingOrderType)

```csharp
public override void AddRange(IEnumerator<Point2D> iter, Point2DList.WindingOrderType windingOrder)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `iter` | `System.Collections.Generic.IEnumerator{Poly2Tri.Point2D}` |  |
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

### FindPointInContour()

```csharp
public Point2D FindPointInContour()
```

#### Returns

**Type:** Poly2Tri.Point2D

### GetActualHoles(bool, ref List<Contour>)

```csharp
public void GetActualHoles(bool parentIsHole, ref List<Contour> holes)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `parentIsHole` | `System.Boolean` |  |
| `holes` | `System.Collections.Generic.List{Poly2Tri.Contour}` |  |

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

### GetHoleEnumerator()

```csharp
public List<Contour>.Enumerator GetHoleEnumerator()
```

#### Returns

**Type:** System.Collections.Generic.List{Poly2Tri.Contour}.Enumerator

### GetNumHoles()

```csharp
public int GetNumHoles()
```

#### Returns

**Type:** System.Int32

### GetNumHoles(bool)

```csharp
public int GetNumHoles(bool parentIsHole)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `parentIsHole` | `System.Boolean` |  |

#### Returns

**Type:** System.Int32

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

### InitializeHoles(ConstrainedPointSet)

```csharp
public void InitializeHoles(ConstrainedPointSet cps)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cps` | `Poly2Tri.ConstrainedPointSet` |  |

### InitializeHoles(List<Contour>, ITriangulatable, ConstrainedPointSet)

```csharp
public static void InitializeHoles(List<Contour> holes, ITriangulatable parent, ConstrainedPointSet cps)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `holes` | `System.Collections.Generic.List{Poly2Tri.Contour}` |  |
| `parent` | `Poly2Tri.ITriangulatable` |  |
| `cps` | `Poly2Tri.ConstrainedPointSet` |  |

### Insert(int, TriangulationPoint)

```csharp
public void Insert(int idx, TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `idx` | `System.Int32` |  |
| `p` | `Poly2Tri.TriangulationPoint` |  |

### IsPointInsideContour(Point2D)

```csharp
public bool IsPointInsideContour(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

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

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
