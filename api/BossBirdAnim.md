# Class BossBirdAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BossBirdAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/AnimScript) → [CreatureAnimScript](/api/CreatureAnimScript) → [CreatureAnimEventCalled](/api/CreatureAnimEventCalled) → BossBirdAnim

## Inherited Members
[Move()](/api/CreatureAnimEventCalled#move), [Stop()](/api/CreatureAnimEventCalled#stop), [Kill()](/api/CreatureAnimEventCalled#kill), [Attract()](/api/CreatureAnimEventCalled#attract), [Attack()](/api/CreatureAnimEventCalled#attack), [OnCalled()](/api/CreatureAnimEventCalled#oncalled), [AgentReset()](/api/CreatureAnimEventCalled#agentreset), [SimpleReset()](/api/CreatureAnimEventCalled#simplereset), [AnimatorEventInit()](/api/CreatureAnimEventCalled#animatoreventinit), [CreatureAnimCall(int, CreatureBase)](/api/CreatureAnimEventCalled#creatureanimcall-int-creaturebase), [StopMoving()](/api/CreatureAnimEventCalled#stopmoving), [SuperArmorEffectSrc](/api/CreatureAnimScript#superarmoreffectsrc), [head](/api/CreatureAnimScript#head), [superArmorEffect](/api/CreatureAnimScript#superarmoreffect), [Awake()](/api/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/CreatureAnimScript#deletesuperarmoreffect), [HasDeadMotion()](/api/CreatureAnimScript#hasdeadmotion), [PlayDeadMotion()](/api/CreatureAnimScript#playdeadmotion), [PlayRevivalMotion()](/api/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/CreatureAnimScript#resetanimator), [animator](/api/AnimScript#animator), [motionDelay](/api/AnimScript#motiondelay), [defaultSpeed](/api/AnimScript#defaultspeed), [SetSpeed(float)](/api/AnimScript#setspeed-float), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** UnityEngine.Canvas

### bossBirdAnim

```csharp
public GameObject bossBirdAnim
```

#### Field Value

**Type:** UnityEngine.GameObject

### castingAnim

```csharp
public AnimationClip castingAnim
```

#### Field Value

**Type:** UnityEngine.AnimationClip

### castingEffectPos

```csharp
public Transform castingEffectPos
```

#### Field Value

**Type:** UnityEngine.Transform

### gutScript

```csharp
public BossBirdGutScript gutScript
```

#### Field Value

**Type:** Global.BossBirdGutScript

### meleeEffectPosFar

```csharp
public Transform meleeEffectPosFar
```

#### Field Value

**Type:** UnityEngine.Transform

### meleeEffectPosNear

```csharp
public Transform meleeEffectPosNear
```

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

#### Field Value

**Type:** Global.BossBird

### TimeFactor

```csharp
public float TimeFactor
```

#### Field Value

**Type:** System.Single

### ultHandFirst

```csharp
public Transform ultHandFirst
```

#### Field Value

**Type:** UnityEngine.Transform

### ultHandSecond

```csharp
public Transform ultHandSecond
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### AttackDamageTimeCalled()

```csharp
public override void AttackDamageTimeCalled()
```

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

### FixedUpdate()

```csharp
protected override void FixedUpdate()
```

### GetHidingState()

```csharp
public bool GetHidingState()
```

#### Returns

**Type:** System.Boolean

### Init()

```csharp
public void Init()
```

### MakeCastingEffect()

```csharp
public void MakeCastingEffect()
```

### OnAllEnable()

```csharp
public void OnAllEnable()
```

### OnCalled(int)

```csharp
public override void OnCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnCancel()

```csharp
public void OnCancel()
```

### OnDie()

```csharp
public void OnDie()
```

### ResetRangeAttack()

```csharp
public void ResetRangeAttack()
```

### SetCreatureAnim(bool)

```csharp
public void SetCreatureAnim(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetHalfEvent(HalfEvent)

```csharp
public void SetHalfEvent(BossBirdGutScript.HalfEvent e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.BossBirdGutScript.HalfEvent` |  |

### SetHidingCanvas(bool)

```csharp
public void SetHidingCanvas(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetNarrationNextState(bool)

```csharp
public void SetNarrationNextState(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetScript(BossBird)

```csharp
public void SetScript(BossBird script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.BossBird` |  |

### ShootGuts(Vector3)

```csharp
public void ShootGuts(Vector3 destPosGlobal)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `destPosGlobal` | `UnityEngine.Vector3` |  |

### SoundMake(string)

```csharp
public override void SoundMake(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### StartCasting()

```csharp
public void StartCasting()
```

### StartLaser()

```csharp
public void StartLaser()
```

### StartMeleeAttack()

```csharp
public void StartMeleeAttack()
```

### StartRangeAttack(List<LaserAttackTargetData>)

```csharp
public void StartRangeAttack(List<BossBird.LaserAttackTargetData> data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.List{BossBird.LaserAttackTargetData}` |  |

### StartRangeAttack(Vector2)

```csharp
public void StartRangeAttack(Vector2 targetPos)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetPos` | `UnityEngine.Vector2` |  |

### StartShooting()

```csharp
public void StartShooting()
```

### StartTeleport()

```csharp
public void StartTeleport()
```

### StartUltimate()

```csharp
public void StartUltimate()
```
