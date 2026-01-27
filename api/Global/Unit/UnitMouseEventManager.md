---
uid: Global.UnitMouseEventManager
canonical_path: /api/Global/Unit/UnitMouseEventManager
---

# Class UnitMouseEventManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnitMouseEventManager : MonoBehaviour
```

Probably manages clicking and hovering events...

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → UnitMouseEventManager

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UnitMouseEventManager()

```csharp
public UnitMouseEventManager()
```

## Fields

### _currentInDragTargets

```csharp
private List<UnitMouseEventTarget> _currentInDragTargets
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnitMouseEventTarget}

### _defualtClickBlocked

```csharp
private bool _defualtClickBlocked
```
#INC


#### Field Value

**Type:** System.Boolean

### _dragBeginPointer

```csharp
private PointerEventData _dragBeginPointer
```
#INC


#### Field Value

**Type:** UnityEngine.EventSystems.PointerEventData

### _dragBeginPosition

```csharp
private Vector2 _dragBeginPosition
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### _dragEnteredTargets

```csharp
private Dictionary<UnitMouseEventTarget, bool> _dragEnteredTargets
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{UnitMouseEventTarget,System.Boolean}

### _dragging

```csharp
private bool _dragging
```
#INC


#### Field Value

**Type:** System.Boolean

### _draggingRight

```csharp
private bool _draggingRight
```
#INC


#### Field Value

**Type:** System.Boolean

### _instance

```csharp
private static UnitMouseEventManager _instance
```
#INC


#### Field Value

**Type:** Global.UnitMouseEventManager

### _pointerEnter

```csharp
private bool _pointerEnter
```
#INC


#### Field Value

**Type:** System.Boolean

### _pointerEnteredRightTarget

```csharp
private UnitMouseEventTarget _pointerEnteredRightTarget
```
#INC


#### Field Value

**Type:** Global.UnitMouseEventTarget

### _pointerEnteredTarget

```csharp
private UnitMouseEventTarget _pointerEnteredTarget
```
#INC


#### Field Value

**Type:** Global.UnitMouseEventTarget

### _selectedTargets

```csharp
private List<UnitMouseEventTarget> _selectedTargets
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnitMouseEventTarget}

### _stageStarted

```csharp
private bool _stageStarted
```
#INC


#### Field Value

**Type:** System.Boolean

### ClickTransitionCurve

```csharp
public AnimationCurve ClickTransitionCurve
```
#INC


#### Field Value

**Type:** UnityEngine.AnimationCurve

### dragImage

```csharp
public Image dragImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### suppressCursor

```csharp
public bool suppressCursor
```
#INC


#### Field Value

**Type:** System.Boolean

## Properties

### DefaultClickBlocked

```csharp
public bool DefaultClickBlocked { get; set; }
```

#### Property Value

**Type:** System.Boolean

### draggingRight

```csharp
public bool draggingRight { get; }
```

#### Property Value

**Type:** System.Boolean

### instance

```csharp
public static UnitMouseEventManager instance { get; }
```

#### Property Value

**Type:** Global.UnitMouseEventManager

### isPointerEntered

```csharp
public bool isPointerEntered { get; }
```

#### Property Value

**Type:** System.Boolean

### seletedtargets

```csharp
public List<UnitMouseEventTarget> seletedtargets { get; }
```

#### Property Value

**Type:** System.Collections.Generic.List{UnitMouseEventTarget}

## Methods

### Awake()

```csharp
private void Awake()
```
#INC
#code-generated


### CancelDrag()

```csharp
public void CancelDrag()
```
#INC


### GetCurrentPointerTargets()

```csharp
public List<UnitMouseEventTarget> GetCurrentPointerTargets()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{UnitMouseEventTarget}

### GetPointerEnteredTarget()

```csharp
public UnitMouseEventTarget GetPointerEnteredTarget()
```
#INC


#### Returns

**Type:** Global.UnitMouseEventTarget

### GetSelectedAgents()

```csharp
public List<AgentModel> GetSelectedAgents()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{AgentModel}

### IsRightClickable(UnitMouseEventTarget)

```csharp
private bool IsRightClickable(UnitMouseEventTarget target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitMouseEventTarget` |  |

#### Returns

**Type:** System.Boolean

### OnBeginDrag(BaseEventData)

```csharp
public void OnBeginDrag(BaseEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnDrag(BaseEventData)

```csharp
public void OnDrag(BaseEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnEndDrag(BaseEventData)

```csharp
public void OnEndDrag(BaseEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnPointerClick(BaseEventData)

```csharp
public void OnPointerClick(BaseEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnPointerClick_bullet(BaseEventData)

```csharp
private void OnPointerClick_bullet(BaseEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnPointerClick_default(BaseEventData)

```csharp
private void OnPointerClick_default(BaseEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnPointerDown(BaseEventData)

```csharp
public void OnPointerDown(BaseEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnPointerEnter(BaseEventData)

```csharp
public void OnPointerEnter(BaseEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnPointerExit(BaseEventData)

```csharp
public void OnPointerExit(BaseEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnPointerUp(BaseEventData)

```csharp
public void OnPointerUp(BaseEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.BaseEventData` |  |

### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### SelectTarget(UnitMouseEventTarget)

```csharp
private void SelectTarget(UnitMouseEventTarget target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitMouseEventTarget` |  |

### SelectTargets(List<UnitMouseEventTarget>)

```csharp
private void SelectTargets(List<UnitMouseEventTarget> targets)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targets` | `System.Collections.Generic.List{UnitMouseEventTarget}` |  |

### SetPointerEnteredRightTarget(UnitMouseEventTarget)

```csharp
private void SetPointerEnteredRightTarget(UnitMouseEventTarget rightTarget)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rightTarget` | `Global.UnitMouseEventTarget` |  |

### SetPointerEnteredTarget(UnitMouseEventTarget)

```csharp
private void SetPointerEnteredTarget(UnitMouseEventTarget target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitMouseEventTarget` |  |

### Unselect(IMouseCommandTargetModel)

```csharp
public void Unselect(IMouseCommandTargetModel targetModel)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetModel` | `Global.IMouseCommandTargetModel` |  |

### UnselectAll()

```csharp
public void UnselectAll()
```
#INC


### Update()

```csharp
private void Update()
```
#INC


### UpdateDrag()

```csharp
private void UpdateDrag()
```
#INC


### UpdatePointEntered()

```csharp
private void UpdatePointEntered()
```
#INC

