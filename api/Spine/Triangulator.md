---
uid: Spine.Triangulator
canonical_path: /api/Spine/Triangulator
---

# Class Triangulator

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
internal class Triangulator
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Triangulator

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Triangulator()

```csharp
public Triangulator()
```

## Fields

### convexPolygons

```csharp
private readonly ExposedList<ExposedList<float>> convexPolygons
```

#### Field Value

**Type:** Spine.ExposedList{Spine.ExposedList{System.Single}}

### convexPolygonsIndices

```csharp
private readonly ExposedList<ExposedList<int>> convexPolygonsIndices
```

#### Field Value

**Type:** Spine.ExposedList{Spine.ExposedList{System.Int32}}

### indicesArray

```csharp
private readonly ExposedList<int> indicesArray
```

#### Field Value

**Type:** Spine.ExposedList{System.Int32}

### isConcaveArray

```csharp
private readonly ExposedList<bool> isConcaveArray
```

#### Field Value

**Type:** Spine.ExposedList{System.Boolean}

### polygonIndicesPool

```csharp
private readonly Pool<ExposedList<int>> polygonIndicesPool
```

#### Field Value

**Type:** Spine.Pool{Spine.ExposedList{System.Int32}}

### polygonPool

```csharp
private readonly Pool<ExposedList<float>> polygonPool
```

#### Field Value

**Type:** Spine.Pool{Spine.ExposedList{System.Single}}

### triangles

```csharp
private readonly ExposedList<int> triangles
```

#### Field Value

**Type:** Spine.ExposedList{System.Int32}

## Methods

### Decompose(ExposedList<float>, ExposedList<int>)

```csharp
public ExposedList<ExposedList<float>> Decompose(ExposedList<float> verticesArray, ExposedList<int> triangles)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `verticesArray` | `Spine.ExposedList{System.Single}` |  |
| `triangles` | `Spine.ExposedList{System.Int32}` |  |

#### Returns

**Type:** Spine.ExposedList{Spine.ExposedList{System.Single}}

### IsConcave(int, int, float[], int[])

```csharp
private static bool IsConcave(int index, int vertexCount, float[] vertices, int[] indices)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `vertexCount` | `System.Int32` |  |
| `vertices` | `System.Single[]` |  |
| `indices` | `System.Int32[]` |  |

#### Returns

**Type:** System.Boolean

### PositiveArea(float, float, float, float, float, float)

```csharp
private static bool PositiveArea(float p1x, float p1y, float p2x, float p2y, float p3x, float p3y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p1x` | `System.Single` |  |
| `p1y` | `System.Single` |  |
| `p2x` | `System.Single` |  |
| `p2y` | `System.Single` |  |
| `p3x` | `System.Single` |  |
| `p3y` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### Triangulate(ExposedList<float>)

```csharp
public ExposedList<int> Triangulate(ExposedList<float> verticesArray)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `verticesArray` | `Spine.ExposedList{System.Single}` |  |

#### Returns

**Type:** Spine.ExposedList{System.Int32}

### Winding(float, float, float, float, float, float)

```csharp
private static int Winding(float p1x, float p1y, float p2x, float p2y, float p3x, float p3y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p1x` | `System.Single` |  |
| `p1y` | `System.Single` |  |
| `p2x` | `System.Single` |  |
| `p2y` | `System.Single` |  |
| `p3x` | `System.Single` |  |
| `p3y` | `System.Single` |  |

#### Returns

**Type:** System.Int32
