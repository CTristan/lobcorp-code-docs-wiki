---
uid: Global.BigBadWolfAnim
canonical_path: /api/Global/Creature/BigBadWolfAnim
---

# Class BigBadWolfAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BigBadWolfAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```

Animation handler for [Big and Will Be Bad Wolf](/api/Global/IOBserver/BigBadWolf).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/Global/Script/AnimScript) → [CreatureAnimScript](/api/Global/Script/CreatureAnimScript) → [CreatureAnimEventCalled](/api/Global/Creature/CreatureAnimEventCalled) → BigBadWolfAnim

## Implements
[IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[Move()](/api/Global/Creature/CreatureAnimEventCalled#move), [Stop()](/api/Global/Creature/CreatureAnimEventCalled#stop), [Kill()](/api/Global/Creature/CreatureAnimEventCalled#kill), [Attract()](/api/Global/Creature/CreatureAnimEventCalled#attract), [Attack()](/api/Global/Creature/CreatureAnimEventCalled#attack), [OnCalled()](/api/Global/Creature/CreatureAnimEventCalled#oncalled), [AgentReset()](/api/Global/Creature/CreatureAnimEventCalled#agentreset), [SimpleReset()](/api/Global/Creature/CreatureAnimEventCalled#simplereset), [AnimatorEventInit()](/api/Global/Creature/CreatureAnimEventCalled#animatoreventinit), [CreatureAnimCall(int, CreatureBase)](/api/Global/Creature/CreatureAnimEventCalled#creatureanimcall-int-creaturebase), [AttackCalled(int)](/api/Global/Creature/CreatureAnimEventCalled#attackcalled-int), [AttackDamageTimeCalled()](/api/Global/Creature/CreatureAnimEventCalled#attackdamagetimecalled), [SoundMake(string)](/api/Global/Creature/CreatureAnimEventCalled#soundmake-string), [StopMoving()](/api/Global/Creature/CreatureAnimEventCalled#stopmoving), [SuperArmorEffectSrc](/api/Global/Script/CreatureAnimScript#superarmoreffectsrc), [head](/api/Global/Script/CreatureAnimScript#head), [superArmorEffect](/api/Global/Script/CreatureAnimScript#superarmoreffect), [updatedParameters](/api/Global/Script/CreatureAnimScript#updatedparameters), [Awake()](/api/Global/Script/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/Global/Script/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/Global/Script/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/Global/Script/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/Global/Script/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#deletesuperarmoreffect), [HasDeadMotion()](/api/Global/Script/CreatureAnimScript#hasdeadmotion), [PlayDeadMotion()](/api/Global/Script/CreatureAnimScript#playdeadmotion), [PlayRevivalMotion()](/api/Global/Script/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/Global/Script/CreatureAnimScript#resetanimator), [animator](/api/Global/Script/AnimScript#animator), [motionDelay](/api/Global/Script/AnimScript#motiondelay), [defaultSpeed](/api/Global/Script/AnimScript#defaultspeed), [SetSpeed(float)](/api/Global/Script/AnimScript#setspeed-float), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BigBadWolfAnim()

```csharp
public BigBadWolfAnim()
```

## Fields

### _badassWolf

```csharp
public GameObject _badassWolf
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### _castingAttackDuration

```csharp
private Timer _castingAttackDuration
```
#INC


#### Field Value

**Type:** Global.Timer

### _castingAttackEffectFreq

```csharp
private Timer _castingAttackEffectFreq
```
#INC


#### Field Value

**Type:** Global.Timer

### _castingAttackEnable

```csharp
private Timer _castingAttackEnable
```
#INC


#### Field Value

**Type:** Global.Timer

### _castingAttackMeshRenderer

```csharp
public MeshRenderer _castingAttackMeshRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.MeshRenderer

### _castingMiddle

```csharp
private bool _castingMiddle
```
#INC


#### Field Value

**Type:** System.Boolean

### _changeFilter

```csharp
public Animator _changeFilter
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### _defaultMaterial

```csharp
public Material _defaultMaterial
```
#INC


#### Field Value

**Type:** UnityEngine.Material

### _effectHeight

```csharp
public Transform _effectHeight
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### _escapeCloseParticle

```csharp
public GameObject _escapeCloseParticle
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### _escapeParticle

```csharp
public GameObject _escapeParticle
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### _eventHnadler

```csharp
public AnimatorEventHandler _eventHnadler
```
#INC


#### Field Value

**Type:** Global.AnimatorEventHandler

### _isMoonRed

```csharp
private bool _isMoonRed
```
#INC


#### Field Value

**Type:** System.Boolean

### _module

```csharp
private SpineOptimizerModule _module
```
#INC


#### Field Value

**Type:** Global.SpineOptimizerModule

### _moonObject

```csharp
public GameObject _moonObject
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### _normalWolf

```csharp
public GameObject _normalWolf
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### moonPosList

```csharp
public List<BigBadWolfAnim.MoonPos> moonPosList
```

#### Field Value

**Type:** System.Collections.Generic.List{BigBadWolfAnim.MoonPos}

### script

```csharp
private BigBadWolf script
```
#INC


#### Field Value

**Type:** Global.BigBadWolf

### sense

```csharp
public BigBadWolfSense sense
```
#INC


#### Field Value

**Type:** Global.BigBadWolfSense

### WorkerEatenSpriteRenderer

```csharp
public SpriteRenderer[] WorkerEatenSpriteRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer[]

## Properties

### _castingEnableFreq

```csharp
private float _castingEnableFreq { get; }
```

#### Property Value

**Type:** System.Single

### _castingFreq

```csharp
private float _castingFreq { get; }
```

#### Property Value

**Type:** System.Single

### MoonAnimator

```csharp
public Animator MoonAnimator { get; }
```

#### Property Value

**Type:** UnityEngine.Animator

## Methods

### ChangeAnim()

```csharp
private void ChangeAnim()
```
#INC


### FixedUpdate()

```csharp
protected override void FixedUpdate()
```
#INC


### GetMoonPos(SefiraEnum)

```csharp
private BigBadWolfAnim.MoonPos GetMoonPos(SefiraEnum sefiraEnum)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraEnum` | `Global.SefiraEnum` |  |

#### Returns

**Type:** Global.BigBadWolfAnim.MoonPos

### Howling()

```csharp
public void Howling()
```
#INC


### IsRedMoon()

```csharp
public bool IsRedMoon()
```
#INC


#### Returns

**Type:** System.Boolean

### OnAttack(WolfAttackType)

```csharp
public void OnAttack(BigBadWolf.WolfAttackType attackType)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `Global.BigBadWolf.WolfAttackType` |  |

### OnCalled(int)

```csharp
public override void OnCalled(int i)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnCastingAttackEnd()

```csharp
public void OnCastingAttackEnd()
```
#INC


### OnCastingEnd()

```csharp
public void OnCastingEnd()
```
#INC


### OnCastingTrigger()

```csharp
public void OnCastingTrigger()
```
#INC


### OnEscape()

```csharp
public void OnEscape()
```
#INC


### ResetAnim()

```csharp
public void ResetAnim()
```
#INC


### SetEatenSprite(int)

```csharp
public void SetEatenSprite(int count)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `count` | `System.Int32` |  |

### SetGetaway(bool)

```csharp
public void SetGetaway(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetGroggy(bool)

```csharp
public void SetGroggy(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetMoon(Sefira)

```csharp
public void SetMoon(Sefira sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

### SetMoonActive()

```csharp
public void SetMoonActive()
```
#INC


### SetMoonState(bool)

```csharp
public void SetMoonState(bool isRed)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isRed` | `System.Boolean` |  |

### SetScript(BigBadWolf)

```csharp
public void SetScript(BigBadWolf wolf)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `wolf` | `Global.BigBadWolf` |  |

### SetWolfAnimState(int)

```csharp
public void SetWolfAnimState(int value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Int32` |  |

### StartCastingAttack()

```csharp
public void StartCastingAttack()
```
#INC


### Update()

```csharp
private void Update()
```
#INC

