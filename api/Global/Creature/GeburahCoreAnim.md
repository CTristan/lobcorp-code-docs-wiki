---
uid: Global.GeburahCoreAnim
canonical_path: /api/Global/Creature/GeburahCoreAnim
---

# Class GeburahCoreAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GeburahCoreAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```

extends [CreatureAnimEventCalled](/api/Global/Creature/CreatureAnimEventCalled)

Animation handler for [The Red Mist](/api/Global/Script/GeburahCoreScript).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/Global/Script/AnimScript) → [CreatureAnimScript](/api/Global/Script/CreatureAnimScript) → [CreatureAnimEventCalled](/api/Global/Creature/CreatureAnimEventCalled) → GeburahCoreAnim

## Implements
[IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[Move()](/api/Global/Creature/CreatureAnimEventCalled#move), [Stop()](/api/Global/Creature/CreatureAnimEventCalled#stop), [Kill()](/api/Global/Creature/CreatureAnimEventCalled#kill), [Attract()](/api/Global/Creature/CreatureAnimEventCalled#attract), [Attack()](/api/Global/Creature/CreatureAnimEventCalled#attack), [OnCalled()](/api/Global/Creature/CreatureAnimEventCalled#oncalled), [OnCalled(int)](/api/Global/Creature/CreatureAnimEventCalled#oncalled-int), [AgentReset()](/api/Global/Creature/CreatureAnimEventCalled#agentreset), [SimpleReset()](/api/Global/Creature/CreatureAnimEventCalled#simplereset), [AnimatorEventInit()](/api/Global/Creature/CreatureAnimEventCalled#animatoreventinit), [CreatureAnimCall(int, CreatureBase)](/api/Global/Creature/CreatureAnimEventCalled#creatureanimcall-int-creaturebase), [AttackCalled(int)](/api/Global/Creature/CreatureAnimEventCalled#attackcalled-int), [AttackDamageTimeCalled()](/api/Global/Creature/CreatureAnimEventCalled#attackdamagetimecalled), [StopMoving()](/api/Global/Creature/CreatureAnimEventCalled#stopmoving), [SuperArmorEffectSrc](/api/Global/Script/CreatureAnimScript#superarmoreffectsrc), [head](/api/Global/Script/CreatureAnimScript#head), [superArmorEffect](/api/Global/Script/CreatureAnimScript#superarmoreffect), [updatedParameters](/api/Global/Script/CreatureAnimScript#updatedparameters), [Awake()](/api/Global/Script/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/Global/Script/CreatureAnimScript#setparameter-string-bool), [FlipDirection(bool)](/api/Global/Script/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/Global/Script/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#deletesuperarmoreffect), [PlayRevivalMotion()](/api/Global/Script/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/Global/Script/CreatureAnimScript#resetanimator), [animator](/api/Global/Script/AnimScript#animator), [motionDelay](/api/Global/Script/AnimScript#motiondelay), [defaultSpeed](/api/Global/Script/AnimScript#defaultspeed), [SetSpeed(float)](/api/Global/Script/AnimScript#setspeed-float), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GeburahCoreAnim()

```csharp
public GeburahCoreAnim()
```

## Fields

### _currentTarget

```csharp
private UnitModel _currentTarget
```
#INC


#### Field Value

**Type:** Global.UnitModel

### _currentTargetMark

```csharp
public SpriteRenderer _currentTargetMark
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### _eventHandler

```csharp
public AnimatorEventHandler _eventHandler
```
#INC


#### Field Value

**Type:** Global.AnimatorEventHandler

### _lastEffect

```csharp
public GameObject _lastEffect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### _script

```csharp
private GeburahCoreScript _script
```
#INC


#### Field Value

**Type:** Global.GeburahCoreScript

### _textInner

```csharp
[Header("TextCanvas")]
public Color _textInner
```

#### Field Value

**Type:** UnityEngine.Color

### _textOutter

```csharp
public Color _textOutter
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### bloodyTreeCurve

```csharp
public AnimationCurve bloodyTreeCurve
```
#INC


#### Field Value

**Type:** UnityEngine.AnimationCurve

### DangoFollower

```csharp
public Transform DangoFollower
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### DangoNear

```csharp
public Transform DangoNear
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### EyeRenderer

```csharp
public GameObject[] EyeRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject[]

### EyeTrail

```csharp
public GameObject EyeTrail
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### GeburahCanvas

```csharp
[Header("UniqueText")]
public Canvas GeburahCanvas
```

#### Field Value

**Type:** UnityEngine.Canvas

### headRenderer

```csharp
[Header("HeadRenderer")]
public SpriteRenderer[] headRenderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer[]

### initLossyScale

```csharp
private Vector3 initLossyScale
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### ketherAttached

```csharp
public GameObject[] ketherAttached
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject[]

### LeftHandFollower

```csharp
[Header("ProjectileRelated")]
public Transform LeftHandFollower
```

#### Field Value

**Type:** UnityEngine.Transform

### partRenderers

```csharp
[Header("DeadEffect")]
public List<WorkerPartRenderer> partRenderers
```

#### Field Value

**Type:** System.Collections.Generic.List{DeadEffect.WorkerPartRenderer}

### RightHandFollower

```csharp
public Transform RightHandFollower
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### TextObject

```csharp
public GameObject TextObject
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

## Properties

### Script

```csharp
public GeburahCoreScript Script { get; }
```

#### Property Value

**Type:** Global.GeburahCoreScript

## Methods

### FixedUpdate()

```csharp
protected override void FixedUpdate()
```
#INC


### GetPartRenderer(GeneratbleRegion)

```csharp
public WorkerPartRenderer GetPartRenderer(BloodyTreeDeadScript.GeneratbleRegion region)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `DeadEffect.BloodyTreeDeadScript.GeneratbleRegion` |  |

#### Returns

**Type:** DeadEffect.WorkerPartRenderer

### HasDeadMotion()

```csharp
public override bool HasDeadMotion()
```
#INC
#code-generated


#### Returns

**Type:** System.Boolean

### KetherAttach()

```csharp
public void KetherAttach()
```
#INC


### LateUpdate()

```csharp
protected override void LateUpdate()
```
#INC


### MakeGeburahText(string)

```csharp
public void MakeGeburahText(string text)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

### OnAttackEnd()

```csharp
public void OnAttackEnd()
```
#INC


### OnDamage()

```csharp
public void OnDamage()
```
#INC


### OnEventCalled(int)

```csharp
public void OnEventCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnRunningEnd()

```csharp
public void OnRunningEnd()
```
#INC


### OnStartAttack(int)

```csharp
public void OnStartAttack(int attackType)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `System.Int32` |  |

### OnTeleportEnd()

```csharp
public void OnTeleportEnd()
```
#INC


### OnTeleportStart()

```csharp
public void OnTeleportStart()
```
#INC


### OnThrowBloodyTree()

```csharp
public void OnThrowBloodyTree()
```
#INC


### PlayDeadMotion()

```csharp
public override void PlayDeadMotion()
```
#INC


### SetEye(int)

```csharp
private void SetEye(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### SetHead(int)

```csharp
private void SetHead(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### SetPhase(GeburahPhase)

```csharp
public void SetPhase(GeburahPhase phase)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `phase` | `GeburahBoss.GeburahPhase` |  |

### SetScript(GeburahCoreScript)

```csharp
public void SetScript(GeburahCoreScript coreScript)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `coreScript` | `Global.GeburahCoreScript` |  |

### SetTarget(UnitModel)

```csharp
public void SetTarget(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### SoundMake(string)

```csharp
public override void SoundMake(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
