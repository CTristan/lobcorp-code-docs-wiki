# Class IsolateRoom

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class IsolateRoom : MonoBehaviour, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → IsolateRoom

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### IsolateRoom()

```csharp
public IsolateRoom()
```

## Fields

### addedFilter

```csharp
[HideInInspector]
public List<IsolateFilter> addedFilter
```

#### Field Value

**Type:** System.Collections.Generic.List{IsolateFilter}

### attachmentPos

```csharp
public IsolatePos attachmentPos
```

#### Field Value

**Type:** Global.IsolatePos

### audioClipPlayer

```csharp
public AudioClipPlayer audioClipPlayer
```

#### Field Value

**Type:** Global.AudioClipPlayer

### binahOverloadUI

```csharp
public BinahOverloadUI binahOverloadUI
```

#### Field Value

**Type:** BinahBoss.BinahOverloadUI

### CancelColor

```csharp
public Color CancelColor
```

#### Field Value

**Type:** UnityEngine.Color

### CancelWork

```csharp
public Image CancelWork
```

#### Field Value

**Type:** UnityEngine.UI.Image

### ClickIsolateArea

```csharp
public Canvas ClickIsolateArea
```

#### Field Value

**Type:** UnityEngine.Canvas

### ClickNameArea

```csharp
public Canvas ClickNameArea
```

#### Field Value

**Type:** UnityEngine.Canvas

### ColorSetted

```csharp
public List<MaskableGraphic> ColorSetted
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### CounterActiveControl

```csharp
[Header("EscapeCounter")]
public GameObject CounterActiveControl
```

#### Field Value

**Type:** UnityEngine.GameObject

### CounterColor

```csharp
public Image CounterColor
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CounterColor_Black

```csharp
public Color CounterColor_Black
```

#### Field Value

**Type:** UnityEngine.Color

### CounterColor_Normal

```csharp
public Color CounterColor_Normal
```

#### Field Value

**Type:** UnityEngine.Color

### CounterColor_Red

```csharp
public Color CounterColor_Red
```

#### Field Value

**Type:** UnityEngine.Color

### CounterColor_White

```csharp
public Color CounterColor_White
```

#### Field Value

**Type:** UnityEngine.Color

### CounterImage_None

```csharp
public Sprite CounterImage_None
```

#### Field Value

**Type:** UnityEngine.Sprite

### CounterImage_Unknown

```csharp
public Sprite CounterImage_Unknown
```

#### Field Value

**Type:** UnityEngine.Sprite

### CounterInnerImage

```csharp
public Image CounterInnerImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CounterOutline

```csharp
public GameObject CounterOutline
```

#### Field Value

**Type:** UnityEngine.GameObject

### CounterText

```csharp
public Text CounterText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### CreatureName

```csharp
public Text CreatureName
```

#### Field Value

**Type:** UnityEngine.UI.Text

### CreatureNameImage

```csharp
public Image CreatureNameImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CubeGridRoot

```csharp
public GameObject CubeGridRoot
```

#### Field Value

**Type:** UnityEngine.GameObject

### CumlativeCrossImage

```csharp
public Image CumlativeCrossImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CumlativeCubeCount

```csharp
public Text CumlativeCubeCount
```

#### Field Value

**Type:** UnityEngine.UI.Text

### CumlativeCubeImage

```csharp
public Image CumlativeCubeImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CurrentObserveLevel

```csharp
public Text CurrentObserveLevel
```

#### Field Value

**Type:** UnityEngine.UI.Text

### CurrentObserveLevelFill

```csharp
public Image CurrentObserveLevelFill
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CurrentResultCooltime

```csharp
public Text CurrentResultCooltime
```

#### Field Value

**Type:** UnityEngine.UI.Text

### CurrentResultFilter

```csharp
public Image CurrentResultFilter
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CurrentResultIcon

```csharp
public Image CurrentResultIcon
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CurrentWorkCubeFill

```csharp
public Image CurrentWorkCubeFill
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CurrentWorkCubeText

```csharp
public Text CurrentWorkCubeText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### CurrentWorkIcon

