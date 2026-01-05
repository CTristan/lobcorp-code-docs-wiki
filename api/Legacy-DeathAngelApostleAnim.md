# Class DeathAngelApostleAnim

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeathAngelApostleAnim : CreatureAnimScript, IAnimatorEventCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/AnimScript) → [CreatureAnimScript](/api/CreatureAnimScript) → DeathAngelApostleAnim

## Inherited Members
[SuperArmorEffectSrc](/api/CreatureAnimScript#superarmoreffectsrc), [head](/api/CreatureAnimScript#head), [superArmorEffect](/api/CreatureAnimScript#superarmoreffect), [SetParameter(string, bool)](/api/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/CreatureAnimScript#deletesuperarmoreffect), [StopMoving()](/api/CreatureAnimScript#stopmoving), [HasDeadMotion()](/api/CreatureAnimScript#hasdeadmotion), [PlayDeadMotion()](/api/CreatureAnimScript#playdeadmotion), [PlayRevivalMotion()](/api/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/CreatureAnimScript#resetanimator), [animator](/api/AnimScript#animator), [motionDelay](/api/AnimScript#motiondelay), [defaultSpeed](/api/AnimScript#defaultspeed), [FixedUpdate()](/api/AnimScript#fixedupdate), [SetSpeed(float)](/api/AnimScript#setspeed-float), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DeathAngelApostleAnim()

```csharp
public DeathAngelApostleAnim()
```

## Fields

### apostleScript

```csharp
public Uncontrollable_DeathApostle apostleScript
```

#### Field Value

**Type:** Legacy.Uncontrollable_DeathApostle

### body

```csharp
public Transform body
```

#### Field Value

**Type:** UnityEngine.Transform

### charge

```csharp
public SpriteRenderer charge
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### currentAttackTarget

```csharp
public Text currentAttackTarget
```

#### Field Value

**Type:** UnityEngine.UI.Text

### defaultSrc

```csharp
public const string defaultSrc = "Sprites/CreatureSprite/DeathAngel/DeathAngelApostle/Mask/apostle_"
```

#### Field Value

**Type:** System.String

### eyelight

```csharp
public GameObject eyelight
```

#### Field Value

**Type:** UnityEngine.GameObject

### hair

```csharp
public SpriteRenderer hair
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### headBack

```csharp
public GameObject headBack
```

#### Field Value

**Type:** UnityEngine.GameObject

### mask1

```csharp
public SpriteRenderer mask1
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### mask2

```csharp
public SpriteRenderer mask2
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### mask3

```csharp
public SpriteRenderer mask3
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### melee

```csharp
public SpriteRenderer melee
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### meleePick

```csharp
public Transform meleePick
```

#### Field Value

**Type:** UnityEngine.Transform

### ranged

```csharp
public SpriteRenderer ranged
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### WhisperSoundMaxInterval

```csharp
public const float WhisperSoundMaxInterval = 30
```

#### Field Value

**Type:** System.Single

### WhisperSoundMinInterval

```csharp
public const float WhisperSoundMinInterval = 10
```

#### Field Value

**Type:** System.Single

### whisperTimer

```csharp
public Timer whisperTimer
```

#### Field Value

**Type:** Global.Timer

## Methods

### AgentReset()

```csharp
public void AgentReset()
```

### AnimatorEventInit()

```csharp
public void AnimatorEventInit()
```

### Attack()

```csharp
public void Attack()
```

### AttackCalled(int)

```csharp
public void AttackCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### AttackDamageTimeCalled()

```csharp
public void AttackDamageTimeCalled()
```

### Awake()

```csharp
protected override void Awake()
```

### CanMove()

```csharp
public bool CanMove()
```

#### Returns

**Type:** System.Boolean

### CreatureAnimCall(int, CreatureBase)

```csharp
public void CreatureAnimCall(int i, CreatureBase script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `script` | `Global.CreatureBase` |  |

### DieAnimSet()

```csharp
public void DieAnimSet()
```

### EffectMakeInCurrentPosGlobal(string)

```csharp
public void EffectMakeInCurrentPosGlobal(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### EndCharge(bool)

```csharp
public void EndCharge(bool hasAttach)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `hasAttach` | `System.Boolean` |  |

### EndRange()

```csharp
public void EndRange()
```

### HeadCut()

```csharp
public void HeadCut()
```

### MeleePick(WorkerUnit)

```csharp
public void MeleePick(WorkerUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.WorkerUnit` |  |

### MeleeRelease()

```csharp
public void MeleeRelease()
```

### Move()

```csharp
public override void Move()
```

### OnCalled()

```csharp
public void OnCalled()
```

### OnCalled(int)

```csharp
public void OnCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnRealDie()

```csharp
public void OnRealDie()
```

### OnResurrect()

```csharp
public void OnResurrect()
```

### OnSuppressed()

```csharp
public void OnSuppressed()
```

### ReadyCharge()

```csharp
public void ReadyCharge()
```

### ReadyMelee()

```csharp
public void ReadyMelee()
```

### ReadyRange()

```csharp
public void ReadyRange()
```

### SetScript(Uncontrollable_DeathApostle)

```csharp
public void SetScript(Uncontrollable_DeathApostle script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Legacy.Uncontrollable_DeathApostle` |  |

### SimpleReset()

```csharp
public void SimpleReset()
```

### SoundMake(string)

```csharp
public void SoundMake(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### Stop()

```csharp
public override void Stop()
```
