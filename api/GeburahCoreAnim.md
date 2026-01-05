# Class GeburahCoreAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GeburahCoreAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/AnimScript) → [CreatureAnimScript](/api/CreatureAnimScript) → [CreatureAnimEventCalled](/api/CreatureAnimEventCalled) → GeburahCoreAnim

## Inherited Members
[Move()](/api/CreatureAnimEventCalled#move), [Stop()](/api/CreatureAnimEventCalled#stop), [Kill()](/api/CreatureAnimEventCalled#kill), [Attract()](/api/CreatureAnimEventCalled#attract), [Attack()](/api/CreatureAnimEventCalled#attack), [OnCalled()](/api/CreatureAnimEventCalled#oncalled), [OnCalled(int)](/api/CreatureAnimEventCalled#oncalled-int), [AgentReset()](/api/CreatureAnimEventCalled#agentreset), [SimpleReset()](/api/CreatureAnimEventCalled#simplereset), [AnimatorEventInit()](/api/CreatureAnimEventCalled#animatoreventinit), [CreatureAnimCall(int, CreatureBase)](/api/CreatureAnimEventCalled#creatureanimcall-int-creaturebase), [AttackCalled(int)](/api/CreatureAnimEventCalled#attackcalled-int), [AttackDamageTimeCalled()](/api/CreatureAnimEventCalled#attackdamagetimecalled), [StopMoving()](/api/CreatureAnimEventCalled#stopmoving), [SuperArmorEffectSrc](/api/CreatureAnimScript#superarmoreffectsrc), [head](/api/CreatureAnimScript#head), [superArmorEffect](/api/CreatureAnimScript#superarmoreffect), [Awake()](/api/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/CreatureAnimScript#setparameter-string-bool), [FlipDirection(bool)](/api/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/CreatureAnimScript#deletesuperarmoreffect), [PlayRevivalMotion()](/api/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/CreatureAnimScript#resetanimator), [animator](/api/AnimScript#animator), [motionDelay](/api/AnimScript#motiondelay), [defaultSpeed](/api/AnimScript#defaultspeed), [SetSpeed(float)](/api/AnimScript#setspeed-float), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### GeburahCoreAnim()

```csharp
public GeburahCoreAnim()
```

## Fields

### _currentTargetMark

```csharp
public SpriteRenderer _currentTargetMark
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### _eventHandler

```csharp
public AnimatorEventHandler _eventHandler
```

#### Field Value

**Type:** Global.AnimatorEventHandler

### _lastEffect

```csharp
public GameObject _lastEffect
```

#### Field Value

**Type:** UnityEngine.GameObject

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

#### Field Value

**Type:** UnityEngine.Color

### bloodyTreeCurve

```csharp
public AnimationCurve bloodyTreeCurve
```

#### Field Value

**Type:** UnityEngine.AnimationCurve

### DangoFollower

```csharp
public Transform DangoFollower
```

#### Field Value

**Type:** UnityEngine.Transform

### DangoNear

```csharp
public Transform DangoNear
```

#### Field Value

**Type:** UnityEngine.Transform

### EyeRenderer

```csharp
public GameObject[] EyeRenderer
```

#### Field Value

**Type:** UnityEngine.GameObject[]

### EyeTrail

```csharp
public GameObject EyeTrail
```

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

### ketherAttached

```csharp
public GameObject[] ketherAttached
```

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

#### Field Value

**Type:** UnityEngine.Transform

### TextObject

```csharp
public GameObject TextObject
```

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

### GetPartRenderer(GeneratbleRegion)

```csharp
public WorkerPartRenderer GetPartRenderer(BloodyTreeDeadScript.GeneratbleRegion region)
```

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

#### Returns

**Type:** System.Boolean

### KetherAttach()

```csharp
public void KetherAttach()
```

### LateUpdate()

```csharp
protected override void LateUpdate()
```

### MakeGeburahText(string)

```csharp
public void MakeGeburahText(string text)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

### OnAttackEnd()

```csharp
public void OnAttackEnd()
```

### OnDamage()

```csharp
public void OnDamage()
```

### OnEventCalled(int)

```csharp
public void OnEventCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnRunningEnd()

```csharp
public void OnRunningEnd()
```

### OnStartAttack(int)

```csharp
public void OnStartAttack(int attackType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `System.Int32` |  |

### OnTeleportEnd()

```csharp
public void OnTeleportEnd()
```

### OnTeleportStart()

```csharp
public void OnTeleportStart()
```

### OnThrowBloodyTree()

```csharp
public void OnThrowBloodyTree()
```

### PlayDeadMotion()

```csharp
public override void PlayDeadMotion()
```

### SetPhase(GeburahPhase)

```csharp
public void SetPhase(GeburahPhase phase)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `phase` | `GeburahBoss.GeburahPhase` |  |

### SetScript(GeburahCoreScript)

```csharp
public void SetScript(GeburahCoreScript coreScript)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `coreScript` | `Global.GeburahCoreScript` |  |

### SetTarget(UnitModel)

```csharp
public void SetTarget(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### SoundMake(string)

```csharp
public override void SoundMake(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
