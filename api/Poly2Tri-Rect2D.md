# Class Rect2D

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Rect2D
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Rect2D

## Inherited Members
[Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Rect2D()

```csharp
public Rect2D()
```

## Properties

### Bottom

```csharp
public double Bottom { get; set; }
```

#### Property Value

**Type:** System.Double

### Empty

```csharp
public bool Empty { get; }
```

#### Property Value

**Type:** System.Boolean

### Height

```csharp
public double Height { get; }
```

#### Property Value

**Type:** System.Double

### Left

```csharp
public double Left { get; set; }
```

#### Property Value

**Type:** System.Double

### MaxX

```csharp
public double MaxX { get; set; }
```

#### Property Value

**Type:** System.Double

### MaxY

```csharp
public double MaxY { get; set; }
```

#### Property Value

**Type:** System.Double

### MinX

```csharp
public double MinX { get; set; }
```

#### Property Value

**Type:** System.Double

### MinY

```csharp
public double MinY { get; set; }
```

#### Property Value

**Type:** System.Double

### Right

```csharp
public double Right { get; set; }
```

#### Property Value

**Type:** System.Double

### Top

```csharp
public double Top { get; set; }
```

#### Property Value

**Type:** System.Double

### Width

```csharp
public double Width { get; }
```

#### Property Value

**Type:** System.Double

## Methods

### AddPoint(Point2D)

```csharp
public void AddPoint(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

### Clear()

```csharp
public void Clear()
```

### Contains(double, double)

```csharp
public bool Contains(double x, double y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

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

### Contains(Rect2D)

```csharp
public bool Contains(Rect2D r)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `r` | `Poly2Tri.Rect2D` |  |

#### Returns

**Type:** System.Boolean

### ContainsInclusive(double, double)

```csharp
public bool ContainsInclusive(double x, double y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

### ContainsInclusive(double, double, double)

```csharp
public bool ContainsInclusive(double x, double y, double epsilon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |
| `epsilon` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

### ContainsInclusive(Point2D)

```csharp
public bool ContainsInclusive(Point2D p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** System.Boolean

### ContainsInclusive(Point2D, double)

```csharp
public bool ContainsInclusive(Point2D p, double epsilon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Point2D` |  |
| `epsilon` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

### ContainsInclusive(Rect2D)

```csharp
public bool ContainsInclusive(Rect2D r)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `r` | `Poly2Tri.Rect2D` |  |

#### Returns

**Type:** System.Boolean

### ContainsInclusive(Rect2D, double)

```csharp
public bool ContainsInclusive(Rect2D r, double epsilon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `r` | `Poly2Tri.Rect2D` |  |
| `epsilon` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

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

### Equals(Rect2D)

```csharp
public bool Equals(Rect2D r)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `r` | `Poly2Tri.Rect2D` |  |

#### Returns

**Type:** System.Boolean

### Equals(Rect2D, double)

```csharp
public bool Equals(Rect2D r, double epsilon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `r` | `Poly2Tri.Rect2D` |  |
| `epsilon` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

### GetCenter()

```csharp
public Point2D GetCenter()
```

#### Returns

**Type:** Poly2Tri.Point2D

### GetHashCode()

```csharp
public override int GetHashCode()
```

#### Returns

**Type:** System.Int32

### Inflate(double, double)

```csharp
public void Inflate(double w, double h)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `w` | `System.Double` |  |
| `h` | `System.Double` |  |

### Inflate(double, double, double, double)

```csharp
public void Inflate(double left, double top, double right, double bottom)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `left` | `System.Double` |  |
| `top` | `System.Double` |  |
| `right` | `System.Double` |  |
| `bottom` | `System.Double` |  |

### Intersection(Rect2D, Rect2D)

```csharp
public bool Intersection(Rect2D r1, Rect2D r2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `r1` | `Poly2Tri.Rect2D` |  |
| `r2` | `Poly2Tri.Rect2D` |  |

#### Returns

**Type:** System.Boolean

### Intersects(Rect2D)

```csharp
public bool Intersects(Rect2D r)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `r` | `Poly2Tri.Rect2D` |  |

#### Returns

**Type:** System.Boolean

### IsNormalized()

```csharp
public bool IsNormalized()
```

#### Returns

**Type:** System.Boolean

### Normalize()

```csharp
public void Normalize()
```

### Offset(double, double)

```csharp
public void Offset(double w, double h)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `w` | `System.Double` |  |
| `h` | `System.Double` |  |

### Set(double, double, double, double)

```csharp
public void Set(double xmin, double xmax, double ymin, double ymax)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `xmin` | `System.Double` |  |
| `xmax` | `System.Double` |  |
| `ymin` | `System.Double` |  |
| `ymax` | `System.Double` |  |

### Set(Rect2D)

```csharp
public void Set(Rect2D b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `Poly2Tri.Rect2D` |  |

### SetPosition(double, double)

```csharp
public void SetPosition(double x, double y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Double` |  |
| `y` | `System.Double` |  |

### SetSize(double, double)

```csharp
public void SetSize(double w, double h)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `w` | `System.Double` |  |
| `h` | `System.Double` |  |

### Union(Rect2D, Rect2D)

```csharp
public void Union(Rect2D r1, Rect2D r2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `r1` | `Poly2Tri.Rect2D` |  |
| `r2` | `Poly2Tri.Rect2D` |  |
