---
uid: Global.IsolateRoom
canonical_path: /api/Global/IOBserver/IsolateRoom
---

# Class IsolateRoom

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class IsolateRoom : MonoBehaviour, IObserver
```

A containment unit for some abnormality.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → IsolateRoom

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### IsolateRoom()

```csharp
public IsolateRoom()
```

## Fields

### _checkCumlatvieCubeCount

```csharp
private bool _checkCumlatvieCubeCount
```
#INC


#### Field Value

**Type:** System.Boolean

### _counterEnabled

```csharp
private bool _counterEnabled
```
#INC


#### Field Value

**Type:** System.Boolean

### _counterObserved

```csharp
private bool _counterObserved
```
#INC


#### Field Value

**Type:** System.Boolean

### _cubeAnimFreq

```csharp
private const float _cubeAnimFreq = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### _cubeTimer

```csharp
private Timer _cubeTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _cumlativeCubeAnimRemain

```csharp
private int _cumlativeCubeAnimRemain
```
#INC


#### Field Value

**Type:** System.Int32

### _currentAllocateWorker

```csharp
private AgentModel _currentAllocateWorker
```
#INC


#### Field Value

**Type:** Global.AgentModel

### _currentCumlatvieCubeCount

```csharp
private int _currentCumlatvieCubeCount
```
#INC


#### Field Value

**Type:** System.Int32

### _currentUsedProcessText

```csharp
private List<int> _currentUsedProcessText
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.Int32}

### _currentWorkType

```csharp
private RwbpType _currentWorkType
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _isEscaped

```csharp
private bool _isEscaped
```
#INC


#### Field Value

**Type:** System.Boolean

### _isResultDisplaying

```csharp
private bool _isResultDisplaying
```
#INC


#### Field Value

**Type:** System.Boolean

### _isWorkAllocated

```csharp
private bool _isWorkAllocated
```
#INC


#### Field Value

**Type:** System.Boolean

### _isWorking

```csharp
private bool _isWorking
```
#INC


#### Field Value

**Type:** System.Boolean

### _maxWorkcountReached

```csharp
private bool _maxWorkcountReached
```
#INC


#### Field Value

**Type:** System.Boolean

### _narrationPosyFix

```csharp
private const float _narrationPosyFix = 4.4
```
#INC


#### Field Value

**Type:** System.Single

### _progressBar

```csharp
private IsolateRoom.WorkProgress _progressBar
```

#### Field Value

**Type:** Global.IsolateRoom.WorkProgress

### _roomPosxFix

```csharp
private const float _roomPosxFix = 0.31
```
#INC


#### Field Value

**Type:** System.Single

### _roomPosyFix

```csharp
private const float _roomPosyFix = 4.4
```
#INC


#### Field Value

**Type:** System.Single

### _targetClick

```csharp
private PointerEventData.InputButton _targetClick
```
#INC


#### Field Value

**Type:** UnityEngine.EventSystems.PointerEventData.InputButton

### _targetUnit

```csharp
private CreatureUnit _targetUnit
```
#INC


#### Field Value

**Type:** Global.CreatureUnit

### _workDescTimer

```csharp
private Timer _workDescTimer
```
#INC


#### Field Value

**Type:** Global.Timer

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
#INC


#### Field Value

**Type:** Global.IsolatePos

### audioClipPlayer

```csharp
public AudioClipPlayer audioClipPlayer
```
#INC


#### Field Value

**Type:** Global.AudioClipPlayer

### binahOverloadUI

```csharp
public BinahOverloadUI binahOverloadUI
```
#INC


#### Field Value

**Type:** BinahBoss.BinahOverloadUI

### CancelColor

```csharp
public Color CancelColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### CancelWork

```csharp
public Image CancelWork
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### ClickIsolateArea

```csharp
public Canvas ClickIsolateArea
```
#INC


#### Field Value

**Type:** UnityEngine.Canvas

### ClickNameArea

```csharp
public Canvas ClickNameArea
```
#INC


#### Field Value

**Type:** UnityEngine.Canvas

### ColorSetted

```csharp
public List<MaskableGraphic> ColorSetted
```
#INC


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
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### CounterColor_Black

```csharp
public Color CounterColor_Black
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### CounterColor_Normal

```csharp
public Color CounterColor_Normal
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### CounterColor_Red

```csharp
public Color CounterColor_Red
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### CounterColor_White

```csharp
public Color CounterColor_White
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### CounterImage_None

```csharp
public Sprite CounterImage_None
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### CounterImage_Unknown

