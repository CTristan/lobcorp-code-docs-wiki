# Class SilentOrchestraAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SilentOrchestraAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/AnimScript) → [CreatureAnimScript](/api/CreatureAnimScript) → [CreatureAnimEventCalled](/api/CreatureAnimEventCalled) → SilentOrchestraAnim

## Inherited Members
[Move()](/api/CreatureAnimEventCalled#move), [Stop()](/api/CreatureAnimEventCalled#stop), [Kill()](/api/CreatureAnimEventCalled#kill), [Attract()](/api/CreatureAnimEventCalled#attract), [Attack()](/api/CreatureAnimEventCalled#attack), [AgentReset()](/api/CreatureAnimEventCalled#agentreset), [SimpleReset()](/api/CreatureAnimEventCalled#simplereset), [AnimatorEventInit()](/api/CreatureAnimEventCalled#animatoreventinit), [CreatureAnimCall(int, CreatureBase)](/api/CreatureAnimEventCalled#creatureanimcall-int-creaturebase), [AttackCalled(int)](/api/CreatureAnimEventCalled#attackcalled-int), [AttackDamageTimeCalled()](/api/CreatureAnimEventCalled#attackdamagetimecalled), [SoundMake(string)](/api/CreatureAnimEventCalled#soundmake-string), [StopMoving()](/api/CreatureAnimEventCalled#stopmoving), [SuperArmorEffectSrc](/api/CreatureAnimScript#superarmoreffectsrc), [head](/api/CreatureAnimScript#head), [superArmorEffect](/api/CreatureAnimScript#superarmoreffect), [Awake()](/api/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/CreatureAnimScript#deletesuperarmoreffect), [HasDeadMotion()](/api/CreatureAnimScript#hasdeadmotion), [PlayDeadMotion()](/api/CreatureAnimScript#playdeadmotion), [PlayRevivalMotion()](/api/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/CreatureAnimScript#resetanimator), [animator](/api/AnimScript#animator), [motionDelay](/api/AnimScript#motiondelay), [defaultSpeed](/api/AnimScript#defaultspeed), [SetSpeed(float)](/api/AnimScript#setspeed-float), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SilentOrchestraAnim()

```csharp
public SilentOrchestraAnim()
```

## Fields

### animCanvas

```csharp
public Canvas animCanvas
```

#### Field Value

**Type:** UnityEngine.Canvas

### canvasEffect

```csharp
public Animator canvasEffect
```

#### Field Value

**Type:** UnityEngine.Animator

### Conductor

```csharp
public GameObject Conductor
```

#### Field Value

**Type:** UnityEngine.GameObject

### curtainAnim

```csharp
public Animator curtainAnim
```

#### Field Value

**Type:** UnityEngine.Animator

### effectCanvas

```csharp
public SilentOrchestraAnim.Effect effectCanvas
```

#### Field Value

**Type:** Global.SilentOrchestraAnim.Effect

### singers

```csharp
public SilentOrchestraAnim.Singer[] singers
```

#### Field Value

**Type:** Global.SilentOrchestraAnim.Singer[]

### StageImage

```csharp
public GameObject StageImage
```

#### Field Value

**Type:** UnityEngine.GameObject

### standEffect

```csharp
public GameObject standEffect
```

#### Field Value

**Type:** UnityEngine.GameObject

### ui

```csharp
public SilentOrchestraAnim.UI ui
```

#### Field Value

**Type:** Global.SilentOrchestraAnim.UI

## Methods

### ActivateCanvasEffect()

```csharp
public void ActivateCanvasEffect()
```

### CloseCanvas()

```csharp
public void CloseCanvas()
```

### CurtainAppear(bool)

```csharp
public void CurtainAppear(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### CurtainOpen(bool)

```csharp
public void CurtainOpen(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### FixedUpdate()

```csharp
protected override void FixedUpdate()
```

### GetCurrentRange()

```csharp
public Timer GetCurrentRange()
```

#### Returns

**Type:** Global.Timer

### Init()

```csharp
public void Init()
```

### InvokeActivate()

```csharp
public void InvokeActivate()
```

### InvokeFinale()

```csharp
public void InvokeFinale()
```

### InvokeStageRise()

```csharp
public void InvokeStageRise()
```

### OnAppearEnd()

```csharp
public void OnAppearEnd()
```

### OnCalled()

```csharp
public override void OnCalled()
```

### OnCalled(int)

```csharp
public override void OnCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnEscapeCancel()

```csharp
public void OnEscapeCancel()
```

### OnEscapeStart()

```csharp
public void OnEscapeStart()
```

### SetAppearAnim(int, float)

```csharp
public void SetAppearAnim(int index, float appearTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `appearTime` | `System.Single` |  |

### SetScript(SilentOrchestra)

```csharp
public void SetScript(SilentOrchestra script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.SilentOrchestra` |  |

### SetUIText(int)

```csharp
public void SetUIText(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### StartConductor()

```csharp
public void StartConductor()
```

### StartEffect(int, float)

```csharp
public void StartEffect(int index, float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `time` | `System.Single` |  |

### Update()

```csharp
public void Update()
```
