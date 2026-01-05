# Class ResearchWindow

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResearchWindow : MonoBehaviour, IAnimatorEventCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → ResearchWindow

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ResearchWindow()

```csharp
public ResearchWindow()
```

## Fields

### Areaname

```csharp
public Text Areaname
```

#### Field Value

**Type:** UnityEngine.UI.Text

### backGround

```csharp
public Image backGround
```

#### Field Value

**Type:** UnityEngine.UI.Image

### ButtonArea

```csharp
public RectTransform ButtonArea
```

#### Field Value

**Type:** UnityEngine.RectTransform

### buttonColorMultiplier

```csharp
public ColorMultiplier[] buttonColorMultiplier
```

#### Field Value

**Type:** Global.ColorMultiplier[]

### coloredTargets

```csharp
public List<MaskableGraphic> coloredTargets
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### controller

```csharp
public UIController controller
```

#### Field Value

**Type:** Global.UIController

### Conversation

```csharp
public Text Conversation
```

#### Field Value

**Type:** UnityEngine.UI.Text

### disableParent

```csharp
public RectTransform disableParent
```

#### Field Value

**Type:** UnityEngine.RectTransform

### dropArea

```csharp
public Image dropArea
```

#### Field Value

**Type:** UnityEngine.UI.Image

### DropFeildPivot

```csharp
public RectTransform DropFeildPivot
```

#### Field Value

**Type:** UnityEngine.RectTransform

### dropHandler

```csharp
public Drop dropHandler
```

#### Field Value

**Type:** Global.Drop

### grayFactor

```csharp
public float grayFactor
```

#### Field Value

**Type:** System.Single

### HelpArea

```csharp
public RectTransform HelpArea
```

#### Field Value

**Type:** UnityEngine.RectTransform

### instructions

```csharp
public ColorMultiplier[] instructions
```

#### Field Value

**Type:** Global.ColorMultiplier[]

### instTime

```csharp
public float instTime
```

#### Field Value

**Type:** System.Single

### layoutParent

```csharp
public RectTransform layoutParent
```

#### Field Value

**Type:** UnityEngine.RectTransform

### LowerArea

```csharp
public RectTransform LowerArea
```

#### Field Value

**Type:** UnityEngine.RectTransform

### panels

```csharp
public List<ResearchPanel> panels
```

#### Field Value

**Type:** System.Collections.Generic.List{ResearchPanel}

### Portrait

```csharp
public Image Portrait
```

#### Field Value

**Type:** UnityEngine.UI.Image

### positionFactor

```csharp
public static float[,] positionFactor
```

#### Field Value

**Type:** System.Single[,]

### researchPanelArea

```csharp
[Header("SefiraBoss")]
public GameObject researchPanelArea
```

#### Field Value

**Type:** UnityEngine.GameObject

### ResearchSound

```csharp
public AudioClipPlayer ResearchSound
```

#### Field Value

**Type:** Global.AudioClipPlayer

### rootObject

```csharp
public GameObject rootObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### sefiraBoss_ListParent

```csharp
public RectTransform sefiraBoss_ListParent
```

#### Field Value

**Type:** UnityEngine.RectTransform

### sefiraBoss_Prefix

```csharp
public Text sefiraBoss_Prefix
```

#### Field Value

**Type:** UnityEngine.UI.Text

### sefiraBossButton

```csharp
public GameObject sefiraBossButton
```

#### Field Value

**Type:** UnityEngine.GameObject

### sefiraBossRoot

```csharp
public GameObject sefiraBossRoot
```

#### Field Value

**Type:** UnityEngine.GameObject

### sefiraTextUnit

```csharp
public GameObject sefiraTextUnit
```

#### Field Value

**Type:** UnityEngine.GameObject

### selectedEffectImage

```csharp
public Image selectedEffectImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### selectedPanel

```csharp
public ResearchPanel selectedPanel
```

#### Field Value

**Type:** Global.ResearchPanel

### title

```csharp
public Text title
```

#### Field Value

**Type:** UnityEngine.UI.Text

### ui

```csharp
public ResearchWindow.UI ui
```

#### Field Value

**Type:** Global.ResearchWindow.UI

## Properties

### CurrentSefira

```csharp
public Sefira CurrentSefira { get; }
```

#### Property Value

**Type:** Global.Sefira

### IsDragging

```csharp
public bool IsDragging { get; }
```

#### Property Value

**Type:** System.Boolean

### UIColor

```csharp
public SefiraUIColor UIColor { get; }
```

#### Property Value

**Type:** Global.SefiraUIColor

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

### CreatureAnimCall(int, CreatureBase)

```csharp
public void CreatureAnimCall(int i, CreatureBase script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `script` | `Global.CreatureBase` |  |

### Init(Sefira)

```csharp
public void Init(Sefira sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

### MakeSefiraBossReward(SefiraEnum)

```csharp
public void MakeSefiraBossReward(SefiraEnum sefiraEnum)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraEnum` | `Global.SefiraEnum` |  |

### OnBeginDrag(ResearchPanel)

```csharp
public void OnBeginDrag(ResearchPanel panel)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `panel` | `Global.ResearchPanel` |  |

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

### OnConfirm()

```csharp
public void OnConfirm()
```

### OnDiscard()

```csharp
public void OnDiscard()
```

### OnDropEvent(params object[])

```csharp
public bool OnDropEvent(params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `param` | `System.Object[]` |  |

#### Returns

**Type:** System.Boolean

### OnEndDrag()

```csharp
public void OnEndDrag()
```

### OnEnter(BaseEventData)

```csharp
public void OnEnter(BaseEventData bpData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bpData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnExit(BaseEventData)

```csharp
public void OnExit(BaseEventData pData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnPanelEnter()

```csharp
public void OnPanelEnter()
```

### OnPanelExit()

```csharp
public void OnPanelExit()
```

### OnSetPanel(bool)

```csharp
public void OnSetPanel(bool isSet)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isSet` | `System.Boolean` |  |

### SetActive(bool)

```csharp
public void SetActive(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetInst(float)

```csharp
public void SetInst(float factor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factor` | `System.Single` |  |

### SetPanelActivate(ResearchPanel, bool)

```csharp
public void SetPanelActivate(ResearchPanel panel, bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `panel` | `Global.ResearchPanel` |  |
| `state` | `System.Boolean` |  |

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
