---
uid: Global.ResearchPanel
canonical_path: /api/Global/Misc/ResearchPanel
---

# Class ResearchPanel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResearchPanel : MonoBehaviour, IDraggableObject
```

Draggable research panel in the [ResearchWindow](/api/Global/IANimatorEventCalled/ResearchWindow).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → ResearchPanel

## Implements
[IDraggableObject](/api/Global/Object/IDraggableObject)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ResearchPanel()

```csharp
public ResearchPanel()
```

## Fields

### _currentColor

```csharp
private Color _currentColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### _currentModel

```csharp
private ResearchItemModel _currentModel
```
#INC


#### Field Value

**Type:** Global.ResearchItemModel

### _dragged

```csharp
private DraggedObject _dragged
```
#INC


#### Field Value

**Type:** Global.DraggedObject

### _dropped

```csharp
private bool _dropped
```
#INC


#### Field Value

**Type:** System.Boolean

### _isDragging

```csharp
private bool _isDragging
```
#INC


#### Field Value

**Type:** System.Boolean

### _isSelectedPanel

```csharp
private bool _isSelectedPanel
```
#INC


#### Field Value

**Type:** System.Boolean

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

### _window

```csharp
private ResearchWindow _window
```
#INC


#### Field Value

**Type:** Global.ResearchWindow

### ActiveControl

```csharp
public GameObject ActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### Anim

```csharp
public Animator Anim
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### coloredTarget

```csharp
public List<MaskableGraphic> coloredTarget
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.MaskableGraphic}

### draggedPanelSrc

```csharp
private const string draggedPanelSrc = "UIComponent/FloatingResearch"
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

### heightMove

```csharp
private const float heightMove = 65
```
#INC


#### Field Value

**Type:** System.Single

### iconDefSrc

```csharp
private const string iconDefSrc = "Sprites/UI/Icons/Research/"
```
#INC


#### Field Value

**Type:** System.String

### index

```csharp
public int index
```
#INC


#### Field Value

**Type:** System.Int32

### PanelName

```csharp
public Text PanelName
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### PanelRectTr

```csharp
public RectTransform PanelRectTr
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### ResearchIcon

```csharp
public Image ResearchIcon
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### ResearchLongDesc

```csharp
public Text ResearchLongDesc
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### ResearchName

```csharp
public Text ResearchName
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### ResearchShortDesc

```csharp
public Text ResearchShortDesc
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### ResearchSound

```csharp
public AudioClipPlayer ResearchSound
```
#INC


#### Field Value

**Type:** Global.AudioClipPlayer

## Properties

### _texture

```csharp
private Image _texture { get; }
```

#### Property Value

**Type:** UnityEngine.UI.Image

### CurrentModel

```csharp
public ResearchItemModel CurrentModel { get; }
```

#### Property Value

**Type:** Global.ResearchItemModel

### RectTransform

```csharp
public RectTransform RectTransform { get; }
```

#### Property Value

**Type:** UnityEngine.RectTransform

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

### OnCanceled()

```csharp
public void OnCanceled()
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


### OnPointerClick()

```csharp
public void OnPointerClick()
```
#INC


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


### PanelReset()

```csharp
public void PanelReset()
```
#INC


### SetColor(Color)

```csharp
public void SetColor(Color c)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### SetData(ResearchItemModel)

```csharp
public void SetData(ResearchItemModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.ResearchItemModel` |  |

### SetIndex(int, int)

```csharp
public void SetIndex(int index, int maxIndex)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `maxIndex` | `System.Int32` |  |

### SetSelectedPanel()

```csharp
public void SetSelectedPanel()
```
#INC
#code-generated


### SetTextureAlpha(float)

```csharp
public void SetTextureAlpha(float alpha)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `alpha` | `System.Single` |  |

### SetUI()

```csharp
private void SetUI()
```
#INC


### SetWindow(ResearchWindow)

```csharp
public void SetWindow(ResearchWindow window)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `window` | `Global.ResearchWindow` |  |

### Start()

```csharp
private void Start()
```
#INC

