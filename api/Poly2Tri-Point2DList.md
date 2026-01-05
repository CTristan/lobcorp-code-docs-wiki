# Class Point2DList

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Point2DList : IList<Point2D>, ICollection<Point2D>, IEnumerable<Point2D>, IEnumerable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Point2DList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Point2DList()

```csharp
public Point2DList()
```

### Point2DList(IList<Point2D>)

```csharp
public Point2DList(IList<Point2D> l)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `l` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |

### Point2DList(int)

```csharp
public Point2DList(int capacity)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `capacity` | `System.Int32` |  |

### Point2DList(Point2DList)

```csharp
public Point2DList(Point2DList l)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `l` | `Poly2Tri.Point2DList` |  |

## Fields

### kAngularSlop

```csharp
public static readonly double kAngularSlop
```

#### Field Value

**Type:** System.Double

### kLinearSlop

```csharp
public static readonly double kLinearSlop
```

#### Field Value

**Type:** System.Double

### kMaxPolygonVertices

```csharp
public static readonly int kMaxPolygonVertices
```

#### Field Value

**Type:** System.Int32

### mBoundingBox

```csharp
protected Rect2D mBoundingBox
```

#### Field Value

**Type:** Poly2Tri.Rect2D

### mEpsilon

```csharp
protected double mEpsilon
```

#### Field Value

**Type:** System.Double

### mPoints

```csharp
protected List<Point2D> mPoints
```

#### Field Value

**Type:** System.Collections.Generic.List{Poly2Tri.Point2D}

### mWindingOrder

```csharp
protected Point2DList.WindingOrderType mWindingOrder
```

#### Field Value

**Type:** Poly2Tri.Point2DList.WindingOrderType

## Properties

### BoundingBox

```csharp
public Rect2D BoundingBox { get; }
```

#### Property Value

**Type:** Poly2Tri.Rect2D

### Count

```csharp
public int Count { get; }
```

#### Property Value

**Type:** System.Int32

### Epsilon

```csharp
public double Epsilon { get; }
```

#### Property Value

**Type:** System.Double

### IsReadOnly

```csharp
public virtual bool IsReadOnly { get; }
```

#### Property Value

**Type:** System.Boolean

### this[int]

```csharp
public Point2D this[int index] { get; set; }
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Property Value

**Type:** Poly2Tri.Point2D

### WindingOrder

```csharp
public Point2DList.WindingOrderType WindingOrder { get; set; }
```

#### Property Value

**Type:** Poly2Tri.Point2DList.WindingOrderType

## Methods

### Add(Point2D)

```csharp
public virtual void Add(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

### Add(Point2D, int, bool)

```csharp
protected virtual void Add(Point2D p, int idx, bool bCalcWindingOrderAndEpsilon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |
| `idx` | `System.Int32` |  |
| `bCalcWindingOrderAndEpsilon` | `System.Boolean` |  |

### AddRange(IEnumerator<Point2D>, WindingOrderType)

```csharp
public virtual void AddRange(IEnumerator<Point2D> iter, Point2DList.WindingOrderType windingOrder)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `iter` | `System.Collections.Generic.IEnumerator{Poly2Tri.Point2D}` |  |
| `windingOrder` | `Poly2Tri.Point2DList.WindingOrderType` |  |

### AddRange(Point2DList)

```csharp
public virtual void AddRange(Point2DList l)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `l` | `Poly2Tri.Point2DList` |  |

### CalculateBounds()

```csharp
public void CalculateBounds()
```

### CalculateEpsilon()

```csharp
public double CalculateEpsilon()
```

#### Returns

**Type:** System.Double

### CalculateWindingOrder()

```csharp
public Point2DList.WindingOrderType CalculateWindingOrder()
```

#### Returns

**Type:** Poly2Tri.Point2DList.WindingOrderType

### CheckPolygon()

```csharp
public Point2DList.PolygonError CheckPolygon()
```

#### Returns

**Type:** Poly2Tri.Point2DList.PolygonError

### Clear()

```csharp
public void Clear()
```

### Contains(Point2D)

```csharp
public bool Contains(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean

### CopyTo(Point2D[], int)

```csharp
public void CopyTo(Point2D[] array, int arrayIndex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `array` | `Poly2Tri.Point2D[]` |  |
| `arrayIndex` | `System.Int32` |  |

### GetArea()

```csharp
public double GetArea()
```

#### Returns

**Type:** System.Double

### GetCentroid()

```csharp
public Point2D GetCentroid()
```

#### Returns

**Type:** Poly2Tri.Point2D

### GetErrorString(PolygonError)

```csharp
public static string GetErrorString(Point2DList.PolygonError error)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `error` | `Poly2Tri.Point2DList.PolygonError` |  |

#### Returns

**Type:** System.String

### GetSignedArea()

```csharp
public double GetSignedArea()
```

#### Returns

**Type:** System.Double

### IndexOf(Point2D)

```csharp
public int IndexOf(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Int32

### Insert(int, Point2D)

```csharp
public virtual void Insert(int idx, Point2D item)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `idx` | `System.Int32` |  |
| `item` | `Poly2Tri.Point2D` |  |

### IsConvex()

```csharp
public bool IsConvex()
```

#### Returns

**Type:** System.Boolean

### IsDegenerate()

```csharp
public bool IsDegenerate()
```

#### Returns

**Type:** System.Boolean

### IsSimple()

```csharp
public bool IsSimple()
```

#### Returns

**Type:** System.Boolean

### MergeParallelEdges(double)

```csharp
public void MergeParallelEdges(double tolerance)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tolerance` | `System.Double` |  |

### NextIndex(int)

```csharp
public int NextIndex(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### PreviousIndex(int)

```csharp
public int PreviousIndex(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### ProjectToAxis(Point2D, out double, out double)

```csharp
public void ProjectToAxis(Point2D axis, out double min, out double max)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `axis` | `Poly2Tri.Point2D` |  |
| `min` | `System.Double` |  |
| `max` | `System.Double` |  |

### Remove(Point2D)

```csharp
public virtual bool Remove(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean

### RemoveAt(int)

```csharp
public virtual void RemoveAt(int idx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `idx` | `System.Int32` |  |

### RemoveDuplicateNeighborPoints()

```csharp
public void RemoveDuplicateNeighborPoints()
```

### RemoveRange(int, int)

```csharp
public virtual void RemoveRange(int idxStart, int count)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `idxStart` | `System.Int32` |  |
| `count` | `System.Int32` |  |

### Rotate(double)

```csharp
public void Rotate(double radians)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `radians` | `System.Double` |  |

### Scale(Point2D)

```csharp
public void Scale(Point2D value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `Poly2Tri.Point2D` |  |

### Simplify()

```csharp
public void Simplify()
```

### Simplify(double)

```csharp
public void Simplify(double bias)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bias` | `System.Double` |  |

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String

### Translate(Point2D)

```csharp
public void Translate(Point2D vector)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `vector` | `Poly2Tri.Point2D` |  |
