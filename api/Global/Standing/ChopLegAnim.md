---
uid: Global.ChopLegAnim
canonical_path: /api/Global/Standing/ChopLegAnim
---

# Class ChopLegAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChopLegAnim : StandingItemAnim, IAnimatorEventCalled
```
#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [StandingItemAnim](/api/Global/Misc/StandingItemAnim) → ChopLegAnim

## Implements
[IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[scriptBase](/api/Global/Misc/StandingItemAnim#scriptbase), [_unit](/api/Global/Misc/StandingItemAnim#unit), [SetUnit(StandingItemUnit)](/api/Global/Misc/StandingItemAnim#setunit-standingitemunit), [SetScript(StandingItemScriptBase)](/api/Global/Misc/StandingItemAnim#setscript-standingitemscriptbase), [Update()](/api/Global/Misc/StandingItemAnim#update), [unit](/api/Global/Misc/StandingItemAnim#unit), [animator](/api/Global/Misc/StandingItemAnim#animator), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ChopLegAnim()

```csharp
public ChopLegAnim()
```

## Fields

### currentAnimationState

```csharp
private ChopLegAnim.AnimationState currentAnimationState
```

#### Field Value

**Type:** Global.ChopLegAnim.AnimationState

### currentData

```csharp
private ChopLegAnim.AnimData currentData
```

#### Field Value

**Type:** Global.ChopLegAnim.AnimData

### currentHeight

```csharp
private float currentHeight
```
#INC


#### Field Value

**Type:** System.Single

### currentRate

```csharp
private float currentRate
```
#INC


#### Field Value

**Type:** System.Single

### damageGived

```csharp
private bool damageGived
```
#INC


#### Field Value

**Type:** System.Boolean

### data

```csharp
public List<ChopLegAnim.AnimData> data
```

#### Field Value

**Type:** System.Collections.Generic.List{ChopLegAnim.AnimData}

### Effect

```csharp
public GameObject Effect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### Gate

```csharp
public GameObject Gate
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### half

```csharp
private bool half
```
#INC


#### Field Value

**Type:** System.Boolean

### isIn

```csharp
private bool isIn
```
#INC


#### Field Value

**Type:** System.Boolean

### Leg

```csharp
public GameObject Leg
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### Mask

```csharp
public GameObject Mask
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### movementScale

```csharp
public float movementScale
```
#INC


#### Field Value

**Type:** System.Single

### movementTimer

```csharp
public Timer movementTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### PositionSetter

```csharp
public GameObject PositionSetter
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### positionTarget

```csharp
public RectTransform positionTarget
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### script

```csharp
public ChopLeg script
```
#INC


#### Field Value

**Type:** Global.ChopLeg

### skeletonControl

```csharp
public SkeletonUIEvent skeletonControl
```
#INC


#### Field Value

**Type:** Global.SkeletonUIEvent

### src

```csharp
public AudioSource src
```
#INC


#### Field Value

**Type:** UnityEngine.AudioSource

### targetRect

```csharp
public RectTransform targetRect
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

## Methods

### AddSpineAnimEvent()

```csharp
private void AddSpineAnimEvent()
```
#INC


### AgentReset()

```csharp
public void AgentReset()
```
#INC


### AnimationEnd(TrackEntry)

```csharp
public void AnimationEnd(TrackEntry entry)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### AnimationStart(TrackEntry)

```csharp
public void AnimationStart(TrackEntry entry)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### AnimatorEventInit()

```csharp
public void AnimatorEventInit()
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


### CalculatePos()

```csharp
public void CalculatePos()
```
#INC


### CancelAttack()

```csharp
public void CancelAttack()
```
#INC


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

### OnClick()

```csharp
public void OnClick()
```
#INC


### OnPointerEnter()

```csharp
public void OnPointerEnter()
```
#INC


### OnPointerExit()

```csharp
public void OnPointerExit()
```
#INC


### ResetCursor()

```csharp
public void ResetCursor()
```
#INC


### RunEffect()

```csharp
public void RunEffect()
```
#INC


### SetHeight(float)

```csharp
public void SetHeight(float yPos)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `yPos` | `System.Single` |  |

### SetScript(ChopLeg)

```csharp
public void SetScript(ChopLeg script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.ChopLeg` |  |

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

### Start()

```csharp
protected override void Start()
```
#INC
#code-generated


### StartAttack()

```csharp
public void StartAttack()
```
#INC


### StartMovement()

```csharp
public void StartMovement()
```
#INC


### Upward()

```csharp
public void Upward()
```
#INC

