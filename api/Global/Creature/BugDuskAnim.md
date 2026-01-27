---
uid: Global.BugDuskAnim
canonical_path: /api/Global/Creature/BugDuskAnim
---

# Class BugDuskAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugDuskAnim : CreatureAnimScript
```

Animation handler for [The Food Chain](/api/Global/Misc/BugDusk).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/Global/Script/AnimScript) → [CreatureAnimScript](/api/Global/Script/CreatureAnimScript) → BugDuskAnim

## Inherited Members
[SuperArmorEffectSrc](/api/Global/Script/CreatureAnimScript#superarmoreffectsrc), [head](/api/Global/Script/CreatureAnimScript#head), [superArmorEffect](/api/Global/Script/CreatureAnimScript#superarmoreffect), [updatedParameters](/api/Global/Script/CreatureAnimScript#updatedparameters), [SetParameter(string, bool)](/api/Global/Script/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/Global/Script/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/Global/Script/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/Global/Script/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#deletesuperarmoreffect), [Move()](/api/Global/Script/CreatureAnimScript#move), [Stop()](/api/Global/Script/CreatureAnimScript#stop), [StopMoving()](/api/Global/Script/CreatureAnimScript#stopmoving), [PlayRevivalMotion()](/api/Global/Script/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/Global/Script/CreatureAnimScript#resetanimator), [animator](/api/Global/Script/AnimScript#animator), [motionDelay](/api/Global/Script/AnimScript#motiondelay), [defaultSpeed](/api/Global/Script/AnimScript#defaultspeed), [SetSpeed(float)](/api/Global/Script/AnimScript#setspeed-float), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BugDuskAnim()

```csharp
public BugDuskAnim()
```

## Fields

### _currentState

```csharp
private BugDusk.AnimationState _currentState
```
#INC


#### Field Value

**Type:** Global.BugDusk.AnimationState

### _defaultPosition

```csharp
private Vector3 _defaultPosition
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### _elapsedTime

```csharp
private float _elapsedTime
```
#INC


#### Field Value

**Type:** System.Single

### _spawnCounter

```csharp
private int _spawnCounter
```
#INC


#### Field Value

**Type:** System.Int32

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

### center

```csharp
public GameObject center
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### defaultSound

```csharp
private SoundEffectPlayer defaultSound
```
#INC


#### Field Value

**Type:** Global.SoundEffectPlayer

### effect_src

```csharp
public const string effect_src = "Effect/Creature/BugDusk/"
```
#INC


#### Field Value

**Type:** System.String

### script

```csharp
private BugDusk script
```
#INC


#### Field Value

**Type:** Global.BugDusk

### sound_src

```csharp
public const string sound_src = "creature/BugDusk/BugDusk_"
```
#INC


#### Field Value

**Type:** System.String

### soundString

```csharp
public static string[] soundString
```
#INC


#### Field Value

**Type:** System.String[]

### src

```csharp
public AudioSource src
```
#INC


#### Field Value

**Type:** UnityEngine.AudioSource

### volume

```csharp
public static float[] volume
```
#INC


#### Field Value

**Type:** System.Single[]

## Methods

### AttachHandler()

```csharp
public void AttachHandler()
```
#INC


### Awake()

```csharp
protected override void Awake()
```
#INC
#code-generated


### CompleteEvent(TrackEntry)

```csharp
public void CompleteEvent(TrackEntry entry)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### CurrentState()

```csharp
public BugDusk.AnimationState CurrentState()
```
#INC


#### Returns

**Type:** Global.BugDusk.AnimationState

### EventHandler(TrackEntry, Event)

```csharp
public void EventHandler(TrackEntry entry, Event eventData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |
| `eventData` | `Spine.Event` |  |

### FixedUpdate()

```csharp
protected override void FixedUpdate()
```
#INC


### HasDeadMotion()

```csharp
public override bool HasDeadMotion()
```
#INC


#### Returns

**Type:** System.Boolean

### IsSpawning()

```csharp
public bool IsSpawning()
```
#INC


#### Returns

**Type:** System.Boolean

### MakeSound(string, float)

```csharp
public void MakeSound(string src, float volume = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `volume` | `System.Single` |  |

### PlayDeadMotion()

```csharp
public override void PlayDeadMotion()
```
#INC


### SetAnimation(AnimationState)

```csharp
public void SetAnimation(BugDusk.AnimationState animState)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animState` | `Global.BugDusk.AnimationState` |  |

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

### SetScript(BugDusk)

```csharp
public void SetScript(BugDusk script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.BugDusk` |  |

### StartEvent(TrackEntry)

```csharp
public void StartEvent(TrackEntry entry)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |
