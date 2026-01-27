---
uid: Global.StoryOptionUI
canonical_path: /api/Global/UI/StoryOptionUI
---

# Class StoryOptionUI

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StoryOptionUI : MonoBehaviour
```

UI element which provides access to the sephirah list and story log.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → StoryOptionUI

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StoryOptionUI()

```csharp
public StoryOptionUI()
```

## Fields

### _logWindowClose

```csharp
private StoryOptionUI.DelegateEvent _logWindowClose
```

#### Field Value

**Type:** Global.StoryOptionUI.DelegateEvent

### _logWindowOpen

```csharp
private StoryOptionUI.DelegateEvent _logWindowOpen
```

#### Field Value

**Type:** Global.StoryOptionUI.DelegateEvent

### _panelOpened

```csharp
private bool _panelOpened
```
#INC


#### Field Value

**Type:** System.Boolean

### _sefiraWindowClose

```csharp
private StoryOptionUI.DelegateEvent _sefiraWindowClose
```

#### Field Value

**Type:** Global.StoryOptionUI.DelegateEvent

### _sefiraWindowOpen

```csharp
private StoryOptionUI.DelegateEvent _sefiraWindowOpen
```

#### Field Value

**Type:** Global.StoryOptionUI.DelegateEvent

### _settingWindowClose

```csharp
private StoryOptionUI.DelegateEvent _settingWindowClose
```

#### Field Value

**Type:** Global.StoryOptionUI.DelegateEvent

### _settingWindowOpen

```csharp
private StoryOptionUI.DelegateEvent _settingWindowOpen
```

#### Field Value

**Type:** Global.StoryOptionUI.DelegateEvent

### ActiveControl

```csharp
public GameObject ActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### isEntered

```csharp
private bool isEntered
```
#INC


#### Field Value

**Type:** System.Boolean

### isOpenedPanel

```csharp
private bool[] isOpenedPanel
```
#INC


#### Field Value

**Type:** System.Boolean[]

### LogButton

```csharp
public Button LogButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### LogIcon

```csharp
public GameObject LogIcon
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### LogoButton

```csharp
public Button LogoButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### LogoIcon

```csharp
public Image LogoIcon
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### OptionButton

```csharp
public Button OptionButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### OptionIcon

```csharp
public GameObject OptionIcon
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### RootButtonAnim

```csharp
public Animator RootButtonAnim
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### RootIcon

```csharp
public GameObject RootIcon
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### SefiraButton

```csharp
public Button SefiraButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### SefiraIcon

```csharp
public GameObject SefiraIcon
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### SefiraPanel

```csharp
public RectTransform SefiraPanel
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

## Properties

### PanelOpened

```csharp
public bool PanelOpened { get; private set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### ButtonInit()

```csharp
private void ButtonInit()
```
#INC


### Init()

```csharp
public void Init()
```
#INC


### OnButtonReset()

```csharp
public void OnButtonReset()
```
#INC


### OnClick()

```csharp
public void OnClick()
```
#INC


### OnClickLog()

```csharp
public void OnClickLog()
```
#INC


### OnClickLogReset()

```csharp
public void OnClickLogReset()
```
#INC


### OnClickOption()

```csharp
public void OnClickOption()
```
#INC


### OnClickOptionReset()

```csharp
public void OnClickOptionReset()
```
#INC


### OnClickSefira()

```csharp
public void OnClickSefira()
```
#INC


### OnClickSefiraReset()

```csharp
public void OnClickSefiraReset()
```
#INC


### OnExit()

```csharp
public void OnExit()
```
#INC


### OnOpen()

```csharp
public void OnOpen()
```
#INC


### OnRootButtonEnter()

```csharp
public void OnRootButtonEnter()
```
#INC


### OnRootButtonExit()

```csharp
public void OnRootButtonExit()
```
#INC


### OpenWindow()

```csharp
public void OpenWindow()
```
#INC


### SetCloseDelegate(EventType, DelegateEvent)

```csharp
public void SetCloseDelegate(StoryOptionUI.EventType type, StoryOptionUI.DelegateEvent d)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.StoryOptionUI.EventType` |  |
| `d` | `Global.StoryOptionUI.DelegateEvent` |  |

### SetOpenDelegate(DelegateEvent, EventType)

```csharp
public void SetOpenDelegate(StoryOptionUI.DelegateEvent d, StoryOptionUI.EventType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `d` | `Global.StoryOptionUI.DelegateEvent` |  |
| `type` | `Global.StoryOptionUI.EventType` |  |

### SetPanelState(bool)

```csharp
public void SetPanelState(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

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
#code-generated

