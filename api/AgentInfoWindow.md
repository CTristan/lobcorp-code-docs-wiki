# Class AgentInfoWindow

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentInfoWindow : MonoBehaviour, IObserver, IDeployResetCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → AgentInfoWindow

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AgentInfoWindow()

```csharp
public AgentInfoWindow()
```

## Fields

### Additional_Minus_ValueColor

```csharp
public string Additional_Minus_ValueColor
```

#### Field Value

**Type:** System.String

### Additional_Plus_ValueColor

```csharp
public string Additional_Plus_ValueColor
```

#### Field Value

**Type:** System.String

### AppearanceActiveControl

```csharp
public GameObject AppearanceActiveControl
```

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

#### Field Value

**Type:** UnityEngine.GameObject

### customizingWindow

```csharp
public CustomizingWindow customizingWindow
```

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

#### Field Value

**Type:** UnityEngine.UI.Button

### GiftAreaActiveButton

```csharp
public List<Button> GiftAreaActiveButton
```

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

#### Field Value

**Type:** UnityEngine.GameObject

### GiftSlot_EffectText

```csharp
public Text GiftSlot_EffectText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### GiftSlot_SymbolImage

```csharp
public Image GiftSlot_SymbolImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### GiftSlot_Title

```csharp
public Text GiftSlot_Title
```

#### Field Value

**Type:** UnityEngine.UI.Text

### GiftSlotParent

```csharp
public RectTransform GiftSlotParent
```

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

#### Field Value

**Type:** UnityEngine.Sprite[]

### MainPivotPos

```csharp
public static Vector3 MainPivotPos
```

#### Field Value

**Type:** UnityEngine.Vector3

### rootCanvas

```csharp
public Canvas rootCanvas
```

#### Field Value

**Type:** UnityEngine.Canvas

### SubPivotPos

```csharp
public static Vector3 SubPivotPos
```

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
public bool IsGiftAreaEnabled { get; }
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
public AgentInfoWindow.AgentInfoWindowType WindowType { get; }
```

#### Property Value

**Type:** Global.AgentInfoWindow.AgentInfoWindowType

## Methods

### CloseWindow()

```csharp
public void CloseWindow()
```

### CreateWindow(AgentModel, bool)

```csharp
public static AgentInfoWindow CreateWindow(AgentModel target, bool forcely = false)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### DeployResetCalled()

```csharp
public void DeployResetCalled()
```

### EnforcementWindow()

```csharp
public static AgentInfoWindow EnforcementWindow()
```

#### Returns

**Type:** Global.AgentInfoWindow

### EquipEvent()

```csharp
public void EquipEvent()
```

### GenerateWindow()

```csharp
public static AgentInfoWindow GenerateWindow()
```

#### Returns

**Type:** Global.AgentInfoWindow

### GetValueRate_FiveStep(float, float)

```csharp
public static int GetValueRate_FiveStep(float Max, float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `Max` | `System.Single` |  |
| `value` | `System.Single` |  |

#### Returns

**Type:** System.Int32

### OnClearOverlay()

```csharp
public void OnClearOverlay()
```

### OnClickEnforceButton()

```csharp
public void OnClickEnforceButton()
```

### OnClickGiftArea(float)

```csharp
public void OnClickGiftArea(float position)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `position` | `System.Single` |  |

### OnClickPortrait()

```csharp
public void OnClickPortrait()
```

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnUpdateAgent()

```csharp
public void OnUpdateAgent()
```

### PinCurrentAgent()

```csharp
public void PinCurrentAgent()
```

### Registration()

```csharp
public void Registration()
```

### SetGiftButtonInteractable(bool)

```csharp
public void SetGiftButtonInteractable(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### UnPinCurrentAgent()

```csharp
public void UnPinCurrentAgent()
```
