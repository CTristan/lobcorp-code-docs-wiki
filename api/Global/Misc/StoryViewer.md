---
uid: Global.StoryViewer
canonical_path: /api/Global/Misc/StoryViewer
---

# Class StoryViewer

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StoryViewer : MonoBehaviour
```

UI allowing playback of old stories.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → StoryViewer

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StoryViewer()

```csharp
public StoryViewer()
```

## Fields

### _dayArea

```csharp
public RectTransform _dayArea
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### _dayButton

```csharp
public Button _dayButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### _sefiraArea

```csharp
[Header("Window")]
public RectTransform _sefiraArea
```

#### Field Value

**Type:** UnityEngine.RectTransform

### _sefiraButton

```csharp
public Button _sefiraButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### ActiveControl

```csharp
public GameObject ActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### AudioCilp

```csharp
public AudioClipPlayer AudioCilp
```
#INC


#### Field Value

**Type:** Global.AudioClipPlayer

### bgm

```csharp
public GameObject bgm
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### dayCount

```csharp
private Dictionary<string, int> dayCount
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Int32}

### DayCountText

```csharp
public Text DayCountText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### DayLayout

```csharp
public RectTransform DayLayout
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### dayStories

```csharp
public List<string> dayStories
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### DayTextUnit_Day

```csharp
public GameObject DayTextUnit_Day
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### DayTextUnit_Sefira

```csharp
public GameObject DayTextUnit_Sefira
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### dayUnits

```csharp
[Header("Day")]
private List<DayUnitButton> dayUnits
```

#### Field Value

**Type:** System.Collections.Generic.List{DayUnitButton}

### EndingButton

```csharp
public Button[] EndingButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button[]

### EndingPanel

```csharp
public RectTransform EndingPanel
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### endingStories

```csharp
public List<string> endingStories
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### endingText

```csharp
private static string[] endingText
```
#INC


#### Field Value

**Type:** System.String[]

### SeedButton

```csharp
public Button[] SeedButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button[]

### SeedPanel

```csharp
public RectTransform SeedPanel
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### seedStories

```csharp
public List<string> seedStories
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### sefiraPanels

```csharp
[Header("Sefira")]
public List<StoryViewerSefiraPanel> sefiraPanels
```

#### Field Value

**Type:** System.Collections.Generic.List{StoryViewerSefiraPanel}

### storyUI

```csharp
public StoryUI storyUI
```
#INC


#### Field Value

**Type:** Global.StoryUI

## Properties

### Controller

```csharp
public static StoryViewer Controller { get; private set; }
```
#INC


#### Property Value

**Type:** Global.StoryViewer

## Methods

### Awake()

```csharp
private void Awake()
```

### ClearDayUnits()

```csharp
private void ClearDayUnits()
```
#INC


### Init()

```csharp
private void Init()
```
#INC


### OnClickStory(string)

```csharp
public void OnClickStory(string storyId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `storyId` | `System.String` |  |

### OnEndStory()

```csharp
public void OnEndStory()
```
#INC


### ReturnToTitle()

```csharp
public void ReturnToTitle()
```
#INC


### SetDay()

```csharp
public void SetDay()
```
#INC


### SetDay(string)

```csharp
private void SetDay(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

### SetSefira()

```csharp
public void SetSefira()
```
#INC


### Start()

```csharp
private void Start()
```
#INC
#code-generated


### StoryInit()

```csharp
private void StoryInit()
```
#INC


### Update()

```csharp
private void Update()
```
#INC

