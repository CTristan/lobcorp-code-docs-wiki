# Class MeshGenerator

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine-Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MeshGenerator
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MeshGenerator

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### MeshGenerator()

```csharp
public MeshGenerator()
```

## Fields

### settings

```csharp
public MeshGenerator.Settings settings
```

#### Field Value

**Type:** Spine.Unity.MeshGenerator.Settings

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
