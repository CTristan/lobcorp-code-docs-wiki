---
uid: Global.GrandmaBugAnim
canonical_path: /api/Global/Standing/GrandmaBugAnim
---

# Class GrandmaBugAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GrandmaBugAnim : StandingItemAnim, IAnimatorEventCalled
```
Animation handler for [GrandmaBug](/api/Global/Misc/GrandmaBug)
#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [StandingItemAnim](/api/Global/Misc/StandingItemAnim) → GrandmaBugAnim

## Implements
[IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[scriptBase](/api/Global/Misc/StandingItemAnim#scriptbase), [_unit](/api/Global/Misc/StandingItemAnim#unit), [SetUnit(StandingItemUnit)](/api/Global/Misc/StandingItemAnim#setunit-standingitemunit), [SetScript(StandingItemScriptBase)](/api/Global/Misc/StandingItemAnim#setscript-standingitemscriptbase), [Start()](/api/Global/Misc/StandingItemAnim#start), [Update()](/api/Global/Misc/StandingItemAnim#update), [unit](/api/Global/Misc/StandingItemAnim#unit), [animator](/api/Global/Misc/StandingItemAnim#animator), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GrandmaBugAnim()

```csharp
public GrandmaBugAnim()
```

## Fields

### anim_skeleton

```csharp
public SkeletonUIEvent anim_skeleton
```
#INC


#### Field Value

**Type:** Global.SkeletonUIEvent

### animString

```csharp
public static string[] animString
```
#INC


#### Field Value

**Type:** System.String[]

### appearEffect

```csharp
public GameObject appearEffect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### appearPosSet

```csharp
private bool appearPosSet
```
#INC


#### Field Value

**Type:** System.Boolean

### appearTimer

```csharp
public Timer appearTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### center

```csharp
public GameObject center
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### createEffect

```csharp
public List<GameObject> createEffect
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### currentControls

```csharp
private List<GrandmaBugAnim.AgentControl> currentControls
```

#### Field Value

**Type:** System.Collections.Generic.List{GrandmaBugAnim.AgentControl}

### currentEffectCount

```csharp
private int currentEffectCount
```
#INC


#### Field Value

**Type:** System.Int32

### disappearEffect

```csharp
public GameObject disappearEffect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### disappearEffectMake

```csharp
private bool disappearEffectMake
```
#INC


#### Field Value

**Type:** System.Boolean

### eatTime

```csharp
private const float eatTime = 0.73333335
```
#INC


#### Field Value

**Type:** System.Single

### EatTimer

```csharp
public Timer EatTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### enableControl

```csharp
private bool enableControl
```
#INC


#### Field Value

**Type:** System.Boolean

### script

```csharp
public GrandmaBug script
```
#INC


#### Field Value

**Type:** Global.GrandmaBug

### soundPrefix

```csharp
public const string soundPrefix = "RandomEvent/HordeOfBugs/Bug3_"
```
#INC


#### Field Value

**Type:** System.String

### src

```csharp
public AudioSource src
```
#INC


#### Field Value

**Type:** UnityEngine.AudioSource

### updateAnim

```csharp
private bool updateAnim
```
#INC


#### Field Value

**Type:** System.Boolean

### updateAnimState

```csharp
private GrandmaBug.AnimationState updateAnimState
```
#INC


#### Field Value

**Type:** Global.GrandmaBug.AnimationState

### y_up

```csharp
public float y_up
```
#INC


#### Field Value

**Type:** System.Single

### yValueCurve

```csharp
public AnimationCurve yValueCurve
```
#INC


#### Field Value

**Type:** UnityEngine.AnimationCurve

## Methods

### AgentReset()

```csharp
public void AgentReset()
```
#INC


### AnimatorEventInit()

```csharp
public void AnimatorEventInit()
```
#INC


### AnimReset()

```csharp
public void AnimReset()
```
#INC


### AppearAnim()

```csharp
public void AppearAnim()
```
#INC


### AppearEffect()

```csharp
public void AppearEffect()
```
#INC


### AttachHandler()

```csharp
public void AttachHandler()
```
#INC


### AttackCalled(int)

```csharp
public void AttackCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### AttackDamageTimeCalled()

```csharp
public void AttackDamageTimeCalled()
```
#INC


### CompleteEvent(TrackEntry)

```csharp
public void CompleteEvent(TrackEntry entry)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### CreatureAnimCall(int, CreatureBase)

```csharp
public void CreatureAnimCall(int i, CreatureBase script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `script` | `Global.CreatureBase` |  |

### Dead()

```csharp
public void Dead()
```
#INC


### FixedUpdate()

```csharp
private void FixedUpdate()
```
#INC


### HandleEvent(TrackEntry, Event)

```csharp
public void HandleEvent(TrackEntry entry, Event e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |
| `e` | `Spine.Event` |  |

### OnCalled()

```csharp
public void OnCalled()
```
#INC


### OnCalled(int)

```csharp
public void OnCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### SetActive(bool)

```csharp
public void SetActive(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetAnimation(AnimationState)

```csharp
public void SetAnimation(GrandmaBug.AnimationState animState)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animState` | `Global.GrandmaBug.AnimationState` |  |

### SetAnimation(string)

```csharp
public void SetAnimation(string state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.String` |  |

### SetAnimation(string, bool)

```csharp
public void SetAnimation(string state, bool loop)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.String` |  |
| `loop` | `System.Boolean` |  |

### SetScript(GrandmaBug)

```csharp
public void SetScript(GrandmaBug script)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.GrandmaBug` |  |

### SimpleReset()

```csharp
public void SimpleReset()
```
#INC


### SoundMake(string)

```csharp
public void SoundMake(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### StartDeadWorkerControl(List<AgentControl>)

```csharp
public void StartDeadWorkerControl(List<GrandmaBugAnim.AgentControl> targets)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targets` | `System.Collections.Generic.List{GrandmaBugAnim.AgentControl}` |  |

### StartEvent(TrackEntry)

```csharp
public void StartEvent(TrackEntry entry)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |
