# Class DamageEffect

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DamageEffect : EffectInvoker
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [EffectInvoker](/api/EffectInvoker) → DamageEffect

## Inherited Members
[PrefabSrc](/api/EffectInvoker#prefabsrc), [destroyEvent](/api/EffectInvoker#destroyevent), [Invoker(string, MovableObjectNode, float, bool)](/api/EffectInvoker#invoker-string-movableobjectnode-float-bool), [Invoker(string, Vector3, float, bool)](/api/EffectInvoker#invoker-string-vector3-float-bool), [OnDestroy()](/api/EffectInvoker#ondestroy), [SetMovableSetting(MovableObjectNode)](/api/EffectInvoker#setmovablesetting-movableobjectnode), [SetDestroyEvent(OnDestroyEvent)](/api/EffectInvoker#setdestroyevent-ondestroyevent), [Attach()](/api/EffectInvoker#attach), [Dettach()](/api/EffectInvoker#dettach), [IsAttached](/api/EffectInvoker#isattached), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DamageEffect()

```csharp
public DamageEffect()
```

## Fields

### DamageContext

```csharp
public Text DamageContext
```

#### Field Value

**Type:** UnityEngine.UI.Text

### DamageCount

```csharp
public Text DamageCount
```

#### Field Value

**Type:** UnityEngine.UI.Text

### DamageCountOutline

```csharp
public Outline DamageCountOutline
```

#### Field Value

**Type:** UnityEngine.UI.Outline

### DamageFontTexture

```csharp
public Sprite[] DamageFontTexture
```

#### Field Value

**Type:** UnityEngine.Sprite[]

### DamageIcon

```csharp
public Sprite[] DamageIcon
```

#### Field Value

**Type:** UnityEngine.Sprite[]

### DamageIconOut

```csharp
public Sprite[] DamageIconOut
```

#### Field Value

**Type:** UnityEngine.Sprite[]

### DamageTextImage

```csharp
public Sprite[] DamageTextImage
```

#### Field Value

**Type:** UnityEngine.Sprite[]

### DefenseTypeInner

```csharp
public Image DefenseTypeInner
```

#### Field Value

**Type:** UnityEngine.UI.Image

### DefenseTypeText

```csharp
public Image DefenseTypeText
```

#### Field Value

**Type:** UnityEngine.UI.Image

### Fill

```csharp
public Image Fill
```

#### Field Value

**Type:** UnityEngine.UI.Image

### Frame

```csharp
public Image Frame
```

#### Field Value

**Type:** UnityEngine.UI.Image

### Icon

```csharp
public Image Icon
```

#### Field Value

**Type:** UnityEngine.UI.Image

### IconOut

```csharp
public Image IconOut
```

#### Field Value

**Type:** UnityEngine.UI.Image

### Speed

```csharp
public float Speed
```

#### Field Value

**Type:** System.Single

## Methods

### Invoker(MovableObjectNode)

```csharp
public static DamageEffect Invoker(MovableObjectNode mov)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.DamageEffect

### Invoker(MovableObjectNode, float)

```csharp
public static DamageEffect Invoker(MovableObjectNode mov, float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |
| `time` | `System.Single` |  |

#### Returns

**Type:** Global.DamageEffect

### Invoker(MovableObjectNode, RwbpType, int, string)

```csharp
public static DamageEffect Invoker(MovableObjectNode mov, RwbpType type, int Damage, string context)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |
| `type` | `Global.RwbpType` |  |
| `Damage` | `System.Int32` |  |
| `context` | `System.String` |  |

#### Returns

**Type:** Global.DamageEffect

### Invoker(MovableObjectNode, RwbpType, int, string, float)

```csharp
public static DamageEffect Invoker(MovableObjectNode mov, RwbpType type, int Damage, string context, float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |
| `type` | `Global.RwbpType` |  |
| `Damage` | `System.Int32` |  |
| `context` | `System.String` |  |
| `time` | `System.Single` |  |

#### Returns

**Type:** Global.DamageEffect

### Invoker(MovableObjectNode, RwbpType, int, Type, UnitModel)

```csharp
public static DamageEffect Invoker(MovableObjectNode mov, RwbpType type, int Damage, DefenseInfo.Type defense, UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |
| `type` | `Global.RwbpType` |  |
| `Damage` | `System.Int32` |  |
| `defense` | `Global.DefenseInfo.Type` |  |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.DamageEffect

### Invoker(Vector3)

```csharp
public static DamageEffect Invoker(Vector3 pos)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** Global.DamageEffect

### Invoker(Vector3, float)

```csharp
public static DamageEffect Invoker(Vector3 pos, float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `time` | `System.Single` |  |

#### Returns

**Type:** Global.DamageEffect

### Invoker(Vector3, RwbpType, int, Type, UnitModel)

```csharp
public static DamageEffect Invoker(Vector3 pos, RwbpType type, int Damage, DefenseInfo.Type defense, UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `type` | `Global.RwbpType` |  |
| `Damage` | `System.Int32` |  |
| `defense` | `Global.DefenseInfo.Type` |  |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.DamageEffect

### Update()

```csharp
protected override void Update()
```
