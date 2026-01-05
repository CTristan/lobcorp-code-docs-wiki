# Class DamageParticleEffect

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DamageParticleEffect : EffectInvoker
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [EffectInvoker](/api/EffectInvoker) → DamageParticleEffect

## Inherited Members
[PrefabSrc](/api/EffectInvoker#prefabsrc), [destroyEvent](/api/EffectInvoker#destroyevent), [Invoker(string, MovableObjectNode, float, bool)](/api/EffectInvoker#invoker-string-movableobjectnode-float-bool), [Invoker(string, Vector3, float, bool)](/api/EffectInvoker#invoker-string-vector3-float-bool), [OnDestroy()](/api/EffectInvoker#ondestroy), [Update()](/api/EffectInvoker#update), [SetMovableSetting(MovableObjectNode)](/api/EffectInvoker#setmovablesetting-movableobjectnode), [SetDestroyEvent(OnDestroyEvent)](/api/EffectInvoker#setdestroyevent-ondestroyevent), [Attach()](/api/EffectInvoker#attach), [Dettach()](/api/EffectInvoker#dettach), [IsAttached](/api/EffectInvoker#isattached), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DamageParticleEffect()

```csharp
public DamageParticleEffect()
```

## Fields

### BTypeParticle

```csharp
public List<GameObject> BTypeParticle
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### ParticleSlot

```csharp
[Header("Traits")]
public GameObject ParticleSlot
```

#### Field Value

**Type:** UnityEngine.GameObject

### PTypeParticle

```csharp
public List<GameObject> PTypeParticle
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### RTypeParticle

```csharp
public List<GameObject> RTypeParticle
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### src

```csharp
public const string src = "DamageParticle/DamageParticleParent"
```

#### Field Value

**Type:** System.String

### time

```csharp
public float time
```

#### Field Value

**Type:** System.Single

### WTypeParticle

```csharp
public List<GameObject> WTypeParticle
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

## Methods

### Invoker(UnitModel, RwbpType, DefenseInfo)

```csharp
public static DamageParticleEffect Invoker(UnitModel target, RwbpType type, DefenseInfo defense)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `type` | `Global.RwbpType` |  |
| `defense` | `Global.DefenseInfo` |  |

#### Returns

**Type:** Global.DamageParticleEffect

### Invoker(UnitModel, RwbpType, DefenseInfo, UnitDirection)

```csharp
public static DamageParticleEffect Invoker(UnitModel target, RwbpType type, DefenseInfo defense, UnitDirection dir)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `type` | `Global.RwbpType` |  |
| `defense` | `Global.DefenseInfo` |  |
| `dir` | `Global.UnitDirection` |  |

#### Returns

**Type:** Global.DamageParticleEffect

### Invoker(UnitModel, RwbpType, float, UnitDirection)

```csharp
public static DamageParticleEffect Invoker(UnitModel target, RwbpType type, float defense, UnitDirection dir)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `type` | `Global.RwbpType` |  |
| `defense` | `System.Single` |  |
| `dir` | `Global.UnitDirection` |  |

#### Returns

**Type:** Global.DamageParticleEffect

### Invoker(UnitModel, RwbpType, int)

```csharp
public static DamageParticleEffect Invoker(UnitModel target, RwbpType type, int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `type` | `Global.RwbpType` |  |
| `level` | `System.Int32` |  |

#### Returns

**Type:** Global.DamageParticleEffect

### Invoker(UnitModel, RwbpType, UnitModel)

```csharp
public static DamageParticleEffect Invoker(UnitModel target, RwbpType type, UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `type` | `Global.RwbpType` |  |
| `actor` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.DamageParticleEffect

### Invoker_Weak(UnitModel, RwbpType, UnitModel)

```csharp
public static DamageParticleEffect Invoker_Weak(UnitModel target, RwbpType type, UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `type` | `Global.RwbpType` |  |
| `actor` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.DamageParticleEffect

### LoadDefaultPrefab(UnitModel)

```csharp
public static DamageParticleEffect LoadDefaultPrefab(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.DamageParticleEffect
