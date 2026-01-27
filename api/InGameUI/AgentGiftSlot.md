---
uid: InGameUI.AgentGiftSlot
canonical_path: /api/InGameUI/AgentGiftSlot
---

# Class AgentGiftSlot

**Namespace:** [InGameUI](/api/InGameUI)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentGiftSlot : MonoBehaviour
```

UI element representing [agents](/api/Global/Worker/AgentModel)' EGO gift slots; can have lock and display toggled, holds description, etc.

See [AgentGiftWindow](/api/InGameUI/AgentGiftWindow)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → AgentGiftSlot

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentGiftSlot()

```csharp
public AgentGiftSlot()
```

## Fields

### _additionalHeight

```csharp
private const float _additionalHeight = 90
```
#INC


#### Field Value

**Type:** System.Single

### _currentAgent

```csharp
private AgentModel _currentAgent
```
#INC


#### Field Value

**Type:** Global.AgentModel

### _dispState

```csharp
private bool _dispState
```
#INC


#### Field Value

**Type:** System.Boolean

### _lockState

```csharp
private bool _lockState
```
#INC


#### Field Value

**Type:** System.Boolean

### _setLayout

```csharp
private bool _setLayout
```
#INC


#### Field Value

**Type:** System.Boolean

### _spacing

```csharp
private const float _spacing = 5
```
#INC


#### Field Value

**Type:** System.Single

### DisplayActive

```csharp
public Image DisplayActive
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### DisplayButton

```csharp
public Button DisplayButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### dispTooltip

```csharp
public TooltipMouseOver dispTooltip
```
#INC


#### Field Value

**Type:** Global.TooltipMouseOver

### Frame

```csharp
public Image Frame
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### GiftDescription

```csharp
public Text GiftDescription
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### GiftName

```csharp
public Text GiftName
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### IsDisplayed

```csharp
public bool IsDisplayed
```
#INC


#### Field Value

**Type:** System.Boolean

### IsLocked

```csharp
public bool IsLocked
```
#INC


#### Field Value

**Type:** System.Boolean

### Lock_Close

```csharp
[Header("Param")]
public Sprite Lock_Close
```

#### Field Value

**Type:** UnityEngine.Sprite

### Lock_Open

```csharp
public Sprite Lock_Open
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### LockButton

```csharp
public Button LockButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### lockTooltip

```csharp
public TooltipMouseOver lockTooltip
```
#INC


#### Field Value

**Type:** Global.TooltipMouseOver

### rectTransform

```csharp
private RectTransform rectTransform
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### region

```csharp
public int region
```
#INC


#### Field Value

**Type:** System.Int32

### RegionName

```csharp
[Header("UI")]
public Text RegionName
```

#### Field Value

**Type:** UnityEngine.UI.Text

## Properties

### CurrentModel

```csharp
public EGOgiftModel CurrentModel { get; private set; }
```
#INC


#### Property Value

**Type:** Global.EGOgiftModel

## Methods

### Awake()

```csharp
private void Awake()
```

### LateUpdate()

```csharp
private void LateUpdate()
```
#INC


### SetButtonInteractable(bool, bool)

```csharp
public void SetButtonInteractable(bool disp, bool lockS)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `disp` | `System.Boolean` |  |
| `lockS` | `System.Boolean` |  |

### SetData()

```csharp
private void SetData()
```
#INC


### SetDisplay()

```csharp
public void SetDisplay()
```
#INC


### SetDisplayButton(bool)

```csharp
public void SetDisplayButton(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetGift(AgentModel, EGOgiftModel)

```csharp
public void SetGift(AgentModel agent, EGOgiftModel gift)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |
| `gift` | `Global.EGOgiftModel` |  |

### SetLayout()

```csharp
private void SetLayout()
```
#INC


### SetLock()

```csharp
public void SetLock()
```
#INC


### SetLockButton(bool)

```csharp
public void SetLockButton(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetRegionName()

```csharp
private void SetRegionName()
```
#INC


### Start()

```csharp
private void Start()
```
#INC
#code-generated

