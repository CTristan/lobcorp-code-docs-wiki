---
uid: Global.FengYunGhoulAnimEventHandler
canonical_path: /api/Global/Animator/FengYunGhoulAnimEventHandler
---

# Class FengYunGhoulAnimEventHandler

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FengYunGhoulAnimEventHandler : AnimatorEventHandler
```

Animation handler for [Clouded Monk](/api/Global/IOBserver/FengYun)'s escaping form.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimatorEventHandler](/api/Global/Misc/AnimatorEventHandler) → FengYunGhoulAnimEventHandler

## Inherited Members
[_giveDamageEvent](/api/Global/Misc/AnimatorEventHandler#givedamageevent), [_attackEndEvent](/api/Global/Misc/AnimatorEventHandler#attackendevent), [_animEvent](/api/Global/Misc/AnimatorEventHandler#animevent), [_suicideEvent](/api/Global/Misc/AnimatorEventHandler#suicideevent), [SetDamageEvent(EventDelegate)](/api/Global/Misc/AnimatorEventHandler#setdamageevent-eventdelegate), [SetAttackEndEvent(EventDelegate)](/api/Global/Misc/AnimatorEventHandler#setattackendevent-eventdelegate), [SetAnimEvent(AnimEventDelegate)](/api/Global/Misc/AnimatorEventHandler#setanimevent-animeventdelegate), [SetSuicideEvent(EventDelegate)](/api/Global/Misc/AnimatorEventHandler#setsuicideevent-eventdelegate), [Damage()](/api/Global/Misc/AnimatorEventHandler#damage), [AttackEnd()](/api/Global/Misc/AnimatorEventHandler#attackend), [OnAnimCalled(int)](/api/Global/Misc/AnimatorEventHandler#onanimcalled-int), [Suicide()](/api/Global/Misc/AnimatorEventHandler#suicide), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FengYunGhoulAnimEventHandler()

```csharp
public FengYunGhoulAnimEventHandler()
```

## Fields

### _eatEndEvent

```csharp
private AnimatorEventHandler.EventDelegate _eatEndEvent
```

#### Field Value

**Type:** Global.AnimatorEventHandler.EventDelegate

### _howlEndEvent

```csharp
private AnimatorEventHandler.EventDelegate _howlEndEvent
```

#### Field Value

**Type:** Global.AnimatorEventHandler.EventDelegate

### _SOUND_ATTACK

```csharp
private const string _SOUND_ATTACK = "creature/FengYUn/Templer_Atk"
```
#INC


#### Field Value

**Type:** System.String

### _SOUND_CAST

```csharp
private const string _SOUND_CAST = "creature/FengYUn/Templer_Cast"
```
#INC


#### Field Value

**Type:** System.String

### _SOUND_EAT

```csharp
private const string _SOUND_EAT = "creature/FengYUn/Templer_Eat"
```
#INC


#### Field Value

**Type:** System.String

### _SOUND_EATGROGGY

```csharp
private const string _SOUND_EATGROGGY = "creature/FengYUn/Templer_EatGroggy"
```
#INC


#### Field Value

**Type:** System.String

### _SOUND_GROGGY

```csharp
private const string _SOUND_GROGGY = "creature/FengYUn/Templer_Groggy"
```
#INC


#### Field Value

**Type:** System.String

### _SOUND_HOWL

```csharp
private const string _SOUND_HOWL = "creature/FengYUn/Templer_Howl"
```
#INC


#### Field Value

**Type:** System.String

### _SOUND_RUN

```csharp
private const string _SOUND_RUN = "creature/FengYUn/Templer_Run"
```
#INC


#### Field Value

**Type:** System.String

### _SOUND_RUNFIRE

```csharp
private const string _SOUND_RUNFIRE = "creature/FengYUn/Templer_Run_Fire"
```
#INC


#### Field Value

**Type:** System.String

### _soundRunLoop

```csharp
private SoundEffectPlayer _soundRunLoop
```
#INC


#### Field Value

**Type:** Global.SoundEffectPlayer

## Methods

### EndEat()

```csharp
public void EndEat()
```
#INC


### EndHowl()

```csharp
public void EndHowl()
```
#INC


### PlayAtkSound()

```csharp
public void PlayAtkSound()
```
#INC


### PlayCastSound()

```csharp
public void PlayCastSound()
```
#INC


### PlayEatGroggySound()

```csharp
public void PlayEatGroggySound()
```
#INC


### PlayEatSound()

```csharp
public void PlayEatSound()
```
#INC


### PlayGroggySound()

```csharp
public void PlayGroggySound()
```
#INC


### PlayHowlSound()

```csharp
public void PlayHowlSound()
```
#INC


### PlayRunFireSound()

```csharp
public void PlayRunFireSound()
```
#INC


### PlayRunLoopSound()

```csharp
public void PlayRunLoopSound()
```
#INC


### SetEatEndEvent(EventDelegate)

```csharp
public void SetEatEndEvent(AnimatorEventHandler.EventDelegate e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.AnimatorEventHandler.EventDelegate` |  |

### SetHowlEndEvent(EventDelegate)

```csharp
public void SetHowlEndEvent(AnimatorEventHandler.EventDelegate e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.AnimatorEventHandler.EventDelegate` |  |

### StopRunLoopSound()

```csharp
public void StopRunLoopSound()
```
#INC

