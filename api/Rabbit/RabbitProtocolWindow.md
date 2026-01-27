---
uid: Rabbit.RabbitProtocolWindow
canonical_path: /api/Rabbit/RabbitProtocolWindow
---

# Class RabbitProtocolWindow

**Namespace:** [Rabbit](/api/Rabbit)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitProtocolWindow : MonoBehaviour, IObserver
```

The Rabbit Protocol UI.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → RabbitProtocolWindow

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RabbitProtocolWindow()

```csharp
public RabbitProtocolWindow()
```

## Fields

### _activated

```csharp
private bool _activated
```
#INC


#### Field Value

**Type:** System.Boolean

### _filterAlphaTimer

```csharp
private UnscaledTimer _filterAlphaTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### _uiUpdateTimer

```csharp
private UnscaledTimer _uiUpdateTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### _window

```csharp
private static RabbitProtocolWindow _window
```
#INC


#### Field Value

**Type:** Rabbit.RabbitProtocolWindow

### activatedAnim

```csharp
public CheckPointUI activatedAnim
```
#INC


#### Field Value

**Type:** Global.CheckPointUI

### ConfirmButton

```csharp
public Button ConfirmButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### Cost

```csharp
[Header("UI")]
public Text Cost
```

#### Field Value

**Type:** UnityEngine.UI.Text

### CostText

```csharp
public Text CostText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### Count

```csharp
public Text Count
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### currentSelected

```csharp
private List<SefiraEnum> currentSelected
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{SefiraEnum}

### enabledSefiraList

```csharp
private List<RabbitProtocolSefiraSlot> enabledSefiraList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{Rabbit.RabbitProtocolSefiraSlot}

### filter

```csharp
private Dictionary<string, List<SefiraFilterMgr>> filter
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{SefiraFilterMgr}}

### filterAlphaCurve

```csharp
public AnimationCurve filterAlphaCurve
```
#INC


#### Field Value

**Type:** UnityEngine.AnimationCurve

### filterFreq

```csharp
public float filterFreq
```
#INC


#### Field Value

**Type:** System.Single

### freq

```csharp
[Header("UI Update")]
public float freq
```

#### Field Value

**Type:** System.Single

### NotAvailableColor

```csharp
public Color NotAvailableColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### openLevelStd

```csharp
private const int openLevelStd = 4
```
#INC


#### Field Value

**Type:** System.Int32

### protocolActivated

```csharp
private bool protocolActivated
```
#INC


#### Field Value

**Type:** System.Boolean

### ProtocolActivationButton

```csharp
[Header("ActvationButton")]
public Button ProtocolActivationButton
```

#### Field Value

**Type:** UnityEngine.UI.Button

### RabbitConnerSprite

```csharp
public Sprite RabbitConnerSprite
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### root

```csharp
public GameObject root
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### rootFilterUpdate

```csharp
public bool rootFilterUpdate
```
#INC


#### Field Value

**Type:** System.Boolean

### sefiraList

```csharp
[Header("Sefira Slots")]
public List<RabbitProtocolSefiraSlot> sefiraList
```

#### Field Value

**Type:** System.Collections.Generic.List{Rabbit.RabbitProtocolSefiraSlot}

### selectMax

```csharp
private const int selectMax = 4
```
#INC


#### Field Value

**Type:** System.Int32

### windowAnim

```csharp
public UIController windowAnim
```
#INC


#### Field Value

**Type:** Global.UIController

## Properties

### Activated

```csharp
public bool Activated { get; private set; }
```

#### Property Value

**Type:** System.Boolean

### Window

```csharp
public static RabbitProtocolWindow Window { get; }
```

#### Property Value

**Type:** Rabbit.RabbitProtocolWindow

## Methods

### ApplyFilter(string, List<SefiraFilterMgr>)

```csharp
public void ApplyFilter(string area, List<SefiraFilterMgr> filterMgr)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |
| `filterMgr` | `System.Collections.Generic.List{SefiraFilterMgr}` |  |

### Awake()

```csharp
private void Awake()
```
#INC
#code-generated


### Calculate()

```csharp
private void Calculate()
```
#INC


### CalculateUnits()

```csharp
private Dictionary<SefiraEnum, RabbitProtocolWindow.SefiraInfo> CalculateUnits()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{SefiraEnum,Rabbit.RabbitProtocolWindow.SefiraInfo}

### ClearFilter()

```csharp
public void ClearFilter()
```
#INC


### ClearFilter(string)

```csharp
public void ClearFilter(string area)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

### CloseProtocolActivatedWindow()

```csharp
public void CloseProtocolActivatedWindow()
```
#INC


### DestroyNotice()

```csharp
private void DestroyNotice()
```
#INC


### GetSlot(SefiraEnum)

```csharp
public RabbitProtocolSefiraSlot GetSlot(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** Rabbit.RabbitProtocolSefiraSlot

### OnClickCommand()

```csharp
public void OnClickCommand()
```
#INC


### OnClose()

```csharp
public void OnClose()
```
#INC


### OnDestroy()

```csharp
private void OnDestroy()
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

### OnOpen()

```csharp
public void OnOpen()
```
#INC


### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### OnTrySelectArea(SefiraEnum, bool)

```csharp
public bool OnTrySelectArea(SefiraEnum sefira, bool currentState)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `currentState` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean

### OnWindowClosed()

```csharp
public void OnWindowClosed()
```
#INC


### SetFilterAlpha(float)

```csharp
private void SetFilterAlpha(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

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


### UpdateText()

```csharp
private void UpdateText()
```
#INC

