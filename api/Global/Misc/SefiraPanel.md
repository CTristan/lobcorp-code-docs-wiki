---
uid: Global.SefiraPanel
canonical_path: /api/Global/Misc/SefiraPanel
---

# Class SefiraPanel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraPanel : MonoBehaviour, IDeployResetCalled
```

Represents a department on the [deployment screen](/api/Global/UI/DeployUI). Holds [slots](/api/Global/Misc/DeploySefiraAgentSlot) for assigning agents.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → SefiraPanel

## Implements
[IDeployResetCalled](/api/Global/Misc/IDeployResetCalled)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraPanel()

```csharp
public SefiraPanel()
```

## Fields

### _allocateMax

```csharp
private int _allocateMax
```
#INC


#### Field Value

**Type:** System.Int32

### _currentAgentCount

```csharp
private int _currentAgentCount
```
#INC


#### Field Value

**Type:** System.Int32

### _currentClickTarget

```csharp
private int _currentClickTarget
```
#INC


#### Field Value

**Type:** System.Int32

### _dataState

```csharp
private SefiraPanel.PanelDataState _dataState
```

#### Field Value

**Type:** Global.SefiraPanel.PanelDataState

### _group

```csharp
private CanvasGroup _group
```
#INC


#### Field Value

**Type:** UnityEngine.CanvasGroup

### _logoDefault

```csharp
private const float _logoDefault = 0.98
```
#INC


#### Field Value

**Type:** System.Single

### _logoTrans

```csharp
private const float _logoTrans = 1.02
```
#INC


#### Field Value

**Type:** System.Single

### _overlayState

```csharp
private SefiraPanel.PanelDataState _overlayState
```

#### Field Value

**Type:** Global.SefiraPanel.PanelDataState

### _sefira

```csharp
private Sefira _sefira
```
#INC


#### Field Value

**Type:** Global.Sefira

### _sefiraColor

```csharp
private Color _sefiraColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### _sefiraUIColor

```csharp
private SefiraUIColor _sefiraUIColor
```
#INC


#### Field Value

**Type:** Global.SefiraUIColor

### activateEffected

```csharp
public List<GameObject> activateEffected
```
#INC


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
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentModel}

### alterGraphics

```csharp
public List<MaskableGraphic> alterGraphics
```
#INC


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
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### DescriptionText

```csharp
public Text DescriptionText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### DescriptionTextArea

```csharp
public Text DescriptionTextArea
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### DoNotCloseMain

```csharp
public bool DoNotCloseMain
```
#INC


#### Field Value

**Type:** System.Boolean

### dragEntered

```csharp
private bool dragEntered
```
#INC


#### Field Value

**Type:** System.Boolean

### dropScript

```csharp
public Drop dropScript
```
#INC


#### Field Value

**Type:** Global.Drop

### FrameOutline

```csharp
public Outline FrameOutline
```
#INC


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
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### FunctionButton

```csharp
public Button FunctionButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### functionRoot

```csharp
public RectTransform functionRoot
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### FunctionText

```csharp
public Text FunctionText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### graphics

```csharp
public List<MaskableGraphic> graphics
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### Kether_Chain

```csharp
public GameObject Kether_Chain
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### Kether_Pivot

```csharp
public GameObject Kether_Pivot
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### leftRoot

```csharp
public RectTransform leftRoot
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### level

```csharp
public SefiraLevel level
```
#INC


#### Field Value

**Type:** Global.SefiraLevel

### LinkedSefira

```csharp
public SefiraPanel LinkedSefira
```
#INC


#### Field Value

**Type:** Global.SefiraPanel

### mainRoot

```csharp
public RectTransform mainRoot
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### maxAgentCount

```csharp
public const int maxAgentCount = 5
```
#INC


#### Field Value

**Type:** System.Int32

### MissionPanelAnim

```csharp
public Animator MissionPanelAnim
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### missionPanelStartTimer

```csharp
private Timer missionPanelStartTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### missionUI

```csharp
public SefiraPanelMissionUI missionUI
```
#INC


#### Field Value

**Type:** Global.SefiraPanelMissionUI

### noDataPortraitSrc

```csharp
private const string noDataPortraitSrc = "Sprites/Unit/creature/NoData"
```
#INC


#### Field Value

**Type:** System.String

### removeCoolTimer

```csharp
private UnscaledTimer removeCoolTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### ResearchButton

```csharp
public Button ResearchButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### researchPanelController

```csharp
public SefiraResearchPanel researchPanelController
```
#INC


#### Field Value

**Type:** Global.SefiraResearchPanel

### ResearchText

```csharp
public Text ResearchText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### rightRoot

```csharp
public RectTransform rightRoot
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### scaleSetted

```csharp
public List<ScaleSetter> scaleSetted
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{ScaleSetter}

### scrollExchanged

```csharp
public List<ScrollExchanger> scrollExchanged
```
#INC


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
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### SefiraBossDesc_Clear

```csharp
public Text SefiraBossDesc_Clear
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### SefiraBossDesc_Condition

