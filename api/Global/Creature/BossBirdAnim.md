---
uid: Global.BossBirdAnim
canonical_path: /api/Global/Creature/BossBirdAnim
---

# Class BossBirdAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BossBirdAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```

Animation handler for [Apocalypse Bird](/api/Global/Misc/BossBird).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/Global/Script/AnimScript) → [CreatureAnimScript](/api/Global/Script/CreatureAnimScript) → [CreatureAnimEventCalled](/api/Global/Creature/CreatureAnimEventCalled) → BossBirdAnim

## Implements
[IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[Move()](/api/Global/Creature/CreatureAnimEventCalled#move), [Stop()](/api/Global/Creature/CreatureAnimEventCalled#stop), [Kill()](/api/Global/Creature/CreatureAnimEventCalled#kill), [Attract()](/api/Global/Creature/CreatureAnimEventCalled#attract), [Attack()](/api/Global/Creature/CreatureAnimEventCalled#attack), [OnCalled()](/api/Global/Creature/CreatureAnimEventCalled#oncalled), [AgentReset()](/api/Global/Creature/CreatureAnimEventCalled#agentreset), [SimpleReset()](/api/Global/Creature/CreatureAnimEventCalled#simplereset), [AnimatorEventInit()](/api/Global/Creature/CreatureAnimEventCalled#animatoreventinit), [CreatureAnimCall(int, CreatureBase)](/api/Global/Creature/CreatureAnimEventCalled#creatureanimcall-int-creaturebase), [StopMoving()](/api/Global/Creature/CreatureAnimEventCalled#stopmoving), [SuperArmorEffectSrc](/api/Global/Script/CreatureAnimScript#superarmoreffectsrc), [head](/api/Global/Script/CreatureAnimScript#head), [superArmorEffect](/api/Global/Script/CreatureAnimScript#superarmoreffect), [updatedParameters](/api/Global/Script/CreatureAnimScript#updatedparameters), [Awake()](/api/Global/Script/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/Global/Script/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/Global/Script/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/Global/Script/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/Global/Script/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#deletesuperarmoreffect), [HasDeadMotion()](/api/Global/Script/CreatureAnimScript#hasdeadmotion), [PlayDeadMotion()](/api/Global/Script/CreatureAnimScript#playdeadmotion), [PlayRevivalMotion()](/api/Global/Script/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/Global/Script/CreatureAnimScript#resetanimator), [animator](/api/Global/Script/AnimScript#animator), [motionDelay](/api/Global/Script/AnimScript#motiondelay), [defaultSpeed](/api/Global/Script/AnimScript#defaultspeed), [SetSpeed(float)](/api/Global/Script/AnimScript#setspeed-float), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BossBirdAnim()

```csharp
public BossBirdAnim()
```

## Fields

### bigBirdHiding

```csharp
public Canvas bigBirdHiding
```
#INC


#### Field Value

**Type:** UnityEngine.Canvas

### bossBirdAnim

```csharp
public GameObject bossBirdAnim
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### castingAnim

```csharp
public AnimationClip castingAnim
```
#INC


#### Field Value

**Type:** UnityEngine.AnimationClip

### castingEffectPos

```csharp
public Transform castingEffectPos
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### castingTimer

```csharp
private Timer castingTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### currentCastingEffect

```csharp
private GameObject currentCastingEffect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### data

```csharp
private List<BossBird.LaserAttackTargetData> data
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{BossBird.LaserAttackTargetData}

### gutScript

```csharp
public BossBirdGutScript gutScript
```
#INC


#### Field Value

**Type:** Global.BossBirdGutScript

### meleeEffectPosFar

```csharp
public Transform meleeEffectPosFar
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### meleeEffectPosNear

```csharp
public Transform meleeEffectPosNear
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### narration

```csharp
public BossBirdAnim.NarrationUI narration
```

#### Field Value

**Type:** Global.BossBirdAnim.NarrationUI

### portalEffect

```csharp
public GameObject portalEffect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### rangeAttackController

```csharp
public BossBirdAnim.RangeAttackController rangeAttackController
```

#### Field Value

**Type:** Global.BossBirdAnim.RangeAttackController

### script

```csharp
public BossBird script
```
#INC


#### Field Value

**Type:** Global.BossBird

### teleportState

```csharp
private bool teleportState
```
#INC


#### Field Value

**Type:** System.Boolean

### TimeFactor

```csharp
public float TimeFactor
```
#INC


#### Field Value

**Type:** System.Single

### ultHandFirst

```csharp
public Transform ultHandFirst
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

### ultHandSecond

```csharp
public Transform ultHandSecond
```
#INC


#### Field Value

**Type:** UnityEngine.Transform

## Properties

### CastingTimer

```csharp
public Timer CastingTimer { get; }
```

#### Property Value

**Type:** Global.Timer

## Methods

### AttachGifts(List<AgentModel>)

```csharp
public IEnumerator AttachGifts(List<AgentModel> giftAttachList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `giftAttachList` | `System.Collections.Generic.List{AgentModel}` |  |

#### Returns

**Type:** System.Collections.IEnumerator

### AttackCalled(int)

```csharp
public override void AttackCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### AttackDamageTimeCalled()

```csharp
public override void AttackDamageTimeCalled()
```
#INC


### DisplayNarration(NarrationState, float, NarrationEndEvent)

```csharp
public void DisplayNarration(BossBird.NarrationState state, float time, BossBirdAnim.NarrationUI.NarrationEndEvent endEvent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.BossBird.NarrationState` |  |
| `time` | `System.Single` |  |
| `endEvent` | `Global.BossBirdAnim.NarrationUI.NarrationEndEvent` |  |

### DisplayNarration(NarrationState, float, NarrationEndEvent, FadeOutEvent)

```csharp
public void DisplayNarration(BossBird.NarrationState state, float time, BossBirdAnim.NarrationUI.NarrationEndEvent endEvent, BossBirdAnim.NarrationUI.FadeOutEvent fEvent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.BossBird.NarrationState` |  |
| `time` | `System.Single` |  |
| `endEvent` | `Global.BossBirdAnim.NarrationUI.NarrationEndEvent` |  |
| `fEvent` | `Global.BossBirdAnim.NarrationUI.FadeOutEvent` |  |

### EndTeleport()

```csharp
private void EndTeleport()
```
#INC


### FixedUpdate()

```csharp
protected override void FixedUpdate()
```
#INC
#code-generated


### GetHidingState()

```csharp
public bool GetHidingState()
```
#INC


#### Returns

**Type:** System.Boolean

### Init()

```csharp
public void Init()
```
#INC


### MakeCastingEffect()

```csharp
public void MakeCastingEffect()
```
#INC


### OnAllEnable()

```csharp
public void OnAllEnable()
```
#INC


### OnCalled(int)

```csharp
public override void OnCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnCancel()

```csharp
public void OnCancel()
```
#INC


### OnCastingEnd()

```csharp
private void OnCastingEnd()
```
#INC


### OnDie()

```csharp
public void OnDie()
```
#INC


### OnNormalAttackEnd()

```csharp
private void OnNormalAttackEnd()
```
#INC


### OnPatternAttackEnd()

```csharp
private void OnPatternAttackEnd()
```
#INC


### ResetRangeAttack()

```csharp
public void ResetRangeAttack()
```
#INC


### SetCreatureAnim(bool)

```csharp
public void SetCreatureAnim(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetHalfEvent(HalfEvent)

```csharp
public void SetHalfEvent(BossBirdGutScript.HalfEvent e)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.BossBirdGutScript.HalfEvent` |  |

### SetHidingCanvas(bool)

```csharp
public void SetHidingCanvas(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetNarrationNextState(bool)

```csharp
public void SetNarrationNextState(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetScript(BossBird)

```csharp
public void SetScript(BossBird script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.BossBird` |  |

### ShootGuts(Vector3)

```csharp
public void ShootGuts(Vector3 destPosGlobal)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `destPosGlobal` | `UnityEngine.Vector3` |  |

### SoundMake(string)

```csharp
public override void SoundMake(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### Start()

```csharp
private void Start()
```
#INC


### StartCasting()

```csharp
public void StartCasting()
```
#INC


### StartLaser()

```csharp
public void StartLaser()
```
#INC


### StartMeleeAttack()

```csharp
public void StartMeleeAttack()
```
#INC


### StartRangeAttack(List<LaserAttackTargetData>)

```csharp
public void StartRangeAttack(List<BossBird.LaserAttackTargetData> data)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.List{BossBird.LaserAttackTargetData}` |  |

### StartRangeAttack(Vector2)

```csharp
public void StartRangeAttack(Vector2 targetPos)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetPos` | `UnityEngine.Vector2` |  |

### StartShooting()

```csharp
public void StartShooting()
```
#INC


### StartTeleport()

```csharp
public void StartTeleport()
```
#INC


### StartUltimate()

```csharp
public void StartUltimate()
```
#INC


### TeleportActivate()

```csharp
private void TeleportActivate()
```
#INC


### Update()

```csharp
private void Update()
```
#INC

