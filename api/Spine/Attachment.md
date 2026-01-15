---
uid: Spine.Attachment
canonical_path: /api/Spine/Attachment
---

# Class Attachment

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public abstract class Attachment
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Attachment

## Derived
[PointAttachment](/api/Spine/PointAttachment), [RegionAttachment](/api/Spine/RegionAttachment), [VertexAttachment](/api/Spine/VertexAttachment)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Extension Methods
- [IsRenderable(Attachment)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_IsRenderable_Spine_Attachment_)
- [GetAtlasRegion(Attachment)](Spine.Unity.Modules.AttachmentTools.AtlasUtilities.html#Spine_Unity_Modules_AttachmentTools_AtlasUtilities_GetAtlasRegion_Spine_Attachment_)
- [GetClone(Attachment, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetClone_Spine_Attachment_System_Boolean_)
- [GetRemappedClone(Attachment, AtlasRegion, bool, bool, float)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetRemappedClone_Spine_Attachment_Spine_AtlasRegion_System_Boolean_System_Boolean_System_Single_)
- [GetRemappedClone(Attachment, Sprite, Material, bool, bool, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetRemappedClone_Spine_Attachment_UnityEngine_Sprite_UnityEngine_Material_System_Boolean_System_Boolean_System_Boolean_)
- [GetRegion(Attachment)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_GetRegion_Spine_Attachment_)
- [SetRegion(Attachment, AtlasRegion, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_SetRegion_Spine_Attachment_Spine_AtlasRegion_System_Boolean_)
- [GetMaterial(Attachment)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetMaterial_Spine_Attachment_)

## Constructors

### Attachment(string)

```csharp
public Attachment(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

## Properties

### Name

```csharp
public string Name { get; private set; }
```

#### Property Value

**Type:** System.String

## Methods

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
