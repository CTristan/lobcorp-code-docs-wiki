---
uid: Spine.RegionAttachment
canonical_path: /api/Spine/RegionAttachment
---

# Class RegionAttachment

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RegionAttachment : Attachment
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Attachment](/api/Spine/Attachment) → RegionAttachment

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
- [GetClone(RegionAttachment)](Spine.Unity.Modules.AttachmentTools.AttachmentCloneExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentCloneExtensions_GetClone_Spine_RegionAttachment_)
- [GetRegion(RegionAttachment)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_GetRegion_Spine_RegionAttachment_)
- [SetPositionOffset(RegionAttachment, float, float)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_SetPositionOffset_Spine_RegionAttachment_System_Single_System_Single_)
- [SetPositionOffset(RegionAttachment, Vector2)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_SetPositionOffset_Spine_RegionAttachment_UnityEngine_Vector2_)
- [SetRegion(RegionAttachment, AtlasRegion, bool)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_SetRegion_Spine_RegionAttachment_Spine_AtlasRegion_System_Boolean_)
- [SetRotation(RegionAttachment, float)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_SetRotation_Spine_RegionAttachment_System_Single_)
- [SetScale(RegionAttachment, float, float)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_SetScale_Spine_RegionAttachment_System_Single_System_Single_)
- [SetScale(RegionAttachment, Vector2)](Spine.Unity.Modules.AttachmentTools.AttachmentRegionExtensions.html#Spine_Unity_Modules_AttachmentTools_AttachmentRegionExtensions_SetScale_Spine_RegionAttachment_UnityEngine_Vector2_)
- [GetColor(RegionAttachment)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetColor_Spine_RegionAttachment_)
- [SetColor(RegionAttachment, Color)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_SetColor_Spine_RegionAttachment_UnityEngine_Color_)
- [SetColor(RegionAttachment, Color32)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_SetColor_Spine_RegionAttachment_UnityEngine_Color32_)

## Constructors

### RegionAttachment(string)

```csharp
public RegionAttachment(string name)
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

### BLX

```csharp
public const int BLX = 0
```

#### Field Value

**Type:** System.Int32

### BLY

```csharp
public const int BLY = 1
```

#### Field Value

**Type:** System.Int32

### BRX

```csharp
public const int BRX = 6
```

#### Field Value

**Type:** System.Int32

### BRY

```csharp
public const int BRY = 7
```

#### Field Value

**Type:** System.Int32

### g

```csharp
internal float g
```

#### Field Value

**Type:** System.Single

### height

```csharp
internal float height
```

#### Field Value

**Type:** System.Single

### offset

```csharp
internal float[] offset
```

#### Field Value

**Type:** System.Single[]

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

### rotation

```csharp
internal float rotation
```

#### Field Value

**Type:** System.Single

### scaleX

```csharp
internal float scaleX
```

#### Field Value

**Type:** System.Single

### scaleY

```csharp
internal float scaleY
```

#### Field Value

**Type:** System.Single

### ULX

```csharp
public const int ULX = 2
```

#### Field Value

**Type:** System.Int32

### ULY

```csharp
public const int ULY = 3
```

#### Field Value

**Type:** System.Int32

### URX

```csharp
public const int URX = 4
```

#### Field Value

**Type:** System.Int32

### URY

```csharp
public const int URY = 5
```

#### Field Value

**Type:** System.Int32

### uvs

```csharp
internal float[] uvs
```

#### Field Value

**Type:** System.Single[]

### width

```csharp
internal float width
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

### Offset

```csharp
public float[] Offset { get; }
```

#### Property Value

**Type:** System.Single[]

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

### RegionWidth

```csharp
public float RegionWidth { get; set; }
```

#### Property Value

**Type:** System.Single

### Rotation

```csharp
public float Rotation { get; set; }
```

#### Property Value

**Type:** System.Single

### ScaleX

```csharp
public float ScaleX { get; set; }
```

#### Property Value

**Type:** System.Single

### ScaleY

```csharp
public float ScaleY { get; set; }
```

#### Property Value

**Type:** System.Single

### UVs

```csharp
public float[] UVs { get; }
```

#### Property Value

**Type:** System.Single[]

### Width

```csharp
public float Width { get; set; }
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

### ComputeWorldVertices(Bone, float[], int, int)

```csharp
public void ComputeWorldVertices(Bone bone, float[] worldVertices, int offset, int stride = 2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `worldVertices` | `System.Single[]` |  |
| `offset` | `System.Int32` |  |
| `stride` | `System.Int32` |  |

### SetUVs(float, float, float, float, bool)

```csharp
public void SetUVs(float u, float v, float u2, float v2, bool rotate)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `u` | `System.Single` |  |
| `v` | `System.Single` |  |
| `u2` | `System.Single` |  |
| `v2` | `System.Single` |  |
| `rotate` | `System.Boolean` |  |

### UpdateOffset()

```csharp
public void UpdateOffset()
```
