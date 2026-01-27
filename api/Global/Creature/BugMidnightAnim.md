---
uid: Global.BugMidnightAnim
canonical_path: /api/Global/Creature/BugMidnightAnim
---

# Class BugMidnightAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugMidnightAnim : CreatureAnimScript
```

Animation handler for [The Eternal Meal](/api/Global/Misc/BugMidnight).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/Global/Script/AnimScript) → [CreatureAnimScript](/api/Global/Script/CreatureAnimScript) → BugMidnightAnim

## Inherited Members
[SuperArmorEffectSrc](/api/Global/Script/CreatureAnimScript#superarmoreffectsrc), [head](/api/Global/Script/CreatureAnimScript#head), [superArmorEffect](/api/Global/Script/CreatureAnimScript#superarmoreffect), [updatedParameters](/api/Global/Script/CreatureAnimScript#updatedparameters), [Awake()](/api/Global/Script/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/Global/Script/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/Global/Script/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/Global/Script/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/Global/Script/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#deletesuperarmoreffect), [Move()](/api/Global/Script/CreatureAnimScript#move), [Stop()](/api/Global/Script/CreatureAnimScript#stop), [StopMoving()](/api/Global/Script/CreatureAnimScript#stopmoving), [PlayRevivalMotion()](/api/Global/Script/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/Global/Script/CreatureAnimScript#resetanimator), [animator](/api/Global/Script/AnimScript#animator), [motionDelay](/api/Global/Script/AnimScript#motiondelay), [defaultSpeed](/api/Global/Script/AnimScript#defaultspeed), [SetSpeed(float)](/api/Global/Script/AnimScript#setspeed-float), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BugMidnightAnim()

```csharp
public BugMidnightAnim()
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
private static string[] animString
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
private Timer appearTimer
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

### crators

```csharp
public GameObject[] crators
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject[]

### createEffect

```csharp
public List<GameObject> createEffect
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### currentControls

```csharp
private List<BugMidnightAnim.AgentControl> currentControls
```

#### Field Value

**Type:** System.Collections.Generic.List{BugMidnightAnim.AgentControl}

### currentEffectCount

```csharp
private int currentEffectCount
```
#INC


#### Field Value

**Type:** System.Int32

### currentState

```csharp
private BugMidnight.AnimationState currentState
```
#INC


#### Field Value

**Type:** Global.BugMidnight.AnimationState

### defaultPos

```csharp
private Vector2 defaultPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### defaultSound

```csharp
private SoundEffectPlayer defaultSound
```
#INC


#### Field Value

**Type:** Global.SoundEffectPlayer

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

### eatTimer

```csharp
private Timer eatTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### effect_dust

```csharp
private const string effect_dust = "BugMidnightDustEffect"
```
#INC


#### Field Value

**Type:** System.String

### effectSrc

```csharp
private const string effectSrc = "Effect/Creature/BugMidnight/"
```
#INC


#### Field Value

**Type:** System.String

### enableControl

```csharp
private bool enableControl
```
#INC


#### Field Value

**Type:** System.Boolean

### script

```csharp
private BugMidnight script
```
#INC


#### Field Value

**Type:** Global.BugMidnight

### soundPrefix

```csharp
private const string soundPrefix = "RandomEvent/HordeOfBugs/Bug3_"
```
#INC


#### Field Value

**Type:** System.String

### spawnCount

```csharp
private int spawnCount
```
#INC


#### Field Value

**Type:** System.Int32

### src

```csharp
public AudioSource src
```
#INC


#### Field Value

**Type:** UnityEngine.AudioSource

### y_up

```csharp
private const float y_up = 0
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


### CompleteEvent(TrackEntry)

```csharp
public void CompleteEvent(TrackEntry entry)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### FixedUpdate()

```csharp
protected override void FixedUpdate()
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

### HasDeadMotion()

```csharp
public override bool HasDeadMotion()
```
#INC
#code-generated


#### Returns

**Type:** System.Boolean

### MakeEffect(string)

```csharp
private GameObject MakeEffect(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject

### OnAppear()

```csharp
public void OnAppear()
```
#INC


### OnAppearEnd()

```csharp
public void OnAppearEnd()
```
#INC


### OnDisappear()

```csharp
public void OnDisappear()
```
#INC


### OnSpawn()

```csharp
public void OnSpawn()
```
#INC


### PlayDeadMotion()

```csharp
public override void PlayDeadMotion()
```
#INC


### SetAnimation(AnimationState)

```csharp
public void SetAnimation(BugMidnight.AnimationState animState)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animState` | `Global.BugMidnight.AnimationState` |  |

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

### SetScript(BugMidnight)

```csharp
public void SetScript(BugMidnight script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.BugMidnight` |  |

### SoundMake(string)

```csharp
private void SoundMake(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### StartDeadWorkerControl(List<AgentControl>)

```csharp
public void StartDeadWorkerControl(List<BugMidnightAnim.AgentControl> targets)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targets` | `System.Collections.Generic.List{BugMidnightAnim.AgentControl}` |  |

### StartEvent(TrackEntry)

```csharp
public void StartEvent(TrackEntry entry)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |
