---
uid: Global.NewTitleScript
canonical_path: /api/Global/IANimatorEventCalled/NewTitleScript
---

# Class NewTitleScript

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class NewTitleScript : MonoBehaviour, ILanguageLinkedData, IAnimatorEventCalled
```

The title screen.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → NewTitleScript

## Implements
[ILanguageLinkedData](/api/Global/Misc/ILanguageLinkedData), [IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### NewTitleScript()

```csharp
public NewTitleScript()
```

## Fields

### _effectStarted

```csharp
private bool _effectStarted
```
#INC


#### Field Value

**Type:** System.Boolean

### _end

```csharp
private NewTitleScript.OnMoveEndDelegate _end
```

#### Field Value

**Type:** Global.NewTitleScript.OnMoveEndDelegate

### _gadgets

```csharp
public UIController _gadgets
```
#INC


#### Field Value

**Type:** Global.UIController

### _instance

```csharp
private static NewTitleScript _instance
```
#INC


#### Field Value

**Type:** Global.NewTitleScript

### _isOpenedOption

```csharp
private bool _isOpenedOption
```
#INC


#### Field Value

**Type:** System.Boolean

### _pinned

```csharp
private bool _pinned
```
#INC


#### Field Value

**Type:** System.Boolean

### AnchorY

```csharp
public float[] AnchorY
```
#INC


#### Field Value

**Type:** System.Single[]

### audioClipPlayer

```csharp
public AudioClipPlayer audioClipPlayer
```
#INC


#### Field Value

**Type:** Global.AudioClipPlayer

### BaseModButton

```csharp
private GameObject BaseModButton
```

#### Field Value

**Type:** UnityEngine.GameObject

### ButtonAreaGroup

```csharp
public CanvasGroup ButtonAreaGroup
```
#INC


#### Field Value

**Type:** UnityEngine.CanvasGroup

### challengeText

```csharp
public Text challengeText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### chalMenuActivated

```csharp
private bool chalMenuActivated
```
#INC


#### Field Value

**Type:** System.Boolean

### cn_trCanvas

```csharp
public GameObject cn_trCanvas
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### cnCanvas

```csharp
public GameObject cnCanvas
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### continueGameObject

```csharp
public GameObject continueGameObject
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### continueText

```csharp
public Text continueText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### contMenuActivated

```csharp
private bool contMenuActivated
```
#INC


#### Field Value

**Type:** System.Boolean

### dayCount

```csharp
public Text dayCount
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### defRoot

```csharp
public GameObject defRoot
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### Disabled

```csharp
public Color Disabled
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### eventColorSettingChallenge

```csharp
public EventColorSetting eventColorSettingChallenge
```
#INC


#### Field Value

**Type:** Global.EventColorSetting

### eventColorSettingContinue

```csharp
public EventColorSetting eventColorSettingContinue
```
#INC


#### Field Value

**Type:** Global.EventColorSetting

### GameVersionChecker

```csharp
public Text GameVersionChecker
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### hiddenOverlay

```csharp
public Image[] hiddenOverlay
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image[]

### hiddenRoot

```csharp
public GameObject hiddenRoot
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### isAlter

```csharp
public bool isAlter
```
#INC


#### Field Value

**Type:** System.Boolean

### isNewGame

```csharp
private bool isNewGame
```
#INC


#### Field Value

**Type:** System.Boolean

### jpCanvas

```csharp
public GameObject jpCanvas
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### LogoAnimator

```csharp
public Animator LogoAnimator
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### MenuPanelAnim

```csharp
public Animator MenuPanelAnim
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### newGameObject

```csharp
public GameObject newGameObject
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### newGameTooltip

```csharp
public GameObject newGameTooltip
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### nextLoading

```csharp
private bool nextLoading
```
#INC


#### Field Value

**Type:** System.Boolean

### OptionWindow

```csharp
public RectTransform OptionWindow
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### overlayTortal

```csharp
public GameObject overlayTortal
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### overlayWithDay

```csharp
public GameObject overlayWithDay
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### overlayWithoutDay

```csharp
public GameObject overlayWithoutDay
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### ruCanvas

```csharp
public GameObject ruCanvas
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### StartAndResetText

```csharp
public Text StartAndResetText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### StartEffectTime

```csharp
private Timer StartEffectTime
```
#INC


#### Field Value

**Type:** Global.Timer

### StartEffectTimer

```csharp
public float StartEffectTimer
```
#INC


#### Field Value

**Type:** System.Single

### StartNewSceneControl

```csharp
public Animator StartNewSceneControl
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### TitleBgm

```csharp
public AudioSource TitleBgm
```
#INC


#### Field Value

**Type:** UnityEngine.AudioSource

### TitleEffectAnimator

```csharp
public Animator TitleEffectAnimator
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### titleObjects

```csharp
public NewTitleScript.TitleObject[] titleObjects
```

#### Field Value

**Type:** Global.NewTitleScript.TitleObject[]

### translationCanvas

```csharp
[Header("Translation Credits")]
public UIController translationCanvas
```

#### Field Value

**Type:** Global.UIController

### vnCanvas

```csharp
public GameObject vnCanvas
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

