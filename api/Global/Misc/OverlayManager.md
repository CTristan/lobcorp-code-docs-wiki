---
uid: Global.OverlayManager
canonical_path: /api/Global/Misc/OverlayManager
---

# Class OverlayManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OverlayManager : MonoBehaviour
```

Handles overlays, the places the mouse can hover over and click on.

#verify


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → OverlayManager

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OverlayManager()

```csharp
public OverlayManager()
```

## Fields

### _canvas

```csharp
[Header("UI")]
public Canvas _canvas
```

#### Field Value

**Type:** UnityEngine.Canvas

### _debugText

```csharp
public Text _debugText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### _enableInitial

```csharp
private Vector3 _enableInitial
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### _instance

```csharp
private static OverlayManager _instance
```
#INC


#### Field Value

**Type:** Global.OverlayManager

### _isEnabled

```csharp
private bool _isEnabled
```
#INC


#### Field Value

**Type:** System.Boolean

### _sizeUpdate

```csharp
private bool _sizeUpdate
```
#INC


#### Field Value

**Type:** System.Boolean

### _textRect

```csharp
private RectTransform _textRect
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### canvasScale

```csharp
public Vector2 canvasScale
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### EnableDelay

```csharp
public float EnableDelay
```
#INC


#### Field Value

**Type:** System.Single

### HorizontalSpace

```csharp
public float HorizontalSpace
```
#INC


#### Field Value

**Type:** System.Single

### MaxWidth

```csharp
[Header("Values")]
public float MaxWidth
```

#### Field Value

**Type:** System.Single

### MouseRelative

```csharp
public Vector2 MouseRelative
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### OverlayBox

```csharp
public RectTransform OverlayBox
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### OverlayText

```csharp
public Text OverlayText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### Pivot

```csharp
public RectTransform Pivot
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### prev

```csharp
public string prev
```
#INC


#### Field Value

**Type:** System.String

### scaleFactor

```csharp
private const float scaleFactor = 2
```
#INC


#### Field Value

**Type:** System.Single

### scaleFactorInv

```csharp
private const float scaleFactorInv = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### VerticalSpace

```csharp
public float VerticalSpace
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### Height

```csharp
private int Height { get; }
```

#### Property Value

**Type:** System.Int32

### Instance

```csharp
public static OverlayManager Instance { get; }
```

#### Property Value

**Type:** Global.OverlayManager

### IsActivated

```csharp
public bool IsActivated { get; }
```

#### Property Value

**Type:** System.Boolean

### IsEnabled

```csharp
public bool IsEnabled { get; set; }
```

#### Property Value

**Type:** System.Boolean

### Width

```csharp
private int Width { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### Awake()

```csharp
private void Awake()
```
#INC
#code-generated


### ClearOverlay()

```csharp
public void ClearOverlay()
```
#INC


### OnEnable()

```csharp
private void OnEnable()
```
#INC


### ReadState()

```csharp
public void ReadState()
```
#INC


### SaveState()

```csharp
public void SaveState()
```
#INC


### SetPosition(bool)

```csharp
public void SetPosition(bool initial = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `initial` | `System.Boolean` |  |

### SetPosition(Camera, bool)

```csharp
public void SetPosition(Camera camera, bool initial = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `camera` | `UnityEngine.Camera` |  |
| `initial` | `System.Boolean` |  |

### SetText(string)

```csharp
public void SetText(string text)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

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


### UpdateSize()

```csharp
public void UpdateSize()
```
#INC

