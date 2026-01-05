# Class AngelaConversationUI

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AngelaConversationUI : MonoBehaviour, ILanguageLinkedData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → AngelaConversationUI

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AngelaConversationUI()

```csharp
public AngelaConversationUI()
```

## Fields

### _Button

```csharp
public Button _Button
```

#### Field Value

**Type:** UnityEngine.UI.Button

### _Canvas

```csharp
public Canvas _Canvas
```

#### Field Value

**Type:** UnityEngine.Canvas

### _Panel

```csharp
public Image _Panel
```

#### Field Value

**Type:** UnityEngine.UI.Image

### audioSrc

```csharp
public AudioSource audioSrc
```

#### Field Value

**Type:** UnityEngine.AudioSource

### backGroundImage

```csharp
public Image backGroundImage
```

#### Field Value

**Type:** UnityEngine.UI.Image

### displayTime

```csharp
public float displayTime
```

#### Field Value

**Type:** System.Single

### FadeIn

```csharp
public bool FadeIn
```

#### Field Value

**Type:** System.Boolean

### fadeInTime

```csharp
public float fadeInTime
```

#### Field Value

**Type:** System.Single

### FadeOut

```csharp
public bool FadeOut
```

#### Field Value

**Type:** System.Boolean

### fadeOutTime

```csharp
public float fadeOutTime
```

#### Field Value

**Type:** System.Single

### isDisplayed

```csharp
[HideInInspector]
public bool isDisplayed
```

#### Field Value

**Type:** System.Boolean

### messageArrived

```csharp
public AudioClip messageArrived
```

#### Field Value

**Type:** UnityEngine.AudioClip

### messageText

```csharp
public Text messageText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### onClickButtonSound

```csharp
public AudioClip onClickButtonSound
```

#### Field Value

**Type:** UnityEngine.AudioClip

### rootGameObject

```csharp
public GameObject rootGameObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### totalTime

```csharp
public float totalTime
```

#### Field Value

**Type:** System.Single

### UpPos

```csharp
public Vector2 UpPos
```

#### Field Value

**Type:** UnityEngine.Vector2

## Properties

### instance

```csharp
public static AngelaConversationUI instance { get; }
```

#### Property Value

**Type:** Global.AngelaConversationUI

### isLock

```csharp
public bool isLock { get; }
```

#### Property Value

**Type:** System.Boolean

### PointerEntered

```csharp
public bool PointerEntered { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### AddAngelaMessage(string)

```csharp
public void AddAngelaMessage(string desc)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `desc` | `System.String` |  |

### ClearAngelaMessage()

```csharp
public void ClearAngelaMessage()
```

### Disable()

```csharp
public void Disable()
```

### EffectEnd()

```csharp
public void EffectEnd()
```

### Enable()

```csharp
public void Enable()
```

### FadeEffect(bool, float)

```csharp
public void FadeEffect(bool isFadeIn, float maxTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isFadeIn` | `System.Boolean` |  |
| `maxTime` | `System.Single` |  |

### ForceDisable()

```csharp
public void ForceDisable()
```

### Interrupt(string)

```csharp
public void Interrupt(string str)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |

### IsAgentDead()

```csharp
public bool IsAgentDead()
```

#### Returns

**Type:** System.Boolean

### LoadSprite()

```csharp
public void LoadSprite()
```

### Lock()

```csharp
public void Lock()
```

### OnClickButton()

```csharp
public void OnClickButton()
```

### OnLanguageChanged()

```csharp
public void OnLanguageChanged()
```

### OnPointerEnter()

```csharp
public void OnPointerEnter()
```

### OnPointerExit()

```csharp
public void OnPointerExit()
```

### ReEnable()

```csharp
public void ReEnable()
```

### SetCurrentMessage()

```csharp
public void SetCurrentMessage()
```

### SetOulineColor(Color)

```csharp
public void SetOulineColor(Color c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `c` | `UnityEngine.Color` |  |

### StartAgentDeadTimer()

```csharp
public void StartAgentDeadTimer()
```

### TutorialNarration(string, bool)

```csharp
public void TutorialNarration(string desc, bool isUp = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `desc` | `System.String` |  |
| `isUp` | `System.Boolean` |  |

### Unlock()

```csharp
public void Unlock()
```
