# Class DeployAgentList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeployAgentList : MonoBehaviour, IScrollMessageReciever
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → DeployAgentList

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DeployAgentList()

```csharp
public DeployAgentList()
```

## Fields

### agentList

```csharp
public List<AgentModel> agentList
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentModel}

### Customizing

```csharp
public Button Customizing
```

#### Field Value

**Type:** UnityEngine.UI.Button

### CustomizingText

```csharp
public Text CustomizingText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### disableParent

```csharp
public RectTransform disableParent
```

#### Field Value

**Type:** UnityEngine.RectTransform

### HireButton

```csharp
public Button HireButton
```

#### Field Value

**Type:** UnityEngine.UI.Button

### HireText

```csharp
public Text HireText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### listParent

```csharp
public RectTransform listParent
```

#### Field Value

**Type:** UnityEngine.RectTransform

### LowerArrow

```csharp
public GameObject LowerArrow
```

#### Field Value

**Type:** UnityEngine.GameObject

### OverlayScaleSetter

```csharp
public ScaleSetter[] OverlayScaleSetter
```

#### Field Value

**Type:** Global.ScaleSetter[]

### scroll

```csharp
public ScrollExchanger scroll
```

#### Field Value

**Type:** Global.ScrollExchanger

### scrollRect

```csharp
public ScrollRect scrollRect
```

#### Field Value

**Type:** UnityEngine.UI.ScrollRect

### slotList

```csharp
public List<DeployAgentSlot> slotList
```

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

#### Field Value

**Type:** UnityEngine.Vector2

### UnitSize

```csharp
public Vector2 UnitSize
```

#### Field Value

**Type:** UnityEngine.Vector2

### UpperArrow

```csharp
public GameObject UpperArrow
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### DeployAgent(AgentModel)

```csharp
public bool DeployAgent(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Boolean

### Init(IList<AgentModel>)

```csharp
public void Init(IList<AgentModel> spareAgents)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spareAgents` | `System.Collections.Generic.IList{AgentModel}` |  |

### ListSort()

```csharp
public void ListSort()
```

### MoveLower()

```csharp
public void MoveLower()
```

### MoveUpper()

```csharp
public void MoveUpper()
```

### OnClickGenderSort()

```csharp
public void OnClickGenderSort()
```

### OnClickLevelSort()

```csharp
public void OnClickLevelSort()
```

### OnClickValueSort()

```csharp
public void OnClickValueSort()
```

### OnEnterButton(int)

```csharp
public void OnEnterButton(int buttonIndexer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `buttonIndexer` | `System.Int32` |  |

### OnExitButton(int)

```csharp
public void OnExitButton(int buttonIndexer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `buttonIndexer` | `System.Int32` |  |

### OnPointerDown(int)

```csharp
public void OnPointerDown(int button)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `button` | `System.Int32` |  |

### OnPointerUp(int)

```csharp
public void OnPointerUp(int button)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `button` | `System.Int32` |  |

### OnScroll(PointerEventData)

```csharp
public void OnScroll(PointerEventData eventData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.PointerEventData` |  |

### OnScrolled(PointerEventData)

```csharp
public void OnScrolled(PointerEventData pData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pData` | `UnityEngine.EventSystems.PointerEventData` |  |

### OnScrolled(Vector2)

```csharp
public void OnScrolled(Vector2 scrollDelta)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `scrollDelta` | `UnityEngine.Vector2` |  |

### OnSortClick(int)

```csharp
public void OnSortClick(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnSortEnter(int)

```csharp
public void OnSortEnter(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
