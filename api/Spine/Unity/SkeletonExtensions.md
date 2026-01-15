---
uid: Spine.Unity.SkeletonExtensions
canonical_path: /api/Spine/Unity/SkeletonExtensions
---

# Class SkeletonExtensions

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class SkeletonExtensions
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkeletonExtensions

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Fields

### ByteToFloat

```csharp
private const float ByteToFloat = 0.003921569
```

#### Field Value

**Type:** System.Single

## Methods

### GetColor(MeshAttachment)

```csharp
public static Color GetColor(this MeshAttachment a)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Spine.MeshAttachment` |  |

#### Returns

**Type:** UnityEngine.Color

### GetColor(RegionAttachment)

```csharp
public static Color GetColor(this RegionAttachment a)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Spine.RegionAttachment` |  |

#### Returns

**Type:** UnityEngine.Color

### GetColor(Skeleton)

```csharp
public static Color GetColor(this Skeleton s)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `Spine.Skeleton` |  |

#### Returns

**Type:** UnityEngine.Color

### GetLocalPosition(Bone)

```csharp
public static Vector2 GetLocalPosition(this Bone bone)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |

#### Returns

**Type:** UnityEngine.Vector2

### GetLocalQuaternion(Bone)

```csharp
public static Quaternion GetLocalQuaternion(this Bone bone)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |

#### Returns

**Type:** UnityEngine.Quaternion

### GetLocalVertices(VertexAttachment, Slot, Vector2[])

```csharp
public static Vector2[] GetLocalVertices(this VertexAttachment va, Slot slot, Vector2[] buffer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `va` | `Spine.VertexAttachment` |  |
| `slot` | `Spine.Slot` |  |
| `buffer` | `UnityEngine.Vector2[]` |  |

#### Returns

**Type:** UnityEngine.Vector2[]

### GetMaterial(Attachment)

```csharp
public static Material GetMaterial(this Attachment a)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Spine.Attachment` |  |

#### Returns

**Type:** UnityEngine.Material

### GetMatrix4x4(Bone)

```csharp
public static Matrix4x4 GetMatrix4x4(this Bone bone)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |

#### Returns

**Type:** UnityEngine.Matrix4x4

### GetQuaternion(Bone)

```csharp
public static Quaternion GetQuaternion(this Bone bone)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |

#### Returns

**Type:** UnityEngine.Quaternion

### GetSkeletonSpacePosition(Bone)

```csharp
public static Vector2 GetSkeletonSpacePosition(this Bone bone)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |

#### Returns

**Type:** UnityEngine.Vector2

### GetSkeletonSpacePosition(Bone, Vector2)

```csharp
public static Vector2 GetSkeletonSpacePosition(this Bone bone, Vector2 boneLocal)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `boneLocal` | `UnityEngine.Vector2` |  |

#### Returns

**Type:** UnityEngine.Vector2

### GetWorldPosition(Bone, Transform)

```csharp
public static Vector3 GetWorldPosition(this Bone bone, Transform spineGameObjectTransform)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `spineGameObjectTransform` | `UnityEngine.Transform` |  |

#### Returns

**Type:** UnityEngine.Vector3

### GetWorldPosition(Bone, Transform, float)

```csharp
public static Vector3 GetWorldPosition(this Bone bone, Transform spineGameObjectTransform, float positionScale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `spineGameObjectTransform` | `UnityEngine.Transform` |  |
| `positionScale` | `System.Single` |  |

#### Returns

**Type:** UnityEngine.Vector3

### GetWorldPosition(PointAttachment, Bone, Transform)

```csharp
public static Vector3 GetWorldPosition(this PointAttachment attachment, Bone bone, Transform spineGameObjectTransform)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attachment` | `Spine.PointAttachment` |  |
| `bone` | `Spine.Bone` |  |
| `spineGameObjectTransform` | `UnityEngine.Transform` |  |

#### Returns

**Type:** UnityEngine.Vector3

### GetWorldPosition(PointAttachment, Slot, Transform)

```csharp
public static Vector3 GetWorldPosition(this PointAttachment attachment, Slot slot, Transform spineGameObjectTransform)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attachment` | `Spine.PointAttachment` |  |
| `slot` | `Spine.Slot` |  |
| `spineGameObjectTransform` | `UnityEngine.Transform` |  |

#### Returns

**Type:** UnityEngine.Vector3

### GetWorldToLocalMatrix(Bone, out float, out float, out float, out float)

```csharp
public static void GetWorldToLocalMatrix(this Bone bone, out float ia, out float ib, out float ic, out float id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `ia` | `System.Single` |  |
| `ib` | `System.Single` |  |
| `ic` | `System.Single` |  |
| `id` | `System.Single` |  |

### GetWorldVertices(VertexAttachment, Slot, Vector2[])

```csharp
public static Vector2[] GetWorldVertices(this VertexAttachment a, Slot slot, Vector2[] buffer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Spine.VertexAttachment` |  |
| `slot` | `Spine.Slot` |  |
| `buffer` | `UnityEngine.Vector2[]` |  |

#### Returns

**Type:** UnityEngine.Vector2[]

### SetColor(MeshAttachment, Color)

```csharp
public static void SetColor(this MeshAttachment attachment, Color color)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attachment` | `Spine.MeshAttachment` |  |
| `color` | `UnityEngine.Color` |  |

### SetColor(MeshAttachment, Color32)

```csharp
public static void SetColor(this MeshAttachment attachment, Color32 color)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attachment` | `Spine.MeshAttachment` |  |
| `color` | `UnityEngine.Color32` |  |

### SetColor(RegionAttachment, Color)

```csharp
public static void SetColor(this RegionAttachment attachment, Color color)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attachment` | `Spine.RegionAttachment` |  |
| `color` | `UnityEngine.Color` |  |

### SetColor(RegionAttachment, Color32)

```csharp
public static void SetColor(this RegionAttachment attachment, Color32 color)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attachment` | `Spine.RegionAttachment` |  |
| `color` | `UnityEngine.Color32` |  |

### SetColor(Skeleton, Color)

```csharp
public static void SetColor(this Skeleton skeleton, Color color)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `color` | `UnityEngine.Color` |  |

### SetColor(Skeleton, Color32)

```csharp
public static void SetColor(this Skeleton skeleton, Color32 color)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `color` | `UnityEngine.Color32` |  |

### SetColor(Slot, Color)

```csharp
public static void SetColor(this Slot slot, Color color)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Spine.Slot` |  |
| `color` | `UnityEngine.Color` |  |

### SetColor(Slot, Color32)

```csharp
public static void SetColor(this Slot slot, Color32 color)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Spine.Slot` |  |
| `color` | `UnityEngine.Color32` |  |

### SetPosition(Bone, Vector2)

```csharp
public static void SetPosition(this Bone bone, Vector2 position)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `position` | `UnityEngine.Vector2` |  |

### SetPosition(Bone, Vector3)

```csharp
public static void SetPosition(this Bone bone, Vector3 position)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `position` | `UnityEngine.Vector3` |  |

### SetPositionSkeletonSpace(Bone, Vector2)

```csharp
public static Vector2 SetPositionSkeletonSpace(this Bone bone, Vector2 skeletonSpacePosition)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `skeletonSpacePosition` | `UnityEngine.Vector2` |  |

#### Returns

**Type:** UnityEngine.Vector2

### WorldToLocal(Bone, Vector2)

```csharp
public static Vector2 WorldToLocal(this Bone bone, Vector2 worldPosition)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `worldPosition` | `UnityEngine.Vector2` |  |

#### Returns

**Type:** UnityEngine.Vector2
