---
uid: CommandWindow.AgentSlot
canonical_path: /api/CommandWindow/AgentSlot
---

# Class AgentSlot

**Namespace:** [CommandWindow](/api/CommandWindow)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentSlot : MonoBehaviour
```
UI element for the [agent](/api/Global/Worker/AgentUnit) in the [suppression and management UIs](/api/CommandWindow). Extends to show equipment or defense information (see [SuppressSlot](/api/CommandWindow/SuppressSlot)) or work stats (see [ManagementSlot](/api/CommandWindow/ManagementSlot)).

#parent 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → AgentSlot

## Derived
[ManagementSlot](/api/CommandWindow/ManagementSlot), [SuppressSlot](/api/CommandWindow/SuppressSlot)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentSlot()

```csharp
public AgentSlot()
```

## Fields

### _currentAgent

```csharp
private AgentModel _currentAgent
```
#INC


#### Field Value

**Type:** Global.AgentModel

### _overlayEntered

```csharp
private bool _overlayEntered
```
#INC


#### Field Value

**Type:** System.Boolean

### _state

```csharp
private AgentState _state
```
#INC


#### Field Value

**Type:** CommandWindow.AgentState

### ActiveControl

```csharp
public GameObject ActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### AgentName

```csharp
public Text AgentName
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### coloredTargets

```csharp
public List<MaskableGraphic> coloredTargets
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### FilterControl

```csharp
[Header("Filter")]
public GameObject FilterControl
```

#### Field Value

**Type:** UnityEngine.GameObject

### FilterFill

```csharp
public Image FilterFill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### FilterText

```csharp
public Text FilterText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### Grade

```csharp
public Image Grade
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### HealthFill

```csharp
public Image HealthFill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### HealthText

```csharp
public Text HealthText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### MentalFill

```csharp
public Image MentalFill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### MentalText

```csharp
public Text MentalText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### Portrait

```csharp
public GameObject Portrait
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### portrait

```csharp
public WorkerPortraitSetter portrait
```
#INC


#### Field Value

**Type:** Global.WorkerPortraitSetter

### WorkFilterControl

```csharp
public GameObject WorkFilterControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### WorkFilterFill

```csharp
public Image WorkFilterFill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### WorkFilterSubText

```csharp
public Text WorkFilterSubText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### WorkFilterText

```csharp
public Text WorkFilterText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

## Properties

### CurrentAgent

```csharp
public AgentModel CurrentAgent { get; }
```

#### Property Value

**Type:** Global.AgentModel

### IsOrderable

```csharp
private bool IsOrderable { get; }
```

#### Property Value

**Type:** System.Boolean

### OverlayEntered

```csharp
public bool OverlayEntered { get; set; }
```

#### Property Value

**Type:** System.Boolean

### State

```csharp
public AgentState State { get; set; }
```

#### Property Value

**Type:** CommandWindow.AgentState

## Methods

### CheckAgentState()

```csharp
public virtual void CheckAgentState()
```
#INC


### GetRate(float, float)

```csharp
public static float GetRate(float value, float max)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |
| `max` | `System.Single` |  |

#### Returns

**Type:** System.Single

### OnClick()

```csharp
public virtual void OnClick()
```
#INC


### OnClickInfo()

```csharp
public void OnClickInfo()
```
#INC


### OnEnable()

```csharp
private void OnEnable()
```
#INC


### OnOvelrayExit()

```csharp
public virtual void OnOvelrayExit()
```
#INC


### OnOvelrayExit(int)

```csharp
public virtual void OnOvelrayExit(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnOverlayEnter()

```csharp
public virtual void OnOverlayEnter()
```
#INC


### OnOverlayEnter(int)

```csharp
public virtual void OnOverlayEnter(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### SetColor(Color)

```csharp
public virtual void SetColor(Color c)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### SetFilter(AgentState)

```csharp
public virtual void SetFilter(AgentState state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `CommandWindow.AgentState` |  |

### SetModel(AgentModel)

```csharp
public virtual void SetModel(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### SetUI(AgentModel)

```csharp
public virtual void SetUI(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### SetUIColor()

```csharp
public virtual void SetUIColor()
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


### UpdateUI()

```csharp
public virtual void UpdateUI()
```
#INC