```csharp
public Text SefiraBossDesc_Condition
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### sefiraBossDescPanel

```csharp
public UIController sefiraBossDescPanel
```
#INC


#### Field Value

**Type:** Global.UIController

### sefiraBossRelated

```csharp
public List<GameObject> sefiraBossRelated
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.GameObject}

### SefiraName

```csharp
public Text SefiraName
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### SefiraSound

```csharp
public AudioClipPlayer SefiraSound
```
#INC


#### Field Value

**Type:** Global.AudioClipPlayer

### TooltipObj

```csharp
public GameObject TooltipObj
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

## Properties

### _isAllcoateable

```csharp
private bool _isAllcoateable { get; }
```

#### Property Value

**Type:** System.Boolean

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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Boolean

### AgentListInit()

```csharp
private void AgentListInit()
```
#INC


### CreaturePortraitInit()

```csharp
public void CreaturePortraitInit()
```
#INC


### DeployColorSetted(Color)

```csharp
public void DeployColorSetted(Color c)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### DeployResetCalled()

```csharp
public void DeployResetCalled()
```
#INC


### DisableSefiraBoss()

```csharp
public void DisableSefiraBoss()
```
#INC


### DropEvent(params object[])

```csharp
public bool DropEvent(params object[] param)
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

### InitialAddAgent(AgentModel)

```csharp
public void InitialAddAgent(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### InitResearch()

```csharp
public void InitResearch()
```
#INC


### OnAgentSlotEnter(DeploySefiraAgentSlot)

```csharp
public void OnAgentSlotEnter(DeploySefiraAgentSlot slot)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Global.DeploySefiraAgentSlot` |  |

### OnAgentSlotExit(DeploySefiraAgentSlot)

```csharp
public void OnAgentSlotExit(DeploySefiraAgentSlot slot)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Global.DeploySefiraAgentSlot` |  |

### OnBossDescDisabled()

```csharp
public void OnBossDescDisabled()
```
#INC


### OnClickAgentSlot(BaseEventData)

```csharp
public void OnClickAgentSlot(BaseEventData bData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnClickAgentSlot(int)

```csharp
public void OnClickAgentSlot(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnClickCreaturePortriat(int)

```csharp
public void OnClickCreaturePortriat(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnClickDescription()

```csharp
public void OnClickDescription()
```
#INC


### OnClickPanel()

```csharp
public void OnClickPanel()
```
#INC


### OnClickResearch()

```csharp
public void OnClickResearch()
```
#INC


### OnClickSefiraFunction()

```csharp
public void OnClickSefiraFunction()
```
#INC


### OnCreaturePortraitEnter(int)

```csharp
public void OnCreaturePortraitEnter(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnCreaturePortraitExit(int)

```csharp
public void OnCreaturePortraitExit(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnDeallocateAll()

```csharp
public void OnDeallocateAll()
```
#INC


### OnDestroy()

```csharp
private void OnDestroy()
```
#INC


### OnManageStart()

```csharp
public void OnManageStart()
```
#INC


### OnOverlayEnter(int)

```csharp
public void OnOverlayEnter(int index)
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

### OnOverlayPanel(PanelDataState)

```csharp
private void OnOverlayPanel(SefiraPanel.PanelDataState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.SefiraPanel.PanelDataState` |  |

### OnPanelEnter(BaseEventData)

```csharp
public void OnPanelEnter(BaseEventData bData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnPanelExit()

```csharp
public void OnPanelExit()
```
#INC


### OnRemoveAgent(int)

```csharp
public void OnRemoveAgent(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnRemoveAgent_NotAddToList(int)

```csharp
public void OnRemoveAgent_NotAddToList(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnSetPanel(PanelDataState)

```csharp
private void OnSetPanel(SefiraPanel.PanelDataState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.SefiraPanel.PanelDataState` |  |

### OnStartBossSession()

```csharp
public void OnStartBossSession()
```
#INC


### Registration()

```csharp
public void Registration()
```
#INC


### RemoveAgent(AgentModel)

```csharp
public bool RemoveAgent(AgentModel agent)
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Boolean

### ResetPanel()

```csharp
private void ResetPanel()
```
#INC


### ScrollInit(Transform)

```csharp
private void ScrollInit(Transform root)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `root` | `UnityEngine.Transform` |  |

### SetAlterGraphicsColor(Color)

```csharp
public void SetAlterGraphicsColor(Color altercolor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `altercolor` | `UnityEngine.Color` |  |

### SetBossPanel(bool)

```csharp
public void SetBossPanel(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetBossState()

```csharp
public void SetBossState()
```
#INC


### SetDescriptionText()

```csharp
public void SetDescriptionText()
```
#INC


### SetSclae(float)

```csharp
public void SetSclae(float factor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factor` | `System.Single` |  |

### SetTextureColor()

```csharp
private void SetTextureColor()
```
#INC


### Start()

```csharp
private void Start()
```
#INC


### Update()

```csharp
private void Update()
```
#INC

