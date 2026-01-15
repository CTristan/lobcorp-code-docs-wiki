---
uid: Spine.Skeleton
canonical_path: /api/Spine/Skeleton
---

# Class Skeleton

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Skeleton
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Skeleton

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Extension Methods
- [PoseWithAnimation(Skeleton, string, float, bool)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_PoseWithAnimation_Spine_Skeleton_System_String_System_Single_System_Boolean_)
- [SetDrawOrderToSetupPose(Skeleton)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_SetDrawOrderToSetupPose_Spine_Skeleton_)
- [SetPropertyToSetupPose(Skeleton, int)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_SetPropertyToSetupPose_Spine_Skeleton_System_Int32_)
- [SetSlotAttachmentToSetupPose(Skeleton, int)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_SetSlotAttachmentToSetupPose_Spine_Skeleton_System_Int32_)
- [GetClonedSkin(Skeleton, string, bool, bool, bool)](Spine.Unity.Modules.AttachmentTools.SkinUtilities.html#Spine_Unity_Modules_AttachmentTools_SkinUtilities_GetClonedSkin_Spine_Skeleton_System_String_System_Boolean_System_Boolean_System_Boolean_)
- [UnshareSkin(Skeleton, bool, bool, AnimationState)](Spine.Unity.Modules.AttachmentTools.SkinUtilities.html#Spine_Unity_Modules_AttachmentTools_SkinUtilities_UnshareSkin_Spine_Skeleton_System_Boolean_System_Boolean_Spine_AnimationState_)
- [AttachUnitySprite(Skeleton, string, Sprite, string, bool, float)](Spine.Unity.Modules.SpriteAttachmentExtensions.html#Spine_Unity_Modules_SpriteAttachmentExtensions_AttachUnitySprite_Spine_Skeleton_System_String_UnityEngine_Sprite_System_String_System_Boolean_System_Single_)
- [AttachUnitySprite(Skeleton, string, Sprite, Shader, bool, float)](Spine.Unity.Modules.SpriteAttachmentExtensions.html#Spine_Unity_Modules_SpriteAttachmentExtensions_AttachUnitySprite_Spine_Skeleton_System_String_UnityEngine_Sprite_UnityEngine_Shader_System_Boolean_System_Single_)
- [GetColor(Skeleton)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_GetColor_Spine_Skeleton_)
- [SetColor(Skeleton, Color)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_SetColor_Spine_Skeleton_UnityEngine_Color_)
- [SetColor(Skeleton, Color32)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_SetColor_Spine_Skeleton_UnityEngine_Color32_)

## Constructors

### Skeleton(SkeletonData)

```csharp
public Skeleton(SkeletonData data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Spine.SkeletonData` |  |

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

### bones

```csharp
internal ExposedList<Bone> bones
```

#### Field Value

**Type:** Spine.ExposedList{Spine.Bone}

### data

```csharp
internal SkeletonData data
```

#### Field Value

**Type:** Spine.SkeletonData

### drawOrder

```csharp
internal ExposedList<Slot> drawOrder
```

#### Field Value

**Type:** Spine.ExposedList{Spine.Slot}

### flipX

```csharp
internal bool flipX
```

#### Field Value

**Type:** System.Boolean

### flipY

```csharp
internal bool flipY
```

#### Field Value

**Type:** System.Boolean

### g

```csharp
internal float g
```

#### Field Value

**Type:** System.Single

### ikConstraints

```csharp
internal ExposedList<IkConstraint> ikConstraints
```

#### Field Value

**Type:** Spine.ExposedList{Spine.IkConstraint}

### pathConstraints

```csharp
internal ExposedList<PathConstraint> pathConstraints
```

#### Field Value

**Type:** Spine.ExposedList{Spine.PathConstraint}

### r

```csharp
internal float r
```

#### Field Value

**Type:** System.Single

### skin

```csharp
internal Skin skin
```

#### Field Value

**Type:** Spine.Skin

### slots

```csharp
internal ExposedList<Slot> slots
```

#### Field Value

**Type:** Spine.ExposedList{Spine.Slot}

### time

```csharp
internal float time
```

#### Field Value

**Type:** System.Single

### transformConstraints

```csharp
internal ExposedList<TransformConstraint> transformConstraints
```

#### Field Value

**Type:** Spine.ExposedList{Spine.TransformConstraint}

### updateCache

```csharp
internal ExposedList<IUpdatable> updateCache
```

#### Field Value

**Type:** Spine.ExposedList{Spine.IUpdatable}

### updateCacheReset

```csharp
internal ExposedList<Bone> updateCacheReset
```

#### Field Value

**Type:** Spine.ExposedList{Spine.Bone}

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

### Bones

```csharp
public ExposedList<Bone> Bones { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.Bone}

### Data

```csharp
public SkeletonData Data { get; }
```

#### Property Value

**Type:** Spine.SkeletonData

### DrawOrder

```csharp
public ExposedList<Slot> DrawOrder { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.Slot}

### FlipX

```csharp
public bool FlipX { get; set; }
```

#### Property Value

**Type:** System.Boolean

### FlipY

```csharp
public bool FlipY { get; set; }
```

#### Property Value

**Type:** System.Boolean

### G

```csharp
public float G { get; set; }
```

#### Property Value

**Type:** System.Single

### IkConstraints

```csharp
public ExposedList<IkConstraint> IkConstraints { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.IkConstraint}

### PathConstraints

```csharp
public ExposedList<PathConstraint> PathConstraints { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.PathConstraint}

### R

```csharp
public float R { get; set; }
```

#### Property Value

**Type:** System.Single

### RootBone

```csharp
public Bone RootBone { get; }
```

#### Property Value

**Type:** Spine.Bone

### Skin

```csharp
public Skin Skin { get; set; }
```

#### Property Value

**Type:** Spine.Skin

### Slots

```csharp
public ExposedList<Slot> Slots { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.Slot}

### Time

```csharp
public float Time { get; set; }
```

#### Property Value

**Type:** System.Single

### TransformConstraints

```csharp
public ExposedList<TransformConstraint> TransformConstraints { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.TransformConstraint}

### UpdateCacheList

```csharp
public ExposedList<IUpdatable> UpdateCacheList { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.IUpdatable}

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

### FindBone(string)

```csharp
public Bone FindBone(string boneName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `boneName` | `System.String` |  |

#### Returns

**Type:** Spine.Bone

### FindBoneIndex(string)

```csharp
public int FindBoneIndex(string boneName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `boneName` | `System.String` |  |

#### Returns

**Type:** System.Int32

### FindIkConstraint(string)

```csharp
public IkConstraint FindIkConstraint(string constraintName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraintName` | `System.String` |  |

#### Returns

**Type:** Spine.IkConstraint

### FindPathConstraint(string)

```csharp
public PathConstraint FindPathConstraint(string constraintName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraintName` | `System.String` |  |

#### Returns

**Type:** Spine.PathConstraint

### FindSlot(string)

```csharp
public Slot FindSlot(string slotName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotName` | `System.String` |  |

#### Returns

**Type:** Spine.Slot

### FindSlotIndex(string)

```csharp
public int FindSlotIndex(string slotName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotName` | `System.String` |  |

#### Returns

**Type:** System.Int32

### FindTransformConstraint(string)

```csharp
public TransformConstraint FindTransformConstraint(string constraintName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraintName` | `System.String` |  |

#### Returns

**Type:** Spine.TransformConstraint

### GetAttachment(int, string)

```csharp
public Attachment GetAttachment(int slotIndex, string attachmentName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotIndex` | `System.Int32` |  |
| `attachmentName` | `System.String` |  |

#### Returns

**Type:** Spine.Attachment

### GetAttachment(string, string)

```csharp
public Attachment GetAttachment(string slotName, string attachmentName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotName` | `System.String` |  |
| `attachmentName` | `System.String` |  |

#### Returns

**Type:** Spine.Attachment

### GetBounds(out float, out float, out float, out float, ref float[])

```csharp
public void GetBounds(out float x, out float y, out float width, out float height, ref float[] vertexBuffer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Single` |  |
| `y` | `System.Single` |  |
| `width` | `System.Single` |  |
| `height` | `System.Single` |  |
| `vertexBuffer` | `System.Single[]` |  |

### SetAttachment(string, string)

```csharp
public void SetAttachment(string slotName, string attachmentName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotName` | `System.String` |  |
| `attachmentName` | `System.String` |  |

### SetBonesToSetupPose()

```csharp
public void SetBonesToSetupPose()
```

### SetSkin(Skin)

```csharp
public void SetSkin(Skin newSkin)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `newSkin` | `Spine.Skin` |  |

### SetSkin(string)

```csharp
public void SetSkin(string skinName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skinName` | `System.String` |  |

### SetSlotsToSetupPose()

```csharp
public void SetSlotsToSetupPose()
```

### SetToSetupPose()

```csharp
public void SetToSetupPose()
```

### SortBone(Bone)

```csharp
private void SortBone(Bone bone)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |

### SortIkConstraint(IkConstraint)

```csharp
private void SortIkConstraint(IkConstraint constraint)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraint` | `Spine.IkConstraint` |  |

### SortPathConstraint(PathConstraint)

```csharp
private void SortPathConstraint(PathConstraint constraint)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraint` | `Spine.PathConstraint` |  |

### SortPathConstraintAttachment(Attachment, Bone)

```csharp
private void SortPathConstraintAttachment(Attachment attachment, Bone slotBone)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attachment` | `Spine.Attachment` |  |
| `slotBone` | `Spine.Bone` |  |

### SortPathConstraintAttachment(Skin, int, Bone)

```csharp
private void SortPathConstraintAttachment(Skin skin, int slotIndex, Bone slotBone)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `slotIndex` | `System.Int32` |  |
| `slotBone` | `Spine.Bone` |  |

### SortReset(ExposedList<Bone>)

```csharp
private static void SortReset(ExposedList<Bone> bones)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bones` | `Spine.ExposedList{Spine.Bone}` |  |

### SortTransformConstraint(TransformConstraint)

```csharp
private void SortTransformConstraint(TransformConstraint constraint)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraint` | `Spine.TransformConstraint` |  |

### Update(float)

```csharp
public void Update(float delta)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `delta` | `System.Single` |  |

### UpdateCache()

```csharp
public void UpdateCache()
```

### UpdateWorldTransform()

```csharp
public void UpdateWorldTransform()
```
