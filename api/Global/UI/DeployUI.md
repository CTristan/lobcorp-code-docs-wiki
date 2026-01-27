---
uid: Global.DeployUI
canonical_path: /api/Global/UI/DeployUI
---

# Class DeployUI

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeployUI : MonoBehaviour, IScrollMessageReciever
```

The deployment UI, including [all departments](/api/Global/List/DeploySefiraList), the hire button and the list of [undeployed agents](/api/Global/List/DeployAgentList), the [research window](/api/Global/IANimatorEventCalled/ResearchWindow) (when research can be obtained), the [memory repository popup](/api/Global/IOBserver/CheckPointUI), a button for the [E.G.O List](/api/Inventory/InventoryUI), a button to access the [manual](/api/Manual), and the Begin Management button.

!
Diagram of the DeployUI screen. #INC
## WARNING: THIS DIAGRAM IS WRONG IN SUBTLE AND IMPORTANT WAYS


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → DeployUI

## Implements
[IScrollMessageReciever](/api/Global/Misc/IScrollMessageReciever)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DeployUI()

```csharp
public DeployUI()
```

## Fields

### _currentColorIndex

```csharp
private int _currentColorIndex
```
#INC


#### Field Value

**Type:** System.Int32

### _currentLevel

```csharp
private SefiraLevel _currentLevel
```
#INC


#### Field Value

**Type:** Global.SefiraLevel

### _instance

```csharp
private static DeployUI _instance
```
#INC


#### Field Value

**Type:** Global.DeployUI

### _isEnabled

```csharp
private bool _isEnabled
```
#INC


#### Field Value

**Type:** System.Boolean

### _isGameStarted

```csharp
private bool _isGameStarted
```
#INC


#### Field Value

**Type:** System.Boolean

### _moveAreaTimer

```csharp
private Timer _moveAreaTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _startAble

```csharp
private bool _startAble
```
#INC


#### Field Value

**Type:** System.Boolean

### _startButtonOverlayed

```csharp
private bool _startButtonOverlayed
```
#INC


#### Field Value

**Type:** System.Boolean

### AgentCustomCost

```csharp
public const int AgentCustomCost = 1
```
#INC


#### Field Value

**Type:** System.Int32

### AgentGradeImage

```csharp
public Sprite[] AgentGradeImage
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite[]

### AgentHireCost

```csharp
public const int AgentHireCost = 1
```
#INC


#### Field Value

**Type:** System.Int32

### AgentLifeStyleImage

```csharp
public Sprite[] AgentLifeStyleImage
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite[]

### AgentLifeStyleThemeColor

```csharp
public Color[] AgentLifeStyleThemeColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color[]

### agentList

```csharp
public DeployAgentList agentList
```
#INC


#### Field Value

**Type:** Global.DeployAgentList

### AgentMaxLevel

```csharp
public const int AgentMaxLevel = 5
```
#INC


#### Field Value

**Type:** System.Int32

### AreaMoveAnim

```csharp
public Animator AreaMoveAnim
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### AreaMoveButton

```csharp
public Button[] AreaMoveButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button[]

### CanavsRect

```csharp
public Vector2 CanavsRect
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### canvas

```csharp
public Canvas canvas
```
#INC


#### Field Value

**Type:** UnityEngine.Canvas

### CheckPointDayCount

```csharp
public const int CheckPointDayCount = 5
```
#INC


#### Field Value

**Type:** System.Int32

### checkPointUI

```csharp
public CheckPointUI checkPointUI
```
#INC


#### Field Value

**Type:** Global.CheckPointUI

### coloredTargets

```csharp
[Space(15)]
public List<MaskableGraphic> coloredTargets
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### currentTutorialIndex

```csharp
private int currentTutorialIndex
```
#INC


#### Field Value

**Type:** System.Int32

### CusomAgentHireCost

```csharp
public static int[] CusomAgentHireCost
```
#INC


#### Field Value

**Type:** System.Int32[]

### DayCircleImage

```csharp
public Image[] DayCircleImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image[]

### dayCount

```csharp
[Space(10)]
public Text dayCount
```

#### Field Value

**Type:** UnityEngine.UI.Text

### defaultWorkIcon

```csharp
public Sprite[] defaultWorkIcon
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite[]

### DeployColorSet

```csharp
[Space(15)]
public Color[] DeployColorSet
```

#### Field Value

**Type:** UnityEngine.Color[]

### Gender_Female

```csharp
public Sprite Gender_Female
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### Gender_Male

