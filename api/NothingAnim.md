# Class NothingAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class NothingAnim : CreatureAnimScript, IAnimatorEventCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/AnimScript) → [CreatureAnimScript](/api/CreatureAnimScript) → NothingAnim

## Inherited Members
[SuperArmorEffectSrc](/api/CreatureAnimScript#superarmoreffectsrc), [head](/api/CreatureAnimScript#head), [superArmorEffect](/api/CreatureAnimScript#superarmoreffect), [SetParameter(string, bool)](/api/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/CreatureAnimScript#deletesuperarmoreffect), [ResetAnimator()](/api/CreatureAnimScript#resetanimator), [animator](/api/AnimScript#animator), [motionDelay](/api/AnimScript#motiondelay), [defaultSpeed](/api/AnimScript#defaultspeed), [FixedUpdate()](/api/AnimScript#fixedupdate), [SetSpeed(float)](/api/AnimScript#setspeed-float), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### NothingAnim()

```csharp
public NothingAnim()
```

## Fields

### changeEffect

```csharp
public Animator changeEffect
```

#### Field Value

**Type:** UnityEngine.Animator

### eggNode

```csharp
public Animator eggNode
```

#### Field Value

**Type:** UnityEngine.Animator

### hookLineEndPintTransform

```csharp
public Transform hookLineEndPintTransform
```

#### Field Value

**Type:** UnityEngine.Transform

### hookLineStartPointTransform

```csharp
public Transform hookLineStartPointTransform
```

#### Field Value

**Type:** UnityEngine.Transform

### hookLineTransform

```csharp
public Transform hookLineTransform
```

#### Field Value

**Type:** UnityEngine.Transform

### lv1HandAttack

```csharp
public Transform lv1HandAttack
```

#### Field Value

**Type:** UnityEngine.Transform

### Lv1Node

```csharp
public Animator Lv1Node
```

#### Field Value

**Type:** UnityEngine.Animator

### lv2HandAttack

```csharp
public Transform lv2HandAttack
```

#### Field Value

**Type:** UnityEngine.Transform

### Lv2Node

```csharp
public Animator Lv2Node
```

#### Field Value

**Type:** UnityEngine.Animator

### model

```csharp
public CreatureModel model
```

#### Field Value

**Type:** Global.CreatureModel

### screenEffectPrefab

```csharp
public GameObject screenEffectPrefab
```

#### Field Value

**Type:** UnityEngine.GameObject

### snipingUIPrefab

```csharp
public GameObject snipingUIPrefab
```

#### Field Value

**Type:** UnityEngine.GameObject

### spearTransform

```csharp
public Transform spearTransform
```

#### Field Value

**Type:** UnityEngine.Transform

## Methods

### AgentReset()

```csharp
public void AgentReset()
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

### AttackLv2()

```csharp
public void AttackLv2()
```

### AttackLv2Strike()

```csharp
public void AttackLv2Strike()
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

### CastHook()

```csharp
public void CastHook()
```

### ChangeForm(NothingForm)

```csharp
public void ChangeForm(Nothing.NothingForm form)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `form` | `Global.Nothing.NothingForm` |  |

### CreatureAnimCall(int, CreatureBase)

```csharp
public void CreatureAnimCall(int i, CreatureBase script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `script` | `Global.CreatureBase` |  |

### HasDeadMotion()

```csharp
public override bool HasDeadMotion()
```

#### Returns

**Type:** System.Boolean

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

### PlayChangeEffectAnimation()

```csharp
public void PlayChangeEffectAnimation()
```

### PlayDeadMotion()

```csharp
public override void PlayDeadMotion()
```

### PlayRevivalMotion()

```csharp
public override void PlayRevivalMotion()
```

### PrepareSpear()

```csharp
public void PrepareSpear()
```

### SetModel(CreatureModel)

```csharp
public void SetModel(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### ShowSnipingUI()

```csharp
public NothingSnipingUI ShowSnipingUI()
```

#### Returns

**Type:** Global.NothingSnipingUI

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

### StartSnipingEffect()

```csharp
public void StartSnipingEffect()
```

### Stop()

```csharp
public override void Stop()
```

### StopMoving()

```csharp
public override void StopMoving()
```

### UpdateHookLine(Vector3, Vector3)

```csharp
public void UpdateHookLine(Vector3 start, Vector3 end)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `start` | `UnityEngine.Vector3` |  |
| `end` | `UnityEngine.Vector3` |  |
