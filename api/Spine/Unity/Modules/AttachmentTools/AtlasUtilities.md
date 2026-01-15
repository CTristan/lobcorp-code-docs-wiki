---
uid: Spine.Unity.Modules.AttachmentTools.AtlasUtilities
canonical_path: /api/Spine/Unity/Modules/AttachmentTools/AtlasUtilities
---

# Class AtlasUtilities

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity) . [Modules](/api/Spine/Unity/Modules) . [AttachmentTools](/api/Spine/Unity/Modules/AttachmentTools)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class AtlasUtilities
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AtlasUtilities

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Fields

### CachedRegionTextures

```csharp
private static Dictionary<AtlasRegion, Texture2D> CachedRegionTextures
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{Spine.AtlasRegion,UnityEngine.Texture2D}

### CachedRegionTexturesList

```csharp
private static List<Texture2D> CachedRegionTexturesList
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Texture2D}

### DefaultMipmapBias

```csharp
internal const float DefaultMipmapBias = -0.5
```

#### Field Value

**Type:** System.Single

### DefaultScale

```csharp
internal const float DefaultScale = 0.01
```

#### Field Value

**Type:** System.Single

### SpineTextureFormat

```csharp
internal const TextureFormat SpineTextureFormat = RGBA32
```

#### Field Value

**Type:** UnityEngine.TextureFormat

### UseMipMaps

```csharp
internal const bool UseMipMaps = false
```

#### Field Value

**Type:** System.Boolean

## Methods

### ApplyPMA(Texture2D, bool)

```csharp
private static void ApplyPMA(this Texture2D texture, bool applyImmediately = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `texture` | `UnityEngine.Texture2D` |  |
| `applyImmediately` | `System.Boolean` |  |

### ClearCache()

```csharp
public static void ClearCache()
```

### GetAtlasRegion(Attachment)

```csharp
private static AtlasRegion GetAtlasRegion(this Attachment a)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Spine.Attachment` |  |

#### Returns

**Type:** Spine.AtlasRegion

### GetClone(Texture2D, bool, TextureFormat, bool)

```csharp
private static Texture2D GetClone(this Texture2D t, bool applyImmediately = true, TextureFormat textureFormat = TextureFormat.RGBA32, bool mipmaps = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `UnityEngine.Texture2D` |  |
| `applyImmediately` | `System.Boolean` |  |
| `textureFormat` | `UnityEngine.TextureFormat` |  |
| `mipmaps` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.Texture2D

### GetMainTexture(AtlasRegion)

```csharp
private static Texture2D GetMainTexture(this AtlasRegion region)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `Spine.AtlasRegion` |  |

#### Returns

**Type:** UnityEngine.Texture2D

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

### GetSpineAtlasRect(AtlasRegion, bool)

```csharp
private static Rect GetSpineAtlasRect(this AtlasRegion region, bool includeRotate = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `Spine.AtlasRegion` |  |
| `includeRotate` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.Rect

### GetUnityRect(AtlasRegion)

```csharp
private static Rect GetUnityRect(this AtlasRegion region)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `Spine.AtlasRegion` |  |

#### Returns

**Type:** UnityEngine.Rect

### GetUnityRect(AtlasRegion, int)

```csharp
private static Rect GetUnityRect(this AtlasRegion region, int textureHeight)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `Spine.AtlasRegion` |  |
| `textureHeight` | `System.Int32` |  |

#### Returns

**Type:** UnityEngine.Rect

### InverseLerp(float, float, float)

```csharp
private static float InverseLerp(float a, float b, float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `System.Single` |  |
| `b` | `System.Single` |  |
| `value` | `System.Single` |  |

#### Returns

**Type:** System.Single

### IsRenderable(Attachment)

```csharp
private static bool IsRenderable(Attachment a)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Spine.Attachment` |  |

#### Returns

**Type:** System.Boolean

### SpineUnityFlipRect(Rect, int)

```csharp
private static Rect SpineUnityFlipRect(this Rect rect, int textureHeight)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rect` | `UnityEngine.Rect` |  |
| `textureHeight` | `System.Int32` |  |

#### Returns

**Type:** UnityEngine.Rect

### TextureRectToUVRect(Rect, int, int)

```csharp
private static Rect TextureRectToUVRect(Rect textureRect, int texWidth, int texHeight)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `textureRect` | `UnityEngine.Rect` |  |
| `texWidth` | `System.Int32` |  |
| `texHeight` | `System.Int32` |  |

#### Returns

**Type:** UnityEngine.Rect

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

### ToAtlasRegion(Sprite, bool)

```csharp
internal static AtlasRegion ToAtlasRegion(this Sprite s, bool isolatedTexture = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `UnityEngine.Sprite` |  |
| `isolatedTexture` | `System.Boolean` |  |

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

### ToTexture(Sprite, bool, TextureFormat, bool)

```csharp
private static Texture2D ToTexture(this Sprite s, bool applyImmediately = true, TextureFormat textureFormat = TextureFormat.RGBA32, bool mipmaps = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `UnityEngine.Sprite` |  |
| `applyImmediately` | `System.Boolean` |  |
| `textureFormat` | `UnityEngine.TextureFormat` |  |
| `mipmaps` | `System.Boolean` |  |

#### Returns

**Type:** UnityEngine.Texture2D

### UVRectToAtlasRegion(Rect, string, AtlasPage, float, float, bool)

```csharp
private static AtlasRegion UVRectToAtlasRegion(Rect uvRect, string name, AtlasPage page, float offsetX, float offsetY, bool rotate)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `uvRect` | `UnityEngine.Rect` |  |
| `name` | `System.String` |  |
| `page` | `Spine.AtlasPage` |  |
| `offsetX` | `System.Single` |  |
| `offsetY` | `System.Single` |  |
| `rotate` | `System.Boolean` |  |

#### Returns

**Type:** Spine.AtlasRegion

### UVRectToTextureRect(Rect, int, int)

```csharp
private static Rect UVRectToTextureRect(Rect uvRect, int texWidth, int texHeight)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `uvRect` | `UnityEngine.Rect` |  |
| `texWidth` | `System.Int32` |  |
| `texHeight` | `System.Int32` |  |

#### Returns

**Type:** UnityEngine.Rect
