# Class RouletteWindow

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RouletteWindow : MonoBehaviour, IAnimatorEventCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → RouletteWindow

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### RouletteWindow()

```csharp
public RouletteWindow()
```

## Fields

### anchorMax

```csharp
public float anchorMax
```

#### Field Value

**Type:** System.Single

### anim

```csharp
public Animator anim
```

#### Field Value

**Type:** UnityEngine.Animator

### audioSrc

```csharp
public AudioSource audioSrc
```

#### Field Value

**Type:** UnityEngine.AudioSource

### autoClose

```csharp
public bool autoClose
```

#### Field Value

**Type:** System.Boolean

### CameraPos

```csharp
[HideInInspector]
public Vector3 CameraPos
```

#### Field Value

**Type:** UnityEngine.Vector3

### CancelButton

```csharp
public Button CancelButton
```

#### Field Value

**Type:** UnityEngine.UI.Button

### closeSound

```csharp
public AudioClip closeSound
```

#### Field Value

**Type:** UnityEngine.AudioClip

### ConfirmButton

```csharp
public Button ConfirmButton
```

#### Field Value

**Type:** UnityEngine.UI.Button

### currentIndexDisplay_Debug

```csharp
public Text currentIndexDisplay_Debug
```

#### Field Value

**Type:** UnityEngine.UI.Text

### currentTarget

```csharp
public CreatureModel currentTarget
```

#### Field Value

**Type:** Global.CreatureModel

### endTime

```csharp
public float endTime
```

#### Field Value

**Type:** System.Single

### filterNormal

```csharp
public Sprite filterNormal
```

#### Field Value

**Type:** UnityEngine.Sprite

### filterRenderer

```csharp
public Image filterRenderer
```

#### Field Value

**Type:** UnityEngine.UI.Image

### filterTransTime

```csharp
public float filterTransTime
```

#### Field Value

**Type:** System.Single

### filterWorkerSelected

```csharp
public Sprite filterWorkerSelected
```

#### Field Value

**Type:** UnityEngine.Sprite

### findingSpeed

```csharp
public Vector2 findingSpeed
```

#### Field Value

**Type:** UnityEngine.Vector2

### findingTime

```csharp
public float findingTime
```

#### Field Value

**Type:** System.Single

### integrate

```csharp
public GameObject integrate
```

#### Field Value

**Type:** UnityEngine.GameObject

### loopRange

```csharp
public Vector2 loopRange
```

#### Field Value

**Type:** UnityEngine.Vector2

### loopSpeedRange

```csharp
[Space(5)]
public Vector2 loopSpeedRange
```

#### Field Value

**Type:** UnityEngine.Vector2

### OnInvalidPanel

```csharp
public GameObject OnInvalidPanel
```

#### Field Value

**Type:** UnityEngine.GameObject

### openSound

```csharp
public AudioClip openSound
```

#### Field Value

**Type:** UnityEngine.AudioClip

### panel

```csharp
public RectTransform panel
```

#### Field Value

**Type:** UnityEngine.RectTransform

### prewarm

```csharp
[Space(5)]
public float prewarm
```

#### Field Value

**Type:** System.Single

### raycastObject

```csharp
public GameObject raycastObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### rouletteMaskHeight

```csharp
public float rouletteMaskHeight
```

#### Field Value

**Type:** System.Single

### scrollArea

```csharp
public ScrollRect scrollArea
```

#### Field Value

**Type:** UnityEngine.UI.ScrollRect

### selectSound

```csharp
public AudioClip selectSound
```

#### Field Value

**Type:** UnityEngine.AudioClip

### speedFactor

```csharp
public float speedFactor
```

#### Field Value

**Type:** System.Single

### stopTime

```csharp
[Space(10)]
public Vector2 stopTime
```

#### Field Value

**Type:** UnityEngine.Vector2

### textItem

```csharp
public GameObject textItem
```

#### Field Value

**Type:** UnityEngine.GameObject

### tickFreqDef

```csharp
public float tickFreqDef
```

#### Field Value

**Type:** System.Single

### tickFreqMin

```csharp
public float tickFreqMin
```

#### Field Value

**Type:** System.Single

### tickSound

```csharp
public AudioClip tickSound
```

#### Field Value

**Type:** UnityEngine.AudioClip

### tickSoundFreqScaler

```csharp
public float tickSoundFreqScaler
```

#### Field Value

**Type:** System.Single

### title

```csharp
public Text title
```

#### Field Value

**Type:** UnityEngine.UI.Text

### unitRectHeight

```csharp
[Space(5)]
public float unitRectHeight
```

#### Field Value

**Type:** System.Single

## Properties

### currentWindow

```csharp
public static RouletteWindow currentWindow { get; }
```

#### Property Value

**Type:** Global.RouletteWindow

### loopSpeed

```csharp
public float loopSpeed { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### AgentReset()

```csharp
public void AgentReset()
```

### AnimatorEventInit()

```csharp
public void AnimatorEventInit()
```

### AttackCalled(int)

```csharp
public void AttackCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### AttackDamageTimeCalled()

```csharp
public void AttackDamageTimeCalled()
```

### CallerSet(IRouletteWindowMessage)

```csharp
public void CallerSet(IRouletteWindowMessage caller)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caller` | `Global.IRouletteWindowMessage` |  |

### CreatureAnimCall(int, CreatureBase)

```csharp
public void CreatureAnimCall(int i, CreatureBase script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `script` | `Global.CreatureBase` |  |

### OnCalled()

```csharp
public void OnCalled()
```

### OnCalled(int)

```csharp
public void OnCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnClickCancel()

```csharp
public void OnClickCancel()
```

### OnClickConfirm()

```csharp
public void OnClickConfirm()
```

### OnClose()

```csharp
public void OnClose()
```

### OnFilterDefault()

```csharp
public void OnFilterDefault()
```

### OnFilterSelected()

```csharp
public void OnFilterSelected()
```

### OnSelectedItemEffectEnd(RouletteItem)

```csharp
public void OnSelectedItemEffectEnd(RouletteItem item)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `Global.RouletteItem` |  |

### OpenWindowGlobal(CreatureModel, OnSelectedEvent)

```csharp
public void OpenWindowGlobal(CreatureModel creature, RouletteWindow.OnSelectedEvent del)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `del` | `Global.RouletteWindow.OnSelectedEvent` |  |

### OpenWindowLocal(CreatureModel, Sefira, OnSelectedEvent)

```csharp
public void OpenWindowLocal(CreatureModel creature, Sefira range, RouletteWindow.OnSelectedEvent del)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `range` | `Global.Sefira` |  |
| `del` | `Global.RouletteWindow.OnSelectedEvent` |  |

### PlaySelectSound()

```csharp
public void PlaySelectSound()
```

### SetFilterAlpha(float)

```csharp
public void SetFilterAlpha(float alpha)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `alpha` | `System.Single` |  |

### SimpleReset()

```csharp
public void SimpleReset()
```

### SoundMake(string)

```csharp
public void SoundMake(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
