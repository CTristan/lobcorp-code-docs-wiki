---
uid: Global.ResearchWindow
canonical_path: /api/Global/IANimatorEventCalled/ResearchWindow
---

# Class ResearchWindow

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResearchWindow : MonoBehaviour, IAnimatorEventCalled
```

The researching UI. #INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → ResearchWindow

## Implements
[IAnimatorEventCalled](/api/Global/Misc/IAnimatorEventCalled)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ResearchWindow()

```csharp
public ResearchWindow()
```

## Fields

### _bossState

```csharp
private bool _bossState
```
#INC


#### Field Value

**Type:** System.Boolean

### _currentSefira

```csharp
private Sefira _currentSefira
```
#INC


#### Field Value

**Type:** Global.Sefira

### _isDragging

```csharp
private bool _isDragging
```
#INC


#### Field Value

**Type:** System.Boolean

### _researchMaxPerArea

```csharp
private const int _researchMaxPerArea = 4
```
#INC


#### Field Value

**Type:** System.Int32

### _uiColor

```csharp
private SefiraUIColor _uiColor
```
#INC


#### Field Value

**Type:** Global.SefiraUIColor

### Areaname

```csharp
public Text Areaname
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### backGround

```csharp
public Image backGround
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### ButtonArea

```csharp
public RectTransform ButtonArea
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### buttonColorMultiplier

```csharp
public ColorMultiplier[] buttonColorMultiplier
```
#INC


#### Field Value

**Type:** Global.ColorMultiplier[]

### coloredTargets

```csharp
public List<MaskableGraphic> coloredTargets
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### controller

```csharp
public UIController controller
```
#INC


#### Field Value

**Type:** Global.UIController

### Conversation

```csharp
public Text Conversation
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### disableParent

```csharp
public RectTransform disableParent
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### dropArea

```csharp
public Image dropArea
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### DropFeildPivot

```csharp
public RectTransform DropFeildPivot
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### dropHandler

```csharp
public Drop dropHandler
```
#INC


#### Field Value

**Type:** Global.Drop

### gray

```csharp
private bool gray
```
#INC


#### Field Value

**Type:** System.Boolean

### grayFactor

```csharp
public float grayFactor
```
#INC


#### Field Value

**Type:** System.Single

### HelpArea

```csharp
public RectTransform HelpArea
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### instructions

```csharp
public ColorMultiplier[] instructions
```
#INC


#### Field Value

**Type:** Global.ColorMultiplier[]

### instTime

```csharp
public float instTime
```
#INC


#### Field Value

**Type:** System.Single

### instTimer

```csharp
private UnscaledTimer instTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### layoutParent

```csharp
public RectTransform layoutParent
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### LowerArea

```csharp
public RectTransform LowerArea
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### panels

```csharp
public List<ResearchPanel> panels
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{ResearchPanel}

### Portrait

```csharp
public Image Portrait
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### positionFactor

```csharp
public static float[,] positionFactor
```
#INC


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
#INC


#### Field Value

**Type:** Global.AudioClipPlayer

### rootObject

```csharp
public GameObject rootObject
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### sefiraBoss_ListParent

```csharp
public RectTransform sefiraBoss_ListParent
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### sefiraBoss_Prefix

```csharp
public Text sefiraBoss_Prefix
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### sefiraBossButton

```csharp
public GameObject sefiraBossButton
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### sefiraBossRoot

```csharp
public GameObject sefiraBossRoot
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### sefiraTextUnit

```csharp
public GameObject sefiraTextUnit
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### selectedEffectImage

```csharp
public Image selectedEffectImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### selectedPanel

```csharp
public ResearchPanel selectedPanel
```
#INC


#### Field Value

**Type:** Global.ResearchPanel

### title

```csharp
public Text title
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### ui

```csharp
public ResearchWindow.UI ui
```

#### Field Value

**Type:** Global.ResearchWindow.UI

## Properties

### ConversationAnim

```csharp
private UIController ConversationAnim { get; }
```

#### Property Value

**Type:** Global.UIController

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

### Init(Sefira)

```csharp
public void Init(Sefira sefira)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

### MakeSefiraBossReward(SefiraEnum)

```csharp
public void MakeSefiraBossReward(SefiraEnum sefiraEnum)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraEnum` | `Global.SefiraEnum` |  |

### OnBeginDrag(ResearchPanel)

```csharp
public void OnBeginDrag(ResearchPanel panel)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `panel` | `Global.ResearchPanel` |  |

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

### OnConfirm()

```csharp
public void OnConfirm()
```
#INC


### OnDiscard()

```csharp
public void OnDiscard()
```
#INC


### OnDropEvent(params object[])

```csharp
public bool OnDropEvent(params object[] param)
```
#INC


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
#INC


### OnEnter(BaseEventData)

```csharp
public void OnEnter(BaseEventData bpData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bpData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnExit(BaseEventData)

```csharp
public void OnExit(BaseEventData pData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnPanelEnter()

```csharp
public void OnPanelEnter()
```
#INC


### OnPanelExit()

```csharp
public void OnPanelExit()
```
#INC


### OnSetPanel(bool)

```csharp
public void OnSetPanel(bool isSet)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isSet` | `System.Boolean` |  |

### ResearchDataInit()

```csharp
private int ResearchDataInit()
```
#INC


#### Returns

**Type:** System.Int32

### SetActive(bool)

```csharp
public void SetActive(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetColor()

```csharp
private void SetColor()
```
#INC


### SetInst(float)

```csharp
public void SetInst(float factor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factor` | `System.Single` |  |

### SetPanelActivate(ResearchPanel, bool)

```csharp
public void SetPanelActivate(ResearchPanel panel, bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `panel` | `Global.ResearchPanel` |  |
| `state` | `System.Boolean` |  |

### SetPanelController(bool)

```csharp
private void SetPanelController(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetPanelPosition(int)

```csharp
private void SetPanelPosition(int max)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `max` | `System.Int32` |  |

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

### Update()

```csharp
private void Update()
```
#INC


### Upgrade(ResearchItemModel)

```csharp
private void Upgrade(ResearchItemModel data)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Global.ResearchItemModel` |  |