```csharp
public Sprite CounterImage_Unknown
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### CounterInnerImage

```csharp
public Image CounterInnerImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### CounterOutline

```csharp
public GameObject CounterOutline
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### CounterText

```csharp
public Text CounterText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### CreatureName

```csharp
public Text CreatureName
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### CreatureNameImage

```csharp
public Image CreatureNameImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### CubeGridRoot

```csharp
public GameObject CubeGridRoot
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### CumlativeCrossImage

```csharp
public Image CumlativeCrossImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### CumlativeCubeCount

```csharp
public Text CumlativeCubeCount
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### CumlativeCubeImage

```csharp
public Image CumlativeCubeImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### CurrentObserveLevel

```csharp
public Text CurrentObserveLevel
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### CurrentObserveLevelFill

```csharp
public Image CurrentObserveLevelFill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### CurrentResultCooltime

```csharp
public Text CurrentResultCooltime
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### CurrentResultFilter

```csharp
public Image CurrentResultFilter
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### CurrentResultIcon

```csharp
public Image CurrentResultIcon
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### CurrentWorkCubeFill

```csharp
public Image CurrentWorkCubeFill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### CurrentWorkCubeText

```csharp
public Text CurrentWorkCubeText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### CurrentWorkIcon

```csharp
public Image CurrentWorkIcon
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### CurrentWorkRoot

```csharp
public GameObject CurrentWorkRoot
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### DamageFilter

```csharp
public Image DamageFilter
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### DefaultEscapeFilter

```csharp
public Image DefaultEscapeFilter
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### DescController

```csharp
public IsolateDescController DescController
```
#INC


#### Field Value

**Type:** Assets.Scripts.UI.Isolate.IsolateDescController

### EscapeCubeSprite

```csharp
public Sprite EscapeCubeSprite
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### EscapeFilter

```csharp
public IsolateFilter EscapeFilter
```
#INC


#### Field Value

**Type:** Global.IsolateFilter

### FailCubeGrid

```csharp
public RectTransform FailCubeGrid
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### FailCubeObject

```csharp
public GameObject FailCubeObject
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### Frame

```csharp
public Image Frame
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### kitCreatureUIs

```csharp
public List<GameObject> kitCreatureUIs
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### KitDisable

```csharp
public Color KitDisable
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### KitNormal

```csharp
public Color KitNormal
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### KitObserveLevel

```csharp
public Text[] KitObserveLevel
```
#INC


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
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### MaxWorkCountLine

```csharp
public GameObject MaxWorkCountLine
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### MaxWorkText_Lower

```csharp
public Text MaxWorkText_Lower
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### MaxWorkText_Upper

```csharp
public Text MaxWorkText_Upper
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### MovingColor

```csharp
public Color MovingColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### nameEntered

```csharp
private bool nameEntered
```
#INC


#### Field Value

**Type:** System.Boolean

### NameTextColor

```csharp
public Color NameTextColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### NameTextureColor

```csharp
public Color NameTextureColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### NarrationFadeEffect

```csharp
public FadeEffecter NarrationFadeEffect
```
#INC


#### Field Value

**Type:** Global.FadeEffecter

### normalCreatureUIs

```csharp
public List<GameObject> normalCreatureUIs
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### NormalCubeSprite

```csharp
public Sprite NormalCubeSprite
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### oldCount

```csharp
private int oldCount
```
#INC


#### Field Value

**Type:** System.Int32

### oldState

```csharp
private CreatureFeelingState oldState
```
#INC


#### Field Value

**Type:** Global.CreatureFeelingState

### OrderColor

```csharp
public Color OrderColor
```
#INC


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
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### overloadUI

```csharp
[Header("Overload")]
public IsolateOverload overloadUI
```

#### Field Value

**Type:** Global.IsolateOverload

### pointerEntered

```csharp
private bool pointerEntered
```
#INC


#### Field Value

**Type:** System.Boolean

### probReductionText

```csharp
public Text probReductionText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### probReductionUI

```csharp
public Animator probReductionUI
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### RabbitBlock

```csharp
public GameObject RabbitBlock
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### RiskLevelImage

```csharp
public Image RiskLevelImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### RoomColor

```csharp
public Color RoomColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### RoomFog

```csharp
public Image RoomFog
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### RoomSpriteRenderer

```csharp
public SpriteRenderer RoomSpriteRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### SkillFilter

```csharp
public IsolateFilter SkillFilter
```
#INC


#### Field Value

**Type:** Global.IsolateFilter

### SpecialSkillName

```csharp
public Text SpecialSkillName
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### SpecialSkillRoot

