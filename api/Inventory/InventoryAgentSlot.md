---
uid: Inventory.InventoryAgentSlot
canonical_path: /api/Inventory/InventoryAgentSlot
---

# Class InventoryAgentSlot

**Namespace:** [Inventory](/api/Inventory)
**Assembly:** Assembly-CSharp.dll

```csharp
public class InventoryAgentSlot : MonoBehaviour, IObserver
```

UI element which displays an agent to be equipped on the [E.G.O List screen](/api/Inventory/InventoryUI).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → InventoryAgentSlot

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### InventoryAgentSlot()

```csharp
public InventoryAgentSlot()
```

## Fields

### _model

```csharp
private AgentModel _model
```
#INC


#### Field Value

**Type:** Global.AgentModel

### _overScaleFactor

```csharp
private const float _overScaleFactor = 1.1
```
#INC


#### Field Value

**Type:** System.Single

### AgentName

```csharp
public Text AgentName
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### AgentTitle

```csharp
public Text AgentTitle
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### defDataRoot

```csharp
public GameObject defDataRoot
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### Grade

```csharp
public Image Grade
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### GradeText

```csharp
public Text GradeText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### HasRequireComponents

```csharp
public bool HasRequireComponents
```
#INC


#### Field Value

**Type:** System.Boolean

### noticeObserving

```csharp
private bool noticeObserving
```
#INC


#### Field Value

**Type:** System.Boolean

### portrait

```csharp
public WorkerPortraitSetter portrait
```
#INC


#### Field Value

**Type:** Global.WorkerPortraitSetter

### require

```csharp
public InventoryRequireLayout require
```
#INC


#### Field Value

**Type:** Inventory.InventoryRequireLayout

### slot

```csharp
private InventorySlot slot
```
#INC


#### Field Value

**Type:** Inventory.InventorySlot

### Texture

```csharp
public Image Texture
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

## Properties

### Model

```csharp
public AgentModel Model { get; }
```

#### Property Value

**Type:** Global.AgentModel

### outline

```csharp
private Outline outline { get; }
```

#### Property Value

**Type:** UnityEngine.UI.Outline

## Methods

### AttachInteraction(Entry, OnClickEvent)

```csharp
private void AttachInteraction(EventTrigger.Entry entry, InventoryAgentSlot.OnClickEvent voidEvent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `UnityEngine.EventSystems.EventTrigger.Entry` |  |
| `voidEvent` | `Inventory.InventoryAgentSlot.OnClickEvent` |  |

### AttachInteractionEvent(EventTrigger)

```csharp
private void AttachInteractionEvent(EventTrigger eventTrigger)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventTrigger` | `UnityEngine.EventSystems.EventTrigger` |  |

### AttachNotice()

```csharp
public void AttachNotice()
```
#INC


### AttachOnClickEvent(OnClickEvent)

```csharp
public void AttachOnClickEvent(InventoryAgentSlot.OnClickEvent c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `Inventory.InventoryAgentSlot.OnClickEvent` |  |

### AttachOnClickEvent(OnClickEventByAgent)

```csharp
public void AttachOnClickEvent(InventoryAgentSlot.OnClickEventByAgent c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `Inventory.InventoryAgentSlot.OnClickEventByAgent` |  |

### DetachNotice()

```csharp
public void DetachNotice()
```
#INC


### Init()

```csharp
public void Init()
```
#INC
#code-generated


### OnClickSefiraController()

```csharp
public void OnClickSefiraController()
```
#INC


### OnDestroy()

```csharp
private void OnDestroy()
```
#INC


### OnEnter()

```csharp
public void OnEnter()
```
#INC


### OnExit()

```csharp
public void OnExit()
```
#INC


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

### SetActive(bool)

```csharp
public void SetActive(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetAgent(AgentModel)

```csharp
public void SetAgent(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### SetDisabled()

```csharp
public void SetDisabled()
```
#INC


### SetEmpty()

```csharp
public void SetEmpty()
```
#INC


### SetInfo(InventorySlot)

```csharp
public void SetInfo(InventorySlot i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `Inventory.InventorySlot` |  |

### SetRequireInfo(EquipmentTypeInfo)

```csharp
public void SetRequireInfo(EquipmentTypeInfo info)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |

### SetState(EquipState)

```csharp
public void SetState(InventoryAgentSlot.EquipState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Inventory.InventoryAgentSlot.EquipState` |  |

### SetTextureColor(Color)

```csharp
public void SetTextureColor(Color c)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### Start()

```csharp
private void Start()
```
#INC


### UpdateTexture()

```csharp
public void UpdateTexture()
```
#INC