```csharp
public Sprite Gender_Male
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### goal

```csharp
public Text goal
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### KetherConnected

```csharp
public GameObject[] KetherConnected
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject[]

### lowerAreaConnected

```csharp
[Header("LowerAreaConnection")]
public List<GameObject> lowerAreaConnected
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### middleAreaConnected

```csharp
[Header("MiddleAreaConnection")]
public List<GameObject> middleAreaConnected
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### MoveControl

```csharp
public RectTransform MoveControl
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### ordeal

```csharp
public Text ordeal
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### OrdealText

```csharp
public Text OrdealText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### Point

```csharp
public const string Point = "LOB"
```
#INC


#### Field Value

**Type:** System.String

### pointCount

```csharp
public Text pointCount
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### ResearchUpgradeWaitQueue

```csharp
private Queue<Sefira> ResearchUpgradeWaitQueue
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Queue{Sefira}

### researchWindow

```csharp
public ResearchWindow researchWindow
```
#INC


#### Field Value

**Type:** Global.ResearchWindow

### resetTargets

```csharp
private List<IDeployResetCalled> resetTargets
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{IDeployResetCalled}

### RiskLevelColor

```csharp
public Color[] RiskLevelColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color[]

### scroll

```csharp
public List<ScrollExchanger> scroll
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{ScrollExchanger}

### SefiraBossTutorial_HorizontalText

```csharp
public RectTransform SefiraBossTutorial_HorizontalText
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### SefiraBossTutorial_Left

```csharp
public Button SefiraBossTutorial_Left
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### SefiraBossTutorial_Right

```csharp
public Button SefiraBossTutorial_Right
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### SefiraBossTutorial_Text

```csharp
public List<Text> SefiraBossTutorial_Text
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.Text}

### SefiraBossTutorial_VerticalText

```csharp
public RectTransform SefiraBossTutorial_VerticalText
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### SefiraBossTutorialBlock

```csharp
public Image SefiraBossTutorialBlock
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### SefiraBossTutorialIndex

```csharp
public Text SefiraBossTutorialIndex
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### SefiraBossTutorialRoot

```csharp
[Header("SefiraBossTutorial")]
public GameObject SefiraBossTutorialRoot
```

#### Field Value

**Type:** UnityEngine.GameObject

### SefiraBossZeroEmpty

```csharp
public GameObject SefiraBossZeroEmpty
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### sefiraList

```csharp
public DeploySefiraList sefiraList
```
#INC


#### Field Value

**Type:** Global.DeploySefiraList

### StartButtonText

```csharp
public Text StartButtonText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### StartButtonTexture

```csharp
public Image StartButtonTexture
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### UIDefaultBlack

```csharp
public Color UIDefaultBlack
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### UIDefaultFill

```csharp
public Color UIDefaultFill
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### UIOverlayColor

```csharp
public Color UIOverlayColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

## Properties

### CurrentColorIndex

```csharp
public int CurrentColorIndex { get; private set; }
```

#### Property Value

**Type:** System.Int32

### CurrentDeployColor

```csharp
public Color CurrentDeployColor { get; }
```

#### Property Value

**Type:** UnityEngine.Color

### CurrentLevel

```csharp
public SefiraLevel CurrentLevel { get; private set; }
```

#### Property Value

**Type:** Global.SefiraLevel

### CurrentMoney

```csharp
public int CurrentMoney { get; }
```

#### Property Value

**Type:** System.Int32

### Day

```csharp
public int Day { get; }
```

#### Property Value

**Type:** System.Int32

### instance

```csharp
public static DeployUI instance { get; }
```

#### Property Value

**Type:** Global.DeployUI

### IsEnabled

```csharp
public bool IsEnabled { get; set; }
```

#### Property Value

**Type:** System.Boolean

### IsGameStarted

```csharp
public bool IsGameStarted { get; set; }
```

#### Property Value

**Type:** System.Boolean

### StartAble

