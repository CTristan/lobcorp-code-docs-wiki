# Class DeployUI

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeployUI : MonoBehaviour, IScrollMessageReciever
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → DeployUI

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DeployUI()

```csharp
public DeployUI()
```

## Fields

### AgentCustomCost

```csharp
public const int AgentCustomCost = 1
```

#### Field Value

**Type:** System.Int32

### AgentGradeImage

```csharp
public Sprite[] AgentGradeImage
```

#### Field Value

**Type:** UnityEngine.Sprite[]

### AgentHireCost

```csharp
public const int AgentHireCost = 1
```

#### Field Value

**Type:** System.Int32

### AgentLifeStyleImage

```csharp
public Sprite[] AgentLifeStyleImage
```

#### Field Value

**Type:** UnityEngine.Sprite[]

### AgentLifeStyleThemeColor

```csharp
public Color[] AgentLifeStyleThemeColor
```

#### Field Value

**Type:** UnityEngine.Color[]

### agentList

```csharp
public DeployAgentList agentList
```

#### Field Value

**Type:** Global.DeployAgentList

### AgentMaxLevel

```csharp
public const int AgentMaxLevel = 5
```

#### Field Value

**Type:** System.Int32

### AreaMoveAnim

```csharp
public Animator AreaMoveAnim
```

#### Field Value

**Type:** UnityEngine.Animator

### AreaMoveButton

```csharp
public Button[] AreaMoveButton
```

#### Field Value

**Type:** UnityEngine.UI.Button[]

### CanavsRect

```csharp
public Vector2 CanavsRect
```

#### Field Value

**Type:** UnityEngine.Vector2

### canvas

```csharp
public Canvas canvas
```

#### Field Value

**Type:** UnityEngine.Canvas

### CheckPointDayCount

```csharp
public const int CheckPointDayCount = 5
```

#### Field Value

**Type:** System.Int32

### checkPointUI

```csharp
public CheckPointUI checkPointUI
```

#### Field Value

**Type:** Global.CheckPointUI

### coloredTargets

```csharp
[Space(15)]
public List<MaskableGraphic> coloredTargets
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### CusomAgentHireCost

```csharp
public static int[] CusomAgentHireCost
```

#### Field Value

**Type:** System.Int32[]

### DayCircleImage

```csharp
public Image[] DayCircleImage
```

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

#### Field Value

**Type:** UnityEngine.Sprite

### Gender_Male

```csharp
public Sprite Gender_Male
```

#### Field Value

**Type:** UnityEngine.Sprite

### goal

```csharp
public Text goal
```

#### Field Value

**Type:** UnityEngine.UI.Text

### KetherConnected

```csharp
public GameObject[] KetherConnected
```

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

#### Field Value

**Type:** UnityEngine.RectTransform

### ordeal

```csharp
public Text ordeal
```

#### Field Value

**Type:** UnityEngine.UI.Text

### OrdealText

```csharp
public Text OrdealText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### Point

```csharp
public const string Point = "LOB"
```

#### Field Value

**Type:** System.String

### pointCount

```csharp
public Text pointCount
```

#### Field Value

**Type:** UnityEngine.UI.Text

### researchWindow

```csharp
public ResearchWindow researchWindow
```

#### Field Value

**Type:** Global.ResearchWindow

### RiskLevelColor

```csharp
public Color[] RiskLevelColor
```

#### Field Value

**Type:** UnityEngine.Color[]

### scroll

```csharp
public List<ScrollExchanger> scroll
```

#### Field Value

**Type:** System.Collections.Generic.List{ScrollExchanger}

### SefiraBossTutorial_HorizontalText

```csharp
public RectTransform SefiraBossTutorial_HorizontalText
```

#### Field Value

**Type:** UnityEngine.RectTransform

### SefiraBossTutorial_Left

```csharp
public Button SefiraBossTutorial_Left
```

#### Field Value

**Type:** UnityEngine.UI.Button

### SefiraBossTutorial_Right

```csharp
public Button SefiraBossTutorial_Right
```

#### Field Value

**Type:** UnityEngine.UI.Button

### SefiraBossTutorial_Text

