---
uid: Spine.ClippingAttachment
canonical_path: /api/Spine/ClippingAttachment
---

# Class ClippingAttachment

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ClippingAttachment : VertexAttachment
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Attachment](/api/Spine/Attachment) → [VertexAttachment](/api/Spine/VertexAttachment) → ClippingAttachment

## Inherited Members
[nextID](/api/Spine/VertexAttachment#nextid), [nextIdLock](/api/Spine/VertexAttachment#nextidlock), [id](/api/Spine/VertexAttachment#id), [bones](/api/Spine/VertexAttachment#bones), [vertices](/api/Spine/VertexAttachment#vertices), [worldVerticesLength](/api/Spine/VertexAttachment#worldverticeslength), [ComputeWorldVertices(Slot, float[])](/api/Spine/VertexAttachment#computeworldvertices-slot-float), [ComputeWorldVertices(Slot, int, int, float[], int, int)](/api/Spine/VertexAttachment#computeworldvertices-slot-int-int-float-int-int), [ApplyDeform(VertexAttachment)](/api/Spine/VertexAttachment#applydeform-vertexattachment), [Id](/api/Spine/VertexAttachment#id), [Bones](/api/Spine/VertexAttachment#bones), [Vertices](/api/Spine/VertexAttachment#vertices), [WorldVerticesLength](/api/Spine/VertexAttachment#worldverticeslength), [<Name>k__BackingField](Spine.Attachment.html#Spine_Attachment__Name_k__BackingField), [ToString()](/api/Spine/Attachment#tostring), [Name](/api/Spine/Attachment#name), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Extension Methods
- [IsRenderable(Attachment)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_IsRenderable_Spine_Attachment_)
- [GetAtlasRegion(Attachment)](Spine.Unity.Modules.AttachmentTools.AtlasUtilities.html#Spine_Unity_Modules_AttachmentTools_AtlasUtilities_GetAtlasRegion_Spine_Attachment_)
- [GetClone(Attachment, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetClone_Spine_Attachment_System_Boolean_)
- [GetRemappedClone(Attachment, AtlasRegion, bool, bool, float)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetRemappedClone_Spine_Attachment_Spine_AtlasRegion_System_Boolean_System_Boolean_System_Single_)
- [GetRemappedClone(Attachment, Sprite, Material, bool, bool, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetRemappedClone_Spine_Attachment_UnityEngine_Sprite_UnityEngine_Material_System_Boolean_System_Boolean_System_Boolean_)
- [GetRegion(Attachment)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_GetRegion_Spine_Attachment_)
- [SetRegion(Attachment, AtlasRegion, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_SetRegion_Spine_Attachment_Spine_AtlasRegion_System_Boolean_)
- [GetMaterial(Attachment)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetMaterial_Spine_Attachment_)
- [GetClone(ClippingAttachment)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetClone_Spine_ClippingAttachment_)
- [IsWeighted(VertexAttachment)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_IsWeighted_Spine_VertexAttachment_)
- [GetLocalVertices(VertexAttachment, Slot, Vector2[])](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetLocalVertices_Spine_VertexAttachment_Spine_Slot_UnityEngine_Vector2___)
- [GetWorldVertices(VertexAttachment, Slot, Vector2[])](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetWorldVertices_Spine_VertexAttachment_Spine_Slot_UnityEngine_Vector2___)

## Constructors

### ClippingAttachment(string)

```csharp
public ClippingAttachment(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

## Fields

### endSlot

```csharp
internal SlotData endSlot
```

#### Field Value

**Type:** Spine.SlotData

## Properties

### EndSlot

```csharp
public SlotData EndSlot { get; set; }
```

#### Property Value

**Type:** Spine.SlotData
