---
uid: Spine.Unity.Modules.AttachmentTools.SkinUtilities
canonical_path: /api/Spine/Unity/Modules/AttachmentTools/SkinUtilities
---

# Class SkinUtilities

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity) . [Modules](/api/Spine/Unity/Modules) . [AttachmentTools](/api/Spine/Unity/Modules/AttachmentTools)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class SkinUtilities
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkinUtilities

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Methods

### Append(Skin, Skin)

```csharp
public static void Append(this Skin destination, Skin source)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `destination` | `Spine.Skin` |  |
| `source` | `Spine.Skin` |  |

### Clear(Skin)

```csharp
public static void Clear(this Skin skin)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |

### CopyTo(Skin, Skin, bool, bool, bool)

```csharp
public static void CopyTo(this Skin source, Skin destination, bool overwrite, bool cloneAttachments, bool cloneMeshesAsLinked = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `source` | `Spine.Skin` |  |
| `destination` | `Spine.Skin` |  |
| `overwrite` | `System.Boolean` |  |
| `cloneAttachments` | `System.Boolean` |  |
| `cloneMeshesAsLinked` | `System.Boolean` |  |

### GetAttachment(Skin, string, string, Skeleton)

```csharp
public static Attachment GetAttachment(this Skin skin, string slotName, string keyName, Skeleton skeleton)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `slotName` | `System.String` |  |
| `keyName` | `System.String` |  |
| `skeleton` | `Spine.Skeleton` |  |

#### Returns

**Type:** Spine.Attachment

### GetClone(Skin)

```csharp
public static Skin GetClone(this Skin original)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `original` | `Spine.Skin` |  |

#### Returns

**Type:** Spine.Skin

### GetClonedSkin(Skeleton, string, bool, bool, bool)

```csharp
public static Skin GetClonedSkin(this Skeleton skeleton, string newSkinName, bool includeDefaultSkin = false, bool cloneAttachments = false, bool cloneMeshesAsLinked = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `newSkinName` | `System.String` |  |
| `includeDefaultSkin` | `System.Boolean` |  |
| `cloneAttachments` | `System.Boolean` |  |
| `cloneMeshesAsLinked` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Skin

### RemoveAttachment(Skin, int, string)

```csharp
public static bool RemoveAttachment(this Skin skin, int slotIndex, string keyName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `slotIndex` | `System.Int32` |  |
| `keyName` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### RemoveAttachment(Skin, string, string, Skeleton)

```csharp
public static bool RemoveAttachment(this Skin skin, string slotName, string keyName, Skeleton skeleton)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `slotName` | `System.String` |  |
| `keyName` | `System.String` |  |
| `skeleton` | `Spine.Skeleton` |  |

#### Returns

**Type:** System.Boolean

### SetAttachment(Skin, int, string, Attachment)

```csharp
public static void SetAttachment(this Skin skin, int slotIndex, string keyName, Attachment attachment)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `slotIndex` | `System.Int32` |  |
| `keyName` | `System.String` |  |
| `attachment` | `Spine.Attachment` |  |

### SetAttachment(Skin, string, string, Attachment, Skeleton)

```csharp
public static void SetAttachment(this Skin skin, string slotName, string keyName, Attachment attachment, Skeleton skeleton)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `slotName` | `System.String` |  |
| `keyName` | `System.String` |  |
| `attachment` | `Spine.Attachment` |  |
| `skeleton` | `Spine.Skeleton` |  |

### UnshareSkin(Skeleton, bool, bool, AnimationState)

```csharp
public static Skin UnshareSkin(this Skeleton skeleton, bool includeDefaultSkin, bool unshareAttachments, AnimationState state = null)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `includeDefaultSkin` | `System.Boolean` |  |
| `unshareAttachments` | `System.Boolean` |  |
| `state` | `Spine.AnimationState` |  |

#### Returns

**Type:** Spine.Skin
