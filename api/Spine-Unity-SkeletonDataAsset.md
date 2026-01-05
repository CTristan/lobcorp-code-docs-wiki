# Class SkeletonDataAsset

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine-Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkeletonDataAsset : ScriptableObject
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [ScriptableObject](#) → SkeletonDataAsset

## Inherited Members
[SetDirty()](#), [CreateInstance(string)](https://learn.microsoft.com/dotnet/api/system.string), [CreateInstance(Type)](https://learn.microsoft.com/dotnet/api/system.type), [CreateInstance<T>()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SkeletonDataAsset()

```csharp
public SkeletonDataAsset()
```

## Fields

### atlasAssets

```csharp
public AtlasAsset[] atlasAssets
```

#### Field Value

**Type:** Spine.Unity.AtlasAsset[]

### controller

```csharp
public RuntimeAnimatorController controller
```

#### Field Value

**Type:** UnityEngine.RuntimeAnimatorController

### defaultMix

```csharp
public float defaultMix
```

#### Field Value

**Type:** System.Single

### duration

```csharp
public float[] duration
```

#### Field Value

**Type:** System.Single[]

### fromAnimation

```csharp
[SpineAnimation("", "", false)]
public string[] fromAnimation
```

#### Field Value

**Type:** System.String[]

### scale

```csharp
public float scale
```

#### Field Value

**Type:** System.Single

### skeletonJSON

```csharp
public TextAsset skeletonJSON
```

#### Field Value

**Type:** UnityEngine.TextAsset

### skeletonJSON_string

```csharp
public string skeletonJSON_string
```

#### Field Value

**Type:** System.String

### skeletonSKEL_byte

```csharp
public byte[] skeletonSKEL_byte
```

#### Field Value

**Type:** System.Byte[]

### toAnimation

```csharp
[SpineAnimation("", "", false)]
public string[] toAnimation
```

#### Field Value

**Type:** System.String[]

## Properties

### IsLoaded

```csharp
public bool IsLoaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### Clear()

```csharp
public void Clear()
```

### CreateRuntimeInstance(byte[], AtlasAsset, bool, float)

```csharp
public static SkeletonDataAsset CreateRuntimeInstance(byte[] skeletonDataFile, AtlasAsset atlasAsset, bool initialize, float scale = 0.01)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonDataFile` | `System.Byte[]` |  |
| `atlasAsset` | `Spine.Unity.AtlasAsset` |  |
| `initialize` | `System.Boolean` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** Spine.Unity.SkeletonDataAsset

### CreateRuntimeInstance(byte[], AtlasAsset[], bool, float)

```csharp
public static SkeletonDataAsset CreateRuntimeInstance(byte[] skeletonDataFile, AtlasAsset[] atlasAssets, bool initialize, float scale = 0.01)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonDataFile` | `System.Byte[]` |  |
| `atlasAssets` | `Spine.Unity.AtlasAsset[]` |  |
| `initialize` | `System.Boolean` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** Spine.Unity.SkeletonDataAsset

### CreateRuntimeInstance(string, AtlasAsset, bool, float)

```csharp
public static SkeletonDataAsset CreateRuntimeInstance(string skeletonDataFile, AtlasAsset atlasAsset, bool initialize, float scale = 0.01)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonDataFile` | `System.String` |  |
| `atlasAsset` | `Spine.Unity.AtlasAsset` |  |
| `initialize` | `System.Boolean` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** Spine.Unity.SkeletonDataAsset

### CreateRuntimeInstance(string, AtlasAsset[], bool, float)

```csharp
public static SkeletonDataAsset CreateRuntimeInstance(string skeletonDataFile, AtlasAsset[] atlasAssets, bool initialize, float scale = 0.01)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonDataFile` | `System.String` |  |
| `atlasAssets` | `Spine.Unity.AtlasAsset[]` |  |
| `initialize` | `System.Boolean` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** Spine.Unity.SkeletonDataAsset

### CreateRuntimeInstance(TextAsset, AtlasAsset, bool, float)

```csharp
public static SkeletonDataAsset CreateRuntimeInstance(TextAsset skeletonDataFile, AtlasAsset atlasAsset, bool initialize, float scale = 0.01)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonDataFile` | `UnityEngine.TextAsset` |  |
| `atlasAsset` | `Spine.Unity.AtlasAsset` |  |
| `initialize` | `System.Boolean` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** Spine.Unity.SkeletonDataAsset

### CreateRuntimeInstance(TextAsset, AtlasAsset[], bool, float)

```csharp
public static SkeletonDataAsset CreateRuntimeInstance(TextAsset skeletonDataFile, AtlasAsset[] atlasAssets, bool initialize, float scale = 0.01)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonDataFile` | `UnityEngine.TextAsset` |  |
| `atlasAssets` | `Spine.Unity.AtlasAsset[]` |  |
| `initialize` | `System.Boolean` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** Spine.Unity.SkeletonDataAsset

### FillStateData()

```csharp
public void FillStateData()
```

### GetAnimationStateData()

```csharp
public AnimationStateData GetAnimationStateData()
```

#### Returns

**Type:** Spine.AnimationStateData

### GetSkeletonData(bool)

```csharp
public SkeletonData GetSkeletonData(bool quiet)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `quiet` | `System.Boolean` |  |

#### Returns

**Type:** Spine.SkeletonData

### GetSkeletonData_Byte(bool)

```csharp
public SkeletonData GetSkeletonData_Byte(bool quiet)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `quiet` | `System.Boolean` |  |

#### Returns

**Type:** Spine.SkeletonData

### GetSkeletonData_string(bool)

```csharp
public SkeletonData GetSkeletonData_string(bool quiet)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `quiet` | `System.Boolean` |  |

#### Returns

**Type:** Spine.SkeletonData
