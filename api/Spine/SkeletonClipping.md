---
uid: Spine.SkeletonClipping
canonical_path: /api/Spine/SkeletonClipping
---

# Class SkeletonClipping

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkeletonClipping
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkeletonClipping

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SkeletonClipping()

```csharp
public SkeletonClipping()
```

## Fields

### clipAttachment

```csharp
internal ClippingAttachment clipAttachment
```

#### Field Value

**Type:** Spine.ClippingAttachment

### clipOutput

```csharp
internal readonly ExposedList<float> clipOutput
```

#### Field Value

**Type:** Spine.ExposedList{System.Single}

### clippedTriangles

```csharp
internal readonly ExposedList<int> clippedTriangles
```

#### Field Value

**Type:** Spine.ExposedList{System.Int32}

### clippedUVs

```csharp
internal readonly ExposedList<float> clippedUVs
```

#### Field Value

**Type:** Spine.ExposedList{System.Single}

### clippedVertices

```csharp
internal readonly ExposedList<float> clippedVertices
```

#### Field Value

**Type:** Spine.ExposedList{System.Single}

### clippingPolygon

```csharp
internal readonly ExposedList<float> clippingPolygon
```

#### Field Value

**Type:** Spine.ExposedList{System.Single}

### clippingPolygons

```csharp
internal ExposedList<ExposedList<float>> clippingPolygons
```

#### Field Value

**Type:** Spine.ExposedList{Spine.ExposedList{System.Single}}

### scratch

```csharp
internal readonly ExposedList<float> scratch
```

#### Field Value

**Type:** Spine.ExposedList{System.Single}

### triangulator

```csharp
internal readonly Triangulator triangulator
```

#### Field Value

**Type:** Spine.Triangulator

## Properties

### ClippedTriangles

```csharp
public ExposedList<int> ClippedTriangles { get; }
```

#### Property Value

**Type:** Spine.ExposedList{System.Int32}

### ClippedUVs

```csharp
public ExposedList<float> ClippedUVs { get; }
```

#### Property Value

**Type:** Spine.ExposedList{System.Single}

### ClippedVertices

```csharp
public ExposedList<float> ClippedVertices { get; }
```

#### Property Value

**Type:** Spine.ExposedList{System.Single}

### IsClipping

```csharp
public bool IsClipping { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### Clip(float, float, float, float, float, float, ExposedList<float>, ExposedList<float>)

```csharp
internal bool Clip(float x1, float y1, float x2, float y2, float x3, float y3, ExposedList<float> clippingArea, ExposedList<float> output)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x1` | `System.Single` |  |
| `y1` | `System.Single` |  |
| `x2` | `System.Single` |  |
| `y2` | `System.Single` |  |
| `x3` | `System.Single` |  |
| `y3` | `System.Single` |  |
| `clippingArea` | `Spine.ExposedList{System.Single}` |  |
| `output` | `Spine.ExposedList{System.Single}` |  |

#### Returns

**Type:** System.Boolean

### ClipEnd()

```csharp
public void ClipEnd()
```

### ClipEnd(Slot)

```csharp
public void ClipEnd(Slot slot)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Spine.Slot` |  |

### ClipStart(Slot, ClippingAttachment)

```csharp
public int ClipStart(Slot slot, ClippingAttachment clip)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Spine.Slot` |  |
| `clip` | `Spine.ClippingAttachment` |  |

#### Returns

**Type:** System.Int32

### ClipTriangles(float[], int, int[], int, float[])

```csharp
public void ClipTriangles(float[] vertices, int verticesLength, int[] triangles, int trianglesLength, float[] uvs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `vertices` | `System.Single[]` |  |
| `verticesLength` | `System.Int32` |  |
| `triangles` | `System.Int32[]` |  |
| `trianglesLength` | `System.Int32` |  |
| `uvs` | `System.Single[]` |  |

### MakeClockwise(ExposedList<float>)

```csharp
private static void MakeClockwise(ExposedList<float> polygon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `polygon` | `Spine.ExposedList{System.Single}` |  |
