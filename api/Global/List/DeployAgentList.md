---
uid: Global.DeployAgentList
canonical_path: /api/Global/List/DeployAgentList
---

# Class DeployAgentList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeployAgentList : MonoBehaviour, IScrollMessageReciever
```

UI element displaying unassigned agents on the deployment screen.

May touch other things... #INC 

(Also, seems they had intended it to be able to sort, though this is not present in the game.)



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → DeployAgentList

## Implements
[IScrollMessageReciever](/api/Global/Misc/IScrollMessageReciever)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DeployAgentList()

```csharp
public DeployAgentList()
```

## Fields

### _currentLinePos

```csharp
private int _currentLinePos
```
#INC


#### Field Value

**Type:** System.Int32

### _currentPersonality

```csharp
private PersonalityType _currentPersonality
```
#INC


#### Field Value

**Type:** Global.PersonalityType

### _disabledList

```csharp
private List<DeployAgentSlot> _disabledList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{DeployAgentSlot}

### _minimumScrollLineCount

```csharp
private const int _minimumScrollLineCount = 4
```
#INC


#### Field Value

**Type:** System.Int32

### _slotsPerLine

```csharp
private const int _slotsPerLine = 3
```
#INC


#### Field Value

**Type:** System.Int32

### _slotSrc

```csharp
private const string _slotSrc = "UIComponent/DeployAgentSlot"
```
#INC


#### Field Value

**Type:** System.String

### agentList

```csharp
public List<AgentModel> agentList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentModel}

### Customizing

```csharp
public Button Customizing
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### CustomizingText

```csharp
public Text CustomizingText
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

### enterLeft

```csharp
private bool enterLeft
```
#INC


#### Field Value

**Type:** System.Boolean

### enterRight

```csharp
private bool enterRight
```
#INC


#### Field Value

**Type:** System.Boolean

### HireButton

```csharp
public Button HireButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### HireText

```csharp
public Text HireText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### listParent

```csharp
public RectTransform listParent
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### LowerArrow

```csharp
public GameObject LowerArrow
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### originalList

```csharp
private List<AgentModel> originalList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentModel}

### OverlayScaleSetter

```csharp
public ScaleSetter[] OverlayScaleSetter
```
#INC


#### Field Value

**Type:** Global.ScaleSetter[]

### scroll

```csharp
public ScrollExchanger scroll
```
#INC


#### Field Value

**Type:** Global.ScrollExchanger

### scrollRect

```csharp
public ScrollRect scrollRect
```
#INC


#### Field Value

**Type:** UnityEngine.UI.ScrollRect

### slotList

```csharp
public List<DeployAgentSlot> slotList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{DeployAgentSlot}

### sortData

```csharp
public DeployAgentList.AgentSortData sortData
```

#### Field Value

**Type:** Global.DeployAgentList.AgentSortData

### Spacing

```csharp
public Vector2 Spacing
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### UnitSize

```csharp
public Vector2 UnitSize
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### UpperArrow

```csharp
public GameObject UpperArrow
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

## Properties

### LineCount

```csharp
public int LineCount { get; }
```

#### Property Value

**Type:** System.Int32

### LineUnit

```csharp
public int LineUnit { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### AddAgent(AgentModel)

```csharp
public void AddAgent(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### CheckArrow()

```csharp
private void CheckArrow()
```
#INC


### DeployAgent(AgentModel)

```csharp
public bool DeployAgent(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Boolean

### DivByLevel(List<AgentModel>)

```csharp
private Dictionary<int, List<AgentModel>> DivByLevel(List<AgentModel> original)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `original` | `System.Collections.Generic.List{AgentModel}` |  |

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.List{AgentModel}}

### DivideByValue(List<AgentModel>)

```csharp
private List<AgentModel>[] DivideByValue(List<AgentModel> original)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `original` | `System.Collections.Generic.List{AgentModel}` |  |

#### Returns

**Type:** System.Collections.Generic.List{AgentModel}[]

### DivideListByGender(List<AgentModel>)

```csharp
private List<AgentModel>[] DivideListByGender(List<AgentModel> original)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `original` | `System.Collections.Generic.List{AgentModel}` |  |

#### Returns

**Type:** System.Collections.Generic.List{AgentModel}[]

### GenSlot(AgentModel)

```csharp
private DeployAgentSlot GenSlot(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** Global.DeployAgentSlot

### GetCopiedList()

```csharp
private List<AgentModel> GetCopiedList()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{AgentModel}

### GetDisabledSlot(AgentModel)

```csharp
private DeployAgentSlot GetDisabledSlot(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** Global.DeployAgentSlot

### GetSlot(AgentModel)

```csharp
private DeployAgentSlot GetSlot(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** Global.DeployAgentSlot

### Init(IList<AgentModel>)

```csharp
public void Init(IList<AgentModel> spareAgents)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spareAgents` | `System.Collections.Generic.IList{AgentModel}` |  |

### InitArrow()

```csharp
private void InitArrow()
```
#INC


### LifeStyleFix(bool)

```csharp
private void LifeStyleFix(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### ListInit()

```csharp
private void ListInit()
```
#INC


### ListSort()

```csharp
public void ListSort()
```
#INC


### MainSort()

```csharp
private List<AgentModel> MainSort()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{AgentModel}

### MoveLower()

```csharp
public void MoveLower()
```
#INC


### MoveUpper()

```csharp
public void MoveUpper()
```
#INC


### OnClickGenderSort()

```csharp
public void OnClickGenderSort()
```
#INC


### OnClickLevelSort()

```csharp
public void OnClickLevelSort()
```
#INC


### OnClickValueSort()

```csharp
public void OnClickValueSort()
```
#INC


### OnEnterButton(int)

```csharp
public void OnEnterButton(int buttonIndexer)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `buttonIndexer` | `System.Int32` |  |

### OnExitButton(int)

```csharp
public void OnExitButton(int buttonIndexer)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `buttonIndexer` | `System.Int32` |  |

### OnPointerDown(int)

```csharp
public void OnPointerDown(int button)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `button` | `System.Int32` |  |

### OnPointerUp(int)

```csharp
public void OnPointerUp(int button)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `button` | `System.Int32` |  |

### OnScroll(PointerEventData)

```csharp
public void OnScroll(PointerEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.PointerEventData` |  |

### OnScrolled(PointerEventData)

```csharp
public void OnScrolled(PointerEventData pData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pData` | `UnityEngine.EventSystems.PointerEventData` |  |

### OnScrolled(Vector2)

```csharp
public void OnScrolled(Vector2 scrollDelta)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `scrollDelta` | `UnityEngine.Vector2` |  |

### OnSortClick(int)

```csharp
public void OnSortClick(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnSortEnter(int)

```csharp
public void OnSortEnter(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### SetList()

```csharp
private void SetList()
```
#INC


### SetSortUI()

```csharp
private void SetSortUI()
```
#INC


### SetSortUIColor()

```csharp
private void SetSortUIColor()
```
#INC


### SortByLevel(List<AgentModel>, bool)

```csharp
private List<AgentModel> SortByLevel(List<AgentModel> sorted, bool isAscending)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sorted` | `System.Collections.Generic.List{AgentModel}` |  |
| `isAscending` | `System.Boolean` |  |

#### Returns

**Type:** System.Collections.Generic.List{AgentModel}

### SortInverse()

```csharp
private void SortInverse()
```
#INC


### Update()

```csharp
private void Update()
```
#INC

