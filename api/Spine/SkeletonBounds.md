---
uid: Spine.SkeletonBounds
canonical_path: /api/Spine/SkeletonBounds
---

# Class SkeletonBounds

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkeletonBounds
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkeletonBounds

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SkeletonBounds()

```csharp
public SkeletonBounds()
```

## Fields

### maxX

```csharp
private float maxX
```

#### Field Value

**Type:** System.Single

### maxY

```csharp
private float maxY
```

#### Field Value

**Type:** System.Single

### minX

```csharp
private float minX
```

#### Field Value

**Type:** System.Single

### minY

```csharp
private float minY
```

#### Field Value

**Type:** System.Single

### polygonPool

```csharp
private ExposedList<Polygon> polygonPool
```

#### Field Value

**Type:** Spine.ExposedList{Spine.Polygon}

## Properties

### BoundingBoxes

```csharp
public ExposedList<BoundingBoxAttachment> BoundingBoxes { get; private set; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.BoundingBoxAttachment}

### Height

```csharp
public float Height { get; }
```

#### Property Value

**Type:** System.Single

### MaxX

```csharp
public float MaxX { get; set; }
```

#### Property Value

**Type:** System.Single

### MaxY

```csharp
public float MaxY { get; set; }
```

#### Property Value

**Type:** System.Single

### MinX

```csharp
public float MinX { get; set; }
```

#### Property Value

**Type:** System.Single

### MinY

```csharp
public float MinY { get; set; }
```

#### Property Value

**Type:** System.Single

### Polygons

```csharp
public ExposedList<Polygon> Polygons { get; private set; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.Polygon}

### Width

```csharp
public float Width { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### AabbCompute()

```csharp
private void AabbCompute()
```

### AabbContainsPoint(float, float)

```csharp
public bool AabbContainsPoint(float x, float y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Single` |  |
| `y` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### AabbIntersectsSegment(float, float, float, float)

```csharp
public bool AabbIntersectsSegment(float x1, float y1, float x2, float y2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x1` | `System.Single` |  |
| `y1` | `System.Single` |  |
| `x2` | `System.Single` |  |
| `y2` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### AabbIntersectsSkeleton(SkeletonBounds)

```csharp
public bool AabbIntersectsSkeleton(SkeletonBounds bounds)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bounds` | `Spine.SkeletonBounds` |  |

#### Returns

**Type:** System.Boolean

### ContainsPoint(float, float)

```csharp
public BoundingBoxAttachment ContainsPoint(float x, float y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Single` |  |
| `y` | `System.Single` |  |

#### Returns

**Type:** Spine.BoundingBoxAttachment

### ContainsPoint(Polygon, float, float)

```csharp
public bool ContainsPoint(Polygon polygon, float x, float y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `polygon` | `Spine.Polygon` |  |
| `x` | `System.Single` |  |
| `y` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### GetPolygon(BoundingBoxAttachment)

```csharp
public Polygon GetPolygon(BoundingBoxAttachment attachment)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attachment` | `Spine.BoundingBoxAttachment` |  |

#### Returns

**Type:** Spine.Polygon

### IntersectsSegment(float, float, float, float)

```csharp
public BoundingBoxAttachment IntersectsSegment(float x1, float y1, float x2, float y2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x1` | `System.Single` |  |
| `y1` | `System.Single` |  |
| `x2` | `System.Single` |  |
| `y2` | `System.Single` |  |

#### Returns

**Type:** Spine.BoundingBoxAttachment

### IntersectsSegment(Polygon, float, float, float, float)

```csharp
public bool IntersectsSegment(Polygon polygon, float x1, float y1, float x2, float y2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `polygon` | `Spine.Polygon` |  |
| `x1` | `System.Single` |  |
| `y1` | `System.Single` |  |
| `x2` | `System.Single` |  |
| `y2` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### Update(Skeleton, bool)

```csharp
public void Update(Skeleton skeleton, bool updateAabb)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `updateAabb` | `System.Boolean` |  |
