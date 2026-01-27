---
uid: Global.OutterGodMidnightAttack
canonical_path: /api/Global/IANimatorEventCalled/OutterGodMidnightAttack
---

# Class OutterGodMidnightAttack

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OutterGodMidnightAttack : MonoBehaviour, IAnimatorEventCalled
```

Script for one of four attack prefabs:
- OutterGodMidnightAttack_R
- OutterGodMidnightAttack_W
- OutterGodMidnightAttack_B
- OutterGodMidnightAttack_P

Corresponding to each of the [shrines](/api/Global/OutterGodMidnight/OutterGodMidnight)' attacks.
Mostly just calls methods on the shrine, I think. #INC 



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → OutterGodMidnightAttack

## Implements
[IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OutterGodMidnightAttack()

```csharp
public OutterGodMidnightAttack()
```

## Fields

### _attackCoolTimeMax

```csharp
private const float _attackCoolTimeMax = 7
```
#INC


#### Field Value

**Type:** System.Single

### _attackCoolTimeMin

```csharp
private const float _attackCoolTimeMin = 4
```
#INC


#### Field Value

**Type:** System.Single

### _attackDelayMax

```csharp
private const float _attackDelayMax = 11
```
#INC


#### Field Value

**Type:** System.Single

### _attackDelayMin

```csharp
private const float _attackDelayMin = 8
```
#INC


#### Field Value

**Type:** System.Single

### _attackRemainTimeMax

```csharp
private const float _attackRemainTimeMax = 14
```
#INC


#### Field Value

**Type:** System.Single

### _attackRemainTimeMin

```csharp
private const float _attackRemainTimeMin = 8
```
#INC


#### Field Value

**Type:** System.Single

### _isEnabled

```csharp
private bool _isEnabled
```
#INC


#### Field Value

**Type:** System.Boolean

### _moveScaleMax

```csharp
private const float _moveScaleMax = 1.2
```
#INC


#### Field Value

**Type:** System.Single

### _moveScaleMin

```csharp
private const float _moveScaleMin = 0.8
```
#INC


#### Field Value

**Type:** System.Single

### _sound_b

```csharp
private const string _sound_b = "Tentacle_b"
```
#INC


#### Field Value

**Type:** System.String

### _sound_b2

```csharp
private const string _sound_b2 = "Tentacle_b2"
```
#INC


#### Field Value

**Type:** System.String

### _sound_p

```csharp
private const string _sound_p = "Eye_p"
```
#INC


#### Field Value

**Type:** System.String

### _sound_p2

```csharp
private const string _sound_p2 = "Eye_p2"
```
#INC


#### Field Value

**Type:** System.String

### _sound_portal_off

```csharp
private const string _sound_portal_off = "Portal_Off"
```
#INC


#### Field Value

**Type:** System.String

### _sound_portal_on

```csharp
private const string _sound_portal_on = "Portal_On"
```
#INC


#### Field Value

**Type:** System.String

### _sound_r

```csharp
private const string _sound_r = "Tentacle_r"
```
#INC


#### Field Value

**Type:** System.String

### _sound_src

```csharp
private const string _sound_src = "creature/OutterGodMidnight/OutterGod_Midnight_"
```
#INC


#### Field Value

**Type:** System.String

### _sound_w

```csharp
private const string _sound_w = "Tentacle_W"
```
#INC


#### Field Value

**Type:** System.String

### animator

```csharp
public Animator animator
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### attackDelayTimer

```csharp
private Timer attackDelayTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### attackRemainTimer_P

```csharp
private Timer attackRemainTimer_P
```
#INC


#### Field Value

**Type:** Global.Timer

### damaged

```csharp
private List<UnitModel> damaged
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

### midnight

```csharp
private OutterGodMidnight midnight
```
#INC


#### Field Value

**Type:** Global.OutterGodMidnight

### targetPos

```csharp
private Vector3 targetPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### type_P

```csharp
public bool type_P
```
#INC


#### Field Value

**Type:** System.Boolean

## Properties

### attackCoolTime

```csharp
private static float attackCoolTime { get; }
```

#### Property Value

**Type:** System.Single

### attackDelay

```csharp
private static float attackDelay { get; }
```

#### Property Value

**Type:** System.Single

### attackRemainTime

```csharp
private static float attackRemainTime { get; }
```

#### Property Value

**Type:** System.Single

### moveScale

```csharp
private static float moveScale { get; }
```

#### Property Value

**Type:** System.Single

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


### AttackEnd()

```csharp
private void AttackEnd()
```
#INC


### AttackStart()

```csharp
private void AttackStart()
```
#INC


### Awake()

```csharp
private void Awake()
```
#INC
#code-generated


### CheckCollision(Collider2D)

```csharp
public void CheckCollision(Collider2D collision)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `collision` | `UnityEngine.Collider2D` |  |

### CheckDamageTarget(UnitModel)

```csharp
private bool CheckDamageTarget(UnitModel unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### CheckEnd()

```csharp
private void CheckEnd()
```
#INC


### CheckStart()

```csharp
private void CheckStart()
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


### GiveDamage(UnitModel)

```csharp
private void GiveDamage(UnitModel unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

### MakeSound(string)

```csharp
private SoundEffectPlayer MakeSound(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MakeSound(string, float)

```csharp
private SoundEffectPlayer MakeSound(string src, float vol)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `vol` | `System.Single` |  |

#### Returns

**Type:** Global.SoundEffectPlayer

### MoveTo(Vector3)

```csharp
public void MoveTo(Vector3 position)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `position` | `UnityEngine.Vector3` |  |

### OnArrive()

```csharp
private void OnArrive()
```
#INC


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

### Setmidnight(OutterGodMidnight)

```csharp
public void Setmidnight(OutterGodMidnight midnight)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `midnight` | `Global.OutterGodMidnight` |  |

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
