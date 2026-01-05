# Class AgentSpriteChanger

**Namespace:** [WorkerSpine](/api/WorkerSpine)
**Assembly:** Assembly-CSharp.dll

[`[UnityEngine.RequireComponent]`](#)

```csharp
[RequireComponent(typeof(SkeletonAnimator), typeof(Animator))]
public class AgentSpriteChanger : MonoBehaviour
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → AgentSpriteChanger

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AgentSpriteChanger()

```csharp
public AgentSpriteChanger()
```

## Fields

### animator

```csharp
public Animator animator
```

#### Field Value

**Type:** UnityEngine.Animator

### basic

```csharp
public List<SpriteChangeData> basic
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerSpine.SpriteChangeData}

### clothes

```csharp
public List<SpriteChangeData> clothes
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerSpine.SpriteChangeData}

### CurrentWeapon

```csharp
public Sprite CurrentWeapon
```

#### Field Value

**Type:** UnityEngine.Sprite

### dummy

```csharp
public SpriteChangeData dummy
```

#### Field Value

**Type:** WorkerSpine.SpriteChangeData

### move

```csharp
public SpriteChangeData move
```

#### Field Value

**Type:** WorkerSpine.SpriteChangeData

### positionFix

```csharp
public Vector2 positionFix
```

#### Field Value

**Type:** UnityEngine.Vector2

### repack

```csharp
public bool repack
```

#### Field Value

**Type:** System.Boolean

### repackedShader

```csharp
public Shader repackedShader
```

#### Field Value

**Type:** UnityEngine.Shader

### rotationFix

```csharp
public float rotationFix
```

#### Field Value

**Type:** System.Single

### runtimeAtlas

```csharp
[Header("Do not assign")]
public Texture2D runtimeAtlas
```

#### Field Value

**Type:** UnityEngine.Texture2D

### runtimeMaterial

```csharp
public Material runtimeMaterial
```

#### Field Value

**Type:** UnityEngine.Material

### skeletonAnimator

```csharp
public SkeletonAnimator skeletonAnimator
```

#### Field Value

**Type:** Spine.Unity.SkeletonAnimator

## Methods

### Apply(List<SpriteChangeData>)

```csharp
public void Apply(List<SpriteChangeData> list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.Generic.List{WorkerSpine.SpriteChangeData}` |  |

### Apply(SpriteChangeData)

```csharp
public void Apply(SpriteChangeData data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `WorkerSpine.SpriteChangeData` |  |

### Apply(SpriteChangeData, bool)

```csharp
public void Apply(SpriteChangeData data, bool set)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `WorkerSpine.SpriteChangeData` |  |
| `set` | `System.Boolean` |  |

### ChangeSpineData(Skeleton, Skin, SpriteChangeData)

```csharp
public void ChangeSpineData(Skeleton skeleton, Skin newSkin, SpriteChangeData data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `newSkin` | `Spine.Skin` |  |
| `data` | `WorkerSpine.SpriteChangeData` |  |

### ChangeSpineData(Skeleton, Skin, SpriteChangeData, bool)

```csharp
public void ChangeSpineData(Skeleton skeleton, Skin newSkin, SpriteChangeData data, bool set)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `newSkin` | `Spine.Skin` |  |
| `data` | `WorkerSpine.SpriteChangeData` |  |
| `set` | `System.Boolean` |  |

### ClothesSetting(AtlasLoadData)

```csharp
public void ClothesSetting(AtlasLoadData atlas)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `atlas` | `WorkerSprite.AtlasLoadData` |  |

### LeftWeaponSetting(Sprite, string, string)

```csharp
public void LeftWeaponSetting(Sprite weaponSprite, string slot, string attach)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `weaponSprite` | `UnityEngine.Sprite` |  |
| `slot` | `System.String` |  |
| `attach` | `System.String` |  |

### WeaponSetting(Sprite, string, string)

```csharp
public void WeaponSetting(Sprite weaponSprite, string slot, string attach)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `weaponSprite` | `UnityEngine.Sprite` |  |
| `slot` | `System.String` |  |
| `attach` | `System.String` |  |
