# Class SefiraPanel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraPanel : MonoBehaviour, IDeployResetCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → SefiraPanel

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SefiraPanel()

```csharp
public SefiraPanel()
```

## Fields

### activateEffected

```csharp
public List<GameObject> activateEffected
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### agentSlots

```csharp
[Space(15)]
public DeploySefiraAgentSlot[] agentSlots
```

#### Field Value

**Type:** Global.DeploySefiraAgentSlot[]

### allocateAgents

```csharp
public List<AgentModel> allocateAgents
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentModel}

### alterGraphics

```csharp
public List<MaskableGraphic> alterGraphics
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### creatureSlots

```csharp
public SefiraPanel.CreaturePortrait[] creatureSlots
```

#### Field Value

**Type:** Global.SefiraPanel.CreaturePortrait[]

### decorations

```csharp
[Space(10)]
public SefiraPanel.Decorations decorations
```

#### Field Value

**Type:** Global.SefiraPanel.Decorations

### DescriptionButton

```csharp
public Button DescriptionButton
```

#### Field Value

**Type:** UnityEngine.UI.Button

### DescriptionText

```csharp
public Text DescriptionText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### DescriptionTextArea

```csharp
public Text DescriptionTextArea
```

#### Field Value

**Type:** UnityEngine.UI.Text

### DoNotCloseMain

```csharp
public bool DoNotCloseMain
```

#### Field Value

**Type:** System.Boolean

### dropScript

```csharp
public Drop dropScript
```

#### Field Value

**Type:** Global.Drop

### FrameOutline

```csharp
public Outline FrameOutline
```

#### Field Value

**Type:** UnityEngine.UI.Outline

### Function_SefiraFunction_Context

```csharp
[Header("Sefira Function")]
public Text Function_SefiraFunction_Context
```

#### Field Value

**Type:** UnityEngine.UI.Text

### Function_SefiraTenure_Context

```csharp
public Text Function_SefiraTenure_Context
```

#### Field Value

**Type:** UnityEngine.UI.Text

### FunctionButton

```csharp
public Button FunctionButton
```

#### Field Value

**Type:** UnityEngine.UI.Button

### functionRoot

```csharp
public RectTransform functionRoot
```

#### Field Value

**Type:** UnityEngine.RectTransform

### FunctionText

```csharp
public Text FunctionText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### graphics

```csharp
public List<MaskableGraphic> graphics
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### Kether_Chain

```csharp
public GameObject Kether_Chain
```

#### Field Value

**Type:** UnityEngine.GameObject

### Kether_Pivot

```csharp
public GameObject Kether_Pivot
```

#### Field Value

**Type:** UnityEngine.GameObject

### leftRoot

```csharp
public RectTransform leftRoot
```

#### Field Value

**Type:** UnityEngine.RectTransform

### level

```csharp
public SefiraLevel level
```

#### Field Value

**Type:** Global.SefiraLevel

### LinkedSefira

```csharp
public SefiraPanel LinkedSefira
```

#### Field Value

**Type:** Global.SefiraPanel

### mainRoot

```csharp
public RectTransform mainRoot
```

#### Field Value

**Type:** UnityEngine.RectTransform

### maxAgentCount

```csharp
public const int maxAgentCount = 5
```

#### Field Value

**Type:** System.Int32

### MissionPanelAnim

```csharp
public Animator MissionPanelAnim
```

#### Field Value

**Type:** UnityEngine.Animator

### missionUI

```csharp
public SefiraPanelMissionUI missionUI
```

#### Field Value

**Type:** Global.SefiraPanelMissionUI

### ResearchButton

```csharp
public Button ResearchButton
```

#### Field Value

**Type:** UnityEngine.UI.Button

### researchPanelController

```csharp
public SefiraResearchPanel researchPanelController
```

#### Field Value

**Type:** Global.SefiraResearchPanel

### ResearchText

```csharp
public Text ResearchText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### rightRoot

```csharp
public RectTransform rightRoot
```

#### Field Value

**Type:** UnityEngine.RectTransform

### scaleSetted

```csharp
public List<ScaleSetter> scaleSetted
```

#### Field Value

**Type:** System.Collections.Generic.List{ScaleSetter}

### scrollExchanged

```csharp
public List<ScrollExchanger> scrollExchanged
```

#### Field Value

**Type:** System.Collections.Generic.List{ScrollExchanger}

### SefiraBossButton

```csharp
[Header("SefiraBoss")]
public Button SefiraBossButton
```

#### Field Value

**Type:** UnityEngine.UI.Button

### SefiraBossButtonText

```csharp
public Text SefiraBossButtonText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### SefiraBossDesc_Clear

```csharp
public Text SefiraBossDesc_Clear
```

#### Field Value

**Type:** UnityEngine.UI.Text

### SefiraBossDesc_Condition

```csharp
public Text SefiraBossDesc_Condition
```

#### Field Value

**Type:** UnityEngine.UI.Text

### sefiraBossDescPanel

```csharp
public UIController sefiraBossDescPanel
```

#### Field Value

**Type:** Global.UIController

### sefiraBossRelated