```csharp
public bool StartAble { get; private set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### AddAgent()

```csharp
public void AddAgent()
```
#INC


### AddAgent(AgentModel)

```csharp
public void AddAgent(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### Awake()

```csharp
private void Awake()
```
#INC
#code-generated


### BuyAgent()

```csharp
public void BuyAgent()
```
#INC


### CheckBossClear()

```csharp
public bool CheckBossClear()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckPointCheck()

```csharp
private bool CheckPointCheck()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckResearch()

```csharp
public void CheckResearch()
```
#INC


### CheckResearchAvailable()

```csharp
private void CheckResearchAvailable()
```
#INC


### CheckResearchRemains(Sefira)

```csharp
private bool CheckResearchRemains(Sefira target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.Sefira` |  |

#### Returns

**Type:** System.Boolean

### CheckStartState()

```csharp
private void CheckStartState()
```
#INC


### GetAgentGenderImage(string)

```csharp
public static Sprite GetAgentGenderImage(string gender)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `gender` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetAgentGradeSprite(AgentModel)

```csharp
public static Sprite GetAgentGradeSprite(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetAgentWorkIcon(AgentModel)

```csharp
public static Sprite[] GetAgentWorkIcon(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** UnityEngine.Sprite[]

### GetCanvasPosition(RectTransform)

```csharp
public Vector2 GetCanvasPosition(RectTransform target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `UnityEngine.RectTransform` |  |

#### Returns

**Type:** UnityEngine.Vector2

### GetCreatureRiskLevelColor(RiskLevel)

```csharp
public static Color GetCreatureRiskLevelColor(RiskLevel level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.RiskLevel` |  |

#### Returns

**Type:** UnityEngine.Color

### GetCustomHireText(bool)

```csharp
public string GetCustomHireText(bool isEnter)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isEnter` | `System.Boolean` |  |

#### Returns

**Type:** System.String

### GetGradeSprite(int)

```csharp
public static Sprite GetGradeSprite(int level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetHireText(bool)

```csharp
public string GetHireText(bool isEnter)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isEnter` | `System.Boolean` |  |

#### Returns

**Type:** System.String

### Init()

```csharp
public void Init()
```
#INC


### InitBossSetting()

```csharp
public void InitBossSetting()
```
#INC


### InitialResearchProcedure()

```csharp
private void InitialResearchProcedure()
```
#INC


### InputCheck()

```csharp
private void InputCheck()
```
#INC


### MakeStartSound()

```csharp
public void MakeStartSound()
```
#INC


### MoveSefira(MoveDirection)

```csharp
private void MoveSefira(MoveDirection dir)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dir` | `Global.MoveDirection` |  |

### OnBossTutorialEnd()

```csharp
public void OnBossTutorialEnd()
```
#INC


### OnClickMoveArea(int)

```csharp
public void OnClickMoveArea(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnClickSefiraBossSession(SefiraEnum)

```csharp
public bool OnClickSefiraBossSession(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### OnClickStartGame()

```csharp
public void OnClickStartGame()
```
#INC


### OnManagementStart()

```csharp
public void OnManagementStart()
```
#INC


### OnScroll(PointerEventData)

```csharp
public void OnScroll(PointerEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.PointerEventData` |  |

### OnSetLevel(SefiraLevel)

```csharp
public void OnSetLevel(SefiraLevel level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.SefiraLevel` |  |

### OnSetStartState(bool)

```csharp
private void OnSetStartState(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### OnStartButtonEnter()

```csharp
public void OnStartButtonEnter()
```
#INC


### OnStartButtonExit()

```csharp
public void OnStartButtonExit()
```
#INC


### OpenCustomizingWindow()

```csharp
public void OpenCustomizingWindow()
```
#INC


### OpenInventroyUI()

```csharp
public void OpenInventroyUI()
```
#INC


### OpenManual()

```csharp
public void OpenManual()
```
#INC


### OrdealTextSetting(bool, string)

```csharp
public void OrdealTextSetting(bool hasOrdeal, string text)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `hasOrdeal` | `System.Boolean` |  |
| `text` | `System.String` |  |

### RegistDeployReset(IDeployResetCalled)

```csharp
public void RegistDeployReset(IDeployResetCalled called)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `called` | `Global.IDeployResetCalled` |  |

### ResetAll()

```csharp
public void ResetAll()
```
#INC


### SefiraTutorialDecrease()

```csharp
public void SefiraTutorialDecrease()
```
#INC


### SefiraTutorialIncrease()

```csharp
public void SefiraTutorialIncrease()
```
#INC


### SetBossTutorial()

```csharp
private void SetBossTutorial()
```
#INC


### SetDayIcon()

```csharp
private void SetDayIcon()
```
#INC


### SetOrdealText(OrdealLevel)

```csharp
public void SetOrdealText(OrdealLevel level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |

### SetResearchWaitQueue(params string[])

```csharp
public void SetResearchWaitQueue(params string[] sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String[]` |  |

### Start()

```csharp
private void Start()
```
#INC


### TextCheckPoint()

```csharp
public void TextCheckPoint()
```
#INC


### Update()

```csharp
private void Update()
```
#INC


### VolumeSetting()

```csharp
public void VolumeSetting()
```
#INC

