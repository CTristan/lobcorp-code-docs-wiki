---
uid: Global.KnightOfDespairAnim
canonical_path: /api/Global/Creature/KnightOfDespairAnim
---

# Class KnightOfDespairAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KnightOfDespairAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```

Animation handler for [Knight of Despair](/api/Global/Misc/KnightOfDespair). #Inc


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/Global/Script/AnimScript) → [CreatureAnimScript](/api/Global/Script/CreatureAnimScript) → [CreatureAnimEventCalled](/api/Global/Creature/CreatureAnimEventCalled) → KnightOfDespairAnim

## Implements
[IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[Move()](/api/Global/Creature/CreatureAnimEventCalled#move), [Stop()](/api/Global/Creature/CreatureAnimEventCalled#stop), [Kill()](/api/Global/Creature/CreatureAnimEventCalled#kill), [Attract()](/api/Global/Creature/CreatureAnimEventCalled#attract), [Attack()](/api/Global/Creature/CreatureAnimEventCalled#attack), [OnCalled()](/api/Global/Creature/CreatureAnimEventCalled#oncalled), [OnCalled(int)](/api/Global/Creature/CreatureAnimEventCalled#oncalled-int), [AgentReset()](/api/Global/Creature/CreatureAnimEventCalled#agentreset), [SimpleReset()](/api/Global/Creature/CreatureAnimEventCalled#simplereset), [AnimatorEventInit()](/api/Global/Creature/CreatureAnimEventCalled#animatoreventinit), [CreatureAnimCall(int, CreatureBase)](/api/Global/Creature/CreatureAnimEventCalled#creatureanimcall-int-creaturebase), [AttackCalled(int)](/api/Global/Creature/CreatureAnimEventCalled#attackcalled-int), [AttackDamageTimeCalled()](/api/Global/Creature/CreatureAnimEventCalled#attackdamagetimecalled), [SoundMake(string)](/api/Global/Creature/CreatureAnimEventCalled#soundmake-string), [StopMoving()](/api/Global/Creature/CreatureAnimEventCalled#stopmoving), [SuperArmorEffectSrc](/api/Global/Script/CreatureAnimScript#superarmoreffectsrc), [head](/api/Global/Script/CreatureAnimScript#head), [superArmorEffect](/api/Global/Script/CreatureAnimScript#superarmoreffect), [updatedParameters](/api/Global/Script/CreatureAnimScript#updatedparameters), [Awake()](/api/Global/Script/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/Global/Script/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/Global/Script/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/Global/Script/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/Global/Script/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#deletesuperarmoreffect), [HasDeadMotion()](/api/Global/Script/CreatureAnimScript#hasdeadmotion), [PlayDeadMotion()](/api/Global/Script/CreatureAnimScript#playdeadmotion), [PlayRevivalMotion()](/api/Global/Script/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/Global/Script/CreatureAnimScript#resetanimator), [animator](/api/Global/Script/AnimScript#animator), [motionDelay](/api/Global/Script/AnimScript#motiondelay), [defaultSpeed](/api/Global/Script/AnimScript#defaultspeed), [FixedUpdate()](/api/Global/Script/AnimScript#fixedupdate), [SetSpeed(float)](/api/Global/Script/AnimScript#setspeed-float), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### KnightOfDespairAnim()

```csharp
public KnightOfDespairAnim()
```

## Fields

### bufUnit

```csharp
public BufRenderer bufUnit
```
#INC


#### Field Value

**Type:** Global.BufRenderer

### eventHandler

```csharp
public AnimatorEventHandler eventHandler
```
#INC


#### Field Value

**Type:** Global.AnimatorEventHandler

### script

```csharp
private KnightOfDespair script
```
#INC


#### Field Value

**Type:** Global.KnightOfDespair

### skeletonAnimator

```csharp
private SkeletonAnimator skeletonAnimator
```
#INC


#### Field Value

**Type:** Spine.Unity.SkeletonAnimator

### sowrdAttachmentName

```csharp
private static string sowrdAttachmentName
```
#INC


#### Field Value

**Type:** System.String

### sowrdSlots

```csharp
private static string[] sowrdSlots
```
#INC


#### Field Value

**Type:** System.String[]

### Spades

```csharp
[Header("DeadEffect")]
public ParticleSystem[] Spades
```

#### Field Value

**Type:** UnityEngine.ParticleSystem[]

### Swords

```csharp
public KnightOfDespairSword[] Swords
```
#INC


#### Field Value

**Type:** Global.KnightOfDespairSword[]

### Throwed

```csharp
public GameObject Throwed
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### Transparent

```csharp
public Sprite Transparent
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

## Methods

### EvalulateParticleSize(float)

```csharp
public void EvalulateParticleSize(float currentScale)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `currentScale` | `System.Single` |  |

### GetSwordIndex()

```csharp
public int GetSwordIndex()
```
#INC


#### Returns

**Type:** System.Int32

### MakeTeleportEffect(string, Vector3)

```csharp
private void MakeTeleportEffect(string src, Vector3 pos)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |

### OnAnimCalled(int)

```csharp
public void OnAnimCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

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


### ResetAnim()

```csharp
public void ResetAnim()
```
#INC


### SetAttackAnim(int)

```csharp
public void SetAttackAnim(int type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `System.Int32` |  |

### SetInitialSpineState()

```csharp
private void SetInitialSpineState()
```
#INC


### SetNormalAnim(AnimKey)

```csharp
public void SetNormalAnim(KnightOfDespairAnim.AnimKey key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `Global.KnightOfDespairAnim.AnimKey` |  |

### SetScript(KnightOfDespair)

```csharp
public void SetScript(KnightOfDespair script)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.KnightOfDespair` |  |

### TurnOnSwords()

```csharp
public void TurnOnSwords()
```
#INC