```csharp
public Image CurrentWorkIcon
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CurrentWorkRoot

```csharp
public GameObject CurrentWorkRoot
```

#### Field Value

**Type:** UnityEngine.GameObject

### DamageFilter

```csharp
public Image DamageFilter
```

#### Field Value

**Type:** UnityEngine.UI.Image

### DefaultEscapeFilter

```csharp
public Image DefaultEscapeFilter
```

#### Field Value

**Type:** UnityEngine.UI.Image

### DescController

```csharp
public IsolateDescController DescController
```

#### Field Value

**Type:** Assets.Scripts.UI.Isolate.IsolateDescController

### EscapeCubeSprite

```csharp
public Sprite EscapeCubeSprite
```

#### Field Value

**Type:** UnityEngine.Sprite

### EscapeFilter

```csharp
public IsolateFilter EscapeFilter
```

#### Field Value

**Type:** Global.IsolateFilter

### FailCubeGrid

```csharp
public RectTransform FailCubeGrid
```

#### Field Value

**Type:** UnityEngine.RectTransform

### FailCubeObject

```csharp
public GameObject FailCubeObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### Frame

```csharp
public Image Frame
```

#### Field Value

**Type:** UnityEngine.UI.Image

### kitCreatureUIs

```csharp
public List<GameObject> kitCreatureUIs
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### KitDisable

```csharp
public Color KitDisable
```

#### Field Value

**Type:** UnityEngine.Color

### KitNormal

```csharp
public Color KitNormal
```

#### Field Value

**Type:** UnityEngine.Color

### KitObserveLevel

```csharp
public Text[] KitObserveLevel
```

#### Field Value

**Type:** UnityEngine.UI.Text[]

### KitObserveRoot

```csharp
[Header("KitCreatureObserveLevel")]
public GameObject KitObserveRoot
```

#### Field Value

**Type:** UnityEngine.GameObject

### MaxWorkCountFilter

```csharp
public GameObject MaxWorkCountFilter
```

#### Field Value

**Type:** UnityEngine.GameObject

### MaxWorkCountLine

```csharp
public GameObject MaxWorkCountLine
```

#### Field Value

**Type:** UnityEngine.GameObject

### MaxWorkText_Lower

```csharp
public Text MaxWorkText_Lower
```

#### Field Value

**Type:** UnityEngine.UI.Text

### MaxWorkText_Upper

```csharp
public Text MaxWorkText_Upper
```

#### Field Value

**Type:** UnityEngine.UI.Text

### MovingColor

```csharp
public Color MovingColor
```

#### Field Value

**Type:** UnityEngine.Color

### NameTextColor

```csharp
public Color NameTextColor
```

#### Field Value

**Type:** UnityEngine.Color

### NameTextureColor

```csharp
public Color NameTextureColor
```

#### Field Value

**Type:** UnityEngine.Color

### NarrationFadeEffect

```csharp
public FadeEffecter NarrationFadeEffect
```

#### Field Value

**Type:** Global.FadeEffecter

### normalCreatureUIs

```csharp
public List<GameObject> normalCreatureUIs
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### NormalCubeSprite

```csharp
public Sprite NormalCubeSprite
```

#### Field Value

**Type:** UnityEngine.Sprite

### OrderColor

```csharp
public Color OrderColor
```

#### Field Value

**Type:** UnityEngine.Color

### OverlayImage

```csharp
[Header("Overlay")]
public Image OverlayImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### OverlayText

```csharp
public Text OverlayText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### overloadUI

```csharp
[Header("Overload")]
public IsolateOverload overloadUI
```

#### Field Value

**Type:** Global.IsolateOverload

### probReductionText

```csharp
public Text probReductionText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### probReductionUI

```csharp
public Animator probReductionUI
```

#### Field Value

**Type:** UnityEngine.Animator

### RabbitBlock

```csharp
public GameObject RabbitBlock
```

#### Field Value

**Type:** UnityEngine.GameObject

### RiskLevelImage

```csharp
public Image RiskLevelImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### RoomColor

```csharp
public Color RoomColor
```

#### Field Value

**Type:** UnityEngine.Color

### RoomFog

```csharp
public Image RoomFog
```

#### Field Value

**Type:** UnityEngine.UI.Image

### RoomSpriteRenderer

