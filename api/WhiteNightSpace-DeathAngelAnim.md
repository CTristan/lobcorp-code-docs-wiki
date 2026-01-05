# Class DeathAngelAnim

**Namespace:** [WhiteNightSpace](/api/WhiteNightSpace)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeathAngelAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/AnimScript) → [CreatureAnimScript](/api/CreatureAnimScript) → [CreatureAnimEventCalled](/api/CreatureAnimEventCalled) → DeathAngelAnim

## Inherited Members
[Move()](/api/CreatureAnimEventCalled#move), [Stop()](/api/CreatureAnimEventCalled#stop), [Kill()](/api/CreatureAnimEventCalled#kill), [Attract()](/api/CreatureAnimEventCalled#attract), [Attack()](/api/CreatureAnimEventCalled#attack), [OnCalled()](/api/CreatureAnimEventCalled#oncalled), [AgentReset()](/api/CreatureAnimEventCalled#agentreset), [SimpleReset()](/api/CreatureAnimEventCalled#simplereset), [AnimatorEventInit()](/api/CreatureAnimEventCalled#animatoreventinit), [CreatureAnimCall(int, CreatureBase)](/api/CreatureAnimEventCalled#creatureanimcall-int-creaturebase), [AttackCalled(int)](/api/CreatureAnimEventCalled#attackcalled-int), [AttackDamageTimeCalled()](/api/CreatureAnimEventCalled#attackdamagetimecalled), [SoundMake(string)](/api/CreatureAnimEventCalled#soundmake-string), [StopMoving()](/api/CreatureAnimEventCalled#stopmoving), [SuperArmorEffectSrc](/api/CreatureAnimScript#superarmoreffectsrc), [head](/api/CreatureAnimScript#head), [superArmorEffect](/api/CreatureAnimScript#superarmoreffect), [Awake()](/api/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/CreatureAnimScript#deletesuperarmoreffect), [PlayRevivalMotion()](/api/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/CreatureAnimScript#resetanimator), [animator](/api/AnimScript#animator), [motionDelay](/api/AnimScript#motiondelay), [defaultSpeed](/api/AnimScript#defaultspeed), [FixedUpdate()](/api/AnimScript#fixedupdate), [SetSpeed(float)](/api/AnimScript#setspeed-float), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DeathAngelAnim()

```csharp
public DeathAngelAnim()
```

## Fields

### _attackCollider

```csharp
public DeathAngelAttackCollider _attackCollider
```

#### Field Value

**Type:** WhiteNightSpace.DeathAngelAttackCollider

### _attackEffect

```csharp
public GameObject _attackEffect
```

#### Field Value

**Type:** UnityEngine.GameObject

### _escapeSenseInspector

```csharp
public CreatureCameraUtil_Inspector _escapeSenseInspector
```

#### Field Value

**Type:** CreatureCameraUtil.CreatureCameraUtil_Inspector

### _eventHandler

```csharp
public AnimatorEventHandler _eventHandler
```

#### Field Value

**Type:** Global.AnimatorEventHandler

### _mouseEventSize

```csharp
public Vector2 _mouseEventSize
```

#### Field Value

**Type:** UnityEngine.Vector2

### Masks

```csharp
[Header("Mask")]
public GameObject[] Masks
```

#### Field Value

**Type:** UnityEngine.GameObject[]

### SuppressAnimator

```csharp
public Animator SuppressAnimator
```

#### Field Value

**Type:** UnityEngine.Animator

## Properties

### AdventClockUI

```csharp
public AdventClockUI AdventClockUI { get; }
```

#### Property Value

**Type:** WhiteNightSpace.AdventClockUI

### Script

```csharp
public DeathAngel Script { get; }
```

#### Property Value

**Type:** WhiteNightSpace.DeathAngel

## Methods

### ActivateSkill()

```csharp
public void ActivateSkill()
```

### HasDeadMotion()

```csharp
public override bool HasDeadMotion()
```

#### Returns

**Type:** System.Boolean

### InitApostleNames(List<string>)

```csharp
public void InitApostleNames(List<string> names)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `names` | `System.Collections.Generic.List{System.String}` |  |

### InitParam()

```csharp
public void InitParam()
```

### OnCalled(int)

```csharp
public override void OnCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnEscape()

```csharp
public void OnEscape()
```

### OnSetSuppressEffect(bool)

```csharp
public void OnSetSuppressEffect(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### PlayDeadMotion()

```csharp
public override void PlayDeadMotion()
```

### SetAdventDesc(string)

```csharp
public void SetAdventDesc(string desc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `desc` | `System.String` |  |

### SetLessMovement(bool)

```csharp
public void SetLessMovement(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetScript(DeathAngel)

```csharp
public void SetScript(DeathAngel deathAngel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `deathAngel` | `WhiteNightSpace.DeathAngel` |  |

### SetTransform(Vector3, Vector3)

```csharp
public void SetTransform(Vector3 pos, Vector3 scale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `scale` | `UnityEngine.Vector3` |  |

### StartWorkSkill(DeathAngelVoidAction)

```csharp
public void StartWorkSkill(DeathAngelVoidAction deathAngelVoidAction)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `deathAngelVoidAction` | `WhiteNightSpace.DeathAngelVoidAction` |  |
