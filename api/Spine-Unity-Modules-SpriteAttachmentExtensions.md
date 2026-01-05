# Class SpriteAttachmentExtensions

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine-Unity) . [Modules](/api/Spine-Unity-Modules)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class SpriteAttachmentExtensions
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpriteAttachmentExtensions

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Methods

### AddUnitySprite(SkeletonData, string, Sprite, string, Shader, bool, float)

```csharp
[Obsolete]
public static RegionAttachment AddUnitySprite(this SkeletonData skeletonData, string slotName, Sprite sprite, string skinName, Shader shader, bool applyPMA, float rotation = 0)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonData` | `Spine.SkeletonData` |  |
| `slotName` | `System.String` |  |
| `sprite` | `UnityEngine.Sprite` |  |
| `skinName` | `System.String` |  |
| `shader` | `UnityEngine.Shader` |  |
| `applyPMA` | `System.Boolean` |  |
| `rotation` | `System.Single` |  |

#### Returns

**Type:** Spine.RegionAttachment

### AddUnitySprite(SkeletonData, string, Sprite, string, string, bool, float)

```csharp
[Obsolete]
public static RegionAttachment AddUnitySprite(this SkeletonData skeletonData, string slotName, Sprite sprite, string skinName = "", string shaderName = "Spine/Skeleton", bool applyPMA = true, float rotation = 0)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonData` | `Spine.SkeletonData` |  |
| `slotName` | `System.String` |  |
| `sprite` | `UnityEngine.Sprite` |  |
| `skinName` | `System.String` |  |
| `shaderName` | `System.String` |  |
| `applyPMA` | `System.Boolean` |  |
| `rotation` | `System.Single` |  |

#### Returns

**Type:** Spine.RegionAttachment

### AttachUnitySprite(Skeleton, string, Sprite, Shader, bool, float)

```csharp
[Obsolete]
public static RegionAttachment AttachUnitySprite(this Skeleton skeleton, string slotName, Sprite sprite, Shader shader, bool applyPMA, float rotation = 0)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `slotName` | `System.String` |  |
| `sprite` | `UnityEngine.Sprite` |  |
| `shader` | `UnityEngine.Shader` |  |
| `applyPMA` | `System.Boolean` |  |
| `rotation` | `System.Single` |  |

#### Returns

**Type:** Spine.RegionAttachment

### AttachUnitySprite(Skeleton, string, Sprite, string, bool, float)

```csharp
[Obsolete]
public static RegionAttachment AttachUnitySprite(this Skeleton skeleton, string slotName, Sprite sprite, string shaderName = "Spine/Skeleton", bool applyPMA = true, float rotation = 0)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `slotName` | `System.String` |  |
| `sprite` | `UnityEngine.Sprite` |  |
| `shaderName` | `System.String` |  |
| `applyPMA` | `System.Boolean` |  |
| `rotation` | `System.Single` |  |

#### Returns

**Type:** Spine.RegionAttachment
