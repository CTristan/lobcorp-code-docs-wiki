---
uid: Global.DeploySefiraAgentSlot
canonical_path: /api/Global/Misc/DeploySefiraAgentSlot
---

# Class DeploySefiraAgentSlot

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeploySefiraAgentSlot : MonoBehaviour, IDraggableObject
```

Draggable slot representing an agent deployed to a department.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → DeploySefiraAgentSlot

## Implements
[IDraggableObject](/api/Global/Object/IDraggableObject)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DeploySefiraAgentSlot()

```csharp
public DeploySefiraAgentSlot()
```

## Fields

### _activaed

```csharp
private bool _activaed
```
#INC


#### Field Value

**Type:** System.Boolean

### _currentState

```csharp
private DeploySefiraAgentSlot.PanelState _currentState
```

#### Field Value

**Type:** Global.DeploySefiraAgentSlot.PanelState

### _dragged

```csharp
private DraggedObject _dragged
```
#INC


#### Field Value

**Type:** Global.DraggedObject

### _isDragging

```csharp
private bool _isDragging
```
#INC


#### Field Value

**Type:** System.Boolean

### _model

```csharp
private AgentModel _model
```
#INC


#### Field Value

**Type:** Global.AgentModel

### _panelDropped

```csharp
private bool _panelDropped
```
#INC


#### Field Value

**Type:** System.Boolean

### _remove

```csharp
private bool _remove
```
#INC


#### Field Value

**Type:** System.Boolean

### CharacterPanel

```csharp
public RectTransform CharacterPanel
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### draggedPortraitSrc

```csharp
private string draggedPortraitSrc
```
#INC


#### Field Value

**Type:** System.String

### dragScript

```csharp
public Drag dragScript
```
#INC


#### Field Value

**Type:** Global.Drag

### emptyDesc

```csharp
private string emptyDesc
```
#INC


#### Field Value

**Type:** System.String

### EmptyPanel

```csharp
public RectTransform EmptyPanel
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### index

```csharp
public int index
```
#INC


#### Field Value

**Type:** System.Int32

### lockDesc

```csharp
private string lockDesc
```
#INC


#### Field Value

**Type:** System.String

### LockedPanel

```csharp
public RectTransform LockedPanel
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### panel

```csharp
public SefiraPanel panel
```
#INC


#### Field Value

**Type:** Global.SefiraPanel

### ui

```csharp
public AgentSlotUI ui
```
#INC


#### Field Value

**Type:** Global.AgentSlotUI

## Properties

### IsActivated

```csharp
public bool IsActivated { get; }
```

#### Property Value

**Type:** System.Boolean

### Model

```csharp
public AgentModel Model { get; }
```

#### Property Value

**Type:** Global.AgentModel

## Methods

### GenDraggedObject(string)

```csharp
public GameObject GenDraggedObject(string name)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject

### GetDraggingObject()

```csharp
public DraggedObject GetDraggingObject()
```
#INC


#### Returns

**Type:** Global.DraggedObject

### GetPanelState()

```csharp
public DeploySefiraAgentSlot.PanelState GetPanelState()
```

#### Returns

**Type:** Global.DeploySefiraAgentSlot.PanelState

### OnCanceled()

```csharp
public void OnCanceled()
```
#INC


### OnDestroy()

```csharp
private void OnDestroy()
```
#INC


### OnDragStart()

```csharp
public void OnDragStart()
```
#INC


### OnDropEnd(Drop, bool)

```csharp
public void OnDropEnd(Drop drop, bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `drop` | `Global.Drop` |  |
| `state` | `System.Boolean` |  |

### OnEndDrag()

```csharp
public void OnEndDrag()
```
#INC


### OnPointerClick(BaseEventData)

```csharp
public void OnPointerClick(BaseEventData bData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnPointerEnter()

```csharp
public void OnPointerEnter()
```
#INC


### OnPointerExit()

```csharp
public void OnPointerExit()
```
#INC


### ResetModel()

```csharp
public void ResetModel()
```
#INC


### SetActive(bool)

```csharp
public void SetActive(bool state)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetModel(AgentModel)

```csharp
public void SetModel(AgentModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.AgentModel` |  |

### SetPanelState(PanelState)

```csharp
public void SetPanelState(DeploySefiraAgentSlot.PanelState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.DeploySefiraAgentSlot.PanelState` |  |

### Start()

```csharp
private void Start()
```
#INC

