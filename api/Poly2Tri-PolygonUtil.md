# Class PolygonUtil

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PolygonUtil
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PolygonUtil

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### PolygonUtil()

```csharp
public PolygonUtil()
```

## Methods

### CalculateWindingOrder(IList<Point2D>)

```csharp
public static Point2DList.WindingOrderType CalculateWindingOrder(IList<Point2D> l)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `l` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |

#### Returns

**Type:** Poly2Tri.Point2DList.WindingOrderType

### ClipPolygonToEdge2D(Point2D, Point2D, IList<Point2D>, out List<Point2D>)

```csharp
public static void ClipPolygonToEdge2D(Point2D edgeBegin, Point2D edgeEnd, IList<Point2D> poly, out List<Point2D> outPoly)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `edgeBegin` | `Poly2Tri.Point2D` |  |
| `edgeEnd` | `Poly2Tri.Point2D` |  |
| `poly` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |
| `outPoly` | `System.Collections.Generic.List{Poly2Tri.Point2D}` |  |

### ClipPolygonToPolygon(IList<Point2D>, IList<Point2D>, out List<Point2D>)

```csharp
public static void ClipPolygonToPolygon(IList<Point2D> poly, IList<Point2D> clipPoly, out List<Point2D> outPoly)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `poly` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |
| `clipPoly` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |
| `outPoly` | `System.Collections.Generic.List{Poly2Tri.Point2D}` |  |

### PointInPolygon2D(IList<Point2D>, Point2D)

```csharp
public static bool PointInPolygon2D(IList<Point2D> polygon, Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `polygon` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |
| `p` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean

### PolygonContainsPolygon(IList<Point2D>, Rect2D, IList<Point2D>, Rect2D)

```csharp
public bool PolygonContainsPolygon(IList<Point2D> poly1, Rect2D boundRect1, IList<Point2D> poly2, Rect2D boundRect2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `poly1` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |
| `boundRect1` | `Poly2Tri.Rect2D` |  |
| `poly2` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |
| `boundRect2` | `Poly2Tri.Rect2D` |  |

#### Returns

**Type:** System.Boolean

### PolygonContainsPolygon(IList<Point2D>, Rect2D, IList<Point2D>, Rect2D, bool)

```csharp
public static bool PolygonContainsPolygon(IList<Point2D> poly1, Rect2D boundRect1, IList<Point2D> poly2, Rect2D boundRect2, bool runIntersectionTest)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `poly1` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |
| `boundRect1` | `Poly2Tri.Rect2D` |  |
| `poly2` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |
| `boundRect2` | `Poly2Tri.Rect2D` |  |
| `runIntersectionTest` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean

### PolygonIntersect(Point2DList, Point2DList, out Point2DList)

```csharp
public static PolygonUtil.PolyUnionError PolygonIntersect(Point2DList polygon1, Point2DList polygon2, out Point2DList intersectOut)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `polygon1` | `Poly2Tri.Point2DList` |  |
| `polygon2` | `Poly2Tri.Point2DList` |  |
| `intersectOut` | `Poly2Tri.Point2DList` |  |

#### Returns

**Type:** Poly2Tri.PolygonUtil.PolyUnionError

### PolygonIntersectInternal(PolygonOperationContext)

```csharp
protected static void PolygonIntersectInternal(PolygonOperationContext ctx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ctx` | `Poly2Tri.PolygonOperationContext` |  |

### PolygonOperation(PolygonOperationContext)

```csharp
public static PolygonUtil.PolyUnionError PolygonOperation(PolygonOperationContext ctx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ctx` | `Poly2Tri.PolygonOperationContext` |  |

#### Returns

**Type:** Poly2Tri.PolygonUtil.PolyUnionError

### PolygonOperation(PolyOperation, Point2DList, Point2DList, out Dictionary<uint, Point2DList>)

```csharp
public static PolygonUtil.PolyUnionError PolygonOperation(PolygonUtil.PolyOperation operations, Point2DList polygon1, Point2DList polygon2, out Dictionary<uint, Point2DList> results)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `operations` | `Poly2Tri.PolygonUtil.PolyOperation` |  |
| `polygon1` | `Poly2Tri.Point2DList` |  |
| `polygon2` | `Poly2Tri.Point2DList` |  |
| `results` | `System.Collections.Generic.Dictionary{System.UInt32,Poly2Tri.Point2DList}` |  |

#### Returns

**Type:** Poly2Tri.PolygonUtil.PolyUnionError

### PolygonsAreSame2D(IList<Point2D>, IList<Point2D>)

```csharp
public static bool PolygonsAreSame2D(IList<Point2D> poly1, IList<Point2D> poly2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `poly1` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |
| `poly2` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |

#### Returns

**Type:** System.Boolean

### PolygonsIntersect2D(IList<Point2D>, Rect2D, IList<Point2D>, Rect2D)

```csharp
public static bool PolygonsIntersect2D(IList<Point2D> poly1, Rect2D boundRect1, IList<Point2D> poly2, Rect2D boundRect2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `poly1` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |
| `boundRect1` | `Poly2Tri.Rect2D` |  |
| `poly2` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |
| `boundRect2` | `Poly2Tri.Rect2D` |  |

#### Returns

**Type:** System.Boolean

### PolygonSubtract(Point2DList, Point2DList, out Point2DList)

```csharp
public static PolygonUtil.PolyUnionError PolygonSubtract(Point2DList polygon1, Point2DList polygon2, out Point2DList subtract)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `polygon1` | `Poly2Tri.Point2DList` |  |
| `polygon2` | `Poly2Tri.Point2DList` |  |
| `subtract` | `Poly2Tri.Point2DList` |  |

#### Returns

**Type:** Poly2Tri.PolygonUtil.PolyUnionError

### PolygonSubtractInternal(PolygonOperationContext)

```csharp
public static void PolygonSubtractInternal(PolygonOperationContext ctx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ctx` | `Poly2Tri.PolygonOperationContext` |  |

### PolygonUnion(Point2DList, Point2DList, out Point2DList)

```csharp
public static PolygonUtil.PolyUnionError PolygonUnion(Point2DList polygon1, Point2DList polygon2, out Point2DList union)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `polygon1` | `Poly2Tri.Point2DList` |  |
| `polygon2` | `Poly2Tri.Point2DList` |  |
| `union` | `Poly2Tri.Point2DList` |  |

#### Returns

**Type:** Poly2Tri.PolygonUtil.PolyUnionError

### PolygonUnionInternal(PolygonOperationContext)

```csharp
protected static void PolygonUnionInternal(PolygonOperationContext ctx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ctx` | `Poly2Tri.PolygonOperationContext` |  |

### SplitComplexPolygon(Point2DList, double)

```csharp
public static List<Point2DList> SplitComplexPolygon(Point2DList verts, double epsilon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `verts` | `Poly2Tri.Point2DList` |  |
| `epsilon` | `System.Double` |  |

#### Returns

**Type:** System.Collections.Generic.List{Poly2Tri.Point2DList}
