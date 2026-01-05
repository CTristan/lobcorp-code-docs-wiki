# Class TriangulationPoint

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TriangulationPoint : Point2D, IComparable<Point2D>
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Point2D](/api/Poly2Tri-Point2D) → TriangulationPoint

## Inherited Members
[mX](/api/Poly2Tri-Point2D#mx), [mY](/api/Poly2Tri-Point2D#my), [Equals(Point2D)](/api/Poly2Tri-Point2D#equals-point2d), [Equals(Point2D, double)](/api/Poly2Tri-Point2D#equals-point2d-double), [CompareTo(Point2D)](/api/Poly2Tri-Point2D#compareto-point2d), [Set(Point2D)](/api/Poly2Tri-Point2D#set-point2d), [Add(Point2D)](/api/Poly2Tri-Point2D#add-point2d), [Add(double)](/api/Poly2Tri-Point2D#add-double), [Subtract(Point2D)](/api/Poly2Tri-Point2D#subtract-point2d), [Subtract(double)](/api/Poly2Tri-Point2D#subtract-double), [Multiply(Point2D)](/api/Poly2Tri-Point2D#multiply-point2d), [Multiply(double)](/api/Poly2Tri-Point2D#multiply-double), [Divide(Point2D)](/api/Poly2Tri-Point2D#divide-point2d), [Divide(double)](/api/Poly2Tri-Point2D#divide-double), [Negate()](/api/Poly2Tri-Point2D#negate), [Magnitude()](/api/Poly2Tri-Point2D#magnitude), [MagnitudeSquared()](/api/Poly2Tri-Point2D#magnitudesquared), [MagnitudeReciprocal()](/api/Poly2Tri-Point2D#magnitudereciprocal), [Normalize()](/api/Poly2Tri-Point2D#normalize), [Dot(Point2D)](/api/Poly2Tri-Point2D#dot-point2d), [Cross(Point2D)](/api/Poly2Tri-Point2D#cross-point2d), [Clamp(Point2D, Point2D)](/api/Poly2Tri-Point2D#clamp-point2d-point2d), [Abs()](/api/Poly2Tri-Point2D#abs), [Reciprocal()](/api/Poly2Tri-Point2D#reciprocal), [Translate(Point2D)](/api/Poly2Tri-Point2D#translate-point2d), [Translate(double, double)](/api/Poly2Tri-Point2D#translate-double-double), [Scale(Point2D)](/api/Poly2Tri-Point2D#scale-point2d), [Scale(double)](/api/Poly2Tri-Point2D#scale-double), [Scale(double, double)](/api/Poly2Tri-Point2D#scale-double-double), [Rotate(double)](/api/Poly2Tri-Point2D#rotate-double), [RotateDegrees(double)](/api/Poly2Tri-Point2D#rotatedegrees-double), [Dot(Point2D, Point2D)](/api/Poly2Tri-Point2D#dot-point2d-point2d), [Cross(Point2D, Point2D)](/api/Poly2Tri-Point2D#cross-point2d-point2d), [Clamp(Point2D, Point2D, Point2D)](/api/Poly2Tri-Point2D#clamp-point2d-point2d-point2d), [Min(Point2D, Point2D)](/api/Poly2Tri-Point2D#min-point2d-point2d), [Max(Point2D, Point2D)](/api/Poly2Tri-Point2D#max-point2d-point2d), [Abs(Point2D)](/api/Poly2Tri-Point2D#abs-point2d), [Reciprocal(Point2D)](/api/Poly2Tri-Point2D#reciprocal-point2d), [Perpendicular(Point2D, double)](/api/Poly2Tri-Point2D#perpendicular-point2d-double), [Perpendicular(double, Point2D)](/api/Poly2Tri-Point2D#perpendicular-double-point2d), [Xf](/api/Poly2Tri-Point2D#xf), [Yf](/api/Poly2Tri-Point2D#yf), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### TriangulationPoint(double, double)

```csharp
public TriangulationPoint(double x, double y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |

### TriangulationPoint(double, double, double)

```csharp
public TriangulationPoint(double x, double y, double precision)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |
| `precision` | `System.Double` |  |

## Fields

### kVertexCodeDefaultPrecision

```csharp
public static readonly double kVertexCodeDefaultPrecision
```

#### Field Value

**Type:** System.Double

### mVertexCode

```csharp
protected uint mVertexCode
```

#### Field Value

**Type:** System.UInt32

## Properties

### Edges

```csharp
public List<DTSweepConstraint> Edges { get; }
```

#### Property Value

**Type:** System.Collections.Generic.List{Poly2Tri.DTSweepConstraint}

### HasEdges

```csharp
public bool HasEdges { get; }
```

#### Property Value

**Type:** System.Boolean

### VertexCode

```csharp
public uint VertexCode { get; }
```

#### Property Value

**Type:** System.UInt32

### X

```csharp
public override double X { get; set; }
```

#### Property Value

**Type:** System.Double

### Y

```csharp
public override double Y { get; set; }
```

#### Property Value

**Type:** System.Double

## Methods

### AddEdge(DTSweepConstraint)

```csharp
public void AddEdge(DTSweepConstraint e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Poly2Tri.DTSweepConstraint` |  |

### CreateVertexCode(double, double, double)

```csharp
public static uint CreateVertexCode(double x, double y, double precision)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |
| `precision` | `System.Double` |  |

#### Returns

**Type:** System.UInt32

### Equals(object)

```csharp
public override bool Equals(object obj)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `obj` | `System.Object` |  |

#### Returns

**Type:** System.Boolean

### GetEdge(TriangulationPoint, out DTSweepConstraint)

```csharp
public bool GetEdge(TriangulationPoint p, out DTSweepConstraint edge)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |
| `edge` | `Poly2Tri.DTSweepConstraint` |  |

#### Returns

**Type:** System.Boolean

### GetHashCode()

```csharp
public override int GetHashCode()
```

#### Returns

**Type:** System.Int32

### HasEdge(TriangulationPoint)

```csharp
public bool HasEdge(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** System.Boolean

### Set(double, double)

```csharp
public override void Set(double x, double y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |

### ToPoint2D(TriangulationPoint)

```csharp
public static Point2D ToPoint2D(TriangulationPoint p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
