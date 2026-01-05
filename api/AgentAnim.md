# Class AgentAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentAnim : AnimScript, IAnimatorEventCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/AnimScript) → AgentAnim

## Inherited Members
[animator](/api/AnimScript#animator), [motionDelay](/api/AnimScript#motiondelay), [defaultSpeed](/api/AnimScript#defaultspeed), [FixedUpdate()](/api/AnimScript#fixedupdate), [SetSpeed(float)](/api/AnimScript#setspeed-float), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AgentAnim()

```csharp
public AgentAnim()
```

## Fields

### afterReset

```csharp
public AgentAnim.AfterResetEvent afterReset
```

#### Field Value

**Type:** Global.AgentAnim.AfterResetEvent

### B_hand

```csharp
public SpriteRenderer B_hand
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### B_low_arm

```csharp
public SpriteRenderer B_low_arm
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### B_low_leg

```csharp
public SpriteRenderer B_low_leg
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### B_up_arm

```csharp
public SpriteRenderer B_up_arm
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### B_up_leg

```csharp
public SpriteRenderer B_up_leg
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### body

```csharp
public SpriteRenderer body
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### currentFaceSprite

```csharp
public Sprite currentFaceSprite
```

#### Field Value

**Type:** UnityEngine.Sprite

### F_hand

```csharp
public SpriteRenderer F_hand
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### F_low_arm

```csharp
public SpriteRenderer F_low_arm
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### F_low_leg

```csharp
public SpriteRenderer F_low_leg
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### F_up_arm

```csharp
public SpriteRenderer F_up_arm
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### F_up_leg

```csharp
public SpriteRenderer F_up_leg
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### face

```csharp
public SpriteRenderer face
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### faceSprites

```csharp
public Sprite[] faceSprites
```

#### Field Value

**Type:** UnityEngine.Sprite[]

### GunFlamePos

```csharp
public Transform GunFlamePos
```

#### Field Value

**Type:** UnityEngine.Transform

### hair

```csharp
public SpriteRenderer hair
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### Melee

```csharp
public SpriteRenderer Melee
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### panicDefFace

```csharp
public SpriteRenderer panicDefFace
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### panicMouth1

```csharp
public SpriteRenderer panicMouth1
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### panicMouth2

```csharp
public SpriteRenderer panicMouth2
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### Ranged

```csharp
public SpriteRenderer Ranged
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### Symbol

```csharp
public SpriteRenderer Symbol
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

## Properties

### Model

```csharp
public WorkerModel Model { get; }
```

#### Property Value

**Type:** Global.WorkerModel

### spriteSet

```csharp
public WorkerSpriteSet spriteSet { get; }
```

#### Property Value

**Type:** Global.WorkerSpriteSet

## Methods

### AfterDeadAnimPlayed()

```csharp
public void AfterDeadAnimPlayed()
```

### AfterResetGetControl()

```csharp
public void AfterResetGetControl()
```

### AgentReset()

```csharp
public void AgentReset()
```

### AgentResetIgnoreFileCheck()

```csharp
public void AgentResetIgnoreFileCheck()
```

### AnimatorEventInit()

```csharp
public void AnimatorEventInit()
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

### AttackedEffect(AgentAnimPos, string)

```csharp
public void AttackedEffect(AgentAnimPos pos, string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `Global.AgentAnimPos` |  |
| `src` | `System.String` |  |

### AttackedEffectByRandomPos(string)

```csharp
public void AttackedEffectByRandomPos(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### AttackedEffectHeadPos(string)

```csharp
public GameObject AttackedEffectHeadPos(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject

### AttackedEffectInBodyPos(string)

```csharp
public GameObject AttackedEffectInBodyPos(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject

### ChangeFaceSprite(Sprite)

```csharp
public void ChangeFaceSprite(Sprite s)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `UnityEngine.Sprite` |  |

### ChangeFaceToDefault()

```csharp
public void ChangeFaceToDefault()
```

### CreatureAnimCall(int, CreatureBase)

```csharp
public void CreatureAnimCall(int i, CreatureBase script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `script` | `Global.CreatureBase` |  |

### EffectMakeInCurrentPos(string)

```csharp
public void EffectMakeInCurrentPos(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### EffectMakeInCurrentPosGlobal(string)

```csharp
public void EffectMakeInCurrentPosGlobal(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### FlipDirection(bool)

```csharp
public void FlipDirection(bool b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `System.Boolean` |  |

### GetBodyPos(AgentAnimPos)

```csharp
public Transform GetBodyPos(AgentAnimPos animPos)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animPos` | `Global.AgentAnimPos` |  |

#### Returns

**Type:** UnityEngine.Transform

### GetFlipDirection()

```csharp
public bool GetFlipDirection()
```

#### Returns

**Type:** System.Boolean

### GetHaltDirectionUpdate()

```csharp
public bool GetHaltDirectionUpdate()
```

#### Returns

**Type:** System.Boolean

### GetIsLookingLeft()

```csharp
public bool GetIsLookingLeft()
```

#### Returns

**Type:** System.Boolean

### Init(WorkerModel)

```csharp
public void Init(WorkerModel am)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `am` | `Global.WorkerModel` |  |

### IsAttackMotion()

```csharp
public bool IsAttackMotion()
```

#### Returns

**Type:** System.Boolean

### LoadWeaponSprite()

```csharp
public void LoadWeaponSprite()
```

### LookLeft()

```csharp
public void LookLeft()
```

### LookRight()

```csharp
public void LookRight()
```

### MakeGunFlame()

```csharp
public void MakeGunFlame()
```

### MakeScreamer()

```csharp
public void MakeScreamer()
```

### OffPanicFace()

```csharp
public void OffPanicFace()
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

### OnDead()

```csharp
public void OnDead()
```

### OnDieAnimCheck()

```csharp
public void OnDieAnimCheck()
```

### PanicActionEventCalled(int)

```csharp
public void PanicActionEventCalled(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### ParamResetToZero(string)

```csharp
public void ParamResetToZero(string pName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pName` | `System.String` |  |

### PlaySound(string, string, bool)

```csharp
public void PlaySound(string src, string key, bool isLoop)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `key` | `System.String` |  |
| `isLoop` | `System.Boolean` |  |

### PlaySoundOneShot(string)

```csharp
public void PlaySoundOneShot(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### PresetPanicFaceByRandom(string, int)

```csharp
public void PresetPanicFaceByRandom(string dir, int range)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dir` | `System.String` |  |
| `range` | `System.Int32` |  |

### ReleaseFlip()

```csharp
public void ReleaseFlip()
```

### ResetAnimator()

```csharp
public void ResetAnimator()
```

### SetFace(Sprite)

```csharp
public void SetFace(Sprite sprite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sprite` | `UnityEngine.Sprite` |  |

### SetHair(Sprite)

```csharp
public void SetHair(Sprite sprite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sprite` | `UnityEngine.Sprite` |  |

### SetPanicFace()

```csharp
public void SetPanicFace()
```

### SetParameterForSecond(string, bool, float)

```csharp
public void SetParameterForSecond(string pname, bool value, float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pname` | `System.String` |  |
| `value` | `System.Boolean` |  |
| `time` | `System.Single` |  |

### SetParameterForSecond(string, int, float)

```csharp
public void SetParameterForSecond(string pname, int value, float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pname` | `System.String` |  |
| `value` | `System.Int32` |  |
| `time` | `System.Single` |  |

### SetWorkerSprite(WorkerSpriteSet)

```csharp
public void SetWorkerSprite(WorkerSpriteSet spriteSet)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spriteSet` | `Global.WorkerSpriteSet` |  |

### ShortInit(WorkerModel)

```csharp
public void ShortInit(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### ShowCreatureActionSpeech(string)

```csharp
public void ShowCreatureActionSpeech(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

### ShowUnconActionSpeech(string)

```csharp
public void ShowUnconActionSpeech(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

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

### Update()

```csharp
public void Update()
```