```csharp
public GameObject SpecialSkillRoot
```
#INC


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
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### SuccessCubeObject

```csharp
public GameObject SuccessCubeObject
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### SuppressColor

```csharp
public Color SuppressColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### TooltipAllAgentDead

```csharp
public TooltipMouseOver TooltipAllAgentDead
```
#INC


#### Field Value

**Type:** Global.TooltipMouseOver

### TooltipCurrentPE

```csharp
public TooltipMouseOver TooltipCurrentPE
```
#INC


#### Field Value

**Type:** Global.TooltipMouseOver

### TooltipGeneratedPE

```csharp
public TooltipMouseOver TooltipGeneratedPE
```
#INC


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
#INC


#### Field Value

**Type:** Global.TooltipMouseOver

### TooltipQliphoth

```csharp
public TooltipMouseOver TooltipQliphoth
```
#INC


#### Field Value

**Type:** Global.TooltipMouseOver

### TooltipReduceProb

```csharp
public TooltipMouseOver TooltipReduceProb
```
#INC


#### Field Value

**Type:** Global.TooltipMouseOver

### TooltipRiskLevel

```csharp
public TooltipMouseOver TooltipRiskLevel
```
#INC


#### Field Value

**Type:** Global.TooltipMouseOver

### TooltipUniquePE

```csharp
public TooltipMouseOver TooltipUniquePE
```
#INC


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
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### WorkCount_Disabled

```csharp
public Color WorkCount_Disabled
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### WorkCount_Enabled

```csharp
public Color WorkCount_Enabled
```
#INC


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
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.Image}

### WorkCounterRayout

```csharp
public RectTransform WorkCounterRayout
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### WorkCounterUnit

```csharp
public GameObject WorkCounterUnit
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### WorkDescFreq

```csharp
public float WorkDescFreq
```
#INC


#### Field Value

**Type:** System.Single

### WorkGear

```csharp
public Image WorkGear
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### WorkNarration

```csharp
public Text WorkNarration
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

## Properties

### CurrentResultRoot

```csharp
private GameObject CurrentResultRoot { get; }
```

#### Property Value

**Type:** UnityEngine.GameObject

### CurrentWorkAnim

```csharp
private Animator CurrentWorkAnim { get; }
```

#### Property Value

**Type:** UnityEngine.Animator

### DamageFilterObject

```csharp
private GameObject DamageFilterObject { get; }
```

#### Property Value

**Type:** UnityEngine.GameObject

### DamageUIController

```csharp
private UIController DamageUIController { get; }
```

#### Property Value

**Type:** Global.UIController

### IsWorkAllocated

```csharp
private bool IsWorkAllocated { get; set; }
```

#### Property Value

**Type:** System.Boolean

### IsWorking

```csharp
private bool IsWorking { get; set; }
```

#### Property Value

**Type:** System.Boolean

### OvelrayEnable

```csharp
private bool OvelrayEnable { get; }
```

#### Property Value

**Type:** System.Boolean

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
public CreatureUnit TargetUnit { get; private set; }
```

#### Property Value

**Type:** Global.CreatureUnit

### WorkResultUIController

```csharp
private UIController WorkResultUIController { get; }
```

#### Property Value

**Type:** Global.UIController

## Methods

### ActivatedSkill()

```csharp
public void ActivatedSkill()
```
#INC


### AddFilter(IsolateFilter)

```csharp
public IsolateFilter AddFilter(IsolateFilter baseFilter)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `baseFilter` | `Global.IsolateFilter` |  |

#### Returns

**Type:** Global.IsolateFilter

### Awake()

```csharp
private void Awake()
```
#INC


### CheckMaxworkCount()

```csharp
private void CheckMaxworkCount()
```
#INC


### CheckOverlay()

```csharp
private void CheckOverlay()
```
#INC


### CheckOverlayState()

```csharp
private bool CheckOverlayState()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckQliphothCounter()

```csharp
public void CheckQliphothCounter()
```
#INC


### CheckWorkerMoving()

```csharp
private void CheckWorkerMoving()
```
#INC


### CheckWorkProcessText()

```csharp
public void CheckWorkProcessText()
```
#INC


### DisableWorkIcon()

```csharp
public void DisableWorkIcon()
```
#INC


### FixedUpdate()

```csharp
private void FixedUpdate()
```
#INC


### GetCurrentWorkSpeed()

```csharp
public float GetCurrentWorkSpeed()
```
#INC


#### Returns

**Type:** System.Single

### GetDesc(string)

