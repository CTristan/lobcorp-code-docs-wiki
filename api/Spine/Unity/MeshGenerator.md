---
uid: Spine.Unity.MeshGenerator
canonical_path: /api/Spine/Unity/MeshGenerator
---

# Class MeshGenerator

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MeshGenerator
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MeshGenerator

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MeshGenerator()

```csharp
public MeshGenerator()
```

## Fields

### BoundsMaxDefault

```csharp
private const float BoundsMaxDefault = -Infinity
```

#### Field Value

**Type:** System.Single

### BoundsMinDefault

```csharp
private const float BoundsMinDefault = Infinity
```

#### Field Value

**Type:** System.Single

### clipper

```csharp
private SkeletonClipping clipper
```

#### Field Value

**Type:** Spine.SkeletonClipping

### colorBuffer

```csharp
private readonly ExposedList<Color32> colorBuffer
```

#### Field Value

**Type:** Spine.ExposedList{UnityEngine.Color32}

### meshBoundsMax

```csharp
private Vector2 meshBoundsMax
```

#### Field Value

**Type:** UnityEngine.Vector2

### meshBoundsMin

```csharp
private Vector2 meshBoundsMin
```

#### Field Value

**Type:** UnityEngine.Vector2

### meshBoundsThickness

```csharp
private float meshBoundsThickness
```

#### Field Value

**Type:** System.Single

### normals

```csharp
private Vector3[] normals
```

#### Field Value

**Type:** UnityEngine.Vector3[]

### regionTriangles

```csharp
private int[] regionTriangles
```

#### Field Value

**Type:** System.Int32[]

### settings

```csharp
public MeshGenerator.Settings settings
```

#### Field Value

**Type:** Spine.Unity.MeshGenerator.Settings

### submeshes

```csharp
private readonly ExposedList<ExposedList<int>> submeshes
```

#### Field Value

**Type:** Spine.ExposedList{Spine.ExposedList{System.Int32}}

### submeshIndex

```csharp
private int submeshIndex
```

#### Field Value

**Type:** System.Int32

### tangents

```csharp
private Vector4[] tangents
```

#### Field Value

**Type:** UnityEngine.Vector4[]

### tempTanBuffer

```csharp
private Vector2[] tempTanBuffer
```

#### Field Value

**Type:** UnityEngine.Vector2[]

### tempVerts

```csharp
private float[] tempVerts
```

#### Field Value

**Type:** System.Single[]

### uv2

```csharp
private ExposedList<Vector2> uv2
```

#### Field Value

**Type:** Spine.ExposedList{UnityEngine.Vector2}

### uv3

```csharp
private ExposedList<Vector2> uv3
```

#### Field Value

**Type:** Spine.ExposedList{UnityEngine.Vector2}

### uvBuffer

```csharp
private readonly ExposedList<Vector2> uvBuffer
```

#### Field Value

**Type:** Spine.ExposedList{UnityEngine.Vector2}

### vertexBuffer

```csharp
private readonly ExposedList<Vector3> vertexBuffer
```

#### Field Value

**Type:** Spine.ExposedList{UnityEngine.Vector3}

## Properties

### Buffers

```csharp
public MeshGeneratorBuffers Buffers { get; }
```

#### Property Value

**Type:** Spine.Unity.MeshGeneratorBuffers

### VertexCount