## Properties

### currentLanguage

```csharp
private string currentLanguage { get; }
```

#### Property Value

**Type:** System.String

### instance

```csharp
public static NewTitleScript instance { get; }
```

#### Property Value

**Type:** Global.NewTitleScript

### IsOpenedOption

```csharp
public bool IsOpenedOption { get; set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### AgentReset()

```csharp
public void AgentReset()
```
#INC


### AnimatorEventInit()

```csharp
public void AnimatorEventInit()
```
#INC


### AttackCalled(int)

```csharp
public void AttackCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### AttackDamageTimeCalled()

```csharp
public void AttackDamageTimeCalled()
```
#INC


### Awake()

```csharp
private void Awake()
```
#INC


### CheckFont()

```csharp
private void CheckFont()
```
#INC


### ClickAfterContinue()

```csharp
private void ClickAfterContinue()
```
#INC


### ClickAfterNewGame()

```csharp
private void ClickAfterNewGame()
```
#INC


### ClickAfterTutorial()

```csharp
public void ClickAfterTutorial()
```
#INC


### CreatureAnimCall(int, CreatureBase)

```csharp
public void CreatureAnimCall(int i, CreatureBase script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `script` | `Global.CreatureBase` |  |

### DeleteMaxObserveData()

```csharp
private void DeleteMaxObserveData()
```
#INC


### GetObject(int)

```csharp
public NewTitleScript.TitleObject GetObject(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.NewTitleScript.TitleObject

### HiddenButtonEnter(int)

```csharp
public void HiddenButtonEnter(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### HiddenButtonExit(int)

```csharp
public void HiddenButtonExit(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### Init()

```csharp
private void Init()
```
#INC


### LoadMainGame()

```csharp
public void LoadMainGame()
```
#INC


### LoadStoryMode()

```csharp
public void LoadStoryMode()
```
#INC


### LoadTutorial()

```csharp
public void LoadTutorial()
```
#INC


### MoveToStoryTester()

```csharp
public void MoveToStoryTester()
```
#INC


### OnCalled()

```csharp
public void OnCalled()
```
#INC


### OnCalled(int)

```csharp
public void OnCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnCickReset(int)

```csharp
public void OnCickReset(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnClickCloseTutorial()

```csharp
public void OnClickCloseTutorial()
```
#INC


### OnClickContinue()

```csharp
public void OnClickContinue()
```
#INC


### OnClickCredit()

```csharp
public void OnClickCredit()
```
#INC


### OnClickExitGame()

```csharp
public void OnClickExitGame()
```
#INC


### OnClickHiddenButton()

```csharp
public void OnClickHiddenButton()
```
#INC


### OnClickHiddenNo()

```csharp
public void OnClickHiddenNo()
```
#INC


### OnClickHiddenYes()

```csharp
public void OnClickHiddenYes()
```
#INC


### OnClickInfinite()

```csharp
public void OnClickInfinite()
```
#INC


### OnClickLanguage(int)

```csharp
public void OnClickLanguage(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnClickNewGame()

```csharp
public void OnClickNewGame()
```
#INC


### OnClickOption()

```csharp
public void OnClickOption()
```
#INC


### OnClickTutorial()

```csharp
public void OnClickTutorial()
```
#INC


### OnClickTutorial(int)

```csharp
public void OnClickTutorial(int step)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `step` | `System.Int32` |  |

### OnEffectRun()

```csharp
public void OnEffectRun()
```
#INC


### OnEnterCredit()

```csharp
public void OnEnterCredit()
```
#INC


### OnExitCredit()

```csharp
public void OnExitCredit()
```
#INC


### OnLanguageChanged()

```csharp
public void OnLanguageChanged()
```
#INC


### OnMoveEnd()

```csharp
public void OnMoveEnd()
```
#INC


### OnNewGameEnter()

```csharp
public void OnNewGameEnter()
```
#INC


### OnNewGameExit()

```csharp
public void OnNewGameExit()
```
#INC


### OnPointerEnter(int)

```csharp
public void OnPointerEnter(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

### OnPointerExit(int)

```csharp
public void OnPointerExit(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

### OnReset()

```csharp
private void OnReset()
```
#INC


### OnSetLanguage(string)

```csharp
public void OnSetLanguage(string language)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `language` | `System.String` |  |

### OnSetOption(bool)

```csharp
private void OnSetOption(bool state)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### OpenCodex()

```csharp
public void OpenCodex()
```
#INC


### Reload()

```csharp
private IEnumerator Reload()
```
#INC


#### Returns

**Type:** System.Collections.IEnumerator

### Reset()

```csharp
private void Reset()
```
#INC


### SetCreditLayout(int)

```csharp
public void SetCreditLayout(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### ShowBaseMod()

```csharp
private void ShowBaseMod()
```

### SimpleReset()

```csharp
public void SimpleReset()
```
#INC


### SoundMake(string)

```csharp
public void SoundMake(string src)
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


### StartLogoEffect()

```csharp
public void StartLogoEffect()
```
#INC


### Update()

```csharp
private void Update()
```
#INC