```csharp
public List<Text> SefiraBossTutorial_Text
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.Text}

### SefiraBossTutorial_VerticalText

```csharp
public RectTransform SefiraBossTutorial_VerticalText
```

#### Field Value

**Type:** UnityEngine.RectTransform

### SefiraBossTutorialBlock

```csharp
public Image SefiraBossTutorialBlock
```

#### Field Value

**Type:** UnityEngine.UI.Image

### SefiraBossTutorialIndex

```csharp
public Text SefiraBossTutorialIndex
```

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

#### Field Value

**Type:** UnityEngine.GameObject

### sefiraList

```csharp
public DeploySefiraList sefiraList
```

#### Field Value

**Type:** Global.DeploySefiraList

### StartButtonText

```csharp
public Text StartButtonText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### StartButtonTexture

```csharp
public Image StartButtonTexture
```

#### Field Value

**Type:** UnityEngine.UI.Image

### UIDefaultBlack

```csharp
public Color UIDefaultBlack
```

#### Field Value

**Type:** UnityEngine.Color

### UIDefaultFill

```csharp
public Color UIDefaultFill
```

#### Field Value

**Type:** UnityEngine.Color

### UIOverlayColor

```csharp
public Color UIOverlayColor
```

#### Field Value

**Type:** UnityEngine.Color

## Properties

### CurrentColorIndex

```csharp
public int CurrentColorIndex { get; }
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
public SefiraLevel CurrentLevel { get; }
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
public bool StartAble { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### AddAgent()

```csharp
public void AddAgent()
```

### AddAgent(AgentModel)

```csharp
public void AddAgent(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### BuyAgent()

```csharp
public void BuyAgent()
```

### CheckBossClear()

```csharp
public bool CheckBossClear()
```

#### Returns

**Type:** System.Boolean

### CheckResearch()

```csharp
public void CheckResearch()
```

### GetAgentGenderImage(string)

```csharp
public static Sprite GetAgentGenderImage(string gender)
```

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

### InitBossSetting()

```csharp
public void InitBossSetting()
```

### MakeStartSound()

```csharp
public void MakeStartSound()
```

### OnBossTutorialEnd()

```csharp
public void OnBossTutorialEnd()
```

### OnClickMoveArea(int)

```csharp
public void OnClickMoveArea(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnClickSefiraBossSession(SefiraEnum)

```csharp
public bool OnClickSefiraBossSession(SefiraEnum sefira)
```

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

### OnManagementStart()

```csharp
public void OnManagementStart()
```

### OnScroll(PointerEventData)

```csharp
public void OnScroll(PointerEventData eventData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.PointerEventData` |  |

### OnSetLevel(SefiraLevel)

```csharp
public void OnSetLevel(SefiraLevel level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.SefiraLevel` |  |

### OnStartButtonEnter()

```csharp
public void OnStartButtonEnter()
```

### OnStartButtonExit()

```csharp
public void OnStartButtonExit()
```

### OpenCustomizingWindow()

```csharp
public void OpenCustomizingWindow()
```

### OpenInventroyUI()

```csharp
public void OpenInventroyUI()
```

### OpenManual()

```csharp
public void OpenManual()
```

### OrdealTextSetting(bool, string)

```csharp
public void OrdealTextSetting(bool hasOrdeal, string text)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `hasOrdeal` | `System.Boolean` |  |
| `text` | `System.String` |  |

### RegistDeployReset(IDeployResetCalled)

```csharp
public void RegistDeployReset(IDeployResetCalled called)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `called` | `Global.IDeployResetCalled` |  |

### ResetAll()

```csharp
public void ResetAll()
```

### SefiraTutorialDecrease()

```csharp
public void SefiraTutorialDecrease()
```

### SefiraTutorialIncrease()

```csharp
public void SefiraTutorialIncrease()
```

### SetOrdealText(OrdealLevel)

```csharp
public void SetOrdealText(OrdealLevel level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |

### SetResearchWaitQueue(params string[])

```csharp
public void SetResearchWaitQueue(params string[] sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String[]` |  |

### TextCheckPoint()

```csharp
public void TextCheckPoint()
```

### VolumeSetting()

```csharp
public void VolumeSetting()
```