```csharp
public int VertexCount { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### AddAttachmentTintBlack(float, float, float, int)

```csharp
private void AddAttachmentTintBlack(float r2, float g2, float b2, int vertexCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `r2` | `System.Single` |  |
| `g2` | `System.Single` |  |
| `b2` | `System.Single` |  |
| `vertexCount` | `System.Int32` |  |

### AddSubmesh(SubmeshInstruction, bool)

```csharp
public void AddSubmesh(SubmeshInstruction instruction, bool updateTriangles = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instruction` | `Spine.Unity.SubmeshInstruction` |  |
| `updateTriangles` | `System.Boolean` |  |

### Begin()

```csharp
public void Begin()
```

### BuildMesh(SkeletonRendererInstruction, bool)

```csharp
public void BuildMesh(SkeletonRendererInstruction instruction, bool updateTriangles)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instruction` | `Spine.Unity.SkeletonRendererInstruction` |  |
| `updateTriangles` | `System.Boolean` |  |

### BuildMeshWithArrays(SkeletonRendererInstruction, bool)

```csharp
public void BuildMeshWithArrays(SkeletonRendererInstruction instruction, bool updateTriangles)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instruction` | `Spine.Unity.SkeletonRendererInstruction` |  |
| `updateTriangles` | `System.Boolean` |  |

### FillTriangles(Mesh)

```csharp
public void FillTriangles(Mesh mesh)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mesh` | `UnityEngine.Mesh` |  |

### FillTrianglesSingle(Mesh)

```csharp
public void FillTrianglesSingle(Mesh mesh)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mesh` | `UnityEngine.Mesh` |  |

### FillVertexData(Mesh)

```csharp
public void FillVertexData(Mesh mesh)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mesh` | `UnityEngine.Mesh` |  |

### GenerateSingleSubmeshInstruction(SkeletonRendererInstruction, Skeleton, Material)

```csharp
public static void GenerateSingleSubmeshInstruction(SkeletonRendererInstruction instructionOutput, Skeleton skeleton, Material material)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instructionOutput` | `Spine.Unity.SkeletonRendererInstruction` |  |
| `skeleton` | `Spine.Skeleton` |  |
| `material` | `UnityEngine.Material` |  |

### GenerateSkeletonRendererInstruction(SkeletonRendererInstruction, Skeleton, Dictionary<Slot, Material>, List<Slot>, bool, bool)

```csharp
public static void GenerateSkeletonRendererInstruction(SkeletonRendererInstruction instructionOutput, Skeleton skeleton, Dictionary<Slot, Material> customSlotMaterials, List<Slot> separatorSlots, bool generateMeshOverride, bool immutableTriangles = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instructionOutput` | `Spine.Unity.SkeletonRendererInstruction` |  |
| `skeleton` | `Spine.Skeleton` |  |
| `customSlotMaterials` | `System.Collections.Generic.Dictionary{Spine.Slot,UnityEngine.Material}` |  |
| `separatorSlots` | `System.Collections.Generic.List{Spine.Slot}` |  |
| `generateMeshOverride` | `System.Boolean` |  |
| `immutableTriangles` | `System.Boolean` |  |

### ScaleVertexData(float)

```csharp
public void ScaleVertexData(float scale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `scale` | `System.Single` |  |

### SolveTangents2DBuffer(Vector4[], Vector2[], int)

```csharp
internal static void SolveTangents2DBuffer(Vector4[] tangents, Vector2[] tempTanBuffer, int vertexCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tangents` | `UnityEngine.Vector4[]` |  |
| `tempTanBuffer` | `UnityEngine.Vector2[]` |  |
| `vertexCount` | `System.Int32` |  |

### SolveTangents2DEnsureSize(ref Vector4[], ref Vector2[], int)

```csharp
internal static void SolveTangents2DEnsureSize(ref Vector4[] tangentBuffer, ref Vector2[] tempTanBuffer, int vertexCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tangentBuffer` | `UnityEngine.Vector4[]` |  |
| `tempTanBuffer` | `UnityEngine.Vector2[]` |  |
| `vertexCount` | `System.Int32` |  |

### SolveTangents2DTriangles(Vector2[], int[], int, Vector3[], Vector2[], int)

```csharp
internal static void SolveTangents2DTriangles(Vector2[] tempTanBuffer, int[] triangles, int triangleCount, Vector3[] vertices, Vector2[] uvs, int vertexCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tempTanBuffer` | `UnityEngine.Vector2[]` |  |
| `triangles` | `System.Int32[]` |  |
| `triangleCount` | `System.Int32` |  |
| `vertices` | `UnityEngine.Vector3[]` |  |
| `uvs` | `UnityEngine.Vector2[]` |  |
| `vertexCount` | `System.Int32` |  |

### TrimExcess()

```csharp
public void TrimExcess()
```

### TryReplaceMaterials(ExposedList<SubmeshInstruction>, Dictionary<Material, Material>)

```csharp
public static void TryReplaceMaterials(ExposedList<SubmeshInstruction> workingSubmeshInstructions, Dictionary<Material, Material> customMaterialOverride)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `workingSubmeshInstructions` | `Spine.ExposedList{Spine.Unity.SubmeshInstruction}` |  |
| `customMaterialOverride` | `System.Collections.Generic.Dictionary{UnityEngine.Material,UnityEngine.Material}` |  |
