# Class RabbitProtocolWindow

**Namespace:** [Rabbit](/api/Rabbit)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitProtocolWindow : MonoBehaviour, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → RabbitProtocolWindow

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### RabbitProtocolWindow()

```csharp
public RabbitProtocolWindow()
```

## Fields

### activatedAnim

```csharp
public CheckPointUI activatedAnim
```

#### Field Value

**Type:** Global.CheckPointUI

### ConfirmButton

```csharp
public Button ConfirmButton
```

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

#### Field Value

**Type:** UnityEngine.UI.Text

### Count

```csharp
public Text Count
```

#### Field Value

**Type:** UnityEngine.UI.Text

### filterAlphaCurve

```csharp
public AnimationCurve filterAlphaCurve
```

#### Field Value

**Type:** UnityEngine.AnimationCurve

### filterFreq

```csharp
public float filterFreq
```

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

#### Field Value

**Type:** UnityEngine.Color

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

#### Field Value

**Type:** UnityEngine.Sprite

### root

```csharp
public GameObject root
```

#### Field Value

**Type:** UnityEngine.GameObject

### rootFilterUpdate

```csharp
public bool rootFilterUpdate
```

#### Field Value

**Type:** System.Boolean

### sefiraList

```csharp
[Header("Sefira Slots")]
public List<RabbitProtocolSefiraSlot> sefiraList
```

#### Field Value

**Type:** System.Collections.Generic.List{Rabbit.RabbitProtocolSefiraSlot}

### windowAnim

```csharp
public UIController windowAnim
```

#### Field Value

**Type:** Global.UIController

## Properties

### Activated

```csharp
public bool Activated { get; }
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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |
| `filterMgr` | `System.Collections.Generic.List{SefiraFilterMgr}` |  |

### ClearFilter()

```csharp
public void ClearFilter()
```

### ClearFilter(string)

```csharp
public void ClearFilter(string area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

### CloseProtocolActivatedWindow()

```csharp
public void CloseProtocolActivatedWindow()
```

### GetSlot(SefiraEnum)

```csharp
public RabbitProtocolSefiraSlot GetSlot(SefiraEnum sefira)
```

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

### OnClose()

```csharp
public void OnClose()
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

### OnOpen()

```csharp
public void OnOpen()
```

### OnStageStart()

```csharp
public void OnStageStart()
```

### OnTrySelectArea(SefiraEnum, bool)

```csharp
public bool OnTrySelectArea(SefiraEnum sefira, bool currentState)
```

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
