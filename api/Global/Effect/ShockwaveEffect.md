---
uid: Global.ShockwaveEffect
canonical_path: /api/Global/Effect/ShockwaveEffect
---

# Class ShockwaveEffect

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ShockwaveEffect : EffectInvoker
```

Shockwave effect used by some [core suppressions](/api/Global/Misc/SefiraBossBase).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [EffectInvoker](/api/Global/Effect/EffectInvoker) → ShockwaveEffect

## Inherited Members
[PrefabSrc](/api/Global/Effect/EffectInvoker#prefabsrc), [destroyEvent](/api/Global/Effect/EffectInvoker#destroyevent), [_attached](/api/Global/Effect/EffectInvoker#attached), [_node](/api/Global/Effect/EffectInvoker#node), [Invoker(string, MovableObjectNode, float, bool)](/api/Global/Effect/EffectInvoker#invoker-string-movableobjectnode-float-bool), [Invoker(string, Vector3, float, bool)](/api/Global/Effect/EffectInvoker#invoker-string-vector3-float-bool), [OnDestroy()](/api/Global/Effect/EffectInvoker#ondestroy), [SetMovableSetting(MovableObjectNode)](/api/Global/Effect/EffectInvoker#setmovablesetting-movableobjectnode), [SetDestroyEvent(OnDestroyEvent)](/api/Global/Effect/EffectInvoker#setdestroyevent-ondestroyevent), [Attach()](/api/Global/Effect/EffectInvoker#attach), [Dettach()](/api/Global/Effect/EffectInvoker#dettach), [IsAttached](/api/Global/Effect/EffectInvoker#isattached), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ShockwaveEffect()

```csharp
public ShockwaveEffect()
```

## Fields

### currentState

```csharp
private ShockwaveEffect.State currentState
```

#### Field Value

**Type:** Global.ShockwaveEffect.State

### distortionCurve

```csharp
public AnimationCurve distortionCurve
```
#INC


#### Field Value

**Type:** UnityEngine.AnimationCurve

### effectSrc

```csharp
private const string effectSrc = "ShockwaveEffect"
```
#INC


#### Field Value

**Type:** System.String

### effectTransform

```csharp
public Transform effectTransform
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### init

```csharp
private bool init
```
#INC


#### Field Value

**Type:** System.Boolean

### lifetimeType

```csharp
private EffectLifetimeType lifetimeType
```
#INC


#### Field Value

**Type:** Global.EffectLifetimeType

### material

```csharp
[HideInInspector]
public Material material
```

#### Field Value

**Type:** UnityEngine.Material

### MaximumShockwaveSize

```csharp
public float MaximumShockwaveSize
```
#INC


#### Field Value

**Type:** System.Single

### meshRenderer

```csharp
public MeshRenderer meshRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.MeshRenderer

### referenceMat

```csharp
public Material referenceMat
```
#INC


#### Field Value

**Type:** UnityEngine.Material

### shockWaveSizeCurve

```csharp
public AnimationCurve shockWaveSizeCurve
```
#INC


#### Field Value

**Type:** UnityEngine.AnimationCurve

### startScale

```csharp
private Vector3 startScale
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### updateTimer

```csharp
public Timer updateTimer
```
#INC


#### Field Value

**Type:** Global.Timer

## Methods

### FixedUpdate()

```csharp
private void FixedUpdate()
```
#INC


### Invoker(Vector3, UnitModel, float, float, EffectLifetimeType)

```csharp
public static ShockwaveEffect Invoker(Vector3 position, UnitModel owner, float lifeTime, float maxSize, EffectLifetimeType lifetimeType = EffectLifetimeType.NORMAL)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `position` | `UnityEngine.Vector3` |  |
| `owner` | `Global.UnitModel` |  |
| `lifeTime` | `System.Single` |  |
| `maxSize` | `System.Single` |  |
| `lifetimeType` | `Global.EffectLifetimeType` |  |

#### Returns

**Type:** Global.ShockwaveEffect

### Start()

```csharp
private void Start()
```
#INC


### Update()

```csharp
protected override void Update()
```
#INC
#code-generated


### UpdateMaterial(float)

```csharp
private void UpdateMaterial(float rate)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rate` | `System.Single` |  |

### UpdateTimer()

```csharp
private void UpdateTimer()
```
#INC

