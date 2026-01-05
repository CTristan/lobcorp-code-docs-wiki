# Class BinahCoreAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahCoreAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/AnimScript) → [CreatureAnimScript](/api/CreatureAnimScript) → [CreatureAnimEventCalled](/api/CreatureAnimEventCalled) → BinahCoreAnim

## Inherited Members
[Move()](/api/CreatureAnimEventCalled#move), [Stop()](/api/CreatureAnimEventCalled#stop), [Kill()](/api/CreatureAnimEventCalled#kill), [Attract()](/api/CreatureAnimEventCalled#attract), [Attack()](/api/CreatureAnimEventCalled#attack), [OnCalled()](/api/CreatureAnimEventCalled#oncalled), [AgentReset()](/api/CreatureAnimEventCalled#agentreset), [SimpleReset()](/api/CreatureAnimEventCalled#simplereset), [AnimatorEventInit()](/api/CreatureAnimEventCalled#animatoreventinit), [CreatureAnimCall(int, CreatureBase)](/api/CreatureAnimEventCalled#creatureanimcall-int-creaturebase), [AttackCalled(int)](/api/CreatureAnimEventCalled#attackcalled-int), [AttackDamageTimeCalled()](/api/CreatureAnimEventCalled#attackdamagetimecalled), [SoundMake(string)](/api/CreatureAnimEventCalled#soundmake-string), [StopMoving()](/api/CreatureAnimEventCalled#stopmoving), [SuperArmorEffectSrc](/api/CreatureAnimScript#superarmoreffectsrc), [head](/api/CreatureAnimScript#head), [superArmorEffect](/api/CreatureAnimScript#superarmoreffect), [Awake()](/api/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/CreatureAnimScript#setparameter-string-bool), [FlipDirection(bool)](/api/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/CreatureAnimScript#deletesuperarmoreffect), [PlayRevivalMotion()](/api/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/CreatureAnimScript#resetanimator), [animator](/api/AnimScript#animator), [motionDelay](/api/AnimScript#motiondelay), [defaultSpeed](/api/AnimScript#defaultspeed), [FixedUpdate()](/api/AnimScript#fixedupdate), [SetSpeed(float)](/api/AnimScript#setspeed-float), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BinahCoreAnim()

```csharp
public BinahCoreAnim()
```

## Fields

### _eventHandler

```csharp
public AnimatorEventHandler _eventHandler
```

#### Field Value

**Type:** Global.AnimatorEventHandler

### _textInner

```csharp
public Color _textInner
```

#### Field Value

**Type:** UnityEngine.Color

### _textOutter

```csharp
public Color _textOutter
```

#### Field Value

**Type:** UnityEngine.Color

### AttackTypeParticle

```csharp
public ParticleSystem AttackTypeParticle
```

#### Field Value

**Type:** UnityEngine.ParticleSystem

### BinahAgentSlow

```csharp
public GameObject BinahAgentSlow
```

#### Field Value

**Type:** UnityEngine.GameObject

### BinahArrived

```csharp
public GameObject BinahArrived
```

#### Field Value

**Type:** UnityEngine.GameObject

### BinahBladeAttackParticle

```csharp
public GameObject BinahBladeAttackParticle
```

#### Field Value

**Type:** UnityEngine.GameObject

### BinahCanvas

```csharp
[Header("TextCanvas")]
public Canvas BinahCanvas
```

#### Field Value

**Type:** UnityEngine.Canvas

### BinahCastDefaultOverload

```csharp
[Header("Effects")]
public GameObject BinahCastDefaultOverload
```

#### Field Value

**Type:** UnityEngine.GameObject

### BinahOverloadClear

```csharp
public GameObject BinahOverloadClear
```

#### Field Value

**Type:** UnityEngine.GameObject

### BinahOverloadClearExplode

```csharp
public GameObject BinahOverloadClearExplode
```

#### Field Value

**Type:** UnityEngine.GameObject

### blackColorMin

```csharp
public Color blackColorMin
```

#### Field Value

**Type:** UnityEngine.Color

### BlackFog

```csharp
public GameObject BlackFog
```

#### Field Value

**Type:** UnityEngine.GameObject

### ColumnCurve

```csharp
public AnimationCurve ColumnCurve
```

#### Field Value

**Type:** UnityEngine.AnimationCurve

### ColumnPivotParent

```csharp
public Transform ColumnPivotParent
```

#### Field Value

**Type:** UnityEngine.Transform

### ColumnPivots

```csharp
public Transform[] ColumnPivots
```

#### Field Value

**Type:** UnityEngine.Transform[]

### debugText

```csharp
public Text debugText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### defaultColorMax

```csharp
public Color defaultColorMax
```

#### Field Value

**Type:** UnityEngine.Color

### DisabledParent

```csharp
public Transform DisabledParent
```

#### Field Value

**Type:** UnityEngine.Transform

### eightColorMin

```csharp
public Color eightColorMin
```

#### Field Value

**Type:** UnityEngine.Color

### EnabledParent

```csharp
[Header("Binah Body Effect")]
public Transform EnabledParent
```

#### Field Value

**Type:** UnityEngine.Transform

### Golden_1

```csharp
public GameObject Golden_1
```

#### Field Value

**Type:** UnityEngine.GameObject

### Golden_2

```csharp
public GameObject Golden_2
```

#### Field Value

**Type:** UnityEngine.GameObject

### Golden_3

```csharp
public GameObject Golden_3
```

#### Field Value

**Type:** UnityEngine.GameObject

### GoldenColor

```csharp
public Color GoldenColor
```

#### Field Value

**Type:** UnityEngine.Color

### goldenColorMin

```csharp
public Color goldenColorMin
```

#### Field Value

**Type:** UnityEngine.Color

### HandFollower

```csharp
public Transform HandFollower
```

#### Field Value

**Type:** UnityEngine.Transform

### HeartFollower

```csharp
public Transform HeartFollower
```

#### Field Value

**Type:** UnityEngine.Transform

### waveColorMin

```csharp
public Color waveColorMin
```

#### Field Value

**Type:** UnityEngine.Color

## Properties

### Script

```csharp
public BinahCoreScript Script { get; }
```

#### Property Value

**Type:** Global.BinahCoreScript

## Methods

### GetOverloadTypeColor(OverloadType)

```csharp
public Color GetOverloadTypeColor(OverloadType overloadType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `overloadType` | `Global.OverloadType` |  |

#### Returns

**Type:** UnityEngine.Color

### HasDeadMotion()

```csharp
public override bool HasDeadMotion()
```

#### Returns

**Type:** System.Boolean

### LateUpdate()

```csharp
protected override void LateUpdate()
```

### MakeBinahText(string)

```csharp
public void MakeBinahText(string text)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

### OnCalled(int)

```csharp
public override void OnCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnCastingCancel()

```csharp
public void OnCastingCancel()
```

### OnCastingEnd()

```csharp
public void OnCastingEnd()
```

### OnEndAttack()

```csharp
public void OnEndAttack()
```

### OnGroggy()

```csharp
public void OnGroggy()
```

### OnGroggyEnd()

```csharp
public void OnGroggyEnd()
```

### OnPrevSuppressed()

```csharp
public void OnPrevSuppressed()
```

### OnStartAttack(BinahAttackType)

```csharp
public void OnStartAttack(BinahAttackType attackType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `BinahBoss.BinahAttackType` |  |

### PlayDeadMotion()

```csharp
public override void PlayDeadMotion()
```

### SetScrpt(BinahCoreScript)

```csharp
public void SetScrpt(BinahCoreScript coreScript)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `coreScript` | `Global.BinahCoreScript` |  |

### TurnOffAttackType()

```csharp
public void TurnOffAttackType()
```

### TurnOffBodyEffect(OverloadType)

```csharp
public void TurnOffBodyEffect(OverloadType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.OverloadType` |  |

### TurnOnAttackTypeEffect()

```csharp
public void TurnOnAttackTypeEffect()
```

### TurnOnAttackTypeEffect(RwbpType)

```csharp
public void TurnOnAttackTypeEffect(RwbpType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

### TurnOnBlackFog()

```csharp
public void TurnOnBlackFog()
```

### TurnOnBodyEffect(OverloadType, BinahPhase)

```csharp
public void TurnOnBodyEffect(OverloadType type, BinahPhase phase)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.OverloadType` |  |
| `phase` | `BinahBoss.BinahPhase` |  |
