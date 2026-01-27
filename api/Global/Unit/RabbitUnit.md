---
uid: Global.RabbitUnit
canonical_path: /api/Global/Unit/RabbitUnit
---

# Class RabbitUnit

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitUnit : MonoBehaviour, IMouseOnSelectListener, IMouseCommandTarget
```

A [rabbit](/api/Global/Model/RabbitModel) as they appear in-game.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → RabbitUnit

## Implements
[IMouseOnSelectListener](/api/Global/Misc/IMouseOnSelectListener), [IMouseCommandTarget](/api/Global/Misc/IMouseCommandTarget)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RabbitUnit()

```csharp
public RabbitUnit()
```

## Fields

### _Execute_src

```csharp
public const string _Execute_src = "Effect/Bullet/RabbitFallback"
```
#INC


#### Field Value

**Type:** System.String

### agentUI

```csharp
public AgentUI agentUI
```
#INC


#### Field Value

**Type:** InGameUI.AgentUI

### animController

```csharp
public RabbitAnimatorController animController
```
#INC


#### Field Value

**Type:** Global.RabbitAnimatorController

### animEventHandler

```csharp
public AnimatorEventHandler animEventHandler
```
#INC


#### Field Value

**Type:** Global.AnimatorEventHandler

### animRoot

```csharp
public Transform animRoot
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### appearEffect

```csharp
private const string appearEffect = "Effect/Rabbit/RabbitAppear"
```
#INC


#### Field Value

**Type:** System.String

### centerRoot

```csharp
public Transform centerRoot
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### currentSpeechType

```csharp
public RabbitConversationType currentSpeechType
```
#INC


#### Field Value

**Type:** Rabbit.RabbitConversationType

### executionCenter

```csharp
public Transform executionCenter
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### faceFollower

```csharp
public Transform faceFollower
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### faceSprites

```csharp
public SpriteRenderer[] faceSprites
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer[]

### model

```csharp
public RabbitModel model
```
#INC


#### Field Value

**Type:** Global.RabbitModel

### particle

```csharp
public List<ParticleSystem> particle
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.ParticleSystem}

### rwbpSet

```csharp
[Header("RWBP Set")]
public RabbitRwbpSet rwbpSet
```

#### Field Value

**Type:** Global.RabbitRwbpSet

### rwbpType

```csharp
public RwbpType rwbpType
```
#INC


#### Field Value

**Type:** Global.RwbpType

### speech

```csharp
public RabbitSpeech speech
```
#INC


#### Field Value

**Type:** Rabbit.RabbitSpeech

### spriteSetter

```csharp
public RabbitSpriteSetter spriteSetter
```
#INC


#### Field Value

**Type:** Rabbit.RabbitSpriteSetter

### ui

```csharp
public RabbitUnitUI ui
```
#INC


#### Field Value

**Type:** Global.RabbitUnitUI

### zValue

```csharp
public float zValue
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### Layer

```csharp
private RabbitLayer Layer { get; }
```

#### Property Value

**Type:** Global.RabbitLayer

## Methods

### Attack(int)

```csharp
public void Attack(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### Fire()

```csharp
public void Fire()
```
#INC


### FixedUpdate()

```csharp
public void FixedUpdate()
```
#INC


### GetCommandTargetModel()

```csharp
public IMouseCommandTargetModel GetCommandTargetModel()
```
#INC


#### Returns

**Type:** Global.IMouseCommandTargetModel

### IsSelectable()

```csharp
public bool IsSelectable()
```
#INC


#### Returns

**Type:** System.Boolean

### OnClear()

```csharp
public void OnClear()
```
#INC


### OnDie()

```csharp
public void OnDie()
```
#INC


### OnDieByMental()

```csharp
public void OnDieByMental()
```
#INC


### OnSelect()

```csharp
public void OnSelect()
```
#INC


### OnSpeechEnd()

```csharp
public void OnSpeechEnd()
```
#INC


### OnUnselect()

```csharp
public void OnUnselect()
```
#INC


### SetDefaultZValue(float)

```csharp
public void SetDefaultZValue(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### SetModel(RabbitModel)

```csharp
public void SetModel(RabbitModel m)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `m` | `Global.RabbitModel` |  |

### Speech(RabbitConversationType, float, float)

```csharp
public void Speech(RabbitConversationType type, float speechProb = 0.6, float speechTime = 3)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Rabbit.RabbitConversationType` |  |
| `speechProb` | `System.Single` |  |
| `speechTime` | `System.Single` |  |

### Start()

```csharp
private void Start()
```
#INC
#code-generated


### StopFire()

```csharp
public void StopFire()
```
#INC


### Update()

```csharp
private void Update()
```
#INC


### UpdateDirection()

```csharp
protected void UpdateDirection()
```
#INC


### UpdateViewPosition()

```csharp
protected void UpdateViewPosition()
```
#INC

