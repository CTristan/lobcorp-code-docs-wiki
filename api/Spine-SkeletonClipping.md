# Class SkeletonClipping

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkeletonClipping
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkeletonClipping

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SkeletonClipping()

```csharp
public SkeletonClipping()
```

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