```csharp
public SpriteRenderer RoomSpriteRenderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### SkillFilter

```csharp
public IsolateFilter SkillFilter
```

#### Field Value

**Type:** Global.IsolateFilter

### SpecialSkillName

```csharp
public Text SpecialSkillName
```

#### Field Value

**Type:** UnityEngine.UI.Text

### SpecialSkillRoot

```csharp
public GameObject SpecialSkillRoot
```

#### Field Value

**Type:** UnityEngine.GameObject

### StateFilter

```csharp
[Header("Filter")]
public IsolateFilter StateFilter
```

#### Field Value

**Type:** Global.IsolateFilter

### SuccessCubeGrid

```csharp
public RectTransform SuccessCubeGrid
```

#### Field Value

**Type:** UnityEngine.RectTransform

### SuccessCubeObject

```csharp
public GameObject SuccessCubeObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### SuppressColor

```csharp
public Color SuppressColor
```

#### Field Value

**Type:** UnityEngine.Color

### TooltipAllAgentDead

```csharp
public TooltipMouseOver TooltipAllAgentDead
```

#### Field Value

**Type:** Global.TooltipMouseOver

### TooltipCurrentPE

```csharp
public TooltipMouseOver TooltipCurrentPE
```

#### Field Value

**Type:** Global.TooltipMouseOver

### TooltipGeneratedPE

```csharp
public TooltipMouseOver TooltipGeneratedPE
```

#### Field Value

**Type:** Global.TooltipMouseOver

### TooltipName

```csharp
[Header("UI Tooltips")]
public TooltipMouseOver TooltipName
```

#### Field Value

**Type:** Global.TooltipMouseOver

### TooltipOverload

```csharp
public TooltipMouseOver TooltipOverload
```

#### Field Value

**Type:** Global.TooltipMouseOver

### TooltipQliphoth

```csharp
public TooltipMouseOver TooltipQliphoth
```

#### Field Value

**Type:** Global.TooltipMouseOver

### TooltipReduceProb

```csharp
public TooltipMouseOver TooltipReduceProb
```

#### Field Value

**Type:** Global.TooltipMouseOver

### TooltipRiskLevel

```csharp
public TooltipMouseOver TooltipRiskLevel
```

#### Field Value

**Type:** Global.TooltipMouseOver

### TooltipUniquePE

```csharp
public TooltipMouseOver TooltipUniquePE
```

#### Field Value

**Type:** Global.TooltipMouseOver

### TouchArea

```csharp
[Header("UI Component")]
public RectTransform TouchArea
```

#### Field Value

**Type:** UnityEngine.RectTransform

### workCount

```csharp
public Text workCount
```

#### Field Value

**Type:** UnityEngine.UI.Text

### WorkCount_Disabled

```csharp
public Color WorkCount_Disabled
```

#### Field Value

**Type:** UnityEngine.Color

### WorkCount_Enabled

```csharp
public Color WorkCount_Enabled
```

#### Field Value

**Type:** UnityEngine.Color

### WorkCounterActiveControl

```csharp
[Header("WorkCounter")]
public GameObject WorkCounterActiveControl
```

#### Field Value

**Type:** UnityEngine.GameObject

### WorkCounterImage

```csharp
public List<Image> WorkCounterImage
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.Image}

### WorkCounterRayout

```csharp
public RectTransform WorkCounterRayout
```

#### Field Value

**Type:** UnityEngine.RectTransform

### WorkCounterUnit

```csharp
public GameObject WorkCounterUnit
```

#### Field Value

**Type:** UnityEngine.GameObject

### WorkDescFreq

```csharp
public float WorkDescFreq
```

#### Field Value

**Type:** System.Single

### WorkGear

```csharp
public Image WorkGear
```

#### Field Value

**Type:** UnityEngine.UI.Image

### WorkNarration

```csharp
public Text WorkNarration
```

#### Field Value

**Type:** UnityEngine.UI.Text

## Properties

### ProgressBar

```csharp
public IsolateRoom.WorkProgress ProgressBar { get; }
```

#### Property Value

**Type:** Global.IsolateRoom.WorkProgress

### TargetClick

```csharp
public PointerEventData.InputButton TargetClick { get; set; }
```

#### Property Value

**Type:** UnityEngine.EventSystems.PointerEventData.InputButton

### TargetUnit

```csharp
public CreatureUnit TargetUnit { get; }
```

#### Property Value

**Type:** Global.CreatureUnit

## Methods

### ActivatedSkill()

```csharp
public void ActivatedSkill()
```

### AddFilter(IsolateFilter)

```csharp
public IsolateFilter AddFilter(IsolateFilter baseFilter)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `baseFilter` | `Global.IsolateFilter` |  |

