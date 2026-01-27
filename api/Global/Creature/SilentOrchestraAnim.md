---
uid: Global.SilentOrchestraAnim
canonical_path: /api/Global/Creature/SilentOrchestraAnim
---

# Class SilentOrchestraAnim

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SilentOrchestraAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```

Animation handler for [The Silent Orchestra](/api/Global/Misc/SilentOrchestra).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/Global/Script/AnimScript) → [CreatureAnimScript](/api/Global/Script/CreatureAnimScript) → [CreatureAnimEventCalled](/api/Global/Creature/CreatureAnimEventCalled) → SilentOrchestraAnim

## Implements
[IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[Move()](/api/Global/Creature/CreatureAnimEventCalled#move), [Stop()](/api/Global/Creature/CreatureAnimEventCalled#stop), [Kill()](/api/Global/Creature/CreatureAnimEventCalled#kill), [Attract()](/api/Global/Creature/CreatureAnimEventCalled#attract), [Attack()](/api/Global/Creature/CreatureAnimEventCalled#attack), [AgentReset()](/api/Global/Creature/CreatureAnimEventCalled#agentreset), [SimpleReset()](/api/Global/Creature/CreatureAnimEventCalled#simplereset), [AnimatorEventInit()](/api/Global/Creature/CreatureAnimEventCalled#animatoreventinit), [CreatureAnimCall(int, CreatureBase)](/api/Global/Creature/CreatureAnimEventCalled#creatureanimcall-int-creaturebase), [AttackCalled(int)](/api/Global/Creature/CreatureAnimEventCalled#attackcalled-int), [AttackDamageTimeCalled()](/api/Global/Creature/CreatureAnimEventCalled#attackdamagetimecalled), [SoundMake(string)](/api/Global/Creature/CreatureAnimEventCalled#soundmake-string), [StopMoving()](/api/Global/Creature/CreatureAnimEventCalled#stopmoving), [SuperArmorEffectSrc](/api/Global/Script/CreatureAnimScript#superarmoreffectsrc), [head](/api/Global/Script/CreatureAnimScript#head), [superArmorEffect](/api/Global/Script/CreatureAnimScript#superarmoreffect), [updatedParameters](/api/Global/Script/CreatureAnimScript#updatedparameters), [Awake()](/api/Global/Script/CreatureAnimScript#awake), [SetParameter(string, bool)](/api/Global/Script/CreatureAnimScript#setparameter-string-bool), [LateUpdate()](/api/Global/Script/CreatureAnimScript#lateupdate), [FlipDirection(bool)](/api/Global/Script/CreatureAnimScript#flipdirection-bool), [LoadSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#loadsuperarmoreffect), [GetSuperArmor()](/api/Global/Script/CreatureAnimScript#getsuperarmor), [DeleteSuperArmorEffect()](/api/Global/Script/CreatureAnimScript#deletesuperarmoreffect), [HasDeadMotion()](/api/Global/Script/CreatureAnimScript#hasdeadmotion), [PlayDeadMotion()](/api/Global/Script/CreatureAnimScript#playdeadmotion), [PlayRevivalMotion()](/api/Global/Script/CreatureAnimScript#playrevivalmotion), [ResetAnimator()](/api/Global/Script/CreatureAnimScript#resetanimator), [animator](/api/Global/Script/AnimScript#animator), [motionDelay](/api/Global/Script/AnimScript#motiondelay), [defaultSpeed](/api/Global/Script/AnimScript#defaultspeed), [SetSpeed(float)](/api/Global/Script/AnimScript#setspeed-float), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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
#INC


#### Field Value

**Type:** UnityEngine.Canvas

### autoDisableTimer

```csharp
private AutoTimer autoDisableTimer
```
#INC


#### Field Value

**Type:** Global.AutoTimer

### canvasEffect

```csharp
public Animator canvasEffect
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### Conductor

```csharp
public GameObject Conductor
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### currentAppearIndex

```csharp
private int currentAppearIndex
```
#INC


#### Field Value

**Type:** System.Int32

### curtainAnim

```csharp
public Animator curtainAnim
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### effectCanvas

```csharp
public SilentOrchestraAnim.Effect effectCanvas
```

#### Field Value

**Type:** Global.SilentOrchestraAnim.Effect

### isClosing

```csharp
private bool isClosing
```
#INC


#### Field Value

**Type:** System.Boolean

### randTimer

```csharp
private Timer randTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### script

```csharp
private SilentOrchestra script
```
#INC


#### Field Value

**Type:** Global.SilentOrchestra

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
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### standEffect

```csharp
public GameObject standEffect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### started

```csharp
private bool started
```
#INC


#### Field Value

**Type:** System.Boolean

### ui

```csharp
public SilentOrchestraAnim.UI ui
```

#### Field Value

**Type:** Global.SilentOrchestraAnim.UI

## Properties

### conductorAnim

```csharp
private Animator conductorAnim { get; }
```

#### Property Value

**Type:** UnityEngine.Animator

## Methods

### ActivateCanvasEffect()

```csharp
public void ActivateCanvasEffect()
```
#INC


### CloseCanvas()

```csharp
public void CloseCanvas()
```
#INC


### CurtainAppear(bool)

```csharp
public void CurtainAppear(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### CurtainOpen(bool)

```csharp
public void CurtainOpen(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### FixedUpdate()

```csharp
protected override void FixedUpdate()
```
#INC
#code-generated


### GetCurrentRange()

```csharp
public Timer GetCurrentRange()
```
#INC


#### Returns

**Type:** Global.Timer

### Init()

```csharp
public void Init()
```
#INC


### InvokeActivate()

```csharp
public void InvokeActivate()
```
#INC


### InvokeFinale()

```csharp
public void InvokeFinale()
```
#INC


### InvokeStageRise()

```csharp
public void InvokeStageRise()
```
#INC


### OnAppearEnd()

```csharp
public void OnAppearEnd()
```
#INC


### OnCalled()

```csharp
public override void OnCalled()
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

### OnEscapeCancel()

```csharp
public void OnEscapeCancel()
```
#INC


### OnEscapeStart()

```csharp
public void OnEscapeStart()
```
#INC


### SetAppearAnim(int, float)

```csharp
public void SetAppearAnim(int index, float appearTime)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `appearTime` | `System.Single` |  |

### SetScript(SilentOrchestra)

```csharp
public void SetScript(SilentOrchestra script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.SilentOrchestra` |  |

### SetUIText(int)

```csharp
public void SetUIText(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### StartConductor()

```csharp
public void StartConductor()
```
#INC


### StartEffect(int, float)

```csharp
public void StartEffect(int index, float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `time` | `System.Single` |  |

### TempUIIint()

```csharp
private void TempUIIint()
```
#INC


### Update()

```csharp
public void Update()
```
#INC

