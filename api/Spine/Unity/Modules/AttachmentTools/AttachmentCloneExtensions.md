---
uid: Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions
canonical_path: /api/Spine/Unity/Modules/AttachmentTools/AttachmentCloneExtensions
---

# Class AttachmentCloneExtensions

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity) . [Modules](/api/Spine/Unity/Modules) . [AttachmentTools](/api/Spine/Unity/Modules/AttachmentTools)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class AttachmentCloneExtensions
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AttachmentCloneExtensions

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Methods

### CloneVertexAttachment(VertexAttachment, VertexAttachment)

```csharp
private static void CloneVertexAttachment(VertexAttachment src, VertexAttachment dest)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `Spine.VertexAttachment` |  |
| `dest` | `Spine.VertexAttachment` |  |

### GetClone(Attachment, bool)

```csharp
public static Attachment GetClone(this Attachment o, bool cloneMeshesAsLinked)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.Attachment` |  |
| `cloneMeshesAsLinked` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Attachment

### GetClone(BoundingBoxAttachment)

```csharp
public static BoundingBoxAttachment GetClone(this BoundingBoxAttachment o)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.BoundingBoxAttachment` |  |

#### Returns

**Type:** Spine.BoundingBoxAttachment

### GetClone(ClippingAttachment)

```csharp
public static ClippingAttachment GetClone(this ClippingAttachment o)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.ClippingAttachment` |  |

#### Returns

**Type:** Spine.ClippingAttachment

### GetClone(MeshAttachment)

```csharp
public static MeshAttachment GetClone(this MeshAttachment o)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.MeshAttachment` |  |

#### Returns

**Type:** Spine.MeshAttachment

### GetClone(PathAttachment)

```csharp
public static PathAttachment GetClone(this PathAttachment o)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.PathAttachment` |  |

#### Returns

**Type:** Spine.PathAttachment

### GetClone(PointAttachment)

```csharp
public static PointAttachment GetClone(this PointAttachment o)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.PointAttachment` |  |

#### Returns

**Type:** Spine.PointAttachment

### GetClone(RegionAttachment)

```csharp
public static RegionAttachment GetClone(this RegionAttachment o)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.RegionAttachment` |  |

#### Returns

**Type:** Spine.RegionAttachment

### GetLinkedClone(MeshAttachment, bool)

```csharp
public static MeshAttachment GetLinkedClone(this MeshAttachment o, bool inheritDeform = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.MeshAttachment` |  |
| `inheritDeform` | `System.Boolean` |  |

#### Returns

**Type:** Spine.MeshAttachment

### GetLinkedMesh(MeshAttachment, Sprite, Material, bool)

```csharp
public static MeshAttachment GetLinkedMesh(this MeshAttachment o, Sprite sprite, Material materialPropertySource, bool inheritDeform = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.MeshAttachment` |  |
| `sprite` | `UnityEngine.Sprite` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |
| `inheritDeform` | `System.Boolean` |  |

#### Returns

**Type:** Spine.MeshAttachment

### GetLinkedMesh(MeshAttachment, Sprite, Shader, bool, Material)

```csharp
public static MeshAttachment GetLinkedMesh(this MeshAttachment o, Sprite sprite, Shader shader, bool inheritDeform = true, Material materialPropertySource = null)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.MeshAttachment` |  |
| `sprite` | `UnityEngine.Sprite` |  |
| `shader` | `UnityEngine.Shader` |  |
| `inheritDeform` | `System.Boolean` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |

#### Returns

**Type:** Spine.MeshAttachment

### GetLinkedMesh(MeshAttachment, string, AtlasRegion, bool)

```csharp
public static MeshAttachment GetLinkedMesh(this MeshAttachment o, string newLinkedMeshName, AtlasRegion region, bool inheritDeform = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.MeshAttachment` |  |
| `newLinkedMeshName` | `System.String` |  |
| `region` | `Spine.AtlasRegion` |  |
| `inheritDeform` | `System.Boolean` |  |

#### Returns

**Type:** Spine.MeshAttachment

### GetRemappedClone(Attachment, AtlasRegion, bool, bool, float)

```csharp
public static Attachment GetRemappedClone(this Attachment o, AtlasRegion atlasRegion, bool cloneMeshAsLinked = true, bool useOriginalRegionSize = false, float scale = 0.01)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.Attachment` |  |
| `atlasRegion` | `Spine.AtlasRegion` |  |
| `cloneMeshAsLinked` | `System.Boolean` |  |
| `useOriginalRegionSize` | `System.Boolean` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** Spine.Attachment

### GetRemappedClone(Attachment, Sprite, Material, bool, bool, bool)

```csharp
public static Attachment GetRemappedClone(this Attachment o, Sprite sprite, Material sourceMaterial, bool premultiplyAlpha = true, bool cloneMeshAsLinked = true, bool useOriginalRegionSize = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.Attachment` |  |
| `sprite` | `UnityEngine.Sprite` |  |
| `sourceMaterial` | `UnityEngine.Material` |  |
| `premultiplyAlpha` | `System.Boolean` |  |
| `cloneMeshAsLinked` | `System.Boolean` |  |
| `useOriginalRegionSize` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Attachment
