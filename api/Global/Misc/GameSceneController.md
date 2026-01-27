---
uid: Global.GameSceneController
canonical_path: /api/Global/Misc/GameSceneController
---

# Class GameSceneController

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GameSceneController : MonoBehaviour
```

Controls scene flow.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → GameSceneController

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GameSceneController()

```csharp
public GameSceneController()
```

## Fields

### _agentAlldeadText

```csharp
private string _agentAlldeadText
```
#INC


#### Field Value

**Type:** System.String

### _creatureEscapedText

```csharp
private string _creatureEscapedText
```
#INC


#### Field Value

**Type:** System.String

### _isAgentAlldead

```csharp
private bool _isAgentAlldead
```
#INC


#### Field Value

**Type:** System.Boolean

### _isCreatureEscaped

```csharp
private bool _isCreatureEscaped
```
#INC


#### Field Value

**Type:** System.Boolean

### _isGameCleared

```csharp
private bool _isGameCleared
```
#INC


#### Field Value

**Type:** System.Boolean

### ActiveControl

```csharp
public GameObject ActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### Addional

```csharp
[Header("Addition")]
public RectTransform Addional
```

#### Field Value

**Type:** UnityEngine.RectTransform

### AddionalAnim

```csharp
public Animator AddionalAnim
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### AdditionalText

```csharp
public Text AdditionalText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### animator

```csharp
public Animator animator
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### EmergecnyController

```csharp
[Header("Emergency")]
public RectTransform EmergecnyController
```

#### Field Value

**Type:** UnityEngine.RectTransform

### EmergenyText

```csharp
public Text EmergenyText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### NextDayButton

```csharp
public Button NextDayButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### NextDayText

```csharp
public Text NextDayText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### RestartButton

```csharp
public Button RestartButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### RestartText

```csharp
public Text RestartText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

## Properties

### IsAdditionalAppeared

```csharp
private bool IsAdditionalAppeared { get; }
```

#### Property Value

**Type:** System.Boolean

### IsAgentAlldead

```csharp
public bool IsAgentAlldead { get; set; }
```

#### Property Value

**Type:** System.Boolean

### IsCreatureEscaped

```csharp
public bool IsCreatureEscaped { get; set; }
```

#### Property Value

**Type:** System.Boolean

### IsEmergency

```csharp
private bool IsEmergency { get; }
```

#### Property Value

**Type:** System.Boolean

### IsEnabled

```csharp
private bool IsEnabled { get; }
```

#### Property Value

**Type:** System.Boolean

### IsGameCleared

```csharp
public bool IsGameCleared { get; set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### AdditionalAppear()

```csharp
public void AdditionalAppear()
```
#INC


### AdditionalDisappear()

```csharp
public void AdditionalDisappear()
```
#INC


### Appear()

```csharp
public void Appear()
```
#INC


### ButtonSelect(bool)

```csharp
public void ButtonSelect(bool isNext)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isNext` | `System.Boolean` |  |

### CheckState()

```csharp
private void CheckState()
```
#INC


### Disappear()

```csharp
public void Disappear()
```
#INC


### OnClickNextDay()

```csharp
public void OnClickNextDay()
```
#INC


### OnClickRestart()

```csharp
public void OnClickRestart()
```
#INC


### OnEmergencyEnter()

```csharp
public void OnEmergencyEnter()
```
#INC


### OnEmergencyRelease()

```csharp
public void OnEmergencyRelease()
```
#INC


### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### Start()

```csharp
private void Start()
```
#INC
#code-generated


### Update()

```csharp
private void Update()
```
#INC


### UpdateAdditionalText()

```csharp
public void UpdateAdditionalText()
```
#INC

