# Class AtlasUtilities

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine-Unity) . [Modules](/api/Spine-Unity-Modules) . [AttachmentTools](/api/Spine-Unity-Modules-AttachmentTools)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class AtlasUtilities
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AtlasUtilities

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Methods

### ClearCache()

```csharp
public static void ClearCache()
```

### GetRepackedAttachments(List<Attachment>, List<Attachment>, Material, out Material, out Texture2D, int, int, TextureFormat, bool, string, bool)

```csharp
public static void GetRepackedAttachments(List<Attachment> sourceAttachments, List<Attachment> outputAttachments, Material materialPropertySource, out Material outputMaterial, out Texture2D outputTexture, int maxAtlasSize = 1024, int padding = 2, TextureFormat textureFormat = TextureFormat.RGBA32, bool mipmaps = false, string newAssetName = "Repacked Attachments", bool clearCache = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sourceAttachments` | `System.Collections.Generic.List{Spine.Attachment}` |  |
| `outputAttachments` | `System.Collections.Generic.List{Spine.Attachment}` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |
| `outputMaterial` | `UnityEngine.Material` |  |
| `outputTexture` | `UnityEngine.Texture2D` |  |
| `maxAtlasSize` | `System.Int32` |  |
| `padding` | `System.Int32` |  |
| `textureFormat` | `UnityEngine.TextureFormat` |  |
| `mipmaps` | `System.Boolean` |  |
| `newAssetName` | `System.String` |  |
| `clearCache` | `System.Boolean` |  |

### GetRepackedSkin(Skin, string, Material, out Material, out Texture2D, int, int, TextureFormat, bool)

```csharp
public static Skin GetRepackedSkin(this Skin o, string newName, Material materialPropertySource, out Material outputMaterial, out Texture2D outputTexture, int maxAtlasSize = 1024, int padding = 2, TextureFormat textureFormat = TextureFormat.RGBA32, bool mipmaps = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.Skin` |  |
| `newName` | `System.String` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |
| `outputMaterial` | `UnityEngine.Material` |  |
| `outputTexture` | `UnityEngine.Texture2D` |  |
| `maxAtlasSize` | `System.Int32` |  |
| `padding` | `System.Int32` |  |
| `textureFormat` | `UnityEngine.TextureFormat` |  |
| `mipmaps` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Skin

### GetRepackedSkin(Skin, string, Shader, out Material, out Texture2D, int, int, TextureFormat, bool, Material, bool)

```csharp
public static Skin GetRepackedSkin(this Skin o, string newName, Shader shader, out Material outputMaterial, out Texture2D outputTexture, int maxAtlasSize = 1024, int padding = 2, TextureFormat textureFormat = TextureFormat.RGBA32, bool mipmaps = false, Material materialPropertySource = null, bool clearCache = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.Skin` |  |
| `newName` | `System.String` |  |
| `shader` | `UnityEngine.Shader` |  |
| `outputMaterial` | `UnityEngine.Material` |  |
| `outputTexture` | `UnityEngine.Texture2D` |  |
| `maxAtlasSize` | `System.Int32` |  |
| `padding` | `System.Int32` |  |
| `textureFormat` | `UnityEngine.TextureFormat` |  |
| `mipmaps` | `System.Boolean` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |
| `clearCache` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Skin

### ToAtlasRegion(Sprite, AtlasPage)

```csharp
public static AtlasRegion ToAtlasRegion(this Sprite s, AtlasPage page)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `UnityEngine.Sprite` |  |
| `page` | `Spine.AtlasPage` |  |

#### Returns

**Type:** Spine.AtlasRegion

### ToAtlasRegion(Sprite, Material)

```csharp
public static AtlasRegion ToAtlasRegion(this Sprite s, Material material)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `UnityEngine.Sprite` |  |
| `material` | `UnityEngine.Material` |  |

#### Returns

**Type:** Spine.AtlasRegion