```csharp
public List<GameObject> sefiraBossRelated
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### SefiraName

```csharp
public Text SefiraName
```

#### Field Value

**Type:** UnityEngine.UI.Text

### SefiraSound

```csharp
public AudioClipPlayer SefiraSound
```

#### Field Value

**Type:** Global.AudioClipPlayer

### TooltipObj

```csharp
public GameObject TooltipObj
```

#### Field Value

**Type:** UnityEngine.GameObject

## Properties

### ActiveControl

```csharp
public GameObject ActiveControl { get; }
```

#### Property Value

**Type:** UnityEngine.GameObject

### CurrentAgentCount

```csharp
public int CurrentAgentCount { get; }
```

#### Property Value

**Type:** System.Int32

### DragEntered

```csharp
public bool DragEntered { get; }
```

#### Property Value

**Type:** System.Boolean

### Group

```csharp
public CanvasGroup Group { get; }
```

#### Property Value

**Type:** UnityEngine.CanvasGroup

### IsActivated

```csharp
public bool IsActivated { get; }
```

#### Property Value

**Type:** System.Boolean

### OverlayState

```csharp
public SefiraPanel.PanelDataState OverlayState { get; set; }
```

#### Property Value

**Type:** Global.SefiraPanel.PanelDataState

### PanelState

```csharp
public SefiraPanel.PanelDataState PanelState { get; set; }
```

#### Property Value

**Type:** Global.SefiraPanel.PanelDataState

### Sefira

```csharp
public Sefira Sefira { get; }
```

#### Property Value

**Type:** Global.Sefira

### SefiraColor

```csharp
public Color SefiraColor { get; }
```

#### Property Value

**Type:** UnityEngine.Color

### SefiraUIColor

```csharp
public SefiraUIColor SefiraUIColor { get; }
```

#### Property Value

**Type:** Global.SefiraUIColor

## Methods

### AddAgent(AgentModel)

```csharp
public bool AddAgent(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Boolean

### CreaturePortraitInit()

```csharp
public void CreaturePortraitInit()
```

### DeployColorSetted(Color)

```csharp
public void DeployColorSetted(Color c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### DeployResetCalled()

```csharp
public void DeployResetCalled()
```

### DisableSefiraBoss()

```csharp
public void DisableSefiraBoss()
```

### DropEvent(params object[])

```csharp
public bool DropEvent(params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `System.Object[]` |  |

#### Returns

**Type:** System.Boolean

### Init(SefiraEnum)

```csharp
public void Init(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

### InitialAddAgent(AgentModel)

```csharp
public void InitialAddAgent(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### InitResearch()

```csharp
public void InitResearch()
```

### OnAgentSlotEnter(DeploySefiraAgentSlot)

```csharp
public void OnAgentSlotEnter(DeploySefiraAgentSlot slot)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Global.DeploySefiraAgentSlot` |  |

### OnAgentSlotExit(DeploySefiraAgentSlot)

```csharp
public void OnAgentSlotExit(DeploySefiraAgentSlot slot)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Global.DeploySefiraAgentSlot` |  |

### OnBossDescDisabled()

```csharp
public void OnBossDescDisabled()
```

### OnClickAgentSlot(BaseEventData)

```csharp
public void OnClickAgentSlot(BaseEventData bData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnClickAgentSlot(int)

```csharp
public void OnClickAgentSlot(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnClickCreaturePortriat(int)

```csharp
public void OnClickCreaturePortriat(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnClickDescription()

```csharp
public void OnClickDescription()
```

### OnClickPanel()

```csharp
public void OnClickPanel()
```

### OnClickResearch()

```csharp
public void OnClickResearch()
```

### OnClickSefiraFunction()

```csharp
public void OnClickSefiraFunction()
```

### OnCreaturePortraitEnter(int)

```csharp
public void OnCreaturePortraitEnter(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnCreaturePortraitExit(int)

```csharp
public void OnCreaturePortraitExit(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnDeallocateAll()

```csharp
public void OnDeallocateAll()
```

### OnManageStart()

```csharp
public void OnManageStart()
```

### OnOverlayEnter(int)

```csharp
public void OnOverlayEnter(int index)
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

### OnPanelEnter(BaseEventData)

```csharp
public void OnPanelEnter(BaseEventData bData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnPanelExit()

```csharp
public void OnPanelExit()
```

### OnRemoveAgent(int)

```csharp
public void OnRemoveAgent(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnRemoveAgent_NotAddToList(int)

```csharp
public void OnRemoveAgent_NotAddToList(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnStartBossSession()

```csharp
public void OnStartBossSession()
```

### Registration()

```csharp
public void Registration()
```

### RemoveAgent(AgentModel)

```csharp
public bool RemoveAgent(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Boolean

### RemoveAgentNotRemoved(AgentModel)

```csharp
public bool RemoveAgentNotRemoved(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Boolean

### SetAlterGraphicsColor(Color)

```csharp
public void SetAlterGraphicsColor(Color altercolor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `altercolor` | `UnityEngine.Color` |  |

### SetBossPanel(bool)

```csharp
public void SetBossPanel(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetBossState()

```csharp
public void SetBossState()
```

### SetDescriptionText()

```csharp
public void SetDescriptionText()
```

### SetSclae(float)

```csharp
public void SetSclae(float factor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factor` | `System.Single` |  |
