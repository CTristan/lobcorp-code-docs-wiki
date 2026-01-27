---
uid: Global.Drag
canonical_path: /api/Global/Misc/Drag
---

# Class Drag

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

[`[UnityEngine.RequireComponent]`](#)

```csharp
[RequireComponent(typeof(Image))]
public class Drag : MonoBehaviour, IBeginDragHandler, IDragHandler, IEndDragHandler, IEventSystemHandler
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → Drag

## Implements
[IBeginDragHandler](#), [IDragHandler](#), [IEndDragHandler](#), [IEventSystemHandler](#)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Drag()

```csharp
public Drag()
```

## Fields

### _beginEvent

```csharp
private Drag.OnDragEvent _beginEvent
```

#### Field Value

**Type:** Global.Drag.OnDragEvent

### _currentDragging

```csharp
private GameObject _currentDragging
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### _draggableScript

```csharp
private IDraggableObject _draggableScript
```
#INC


#### Field Value

**Type:** Global.IDraggableObject

### _draggingImages

```csharp
private Dictionary<int, GameObject> _draggingImages
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,UnityEngine.GameObject}

### _draggingPlanes

```csharp
private Dictionary<int, RectTransform> _draggingPlanes
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,UnityEngine.RectTransform}

### _endEvent

```csharp
private Drag.OnDragEvent _endEvent
```

#### Field Value

**Type:** Global.Drag.OnDragEvent

### _image

```csharp
public Image _image
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### _isDragging

```csharp
private bool _isDragging
```
#INC


#### Field Value

**Type:** System.Boolean

### _pointerId

```csharp
private int _pointerId
```
#INC


#### Field Value

**Type:** System.Int32

### delta

```csharp
public float delta
```
#INC


#### Field Value

**Type:** System.Single

### DragPositionFix

```csharp
public Vector3 DragPositionFix
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### DragRotationFix

```csharp
public float DragRotationFix
```
#INC


#### Field Value

**Type:** System.Single

### dragStarted

```csharp
private bool dragStarted
```
#INC


#### Field Value

**Type:** System.Boolean

### eventTarget

```csharp
public GameObject eventTarget
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### generated

```csharp
private bool generated
```
#INC


#### Field Value

**Type:** System.Boolean

### startedPos

```csharp
private Vector2 startedPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

## Properties

### DraggableScript

```csharp
public IDraggableObject DraggableScript { get; }
```

#### Property Value

**Type:** Global.IDraggableObject

### Image

```csharp
public Image Image { get; }
```

#### Property Value

**Type:** UnityEngine.UI.Image

## Methods

### Awake()

```csharp
private void Awake()
```
#INC


### FindInParents<T>(GameObject)

```csharp
public static T FindInParents<T>(GameObject go) where T : Component
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `go` | `UnityEngine.GameObject` |  |

#### Returns

**Type:** {T}

### GetDraggableScript()

```csharp
public IDraggableObject GetDraggableScript()
```
#INC


#### Returns

**Type:** Global.IDraggableObject

### OnBeginDrag(PointerEventData)

```csharp
public void OnBeginDrag(PointerEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.PointerEventData` |  |

### OnDrag(PointerEventData)

```csharp
public void OnDrag(PointerEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.PointerEventData` |  |

### OnEndDrag(PointerEventData)

```csharp
public void OnEndDrag(PointerEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.PointerEventData` |  |

### OnManualEnd()

```csharp
public void OnManualEnd()
```
#INC


### SetBeginEvent(OnDragEvent)

```csharp
public void SetBeginEvent(Drag.OnDragEvent begin)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `begin` | `Global.Drag.OnDragEvent` |  |

### SetDraggedPosition(PointerEventData)

```csharp
private void SetDraggedPosition(PointerEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.PointerEventData` |  |

### SetEndEvent(OnDragEvent)

```csharp
public void SetEndEvent(Drag.OnDragEvent end)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `end` | `Global.Drag.OnDragEvent` |  |

### Start()

```csharp
private void Start()
```
#INC


### StartDrag(PointerEventData)

```csharp
private void StartDrag(PointerEventData eventData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventData` | `UnityEngine.EventSystems.PointerEventData` |  |

### Update()

```csharp
private void Update()
```
#INC

