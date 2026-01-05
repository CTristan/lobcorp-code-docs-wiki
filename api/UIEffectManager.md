# Class UIEffectManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UIEffectManager : MonoBehaviour
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → UIEffectManager

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### UIEffectManager()

```csharp
public UIEffectManager()
```

## Fields

### currentModuleAry

```csharp
public ScreenEffectModule[] currentModuleAry
```

#### Field Value

**Type:** Global.ScreenEffectModule[]

### isUsingAry

```csharp
public bool[] isUsingAry
```

#### Field Value

**Type:** System.Boolean[]

### modules

```csharp
public List<ScreenEffectModule> modules
```

#### Field Value

**Type:** System.Collections.Generic.List{ScreenEffectModule}

### renderImage

```csharp
public List<Image> renderImage
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.Image}

### Siren

```csharp
public GameObject Siren
```

#### Field Value

**Type:** UnityEngine.GameObject

## Properties

### instance

```csharp
public static UIEffectManager instance { get; }
```

#### Property Value

**Type:** Global.UIEffectManager

## Methods

### ActivateUIEffect(string, float, int, bool)

```csharp
public void ActivateUIEffect(string targetName, float displayTime, int fps, bool useDefaultImage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetName` | `System.String` |  |
| `displayTime` | `System.Single` |  |
| `fps` | `System.Int32` |  |
| `useDefaultImage` | `System.Boolean` |  |

### Awake()

```csharp
public void Awake()
```

### ChagneSirenSprite(Sprite)

```csharp
public void ChagneSirenSprite(Sprite sprite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sprite` | `UnityEngine.Sprite` |  |

### EndEffect(UIEffectType)

```csharp
public void EndEffect(UIEffectType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.UIEffectType` |  |

### EndSiren()

```csharp
public void EndSiren()
```

### FixedUpdate()

```csharp
public void FixedUpdate()
```

### GetAnimParam(UIEffectType)

```csharp
public string GetAnimParam(UIEffectType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.UIEffectType` |  |

#### Returns

**Type:** System.String

### GetModule(long)

```csharp
public ScreenEffectModule GetModule(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.ScreenEffectModule

### GetModule(string)

```csharp
public ScreenEffectModule GetModule(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** Global.ScreenEffectModule

### OnClickManual()

```csharp
public void OnClickManual()
```

### OnStageStart()

```csharp
public void OnStageStart()
```

### ReturnSirenSprite()

```csharp
public void ReturnSirenSprite()
```

### Start()

```csharp
public void Start()
```

### StartCustomEffect(Sprite[], int)

```csharp
public void StartCustomEffect(Sprite[] spriteSequence, int fps)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spriteSequence` | `UnityEngine.Sprite[]` |  |
| `fps` | `System.Int32` |  |

### StartCustomEffect(Sprite[], int, Callback)

```csharp
public void StartCustomEffect(Sprite[] spriteSequence, int fps, Callback effectFinishCallback)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spriteSequence` | `UnityEngine.Sprite[]` |  |
| `fps` | `System.Int32` |  |
| `effectFinishCallback` | `Global.Callback` |  |

### StartEffect(object, params float[])

```csharp
public void StartEffect(object o, params float[] time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `System.Object` |  |
| `time` | `System.Single[]` |  |

### StartSiren()

```csharp
public void StartSiren()
```
