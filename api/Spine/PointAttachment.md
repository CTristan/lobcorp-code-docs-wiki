---
uid: Spine.PointAttachment
canonical_path: /api/Spine/PointAttachment
---

# Class PointAttachment

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PointAttachment : Attachment
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Attachment](/api/Spine/Attachment) → PointAttachment

## Inherited Members
[<Name>k__BackingField](Spine.Attachment.html#Spine_Attachment__Name_k__BackingField), [ToString()](/api/Spine/Attachment#tostring), [Name](/api/Spine/Attachment#name), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Extension Methods
- [IsRenderable(Attachment)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_IsRenderable_Spine_Attachment_)
- [GetAtlasRegion(Attachment)](Spine.Unity.Modules.AttachmentTools.AtlasUtilities.html#Spine_Unity_Modules_AttachmentTools_AtlasUtilities_GetAtlasRegion_Spine_Attachment_)
- [GetClone(Attachment, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetClone_Spine_Attachment_System_Boolean_)
- [GetRemappedClone(Attachment, AtlasRegion, bool, bool, float)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetRemappedClone_Spine_Attachment_Spine_AtlasRegion_System_Boolean_System_Boolean_System_Single_)
- [GetRemappedClone(Attachment, Sprite, Material, bool, bool, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetRemappedClone_Spine_Attachment_UnityEngine_Sprite_UnityEngine_Material_System_Boolean_System_Boolean_System_Boolean_)
- [GetRegion(Attachment)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_GetRegion_Spine_Attachment_)
- [SetRegion(Attachment, AtlasRegion, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_SetRegion_Spine_Attachment_Spine_AtlasRegion_System_Boolean_)
- [GetMaterial(Attachment)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetMaterial_Spine_Attachment_)
- [GetClone(PointAttachment)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetClone_Spine_PointAttachment_)
- [GetWorldPosition(PointAttachment, Bone, Transform)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetWorldPosition_Spine_PointAttachment_Spine_Bone_UnityEngine_Transform_)
- [GetWorldPosition(PointAttachment, Slot, Transform)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetWorldPosition_Spine_PointAttachment_Spine_Slot_UnityEngine_Transform_)

## Constructors

### PointAttachment(string)

```csharp
public PointAttachment(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

## Fields

### rotation

```csharp
internal float rotation
```

#### Field Value

**Type:** System.Single

### x

```csharp
internal float x
```

#### Field Value

**Type:** System.Single

### y

```csharp
internal float y
```

#### Field Value

**Type:** System.Single

## Properties

### Rotation

```csharp
public float Rotation { get; set; }
```

#### Property Value

**Type:** System.Single

### X

```csharp
public float X { get; set; }
```

#### Property Value

**Type:** System.Single

### Y

```csharp
public float Y { get; set; }
```

#### Property Value

**Type:** System.Single

## Methods

### ComputeWorldPosition(Bone, out float, out float)

```csharp
public void ComputeWorldPosition(Bone bone, out float ox, out float oy)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `ox` | `System.Single` |  |
| `oy` | `System.Single` |  |

### ComputeWorldRotation(Bone)

```csharp
public float ComputeWorldRotation(Bone bone)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |

#### Returns

**Type:** System.Single