#### Returns

**Type:** Global.IsolateFilter

### CheckQliphothCounter()

```csharp
public void CheckQliphothCounter()
```

### CheckWorkProcessText()

```csharp
public void CheckWorkProcessText()
```

### DisableWorkIcon()

```csharp
public void DisableWorkIcon()
```

### GetCurrentWorkSpeed()

```csharp
public float GetCurrentWorkSpeed()
```

#### Returns

**Type:** System.Single

### GetStateText(string)

```csharp
public string GetStateText(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### Init()

```csharp
public void Init()
```

### OnCancelWork()

```csharp
public void OnCancelWork()
```

### OnChangeProbReduction()

```csharp
public void OnChangeProbReduction()
```

### OnClick(BaseEventData)

```csharp
public void OnClick(BaseEventData eventData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnClickCollectionButton(BaseEventData)

```csharp
public void OnClickCollectionButton(BaseEventData eventData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnCubeArrived()

```csharp
public void OnCubeArrived()
```

### OnCurrentWorkRootAnimEnd()

```csharp
public void OnCurrentWorkRootAnimEnd()
```

### OnDamageAnimArrived()

```csharp
public void OnDamageAnimArrived()
```

### OnDamageInvoked(DamageInfo)

```csharp
public void OnDamageInvoked(DamageInfo damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `Global.DamageInfo` |  |

### OnDescriptionUnitEnded(int)

```csharp
public void OnDescriptionUnitEnded(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

### OnEnterRoom(AgentModel, UseSkill)

```csharp
public void OnEnterRoom(AgentModel worker, UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.AgentModel` |  |
| `skill` | `Global.UseSkill` |  |

### OnEscape()

```csharp
public void OnEscape()
```

### OnExitRoom()

```csharp
public void OnExitRoom()
```

### OnFeelingStateDisplayEnd()

```csharp
public void OnFeelingStateDisplayEnd()
```

### OnFeelingStateDisplayStart(CreatureFeelingState)

```csharp
public void OnFeelingStateDisplayStart(CreatureFeelingState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.CreatureFeelingState` |  |

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnObservationLevelChanged()

```csharp
public void OnObservationLevelChanged()
```

### OnOvelrayEnter(int)

```csharp
public void OnOvelrayEnter(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnOverlayExit(int)

```csharp
public void OnOverlayExit(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnReturn()

```csharp
public void OnReturn()
```

### OnWorkAllocated(AgentModel)

```csharp
public void OnWorkAllocated(AgentModel incomingWorker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `incomingWorker` | `Global.AgentModel` |  |

### OnWorkEnd()

```csharp
public void OnWorkEnd()
```

### ProcessNarration(string)

```csharp
public void ProcessNarration(string desc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `desc` | `System.String` |  |

### SetBinahBoss()

```csharp
public void SetBinahBoss()
```

### SetCounterEnable(bool)

```csharp
public void SetCounterEnable(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetCounterText(string)

```csharp
public void SetCounterText(string text)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

### SetCounterText(string, Color)

```csharp
public void SetCounterText(string text, Color color)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |
| `color` | `UnityEngine.Color` |  |

### SetCreature(CreatureUnit)

```csharp
public void SetCreature(CreatureUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### SetCumlativeCubeCount()

```csharp
public void SetCumlativeCubeCount()
```

### SetKitObserveLevel()

```csharp
public void SetKitObserveLevel()
```

### SetOverloadAlarmColor(OverloadType)

```csharp
public void SetOverloadAlarmColor(OverloadType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.OverloadType` |  |

### SetRiskLevel()

```csharp
public void SetRiskLevel()
```

### SetWorkIcon(Sprite)

```csharp
public void SetWorkIcon(Sprite s)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `UnityEngine.Sprite` |  |

### StartWorkDesc()

```csharp
public void StartWorkDesc()
```

### StopWorkDesc()

```csharp
public void StopWorkDesc()
```

### TurnOffRoomLight()

```csharp
public void TurnOffRoomLight()
```

### TurnOnRoomLight()

```csharp
public void TurnOnRoomLight()
```

### UpdateStatus()

```csharp
public void UpdateStatus()
```
