---
uid: Spine.VertexAttachment
canonical_path: /api/Spine/VertexAttachment
---

# Class VertexAttachment

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class VertexAttachment : Attachment
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Attachment](/api/Spine/Attachment) → VertexAttachment

## Derived
[BoundingBoxAttachment](/api/Spine/BoundingBoxAttachment), [ClippingAttachment](/api/Spine/ClippingAttachment), [MeshAttachment](/api/Spine/MeshAttachment), [PathAttachment](/api/Spine/PathAttachment)

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
- [IsWeighted(VertexAttachment)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_IsWeighted_Spine_VertexAttachment_)
- [GetLocalVertices(VertexAttachment, Slot, Vector2[])](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetLocalVertices_Spine_VertexAttachment_Spine_Slot_UnityEngine_Vector2___)
- [GetWorldVertices(VertexAttachment, Slot, Vector2[])](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetWorldVertices_Spine_VertexAttachment_Spine_Slot_UnityEngine_Vector2___)

## Constructors

### VertexAttachment(string)

```csharp
public VertexAttachment(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

## Fields

### bones

```csharp
internal int[] bones
```

#### Field Value

**Type:** System.Int32[]

### id

```csharp
internal readonly int id
```

#### Field Value

**Type:** System.Int32

### nextID

```csharp
private static int nextID
```

#### Field Value

**Type:** System.Int32

### nextIdLock

```csharp
private static readonly object nextIdLock
```

#### Field Value

**Type:** System.Object

### vertices

```csharp
internal float[] vertices
```

#### Field Value

**Type:** System.Single[]

### worldVerticesLength

```csharp
internal int worldVerticesLength
```

#### Field Value

**Type:** System.Int32

## Properties

### Bones

```csharp
public int[] Bones { get; set; }
```

#### Property Value

**Type:** System.Int32[]

### Id

```csharp
public int Id { get; }
```

#### Property Value

**Type:** System.Int32

### Vertices

```csharp
public float[] Vertices { get; set; }
```

#### Property Value

**Type:** System.Single[]

### WorldVerticesLength

```csharp
public int WorldVerticesLength { get; set; }
```

#### Property Value

**Type:** System.Int32

## Methods

### ApplyDeform(VertexAttachment)

```csharp
public virtual bool ApplyDeform(VertexAttachment sourceAttachment)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sourceAttachment` | `Spine.VertexAttachment` |  |

#### Returns

**Type:** System.Boolean

### ComputeWorldVertices(Slot, float[])

```csharp
public void ComputeWorldVertices(Slot slot, float[] worldVertices)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Spine.Slot` |  |
| `worldVertices` | `System.Single[]` |  |

### ComputeWorldVertices(Slot, int, int, float[], int, int)

```csharp
public void ComputeWorldVertices(Slot slot, int start, int count, float[] worldVertices, int offset, int stride = 2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Spine.Slot` |  |
| `start` | `System.Int32` |  |
| `count` | `System.Int32` |  |
| `worldVertices` | `System.Single[]` |  |
| `offset` | `System.Int32` |  |
| `stride` | `System.Int32` |  |
