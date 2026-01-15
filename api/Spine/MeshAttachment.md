---
uid: Spine.MeshAttachment
canonical_path: /api/Spine/MeshAttachment
---

# Class MeshAttachment

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MeshAttachment : VertexAttachment
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Attachment](/api/Spine/Attachment) → [VertexAttachment](/api/Spine/VertexAttachment) → MeshAttachment

## Inherited Members
[nextID](/api/Spine/VertexAttachment#nextid), [nextIdLock](/api/Spine/VertexAttachment#nextidlock), [id](/api/Spine/VertexAttachment#id), [bones](/api/Spine/VertexAttachment#bones), [vertices](/api/Spine/VertexAttachment#vertices), [worldVerticesLength](/api/Spine/VertexAttachment#worldverticeslength), [ComputeWorldVertices(Slot, float[])](/api/Spine/VertexAttachment#computeworldvertices-slot-float), [ComputeWorldVertices(Slot, int, int, float[], int, int)](/api/Spine/VertexAttachment#computeworldvertices-slot-int-int-float-int-int), [Id](/api/Spine/VertexAttachment#id), [Bones](/api/Spine/VertexAttachment#bones), [Vertices](/api/Spine/VertexAttachment#vertices), [WorldVerticesLength](/api/Spine/VertexAttachment#worldverticeslength), [<Name>k__BackingField](Spine.Attachment.html#Spine_Attachment__Name_k__BackingField), [ToString()](/api/Spine/Attachment#tostring), [Name](/api/Spine/Attachment#name), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Extension Methods
- [IsRenderable(Attachment)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_IsRenderable_Spine_Attachment_)
- [GetAtlasRegion(Attachment)](Spine.Unity.Modules.AttachmentTools.AtlasUtilities.html#Spine_Unity_Modules_AttachmentTools_AtlasUtilities_GetAtlasRegion_Spine_Attachment_)
- [GetClone(Attachment, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetClone_Spine_Attachment_System_Boolean_)
- [GetRemappedClone(Attachment, AtlasRegion, bool, bool, float)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetRemappedClone_Spine_Attachment_Spine_AtlasRegion_System_Boolean_System_Boolean_System_Single_)
- [GetRemappedClone(Attachment, Sprite, Material, bool, bool, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetRemappedClone_Spine_Attachment_UnityEngine_Sprite_UnityEngine_Material_System_Boolean_System_Boolean_System_Boolean_)
- [GetRegion(Attachment)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_GetRegion_Spine_Attachment_)
- [SetRegion(Attachment, AtlasRegion, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_SetRegion_Spine_Attachment_Spine_AtlasRegion_System_Boolean_)
- [GetMaterial(Attachment)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetMaterial_Spine_Attachment_)
- [GetClone(MeshAttachment)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetClone_Spine_MeshAttachment_)
- [GetLinkedClone(MeshAttachment, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetLinkedClone_Spine_MeshAttachment_System_Boolean_)
- [GetLinkedMesh(MeshAttachment, string, AtlasRegion, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetLinkedMesh_Spine_MeshAttachment_System_String_Spine_AtlasRegion_System_Boolean_)
- [GetLinkedMesh(MeshAttachment, Sprite, Material, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetLinkedMesh_Spine_MeshAttachment_UnityEngine_Sprite_UnityEngine_Material_System_Boolean_)
- [GetLinkedMesh(MeshAttachment, Sprite, Shader, bool, Material)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetLinkedMesh_Spine_MeshAttachment_UnityEngine_Sprite_UnityEngine_Shader_System_Boolean_UnityEngine_Material_)
- [GetRegion(MeshAttachment)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_GetRegion_Spine_MeshAttachment_)
- [SetRegion(MeshAttachment, AtlasRegion, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_SetRegion_Spine_MeshAttachment_Spine_AtlasRegion_System_Boolean_)
- [GetColor(MeshAttachment)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetColor_Spine_MeshAttachment_)
- [SetColor(MeshAttachment, Color)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_SetColor_Spine_MeshAttachment_UnityEngine_Color_)
- [SetColor(MeshAttachment, Color32)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_SetColor_Spine_MeshAttachment_UnityEngine_Color32_)
- [IsWeighted(VertexAttachment)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_IsWeighted_Spine_VertexAttachment_)
- [GetLocalVertices(VertexAttachment, Slot, Vector2[])](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetLocalVertices_Spine_VertexAttachment_Spine_Slot_UnityEngine_Vector2___)
- [GetWorldVertices(VertexAttachment, Slot, Vector2[])](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetWorldVertices_Spine_VertexAttachment_Spine_Slot_UnityEngine_Vector2___)

## Constructors

### MeshAttachment(string)

```csharp
public MeshAttachment(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

## Fields

### a

```csharp
internal float a
```

#### Field Value

**Type:** System.Single

### b

```csharp
internal float b
```

#### Field Value

**Type:** System.Single

### g

```csharp
internal float g
```

#### Field Value

**Type:** System.Single

### hulllength

```csharp
internal int hulllength
```

#### Field Value

**Type:** System.Int32

### inheritDeform

```csharp
internal bool inheritDeform
```

#### Field Value

**Type:** System.Boolean

### parentMesh

```csharp
private MeshAttachment parentMesh
```

#### Field Value

**Type:** Spine.MeshAttachment

### r

```csharp
internal float r
```

#### Field Value

**Type:** System.Single

### regionHeight

```csharp
internal float regionHeight
```

#### Field Value

**Type:** System.Single

### regionOffsetX

```csharp
internal float regionOffsetX
```

#### Field Value

**Type:** System.Single

### regionOffsetY

```csharp
internal float regionOffsetY
```

#### Field Value

**Type:** System.Single

### regionOriginalHeight

```csharp
internal float regionOriginalHeight
```

#### Field Value

**Type:** System.Single

### regionOriginalWidth

```csharp
internal float regionOriginalWidth
```

#### Field Value

**Type:** System.Single

### regionUVs

```csharp
internal float[] regionUVs
```

#### Field Value

**Type:** System.Single[]

### regionWidth

```csharp
internal float regionWidth
```

#### Field Value

**Type:** System.Single

### RendererObject

```csharp
public object RendererObject
```

#### Field Value

**Type:** System.Object

### triangles

```csharp
internal int[] triangles
```

#### Field Value

**Type:** System.Int32[]

### uvs

```csharp
internal float[] uvs
```

#### Field Value

**Type:** System.Single[]

## Properties

### A

```csharp
public float A { get; set; }
```

#### Property Value

**Type:** System.Single

### B

```csharp
public float B { get; set; }
```

#### Property Value

**Type:** System.Single

### Edges

```csharp
public int[] Edges { get; set; }
```

#### Property Value

**Type:** System.Int32[]

### G

```csharp
public float G { get; set; }
```

#### Property Value

**Type:** System.Single

### Height

```csharp
public float Height { get; set; }
```

#### Property Value

**Type:** System.Single

### HullLength

```csharp
public int HullLength { get; set; }
```

#### Property Value

**Type:** System.Int32

### InheritDeform

```csharp
public bool InheritDeform { get; set; }
```

#### Property Value

**Type:** System.Boolean

### ParentMesh

```csharp
public MeshAttachment ParentMesh { get; set; }
```

#### Property Value

**Type:** Spine.MeshAttachment

### Path

```csharp
public string Path { get; set; }
```

#### Property Value

**Type:** System.String

### R

```csharp
public float R { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionHeight

```csharp
public float RegionHeight { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionOffsetX

```csharp
public float RegionOffsetX { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionOffsetY

```csharp
public float RegionOffsetY { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionOriginalHeight

```csharp
public float RegionOriginalHeight { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionOriginalWidth

```csharp
public float RegionOriginalWidth { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionRotate

```csharp
public bool RegionRotate { get; set; }
```

#### Property Value

**Type:** System.Boolean

### RegionU

```csharp
public float RegionU { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionU2

```csharp
public float RegionU2 { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionUVs

```csharp
public float[] RegionUVs { get; set; }
```

#### Property Value

**Type:** System.Single[]

### RegionV

```csharp
public float RegionV { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionV2

```csharp
public float RegionV2 { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionWidth

```csharp
public float RegionWidth { get; set; }
```

#### Property Value

**Type:** System.Single

### Triangles

```csharp
public int[] Triangles { get; set; }
```

#### Property Value

**Type:** System.Int32[]

### UVs

```csharp
public float[] UVs { get; set; }
```

#### Property Value

**Type:** System.Single[]

### Width

```csharp
public float Width { get; set; }
```

#### Property Value

**Type:** System.Single

## Methods

### ApplyDeform(VertexAttachment)

```csharp
public override bool ApplyDeform(VertexAttachment sourceAttachment)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sourceAttachment` | `Spine.VertexAttachment` |  |

#### Returns

**Type:** System.Boolean

### UpdateUVs()

```csharp
public void UpdateUVs()
```
