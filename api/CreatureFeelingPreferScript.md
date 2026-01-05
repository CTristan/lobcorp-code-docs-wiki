# Class CreatureFeelingPreferScript

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureFeelingPreferScript : MenuScript
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [MenuScript](/api/MenuScript) → CreatureFeelingPreferScript

## Inherited Members
[menus](/api/MenuScript#menus), [EnableOverlayPrevView](/api/MenuScript#enableoverlayprevview), [selected](/api/MenuScript#selected), [currentIndex](/api/MenuScript#currentindex), [Start()](/api/MenuScript#start), [SelectMenu()](/api/MenuScript#selectmenu), [SelectMenu(int)](/api/MenuScript#selectmenu-int), [GetSelectedRect()](/api/MenuScript#getselectedrect), [GetCurrentSelectedIndex()](/api/MenuScript#getcurrentselectedindex), [OnOverlayEnter(Button)](/api/MenuScript#onoverlayenter-button), [OnOverlayExit(Button)](/api/MenuScript#onoverlayexit-button), [GetMenu(Button)](/api/MenuScript#getmenu-button), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreatureFeelingPreferScript()

```csharp
public CreatureFeelingPreferScript()
```

## Fields

### ClickedColor

```csharp
public Color ClickedColor
```

#### Field Value

**Type:** UnityEngine.Color

### disabledColor

```csharp
public Color disabledColor
```

#### Field Value

**Type:** UnityEngine.Color

### EnergyGenIcon

```csharp
public Image[] EnergyGenIcon
```

#### Field Value

**Type:** UnityEngine.UI.Image[]

### NormalColor

```csharp
public Color NormalColor
```

#### Field Value

**Type:** UnityEngine.Color

### PreferParent

```csharp
public RectTransform[] PreferParent
```

#### Field Value

**Type:** UnityEngine.RectTransform[]

### WorkIcon

```csharp
public RectTransform[] WorkIcon
```

#### Field Value

**Type:** UnityEngine.RectTransform[]

## Properties

### currentCreatureTarget

```csharp
public CreatureModel currentCreatureTarget { get; set; }
```

#### Property Value

**Type:** Global.CreatureModel

## Methods

### GetFeelingIndex(CreatureFeelingState)

```csharp
public static int GetFeelingIndex(CreatureFeelingState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.CreatureFeelingState` |  |

#### Returns

**Type:** System.Int32

### GetIndexOfFeeling(int)

```csharp
public static CreatureFeelingState GetIndexOfFeeling(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.CreatureFeelingState

### GetWorkEfficientSection(float)

```csharp
public static CreatureFeelingPreferScript.FeelingPrefer GetWorkEfficientSection(float val)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |

#### Returns

**Type:** Global.CreatureFeelingPreferScript.FeelingPrefer

### Init()

```csharp
public void Init()
```

### OnClick(Button)

```csharp
public override void OnClick(Button target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `UnityEngine.UI.Button` |  |

### SetButtonColor(int, bool)

```csharp
public void SetButtonColor(int index, bool isDisabled)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `isDisabled` | `System.Boolean` |  |

### SetChart(CreatureFeelingState)

```csharp
public void SetChart(CreatureFeelingState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.CreatureFeelingState` |  |

### SetCreature(CreatureModel)

```csharp
public void SetCreature(CreatureModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |

### SetEnergyGenSprite(Image, float, CreatureFeelingState)

```csharp
public void SetEnergyGenSprite(Image targetRenderer, float val, CreatureFeelingState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetRenderer` | `UnityEngine.UI.Image` |  |
| `val` | `System.Single` |  |
| `state` | `Global.CreatureFeelingState` |  |

### StartInit()

```csharp
public void StartInit()
```
