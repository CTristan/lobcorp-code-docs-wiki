---
uid: InGameUI.AgentUI
canonical_path: /api/InGameUI/AgentUI
---

# Class AgentUI

**Namespace:** [InGameUI](/api/InGameUI)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentUI : MonoBehaviour
```

UI that appears above (or below) [agent units](/api/Global/Worker/AgentUnit) displaying [name](/api/Global/Misc/AgentName), [rank title](/api/Global/UI/AgentContinueUI), department, tool status, HP, and SP, once Yesod's research for it is obtained.

See [AgentUnitUI](/api/Global/UI/AgentUnitUI) for before Yesod's upgrade.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → AgentUI

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentUI()

```csharp
public AgentUI()
```

## Fields

### _continueUI

```csharp
private AgentContinueUI _continueUI
```
#INC


#### Field Value

**Type:** Global.AgentContinueUI

### _encounterTimer

```csharp
private Timer _encounterTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _model

```csharp
private UnitModel _model
```
#INC


#### Field Value

**Type:** Global.UnitModel

### _state

```csharp
private AgentUI.UIAgentState _state
```

#### Field Value

**Type:** InGameUI.AgentUI.UIAgentState

### ActiveControl

```csharp
public GameObject ActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### BlackHide

```csharp
public Image BlackHide
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### currentHorrorLevel

```csharp
private int currentHorrorLevel
```
#INC


#### Field Value

**Type:** System.Int32

### EncounterActiveControl

```csharp
[Header("Encounter")]
public GameObject EncounterActiveControl
```

#### Field Value

**Type:** UnityEngine.GameObject

### EncounterEffectTime

```csharp
public float EncounterEffectTime
```
#INC


#### Field Value

**Type:** System.Single

### EncounterIcon

```csharp
public Image EncounterIcon
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### EncounterText

```csharp
public Text EncounterText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### Grade

```csharp
public Image Grade
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### HpFill

```csharp
public Image HpFill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### level_Color

```csharp
public Color[] level_Color
```
#INC


#### Field Value

**Type:** UnityEngine.Color[]

### level_Exclams

```csharp
[Header("Encounter_common")]
public Sprite[] level_Exclams
```

#### Field Value

**Type:** UnityEngine.Sprite[]

### MentalFill

```csharp
public Image MentalFill
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### Name

```csharp
public Text Name
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### stateColor

```csharp
[Header("Color")]
public Color[] stateColor
```

#### Field Value

**Type:** UnityEngine.Color[]

### Texture

```csharp
public Image Texture
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### UIAnim

```csharp
public Animator UIAnim
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

## Properties

### _isActivated

```csharp
private bool _isActivated { get; }
```

#### Property Value

**Type:** System.Boolean

### Black

```csharp
private Color Black { get; }
```

#### Property Value

**Type:** UnityEngine.Color

### Model

```csharp
public UnitModel Model { get; }
```

#### Property Value

**Type:** Global.UnitModel

### State

```csharp
public AgentUI.UIAgentState State { get; set; }
```

#### Property Value

**Type:** InGameUI.AgentUI.UIAgentState

## Methods

### EncounterActivate(int)

```csharp
public void EncounterActivate(int level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### Init(UnitModel)

```csharp
public void Init(UnitModel model)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

### OnSetState(UIAgentState)

```csharp
private void OnSetState(AgentUI.UIAgentState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `InGameUI.AgentUI.UIAgentState` |  |

### SetActive(bool)

```csharp
public void SetActive(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetAgentState(UIAgentState)

```csharp
public void SetAgentState(AgentUI.UIAgentState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `InGameUI.AgentUI.UIAgentState` |  |

### SetOverlayState(bool)

```csharp
public void SetOverlayState(bool b)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `System.Boolean` |  |

### SetSelectState(bool)

```csharp
public void SetSelectState(bool b)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `System.Boolean` |  |

### Update()

```csharp
private void Update()
```
#INC


### UpdateHp()

```csharp
private void UpdateHp()
```
#INC


### UpdateMental()

```csharp
private void UpdateMental()
```
#INC


### UpdateState()

```csharp
private void UpdateState()
```
#INC


### ValidateUIActiate()

```csharp
private bool ValidateUIActiate()
```
#INC


#### Returns

**Type:** System.Boolean