```csharp
private string GetDesc(string id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns

**Type:** System.String

### GetStateText(string)

```csharp
public string GetStateText(string key)
```
#INC


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
#INC


### InitProcessText(RwbpType)

```csharp
private void InitProcessText(RwbpType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

### InitWorkCountUI()

```csharp
private void InitWorkCountUI()
```
#INC
#code-generated


### IsKitReturnning()

```csharp
private bool IsKitReturnning()
```
#INC


#### Returns

**Type:** System.Boolean

### OnCancelWork()

```csharp
public void OnCancelWork()
```
#INC


### OnChangeProbReduction()

```csharp
public void OnChangeProbReduction()
```
#INC


### OnClick(BaseEventData)

```csharp
public void OnClick(BaseEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnClickCollectionButton(BaseEventData)

```csharp
public void OnClickCollectionButton(BaseEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnCubeArrived()

```csharp
public void OnCubeArrived()
```
#INC


### OnCurrentWorkRootAnimEnd()

```csharp
public void OnCurrentWorkRootAnimEnd()
```
#INC


### OnDamageAnimArrived()

```csharp
public void OnDamageAnimArrived()
```
#INC


### OnDamageInvoked(DamageInfo)

```csharp
public void OnDamageInvoked(DamageInfo damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `Global.DamageInfo` |  |

### OnDescriptionUnitEnded(int)

```csharp
public void OnDescriptionUnitEnded(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

### OnDisable()

```csharp
private void OnDisable()
```
#INC


### OnEnterRoom(AgentModel, UseSkill)

```csharp
public void OnEnterRoom(AgentModel worker, UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.AgentModel` |  |
| `skill` | `Global.UseSkill` |  |

### OnEscape()

```csharp
public void OnEscape()
```
#INC


### OnExitRoom()

```csharp
public void OnExitRoom()
```
#INC


### OnFeelingStateDisplayEnd()

```csharp
public void OnFeelingStateDisplayEnd()
```
#INC


### OnFeelingStateDisplayStart(CreatureFeelingState)

```csharp
public void OnFeelingStateDisplayStart(CreatureFeelingState state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.CreatureFeelingState` |  |

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnObservationLevelChanged()

```csharp
public void OnObservationLevelChanged()
```
#INC


### OnOvelrayEnter(int)

```csharp
public void OnOvelrayEnter(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnOverlayExit(int)

```csharp
public void OnOverlayExit(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnReturn()

```csharp
public void OnReturn()
```
#INC


### OnWorkAllocated(AgentModel)

```csharp
public void OnWorkAllocated(AgentModel incomingWorker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `incomingWorker` | `Global.AgentModel` |  |

### OnWorkEnd()

```csharp
public void OnWorkEnd()
```
#INC


### ProcessNarration(string)

```csharp
public void ProcessNarration(string desc)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `desc` | `System.String` |  |

### SetBinahBoss()

```csharp
public void SetBinahBoss()
```
#INC


### SetCounterEnable(bool)

```csharp
public void SetCounterEnable(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetCounterText(string)

```csharp
public void SetCounterText(string text)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

### SetCounterText(string, Color)

```csharp
public void SetCounterText(string text, Color color)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |
| `color` | `UnityEngine.Color` |  |

### SetCreature(CreatureUnit)

```csharp
public void SetCreature(CreatureUnit unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### SetCumlativeCubeCount()

```csharp
public void SetCumlativeCubeCount()
```
#INC


### SetKitObserveLevel()

```csharp
public void SetKitObserveLevel()
```
#INC


### SetOverloadAlarmColor(OverloadType)

```csharp
public void SetOverloadAlarmColor(OverloadType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.OverloadType` |  |

### SetResult(CreatureFeelingState)

```csharp
private void SetResult(CreatureFeelingState state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.CreatureFeelingState` |  |

### SetRiskLevel()

```csharp
public void SetRiskLevel()
```
#INC


### SetWorkIcon(Sprite)

```csharp
public void SetWorkIcon(Sprite s)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `UnityEngine.Sprite` |  |

### Start()

```csharp
private void Start()
```
#INC


### StartCubeAnim()

```csharp
private void StartCubeAnim()
```
#INC


### StartWorkDesc()

```csharp
public void StartWorkDesc()
```
#INC


### StopWorkDesc()

```csharp
public void StopWorkDesc()
```
#INC


### TurnOffRoomLight()

```csharp
public void TurnOffRoomLight()
```
#INC


### TurnOnRoomLight()

```csharp
public void TurnOnRoomLight()
```
#INC


### Update()

```csharp
private void Update()
```
#INC


### UpdateStatus()

```csharp
public void UpdateStatus()
```
#INC

