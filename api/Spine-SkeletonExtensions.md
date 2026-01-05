# Class SkeletonExtensions

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class SkeletonExtensions
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkeletonExtensions

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Methods

### FindAttachmentsForSlot(Skin, string, SkeletonData, List<Attachment>)

```csharp
public static void FindAttachmentsForSlot(this Skin skin, string slotName, SkeletonData skeletonData, List<Attachment> results)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `slotName` | `System.String` |  |
| `skeletonData` | `Spine.SkeletonData` |  |
| `results` | `System.Collections.Generic.List{Spine.Attachment}` |  |

### FindNamesForSlot(Skin, string, SkeletonData, List<string>)

```csharp
public static void FindNamesForSlot(this Skin skin, string slotName, SkeletonData skeletonData, List<string> results)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `slotName` | `System.String` |  |
| `skeletonData` | `Spine.SkeletonData` |  |
| `results` | `System.Collections.Generic.List{System.String}` |  |

### InheritsRotation(TransformMode)

```csharp
public static bool InheritsRotation(this TransformMode mode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mode` | `Spine.TransformMode` |  |

#### Returns

**Type:** System.Boolean

### InheritsScale(TransformMode)

```csharp
public static bool InheritsScale(this TransformMode mode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mode` | `Spine.TransformMode` |  |

#### Returns

**Type:** System.Boolean

### IsRenderable(Attachment)

```csharp
public static bool IsRenderable(this Attachment a)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Spine.Attachment` |  |

#### Returns

**Type:** System.Boolean

### IsWeighted(VertexAttachment)

```csharp
public static bool IsWeighted(this VertexAttachment va)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `va` | `Spine.VertexAttachment` |  |

#### Returns

**Type:** System.Boolean

### PoseSkeleton(Animation, Skeleton, float, bool)

```csharp
public static void PoseSkeleton(this Animation animation, Skeleton skeleton, float time, bool loop = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animation` | `Spine.Animation` |  |
| `skeleton` | `Spine.Skeleton` |  |
| `time` | `System.Single` |  |
| `loop` | `System.Boolean` |  |

### PoseWithAnimation(Skeleton, string, float, bool)

```csharp
public static void PoseWithAnimation(this Skeleton skeleton, string animationName, float time, bool loop = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `animationName` | `System.String` |  |
| `time` | `System.Single` |  |
| `loop` | `System.Boolean` |  |

### SetAttachmentToSetupPose(Slot)

```csharp
public static void SetAttachmentToSetupPose(this Slot slot)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Spine.Slot` |  |

### SetColorToSetupPose(Slot)

```csharp
public static void SetColorToSetupPose(this Slot slot)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Spine.Slot` |  |

### SetDrawOrderToSetupPose(Skeleton)

```csharp
public static void SetDrawOrderToSetupPose(this Skeleton skeleton)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |

### SetKeyedItemsToSetupPose(Animation, Skeleton)

```csharp
public static void SetKeyedItemsToSetupPose(this Animation animation, Skeleton skeleton)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animation` | `Spine.Animation` |  |
| `skeleton` | `Spine.Skeleton` |  |

### SetSlotAttachmentToSetupPose(Skeleton, int)

```csharp
public static void SetSlotAttachmentToSetupPose(this Skeleton skeleton, int slotIndex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `slotIndex` | `System.Int32` |  |
