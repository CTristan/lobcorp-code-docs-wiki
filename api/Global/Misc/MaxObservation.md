---
uid: Global.MaxObservation
canonical_path: /api/Global/Misc/MaxObservation
---

# Class MaxObservation

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MaxObservation : MonoBehaviour
```

UI for a legacy 'Final Observation' mechanic that never reached the main game.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → MaxObservation

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MaxObservation()

```csharp
public MaxObservation()
```

## Fields

### _instance

```csharp
private static MaxObservation _instance
```
#INC


#### Field Value

**Type:** Global.MaxObservation

### _module

```csharp
private CreatureMaxObserve _module
```
#INC


#### Field Value

**Type:** Global.CreatureMaxObserve

### _select

```csharp
private CreatureMaxObserve.Select _select
```
#INC


#### Field Value

**Type:** Global.CreatureMaxObserve.Select

### arrow

```csharp
public GameObject arrow
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### CheckSection

```csharp
public GameObject CheckSection
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### clickDelay

```csharp
public float clickDelay
```
#INC


#### Field Value

**Type:** System.Single

### clickDelayTimer

```csharp
private UnscaledTimer clickDelayTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### CreatureIndex

```csharp
public Text CreatureIndex
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### CreatureSerialNumber

```csharp
public Text CreatureSerialNumber
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### currentDesc

```csharp
private int currentDesc
```
#INC


#### Field Value

**Type:** System.Int32

### currentTarget

```csharp
public CreatureModel currentTarget
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### CurrentTime

```csharp
public Text CurrentTime
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### descList

```csharp
private List<string> descList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### descMax

```csharp
private int descMax
```
#INC


#### Field Value

**Type:** System.Int32

### descTextBox

```csharp
public Text descTextBox
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### endAsFail

```csharp
private bool endAsFail
```
#INC


#### Field Value

**Type:** System.Boolean

### endConversation

```csharp
private bool endConversation
```
#INC


#### Field Value

**Type:** System.Boolean

### isEnabled

```csharp
public bool isEnabled
```
#INC


#### Field Value

**Type:** System.Boolean

### lastSelected

```csharp
private CreatureMaxObserve.Desc lastSelected
```
#INC


#### Field Value

**Type:** Global.CreatureMaxObserve.Desc

### NoiseArea

```csharp
public GameObject NoiseArea
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### nonOverlayedColor

```csharp
public Color nonOverlayedColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### normalColor

```csharp
public Color normalColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### overlayColor

```csharp
public Color overlayColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### overlayedHideColor

```csharp
public Color overlayedHideColor
```
#INC


#### Field Value

**Type:** UnityEngine.Color

### OverlayText

```csharp
public Text[] OverlayText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text[]

### pauseUI

```csharp
public GameObject pauseUI
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### ProcessSetion

```csharp
public GameObject ProcessSetion
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### Root

```csharp
public GameObject Root
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### saveOrtho

```csharp
private float saveOrtho
```
#INC


#### Field Value

**Type:** System.Single

### selectBox

```csharp
public List<Text> selectBox
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.Text}

### selectEnable

```csharp
private bool selectEnable
```
#INC


#### Field Value

**Type:** System.Boolean

### selectIndex

```csharp
private int selectIndex
```
#INC


#### Field Value

**Type:** System.Int32

### SelectOverlay

```csharp
public Image[] SelectOverlay
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image[]

### shortConversation

```csharp
private bool shortConversation
```
#INC


#### Field Value

**Type:** System.Boolean

### timeDisplay

```csharp
private bool timeDisplay
```
#INC


#### Field Value

**Type:** System.Boolean

## Properties

### currentSelectCount

```csharp
private int currentSelectCount { get; }
```

#### Property Value

**Type:** System.Int32

### gameTime

```csharp
private float gameTime { get; }
```

#### Property Value

**Type:** System.Single

### instance

```csharp
public static MaxObservation instance { get; }
```

#### Property Value

**Type:** Global.MaxObservation

### module

```csharp
private CreatureMaxObserve module { get; }
```

#### Property Value

**Type:** Global.CreatureMaxObserve

### select

```csharp
private CreatureMaxObserve.Select select { get; }
```

#### Property Value

**Type:** Global.CreatureMaxObserve.Select

## Methods

### Awake()

```csharp
private void Awake()
```
#INC
#code-generated


### ChangeDesc(int)

```csharp
public void ChangeDesc(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

### CloseCheckOverlay()

```csharp
private void CloseCheckOverlay()
```
#INC


### CloseSelectOverlay()

```csharp
private void CloseSelectOverlay()
```
#INC


### ObserveFail()

```csharp
private void ObserveFail()
```
#INC


### ObserveSuccess()

```csharp
private void ObserveSuccess()
```
#INC


### OnCameraMoveEnd()

```csharp
public void OnCameraMoveEnd()
```
#INC


### OnCheck()

```csharp
public void OnCheck()
```
#INC


### OnCheckClose()

```csharp
public void OnCheckClose()
```
#INC


### OnCheckNo()

```csharp
public void OnCheckNo()
```
#INC


### OnCheckOverlayEnter(int)

```csharp
public void OnCheckOverlayEnter(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnCheckOverlayExit(int)

```csharp
public void OnCheckOverlayExit(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnCheckYes()

```csharp
public void OnCheckYes()
```
#INC


### OnClose()

```csharp
public void OnClose()
```
#INC


### OnObserveEnd()

```csharp
private void OnObserveEnd()
```
#INC


### OnProcessStart()

```csharp
public void OnProcessStart()
```
#INC


### OnSelectOverlayEnter(int)

```csharp
public void OnSelectOverlayEnter(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnSelectOverlayExit(int)

```csharp
public void OnSelectOverlayExit(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### ProcessDesc()

```csharp
public void ProcessDesc()
```
#INC


### ProcessSelect()

```csharp
private void ProcessSelect()
```
#INC


### Select(int)

```csharp
public void Select(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### SelectSetActive(bool)

```csharp
private void SelectSetActive(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetColorAsDef()

```csharp
public void SetColorAsDef()
```
#INC


### StartObservation(CreatureModel)

```csharp
public void StartObservation(CreatureModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### Update()

```csharp
public void Update()
```
#INC

