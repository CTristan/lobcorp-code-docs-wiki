# Class AttachmentRegionExtensions

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine-Unity) . [Modules](/api/Spine-Unity-Modules) . [AttachmentTools](/api/Spine-Unity-Modules-AttachmentTools)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class AttachmentRegionExtensions
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AttachmentRegionExtensions

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Methods

### GetRegion(Attachment)

```csharp
public static AtlasRegion GetRegion(this Attachment attachment)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attachment` | `Spine.Attachment` |  |

#### Returns

**Type:** Spine.AtlasRegion

### GetRegion(MeshAttachment)

```csharp
public static AtlasRegion GetRegion(this MeshAttachment meshAttachment)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `meshAttachment` | `Spine.MeshAttachment` |  |

#### Returns

**Type:** Spine.AtlasRegion

### GetRegion(RegionAttachment)

```csharp
public static AtlasRegion GetRegion(this RegionAttachment regionAttachment)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `regionAttachment` | `Spine.RegionAttachment` |  |

#### Returns

**Type:** Spine.AtlasRegion

### SetPositionOffset(RegionAttachment, float, float)

```csharp
public static void SetPositionOffset(this RegionAttachment regionAttachment, float x, float y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `regionAttachment` | `Spine.RegionAttachment` |  |
| `x` | `System.Single` |  |
| `y` | `System.Single` |  |

### SetPositionOffset(RegionAttachment, Vector2)

```csharp
public static void SetPositionOffset(this RegionAttachment regionAttachment, Vector2 offset)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `regionAttachment` | `Spine.RegionAttachment` |  |
| `offset` | `UnityEngine.Vector2` |  |

### SetRegion(Attachment, AtlasRegion, bool)

```csharp
public static void SetRegion(this Attachment attachment, AtlasRegion region, bool updateOffset = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attachment` | `Spine.Attachment` |  |
| `region` | `Spine.AtlasRegion` |  |
| `updateOffset` | `System.Boolean` |  |

### SetRegion(MeshAttachment, AtlasRegion, bool)

```csharp
public static void SetRegion(this MeshAttachment attachment, AtlasRegion region, bool updateUVs = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attachment` | `Spine.MeshAttachment` |  |
| `region` | `Spine.AtlasRegion` |  |
| `updateUVs` | `System.Boolean` |  |

### SetRegion(RegionAttachment, AtlasRegion, bool)

```csharp
public static void SetRegion(this RegionAttachment attachment, AtlasRegion region, bool updateOffset = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attachment` | `Spine.RegionAttachment` |  |
| `region` | `Spine.AtlasRegion` |  |
| `updateOffset` | `System.Boolean` |  |

### SetRotation(RegionAttachment, float)

```csharp
public static void SetRotation(this RegionAttachment regionAttachment, float rotation)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `regionAttachment` | `Spine.RegionAttachment` |  |
| `rotation` | `System.Single` |  |

### SetScale(RegionAttachment, float, float)

```csharp
public static void SetScale(this RegionAttachment regionAttachment, float x, float y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `regionAttachment` | `Spine.RegionAttachment` |  |
| `x` | `System.Single` |  |
| `y` | `System.Single` |  |

### SetScale(RegionAttachment, Vector2)

```csharp
public static void SetScale(this RegionAttachment regionAttachment, Vector2 scale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `regionAttachment` | `Spine.RegionAttachment` |  |
| `scale` | `UnityEngine.Vector2` |  |

### ToRegionAttachment(AtlasRegion, string, float, float)

```csharp
public static RegionAttachment ToRegionAttachment(this AtlasRegion region, string attachmentName, float scale = 0.01, float rotation = 0)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `Spine.AtlasRegion` |  |
| `attachmentName` | `System.String` |  |
| `scale` | `System.Single` |  |
| `rotation` | `System.Single` |  |

#### Returns

**Type:** Spine.RegionAttachment

### ToRegionAttachment(Sprite, AtlasPage, float)

```csharp
public static RegionAttachment ToRegionAttachment(this Sprite sprite, AtlasPage page, float rotation = 0)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sprite` | `UnityEngine.Sprite` |  |
| `page` | `Spine.AtlasPage` |  |
| `rotation` | `System.Single` |  |

#### Returns

**Type:** Spine.RegionAttachment

### ToRegionAttachment(Sprite, Material, float)

```csharp
public static RegionAttachment ToRegionAttachment(this Sprite sprite, Material material, float rotation = 0)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sprite` | `UnityEngine.Sprite` |  |
| `material` | `UnityEngine.Material` |  |
| `rotation` | `System.Single` |  |

#### Returns

**Type:** Spine.RegionAttachment

### ToRegionAttachmentPMAClone(Sprite, Material, TextureFormat, bool, float)

```csharp
public static RegionAttachment ToRegionAttachmentPMAClone(this Sprite sprite, Material materialPropertySource, TextureFormat textureFormat = TextureFormat.RGBA32, bool mipmaps = false, float rotation = 0)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sprite` | `UnityEngine.Sprite` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |
| `textureFormat` | `UnityEngine.TextureFormat` |  |
| `mipmaps` | `System.Boolean` |  |
| `rotation` | `System.Single` |  |

#### Returns

**Type:** Spine.RegionAttachment

### ToRegionAttachmentPMAClone(Sprite, Shader, TextureFormat, bool, Material, float)

```csharp
public static RegionAttachment ToRegionAttachmentPMAClone(this Sprite sprite, Shader shader, TextureFormat textureFormat = TextureFormat.RGBA32, bool mipmaps = false, Material materialPropertySource = null, float rotation = 0)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sprite` | `UnityEngine.Sprite` |  |
| `shader` | `UnityEngine.Shader` |  |
| `textureFormat` | `UnityEngine.TextureFormat` |  |
| `mipmaps` | `System.Boolean` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |
| `rotation` | `System.Single` |  |

#### Returns

**Type:** Spine.RegionAttachment
