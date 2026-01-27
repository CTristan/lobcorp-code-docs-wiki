---
uid: Global.AgentInfoWindow
canonical_path: /api/Global/Misc/AgentInfoWindow
---

# Class AgentInfoWindow

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentInfoWindow : MonoBehaviour, IObserver, IDeployResetCalled
```

Pop-up to display [agent](/api/Global/Worker/AgentUnit) information when selected. Presumably used when an [AgentUnit](/api/Global/Worker/AgentUnit) is clicked in-game, and on the [deployment screen](/api/Global/UI/DeployUI) when an agent is selected.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → AgentInfoWindow

## Implements
[IObserver](/api/Global/Misc/IObserver), [IDeployResetCalled](/api/Global/Misc/IDeployResetCalled)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentInfoWindow()

```csharp
public AgentInfoWindow()
```

## Fields

### _currentAgent

```csharp
private AgentModel _currentAgent
```
#INC


#### Field Value

**Type:** Global.AgentModel

### _fillLevel

```csharp
private static float[] _fillLevel
```
#INC


#### Field Value

**Type:** System.Single[]

### _fillMax

```csharp
private const float _fillMax = 0
```
#INC


#### Field Value

**Type:** System.Single

### _fillMin

```csharp
private const float _fillMin = 0
```
#INC


#### Field Value

**Type:** System.Single

### _isEanbled

```csharp
private bool _isEanbled
```
#INC


#### Field Value

**Type:** System.Boolean

### _isGiftAreaEnabled

```csharp
private bool _isGiftAreaEnabled
```
#INC


#### Field Value

**Type:** System.Boolean

### _pinnedAgent

```csharp
private AgentModel _pinnedAgent
```
#INC


#### Field Value

**Type:** Global.AgentModel

### Additional_Minus_ValueColor

```csharp
public string Additional_Minus_ValueColor
```
#INC


#### Field Value

**Type:** System.String

### Additional_Plus_ValueColor

```csharp
public string Additional_Plus_ValueColor
```
#INC


#### Field Value

**Type:** System.String

### AppearanceActiveControl

```csharp
public GameObject AppearanceActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### currentWindow

```csharp
[HideInInspector]
public static AgentInfoWindow currentWindow
```

#### Field Value

**Type:** Global.AgentInfoWindow

### customizingBlock

```csharp
public GameObject customizingBlock
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### customizingWindow

```csharp
public CustomizingWindow customizingWindow
```
#INC


#### Field Value

**Type:** Customizing.CustomizingWindow

### DeployActiveControl

```csharp
[Space(10)]
public GameObject DeployActiveControl
```

#### Field Value

**Type:** UnityEngine.GameObject

### EnforcenButton

```csharp
public Button EnforcenButton
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Button

### GiftAreaActiveButton

```csharp
public List<Button> GiftAreaActiveButton
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.UI.Button}

### GiftRoot

```csharp
[Header("Gift Area")]
public RectTransform GiftRoot
```

#### Field Value

**Type:** UnityEngine.RectTransform

### GiftSlot

```csharp
public GameObject GiftSlot
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### GiftSlot_EffectText

```csharp
public Text GiftSlot_EffectText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### GiftSlot_SymbolImage

```csharp
public Image GiftSlot_SymbolImage
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### GiftSlot_Title

```csharp
public Text GiftSlot_Title
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### GiftSlotParent

```csharp
public RectTransform GiftSlotParent
```
#INC


#### Field Value

**Type:** UnityEngine.RectTransform

### giftWindow

```csharp
[Header("Gift Window")]
public AgentGiftWindow giftWindow
```

#### Field Value

**Type:** InGameUI.AgentGiftWindow

### IngameActiveControl

```csharp
public GameObject IngameActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### inGameModeComponent

```csharp
[Space(10)]
public AgentInfoWindow.InGameModeComponent inGameModeComponent
```

#### Field Value

**Type:** Global.AgentInfoWindow.InGameModeComponent

### LevelImage

