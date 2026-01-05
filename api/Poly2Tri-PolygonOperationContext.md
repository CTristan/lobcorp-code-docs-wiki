# Class PolygonOperationContext

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PolygonOperationContext
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PolygonOperationContext

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### PolygonOperationContext()

```csharp
public PolygonOperationContext()
```

## Fields

### mError

```csharp
public PolygonUtil.PolyUnionError mError
```

#### Field Value

**Type:** Poly2Tri.PolygonUtil.PolyUnionError

### mIntersections

```csharp
public List<EdgeIntersectInfo> mIntersections
```

#### Field Value

**Type:** System.Collections.Generic.List{Poly2Tri.EdgeIntersectInfo}

### mOperations

```csharp
public PolygonUtil.PolyOperation mOperations
```

#### Field Value

**Type:** Poly2Tri.PolygonUtil.PolyOperation

### mOriginalPolygon1

```csharp
public Point2DList mOriginalPolygon1
```

#### Field Value

**Type:** Poly2Tri.Point2DList

### mOriginalPolygon2

```csharp
public Point2DList mOriginalPolygon2
```

#### Field Value

**Type:** Poly2Tri.Point2DList

### mOutput

```csharp
public Dictionary<uint, Point2DList> mOutput
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.UInt32,Poly2Tri.Point2DList}

### mPoly1

```csharp
public Point2DList mPoly1
```

#### Field Value

**Type:** Poly2Tri.Point2DList

### mPoly1VectorAngles

```csharp
public List<int> mPoly1VectorAngles
```

#### Field Value

**Type:** System.Collections.Generic.List{System.Int32}

### mPoly2

```csharp
public Point2DList mPoly2
```

#### Field Value

**Type:** Poly2Tri.Point2DList

### mPoly2VectorAngles

```csharp
public List<int> mPoly2VectorAngles
```

#### Field Value

**Type:** System.Collections.Generic.List{System.Int32}

### mStartingIndex

```csharp
public int mStartingIndex
```

#### Field Value

**Type:** System.Int32

## Properties

### Intersect

```csharp
public Point2DList Intersect { get; }
```

#### Property Value

**Type:** Poly2Tri.Point2DList

### Subtract

```csharp
public Point2DList Subtract { get; }
```

#### Property Value

**Type:** Poly2Tri.Point2DList

### Union

```csharp
public Point2DList Union { get; }
```

#### Property Value

**Type:** Poly2Tri.Point2DList

## Methods

### Clear()

```csharp
public void Clear()
```

### Init(PolyOperation, Point2DList, Point2DList)

```csharp
public bool Init(PolygonUtil.PolyOperation operations, Point2DList polygon1, Point2DList polygon2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `operations` | `Poly2Tri.PolygonUtil.PolyOperation` |  |
| `polygon1` | `Poly2Tri.Point2DList` |  |
| `polygon2` | `Poly2Tri.Point2DList` |  |

#### Returns

**Type:** System.Boolean

### PointInPolygonAngle(Point2D, Point2DList)

```csharp
public bool PointInPolygonAngle(Point2D point, Point2DList polygon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `point` | `Poly2Tri.Point2D` |  |
| `polygon` | `Poly2Tri.Point2DList` |  |

#### Returns

**Type:** System.Boolean

### VectorAngle(Point2D, Point2D)

```csharp
public double VectorAngle(Point2D p1, Point2D p2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p1` | `Poly2Tri.Point2D` |  |
| `p2` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Double
