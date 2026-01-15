---
uid: Poly2Tri.Point2D
canonical_path: /api/Poly2Tri/Point2D
---

# Class Point2D

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Point2D : IComparable<Point2D>
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Point2D

## Derived
[TriangulationPoint](/api/Poly2Tri/TriangulationPoint)

## Implements
[IComparable<Point2D>](https://learn.microsoft.com/dotnet/api/system.icomparable-1)

## Inherited Members
[Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Point2D()

```csharp
public Point2D()
```

### Point2D(double, double)

```csharp
public Point2D(double x, double y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |

### Point2D(Point2D)

```csharp
public Point2D(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

## Fields

### mX

```csharp
protected double mX
```

#### Field Value

**Type:** System.Double

### mY

```csharp
protected double mY
```

#### Field Value

**Type:** System.Double

## Properties

### X

```csharp
public virtual double X { get; set; }
```

#### Property Value

**Type:** System.Double

### Xf

```csharp
public float Xf { get; }
```

#### Property Value

**Type:** System.Single

### Y

```csharp
public virtual double Y { get; set; }
```

#### Property Value

**Type:** System.Double

### Yf

```csharp
public float Yf { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### Abs()

```csharp
public void Abs()
```

### Abs(Point2D)

```csharp
public static Point2D Abs(Point2D a)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### Add(double)

```csharp
public void Add(double scalar)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `scalar` | `System.Double` |  |

### Add(Point2D)

```csharp
public void Add(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

### Clamp(Point2D, Point2D)

```csharp
public void Clamp(Point2D low, Point2D high)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `low` | `Poly2Tri.Point2D` |  |
| `high` | `Poly2Tri.Point2D` |  |

### Clamp(Point2D, Point2D, Point2D)

```csharp
public static Point2D Clamp(Point2D a, Point2D low, Point2D high)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Poly2Tri.Point2D` |  |
| `low` | `Poly2Tri.Point2D` |  |
| `high` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### CompareTo(Point2D)

```csharp
public int CompareTo(Point2D other)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `other` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Int32

### Cross(Point2D)

```csharp
public double Cross(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Double

### Cross(Point2D, Point2D)

```csharp
public static double Cross(Point2D lhs, Point2D rhs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `rhs` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Double

### Divide(double)

```csharp
public void Divide(double scalar)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `scalar` | `System.Double` |  |

### Divide(Point2D)

```csharp
public void Divide(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

### Dot(Point2D)

```csharp
public double Dot(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Double

### Dot(Point2D, Point2D)

```csharp
public static double Dot(Point2D lhs, Point2D rhs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `rhs` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Double

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

### Equals(Point2D)

```csharp
public bool Equals(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean

### Equals(Point2D, double)

```csharp
public bool Equals(Point2D p, double epsilon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |
| `epsilon` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

### GetHashCode()

```csharp
public override int GetHashCode()
```

#### Returns

**Type:** System.Int32

### Magnitude()

```csharp
public double Magnitude()
```

#### Returns

**Type:** System.Double

### MagnitudeReciprocal()

```csharp
public double MagnitudeReciprocal()
```

#### Returns

**Type:** System.Double

### MagnitudeSquared()

```csharp
public double MagnitudeSquared()
```

#### Returns

**Type:** System.Double

### Max(Point2D, Point2D)

```csharp
public static Point2D Max(Point2D a, Point2D b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Poly2Tri.Point2D` |  |
| `b` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### Min(Point2D, Point2D)

```csharp
public static Point2D Min(Point2D a, Point2D b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Poly2Tri.Point2D` |  |
| `b` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### Multiply(double)

```csharp
public void Multiply(double scalar)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `scalar` | `System.Double` |  |

### Multiply(Point2D)

```csharp
public void Multiply(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

### Negate()

```csharp
public void Negate()
```

### Normalize()

```csharp
public void Normalize()
```

### Perpendicular(double, Point2D)

```csharp
public static Point2D Perpendicular(double scalar, Point2D rhs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `scalar` | `System.Double` |  |
| `rhs` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### Perpendicular(Point2D, double)

```csharp
public static Point2D Perpendicular(Point2D lhs, double scalar)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `scalar` | `System.Double` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### Reciprocal()

```csharp
public void Reciprocal()
```

### Reciprocal(Point2D)

```csharp
public static Point2D Reciprocal(Point2D a)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### Rotate(double)

```csharp
public void Rotate(double radians)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `radians` | `System.Double` |  |

### RotateDegrees(double)

```csharp
public void RotateDegrees(double degrees)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `degrees` | `System.Double` |  |

### Scale(double)

```csharp
public void Scale(double scalar)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `scalar` | `System.Double` |  |

### Scale(double, double)

```csharp
public void Scale(double x, double y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |

### Scale(Point2D)

```csharp
public void Scale(Point2D vector)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `vector` | `Poly2Tri.Point2D` |  |

### Set(double, double)

```csharp
public virtual void Set(double x, double y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |

### Set(Point2D)

```csharp
public virtual void Set(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

### Subtract(double)

```csharp
public void Subtract(double scalar)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `scalar` | `System.Double` |  |

### Subtract(Point2D)

```csharp
public void Subtract(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String

### Translate(double, double)

```csharp
public void Translate(double x, double y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |

### Translate(Point2D)

```csharp
public void Translate(Point2D vector)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `vector` | `Poly2Tri.Point2D` |  |

## Operators

### operator *(double, Point2D)

```csharp
public static Point2D operator *(double scalar, Point2D lhs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `scalar` | `System.Double` |  |
| `lhs` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### operator *(Point2D, double)

```csharp
public static Point2D operator *(Point2D lhs, double scalar)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `scalar` | `System.Double` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### operator *(Point2D, Point2D)

```csharp
public static Point2D operator *(Point2D lhs, Point2D rhs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `rhs` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### operator +(Point2D, double)

```csharp
public static Point2D operator +(Point2D lhs, double scalar)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `scalar` | `System.Double` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### operator +(Point2D, Point2D)

```csharp
public static Point2D operator +(Point2D lhs, Point2D rhs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `rhs` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### operator -(Point2D)

```csharp
public static Point2D operator -(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### operator -(Point2D, double)

```csharp
public static Point2D operator -(Point2D lhs, double scalar)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `scalar` | `System.Double` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### operator -(Point2D, Point2D)

```csharp
public static Point2D operator -(Point2D lhs, Point2D rhs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `rhs` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### operator /(Point2D, double)

```csharp
public static Point2D operator /(Point2D lhs, double scalar)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `scalar` | `System.Double` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### operator /(Point2D, Point2D)

```csharp
public static Point2D operator /(Point2D lhs, Point2D rhs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `rhs` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** Poly2Tri.Point2D

### operator <(Point2D, Point2D)

```csharp
public static bool operator <(Point2D lhs, Point2D rhs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `rhs` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean

### operator <=(Point2D, Point2D)

```csharp
public static bool operator <=(Point2D lhs, Point2D rhs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `rhs` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean

### operator >(Point2D, Point2D)

```csharp
public static bool operator >(Point2D lhs, Point2D rhs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `rhs` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean

### operator >=(Point2D, Point2D)

```csharp
public static bool operator >=(Point2D lhs, Point2D rhs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.Point2D` |  |
| `rhs` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean
