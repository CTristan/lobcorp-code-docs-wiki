---
uid: Global.AnimatorEventHandler
canonical_path: /api/Global/Misc/AnimatorEventHandler
---

# Class AnimatorEventHandler

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AnimatorEventHandler : MonoBehaviour
```
Holds a list of methods to call when certain events happen.

These can include: taking damage, ending an attack, playing an animation(?), and suicide.

(Seems to be mainly used as a parent class...)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → AnimatorEventHandler

## Derived
[CircusMessageReciever](/api/Global/Animator/CircusMessageReciever), [DangoCreatureEventHandler](/api/Global/Animator/DangoCreatureEventHandler), [FengYunGhoulAnimEventHandler](/api/Global/Animator/FengYunGhoulAnimEventHandler), [FengYunMonkAnimEventHandler](/api/Global/Animator/FengYunMonkAnimEventHandler), [FreischutzAnimEventHandler](/api/Global/Animator/FreischutzAnimEventHandler), [FreischutzMagicEventHandler](/api/Global/Animator/FreischutzMagicEventHandler), [HellTrainAnimEventHandler](/api/Global/Animator/HellTrainAnimEventHandler), [IronMaidenAnimEventHandler](/api/Global/Animator/IronMaidenAnimEventHandler), [MachineDawnAnimEventHandler](/api/Global/Animator/MachineDawnAnimEventHandler), [OutterGodNoonAnimEventHandler](/api/Global/Animator/OutterGodNoonAnimEventHandler), [OutterGodNoonGateAnimEventHandler](/api/Global/Animator/OutterGodNoonGateAnimEventHandler), [PpodaeAnimEventHandler](/api/Global/Animator/PpodaeAnimEventHandler), [PromiseAndFaithAnimEventHandler](/api/Global/Animator/PromiseAndFaithAnimEventHandler), [ReverseClockAnimEventHandler](/api/Global/Animator/ReverseClockAnimEventHandler), [UnionAnimEventHandler](/api/Global/Animator/UnionAnimEventHandler), [YangAnimEventHandler](/api/Global/Animator/YangAnimEventHandler), [YinAnimEventHandler](/api/Global/Animator/YinAnimEventHandler), [YouMustHappyAnimEventHandler](/api/Global/Animator/YouMustHappyAnimEventHandler)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AnimatorEventHandler()

```csharp
public AnimatorEventHandler()
```

## Fields

### _animEvent

```csharp
private AnimatorEventHandler.AnimEventDelegate _animEvent
```

#### Field Value

**Type:** Global.AnimatorEventHandler.AnimEventDelegate

### _attackEndEvent

```csharp
private AnimatorEventHandler.EventDelegate _attackEndEvent
```

#### Field Value

**Type:** Global.AnimatorEventHandler.EventDelegate

### _giveDamageEvent

```csharp
private AnimatorEventHandler.EventDelegate _giveDamageEvent
```

#### Field Value

**Type:** Global.AnimatorEventHandler.EventDelegate

### _suicideEvent

```csharp
private AnimatorEventHandler.EventDelegate _suicideEvent
```

#### Field Value

**Type:** Global.AnimatorEventHandler.EventDelegate

## Methods

### AttackEnd()

```csharp
public void AttackEnd()
```
#INC


### Damage()

```csharp
public void Damage()
```
#INC


### OnAnimCalled(int)

```csharp
public void OnAnimCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### SetAnimEvent(AnimEventDelegate)

```csharp
public void SetAnimEvent(AnimatorEventHandler.AnimEventDelegate e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.AnimatorEventHandler.AnimEventDelegate` |  |

### SetAttackEndEvent(EventDelegate)

```csharp
public void SetAttackEndEvent(AnimatorEventHandler.EventDelegate e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.AnimatorEventHandler.EventDelegate` |  |

### SetDamageEvent(EventDelegate)

```csharp
public void SetDamageEvent(AnimatorEventHandler.EventDelegate e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.AnimatorEventHandler.EventDelegate` |  |

### SetSuicideEvent(EventDelegate)

```csharp
public void SetSuicideEvent(AnimatorEventHandler.EventDelegate e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.AnimatorEventHandler.EventDelegate` |  |

### Suicide()

```csharp
public void Suicide()
```
#INC