```csharp
public Sprite[] LevelImage
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite[]

### MainPivotPos

```csharp
public static Vector3 MainPivotPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### rootCanvas

```csharp
public Canvas rootCanvas
```
#INC


#### Field Value

**Type:** UnityEngine.Canvas

### SubPivotPos

```csharp
public static Vector3 SubPivotPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### UIComponents

```csharp
[Space(10)]
public AgentInfoWindow.UIComponent UIComponents
```

#### Field Value

**Type:** Global.AgentInfoWindow.UIComponent

## Properties

### CurrentAgent

```csharp
public AgentModel CurrentAgent { get; set; }
```

#### Property Value

**Type:** Global.AgentModel

### IsEnabled

```csharp
public bool IsEnabled { get; set; }
```

#### Property Value

**Type:** System.Boolean

### IsGiftAreaEnabled

```csharp
public bool IsGiftAreaEnabled { get; private set; }
```

#### Property Value

**Type:** System.Boolean

### PinnedAgent

```csharp
public AgentModel PinnedAgent { get; }
```

#### Property Value

**Type:** Global.AgentModel

### WindowType

```csharp
public AgentInfoWindow.AgentInfoWindowType WindowType { get; private set; }
```

#### Property Value

**Type:** Global.AgentInfoWindow.AgentInfoWindowType

## Methods

### Awake()

```csharp
private void Awake()
```
#INC


### CloseWindow()

```csharp
public void CloseWindow()
```
#INC


### CreateWindow(AgentModel, bool)

```csharp
public static AgentInfoWindow CreateWindow(AgentModel target, bool forcely = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |
| `forcely` | `System.Boolean` |  |

#### Returns

**Type:** Global.AgentInfoWindow

### DeployColorSetted(Color)

```csharp
public void DeployColorSetted(Color c)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### DeployResetCalled()

```csharp
public void DeployResetCalled()
```
#INC


### EnforcementWindow()

```csharp
public static AgentInfoWindow EnforcementWindow()
```
#INC


#### Returns

**Type:** Global.AgentInfoWindow

### EquipEvent()

```csharp
public void EquipEvent()
```
#INC


### GenerateWindow()

```csharp
public static AgentInfoWindow GenerateWindow()
```
#INC
#code-generated


#### Returns

**Type:** Global.AgentInfoWindow

### GetCurrentColor()

```csharp
private Color GetCurrentColor()
```
#INC


#### Returns

**Type:** UnityEngine.Color

### GetValueRate_FiveStep(float, float)

```csharp
public static int GetValueRate_FiveStep(float Max, float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `Max` | `System.Single` |  |
| `value` | `System.Single` |  |

#### Returns

**Type:** System.Int32

### Init()

```csharp
private void Init()
```
#INC


### InitGiftArea()

```csharp
private void InitGiftArea()
```
#INC


### OnChangeAgent(AgentModel)

```csharp
private void OnChangeAgent(AgentModel newAgent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `newAgent` | `Global.AgentModel` |  |

### OnClearOverlay()

```csharp
public void OnClearOverlay()
```
#INC


### OnClickEnforceButton()

```csharp
public void OnClickEnforceButton()
```
#INC


### OnClickGiftArea(float)

```csharp
public void OnClickGiftArea(float position)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `position` | `System.Single` |  |

### OnClickPortrait()

```csharp
public void OnClickPortrait()
```
#INC


### OnDisable()

```csharp
private void OnDisable()
```
#INC


### OnEnable()

```csharp
private void OnEnable()
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

### OnUpdateAgent()

```csharp
public void OnUpdateAgent()
```
#INC


### PinCurrentAgent()

```csharp
public void PinCurrentAgent()
```
#INC


### Registration()

```csharp
public void Registration()
```
#INC


### SetGiftAreaAgent(AgentModel)

```csharp
private void SetGiftAreaAgent(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### SetGiftButtonInteractable(bool)

```csharp
public void SetGiftButtonInteractable(bool state)
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


### UnPinCurrentAgent()

```csharp
public void UnPinCurrentAgent()
```
#INC


### Update()

```csharp
private void Update()
```
#INC

