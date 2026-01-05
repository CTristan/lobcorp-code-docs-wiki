# Class CreatureSelectUI

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureSelectUI : MonoBehaviour, IAnimatorEventCalled
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → CreatureSelectUI

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreatureSelectUI()

```csharp
public CreatureSelectUI()
```

## Fields

### Block

```csharp
public UIController Block
```

#### Field Value

**Type:** Global.UIController

### clip

```csharp
public AudioClip clip
```

#### Field Value

**Type:** UnityEngine.AudioClip

### deathangel

```csharp
public const long deathangel = 100015
```

#### Field Value

**Type:** System.Int64

### filter

```csharp
public CameraFilterPack_TV_80 filter
```

#### Field Value

**Type:** Global.CameraFilterPack_TV_80

### GlobalControlAnim

```csharp
[Header("Effect")]
public Animator GlobalControlAnim
```

#### Field Value

**Type:** UnityEngine.Animator

### Index_Normal

```csharp
[Header("Index")]
public RectTransform Index_Normal
```

#### Field Value

**Type:** UnityEngine.RectTransform

### Index_Select

```csharp
public RectTransform Index_Select
```

#### Field Value

**Type:** UnityEngine.RectTransform

### plagueDoctor

```csharp
public const long plagueDoctor = 100014
```

#### Field Value

**Type:** System.Int64

### reExtractController

```csharp
[Header("ReExtract")]
public UIController reExtractController
```

#### Field Value

**Type:** Global.UIController

### RootObject

```csharp
public GameObject RootObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### SelectEndDay

```csharp
public const int SelectEndDay = 51
```

#### Field Value

**Type:** System.Int32

### SelectStartDay

```csharp
public const int SelectStartDay = 0
```

#### Field Value

**Type:** System.Int32

### TextBoxController

```csharp
[Header("TextBox")]
public UIController TextBoxController
```

#### Field Value

**Type:** Global.UIController

### TextBoxText

```csharp
public Text TextBoxText
```

#### Field Value

**Type:** UnityEngine.UI.Text

### Units

```csharp
[Header("UI")]
public CreatureSelectUnit[] Units
```

#### Field Value

**Type:** CreatureSelect.CreatureSelectUnit[]

### yang

```csharp
public const long yang = 300109
```

#### Field Value

**Type:** System.Int64

### yin

```csharp
public const long yin = 100104
```

#### Field Value

**Type:** System.Int64

## Properties

### instance

```csharp
public static CreatureSelectUI instance { get; }
```

#### Property Value

**Type:** Global.CreatureSelectUI

### IsEnabled

```csharp
public bool IsEnabled { get; }
```

#### Property Value

**Type:** System.Boolean

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

### CheckCreatureExisting(long)

```csharp
public static bool CheckCreatureExisting(long targetId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetId` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean

### CreatureAnimCall(int, CreatureBase)

```csharp
public void CreatureAnimCall(int i, CreatureBase script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `script` | `Global.CreatureBase` |  |

### FadeoutEffect(float)

```csharp
public void FadeoutEffect(float time = 3)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

### Init()

```csharp
public void Init()
```

### IsInteractable()

```csharp
public bool IsInteractable()
```

#### Returns

**Type:** System.Boolean

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

### OnClickReExtract()

```csharp
public void OnClickReExtract()
```

### OnClickUnit(CreatureSelectUnit)

```csharp
public void OnClickUnit(CreatureSelectUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `CreatureSelect.CreatureSelectUnit` |  |

### OnEnterUnit(CreatureSelectUnit)

```csharp
public void OnEnterUnit(CreatureSelectUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `CreatureSelect.CreatureSelectUnit` |  |

### OnExitUnit(CreatureSelectUnit)

```csharp
public void OnExitUnit(CreatureSelectUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `CreatureSelect.CreatureSelectUnit` |  |

### OnUIActionEnd()

```csharp
public void OnUIActionEnd()
```

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
