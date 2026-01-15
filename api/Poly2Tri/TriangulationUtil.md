---
uid: Poly2Tri.TriangulationUtil
canonical_path: /api/Poly2Tri/TriangulationUtil
---

# Class TriangulationUtil

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TriangulationUtil
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TriangulationUtil

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TriangulationUtil()

```csharp
public TriangulationUtil()
```

## Methods

### InScanArea(Point2D, Point2D, Point2D, Point2D)

```csharp
public static bool InScanArea(Point2D pa, Point2D pb, Point2D pc, Point2D pd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pa` | `Poly2Tri.Point2D` |  |
| `pb` | `Poly2Tri.Point2D` |  |
| `pc` | `Poly2Tri.Point2D` |  |
| `pd` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean

### LI2DDotProduct(Point2D, Point2D)

```csharp
public static double LI2DDotProduct(Point2D v0, Point2D v1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `v0` | `Poly2Tri.Point2D` |  |
| `v1` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Double

### LinesIntersect2D(Point2D, Point2D, Point2D, Point2D, bool, bool, bool, ref Point2D, double)

```csharp
public static bool LinesIntersect2D(Point2D ptStart0, Point2D ptEnd0, Point2D ptStart1, Point2D ptEnd1, bool firstIsSegment, bool secondIsSegment, bool coincidentEndPointCollisions, ref Point2D pIntersectionPt, double epsilon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ptStart0` | `Poly2Tri.Point2D` |  |
| `ptEnd0` | `Poly2Tri.Point2D` |  |
| `ptStart1` | `Poly2Tri.Point2D` |  |
| `ptEnd1` | `Poly2Tri.Point2D` |  |
| `firstIsSegment` | `System.Boolean` |  |
| `secondIsSegment` | `System.Boolean` |  |
| `coincidentEndPointCollisions` | `System.Boolean` |  |
| `pIntersectionPt` | `Poly2Tri.Point2D` |  |
| `epsilon` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

### LinesIntersect2D(Point2D, Point2D, Point2D, Point2D, ref Point2D, double)

```csharp
public static bool LinesIntersect2D(Point2D ptStart0, Point2D ptEnd0, Point2D ptStart1, Point2D ptEnd1, ref Point2D pIntersectionPt, double epsilon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ptStart0` | `Poly2Tri.Point2D` |  |
| `ptEnd0` | `Poly2Tri.Point2D` |  |
| `ptStart1` | `Poly2Tri.Point2D` |  |
| `ptEnd1` | `Poly2Tri.Point2D` |  |
| `pIntersectionPt` | `Poly2Tri.Point2D` |  |
| `epsilon` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

### Orient2d(Point2D, Point2D, Point2D)

```csharp
public static Orientation Orient2d(Point2D pa, Point2D pb, Point2D pc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pa` | `Poly2Tri.Point2D` |  |
| `pb` | `Poly2Tri.Point2D` |  |
| `pc` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** Poly2Tri.Orientation

### PointInBoundingBox(double, double, double, double, Point2D)

```csharp
public static bool PointInBoundingBox(double xmin, double xmax, double ymin, double ymax, Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `xmin` | `System.Double` |  |
| `xmax` | `System.Double` |  |
| `ymin` | `System.Double` |  |
| `ymax` | `System.Double` |  |
| `p` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean

### PointOnLineSegment2D(double, double, double, double, double, double, double)

```csharp
public static bool PointOnLineSegment2D(double x1, double y1, double x2, double y2, double x, double y, double epsilon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x1` | `System.Double` |  |
| `y1` | `System.Double` |  |
| `x2` | `System.Double` |  |
| `y2` | `System.Double` |  |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |
| `epsilon` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

### PointOnLineSegment2D(Point2D, Point2D, Point2D, double)

```csharp
public static bool PointOnLineSegment2D(Point2D lineStart, Point2D lineEnd, Point2D p, double epsilon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lineStart` | `Poly2Tri.Point2D` |  |
| `lineEnd` | `Poly2Tri.Point2D` |  |
| `p` | `Poly2Tri.Point2D` |  |
| `epsilon` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

### RaysIntersect2D(Point2D, Point2D, Point2D, Point2D, ref Point2D)

```csharp
public static bool RaysIntersect2D(Point2D ptRayOrigin0, Point2D ptRayVector0, Point2D ptRayOrigin1, Point2D ptRayVector1, ref Point2D ptIntersection)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ptRayOrigin0` | `Poly2Tri.Point2D` |  |
| `ptRayVector0` | `Poly2Tri.Point2D` |  |
| `ptRayOrigin1` | `Poly2Tri.Point2D` |  |
| `ptRayVector1` | `Poly2Tri.Point2D` |  |
| `ptIntersection` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean

### RectsIntersect(Rect2D, Rect2D)

```csharp
public static bool RectsIntersect(Rect2D r1, Rect2D r2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `r1` | `Poly2Tri.Rect2D` |  |
| `r2` | `Poly2Tri.Rect2D` |  |

#### Returns

**Type:** System.Boolean

### SmartIncircle(Point2D, Point2D, Point2D, Point2D)

```csharp
public static bool SmartIncircle(Point2D pa, Point2D pb, Point2D pc, Point2D pd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pa` | `Poly2Tri.Point2D` |  |
| `pb` | `Poly2Tri.Point2D` |  |
| `pc` | `Poly2Tri.Point2D` |  |
| `pd` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean
