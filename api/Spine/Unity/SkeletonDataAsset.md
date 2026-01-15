---
uid: Spine.Unity.SkeletonDataAsset
canonical_path: /api/Spine/Unity/SkeletonDataAsset
---

# Class SkeletonDataAsset

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkeletonDataAsset : ScriptableObject
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [ScriptableObject](#) → SkeletonDataAsset

## Inherited Members
[Internal_CreateScriptableObject(ScriptableObject)](#), [SetDirty()](#), [INTERNAL_CALL_SetDirty(ScriptableObject)](#), [CreateInstance(string)](https://learn.microsoft.com/dotnet/api/system.string), [CreateInstance(Type)](https://learn.microsoft.com/dotnet/api/system.type), [CreateInstanceFromType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [CreateInstance<T>()](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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

### skeletonData

```csharp
private SkeletonData skeletonData
```

#### Field Value

**Type:** Spine.SkeletonData

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

### stateData

```csharp
private AnimationStateData stateData
```

#### Field Value

**Type:** Spine.AnimationStateData

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

### GetAtlasArray()

```csharp
internal Atlas[] GetAtlasArray()
```

#### Returns

**Type:** Spine.Atlas[]

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

### InitializeWithData(SkeletonData)

```csharp
internal void InitializeWithData(SkeletonData sd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sd` | `Spine.SkeletonData` |  |

### ReadSkeletonData(byte[], AttachmentLoader, float)

```csharp
internal static SkeletonData ReadSkeletonData(byte[] bytes, AttachmentLoader attachmentLoader, float scale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bytes` | `System.Byte[]` |  |
| `attachmentLoader` | `Spine.AttachmentLoader` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** Spine.SkeletonData

### ReadSkeletonData(string, AttachmentLoader, float)

```csharp
internal static SkeletonData ReadSkeletonData(string text, AttachmentLoader attachmentLoader, float scale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |
| `attachmentLoader` | `Spine.AttachmentLoader` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** Spine.SkeletonData

### Reset()

```csharp
private void Reset()
```