### ToAtlasRegion(Texture2D, Material, float)

```csharp
public static AtlasRegion ToAtlasRegion(this Texture2D t, Material materialPropertySource, float scale = 0.01)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `UnityEngine.Texture2D` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** Spine.AtlasRegion

### ToAtlasRegion(Texture2D, Shader, float, Material)

```csharp
public static AtlasRegion ToAtlasRegion(this Texture2D t, Shader shader, float scale = 0.01, Material materialPropertySource = null)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `UnityEngine.Texture2D` |  |
| `shader` | `UnityEngine.Shader` |  |
| `scale` | `System.Single` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |

#### Returns

**Type:** Spine.AtlasRegion

### ToAtlasRegionPMAClone(Sprite, Material, TextureFormat, bool)

```csharp
public static AtlasRegion ToAtlasRegionPMAClone(this Sprite s, Material materialPropertySource, TextureFormat textureFormat = TextureFormat.RGBA32, bool mipmaps = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `UnityEngine.Sprite` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |
| `textureFormat` | `UnityEngine.TextureFormat` |  |
| `mipmaps` | `System.Boolean` |  |

#### Returns

**Type:** Spine.AtlasRegion

### ToAtlasRegionPMAClone(Sprite, Shader, TextureFormat, bool, Material)

```csharp
public static AtlasRegion ToAtlasRegionPMAClone(this Sprite s, Shader shader, TextureFormat textureFormat = TextureFormat.RGBA32, bool mipmaps = false, Material materialPropertySource = null)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `UnityEngine.Sprite` |  |
| `shader` | `UnityEngine.Shader` |  |
| `textureFormat` | `UnityEngine.TextureFormat` |  |
| `mipmaps` | `System.Boolean` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |

#### Returns

**Type:** Spine.AtlasRegion

### ToAtlasRegionPMAClone(Texture2D, Material, TextureFormat, bool)

```csharp
public static AtlasRegion ToAtlasRegionPMAClone(this Texture2D t, Material materialPropertySource, TextureFormat textureFormat = TextureFormat.RGBA32, bool mipmaps = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `UnityEngine.Texture2D` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |
| `textureFormat` | `UnityEngine.TextureFormat` |  |
| `mipmaps` | `System.Boolean` |  |

#### Returns

**Type:** Spine.AtlasRegion

### ToAtlasRegionPMAClone(Texture2D, Shader, TextureFormat, bool, Material)

```csharp
public static AtlasRegion ToAtlasRegionPMAClone(this Texture2D t, Shader shader, TextureFormat textureFormat = TextureFormat.RGBA32, bool mipmaps = false, Material materialPropertySource = null)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `UnityEngine.Texture2D` |  |
| `shader` | `UnityEngine.Shader` |  |
| `textureFormat` | `UnityEngine.TextureFormat` |  |
| `mipmaps` | `System.Boolean` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |

#### Returns

**Type:** Spine.AtlasRegion

### ToSpineAtlasPage(Material)

```csharp
public static AtlasPage ToSpineAtlasPage(this Material m)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `m` | `UnityEngine.Material` |  |

#### Returns

**Type:** Spine.AtlasPage

### ToSprite(AtlasRegion, float)

```csharp
public static Sprite ToSprite(this AtlasRegion ar, float pixelsPerUnit = 100)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ar` | `Spine.AtlasRegion` |  |
| `pixelsPerUnit` | `System.Single` |  |

#### Returns

**Type:** UnityEngine.Sprite

### ToTexture(AtlasRegion, bool, TextureFormat, bool)

```csharp
public static Texture2D ToTexture(this AtlasRegion ar, bool applyImmediately = true, TextureFormat textureFormat = TextureFormat.RGBA32, bool mipmaps = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ar` | `Spine.AtlasRegion` |  |
| `applyImmediately` | `System.Boolean` |  |
| `textureFormat` | `UnityEngine.TextureFormat` |  |
| `mipmaps` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.Texture2D
