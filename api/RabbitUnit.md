# Class RabbitUnit

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitUnit : MonoBehaviour, IMouseOnSelectListener, IMouseCommandTarget
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → RabbitUnit

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### RabbitUnit()

```csharp
public RabbitUnit()
```

## Fields

### _Execute_src

```csharp
public const string _Execute_src = "Effect/Bullet/RabbitFallback"
```

#### Field Value

**Type:** System.String

### agentUI

```csharp
public AgentUI agentUI
```

#### Field Value

**Type:** InGameUI.AgentUI

### animController

```csharp
public RabbitAnimatorController animController
```

#### Field Value

**Type:** Global.RabbitAnimatorController

### animEventHandler

```csharp
public AnimatorEventHandler animEventHandler
```

#### Field Value

**Type:** Global.AnimatorEventHandler

### animRoot

```csharp
public Transform animRoot
```

#### Field Value

**Type:** UnityEngine.Transform

### centerRoot

```csharp
public Transform centerRoot
```

#### Field Value

**Type:** UnityEngine.Transform

### currentSpeechType

```csharp
public RabbitConversationType currentSpeechType
```

#### Field Value

**Type:** Rabbit.RabbitConversationType

### executionCenter

```csharp
public Transform executionCenter
```

#### Field Value

**Type:** UnityEngine.Transform

### faceFollower

```csharp
public Transform faceFollower
```

#### Field Value

**Type:** UnityEngine.Transform

### faceSprites

```csharp
public SpriteRenderer[] faceSprites
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer[]

### model

```csharp
public RabbitModel model
```

#### Field Value

**Type:** Global.RabbitModel

### particle

```csharp
public List<ParticleSystem> particle
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.ParticleSystem}

### rwbpSet

```csharp
[Header("RWBP Set")]
public RabbitRwbpSet rwbpSet
```

#### Field Value

**Type:** Global.RabbitRwbpSet

### rwbpType

```csharp
public RwbpType rwbpType
```

#### Field Value

**Type:** Global.RwbpType

### speech

```csharp
public RabbitSpeech speech
```

#### Field Value

**Type:** Rabbit.RabbitSpeech

### spriteSetter

```csharp
public RabbitSpriteSetter spriteSetter
```

#### Field Value

**Type:** Rabbit.RabbitSpriteSetter

### ui

```csharp
public RabbitUnitUI ui
```

#### Field Value

**Type:** Global.RabbitUnitUI

### zValue

```csharp
public float zValue
```

#### Field Value

**Type:** System.Single

## Methods

### Attack(int)

```csharp
public void Attack(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### Fire()

```csharp
public void Fire()
```

### FixedUpdate()

```csharp
public void FixedUpdate()
```

### GetCommandTargetModel()

```csharp
public IMouseCommandTargetModel GetCommandTargetModel()
```

#### Returns

**Type:** Global.IMouseCommandTargetModel

### IsSelectable()

```csharp
public bool IsSelectable()
```

#### Returns

**Type:** System.Boolean

### OnClear()

```csharp
public void OnClear()
```

### OnDie()

```csharp
public void OnDie()
```

### OnDieByMental()

```csharp
public void OnDieByMental()
```

### OnSelect()

```csharp
public void OnSelect()
```

### OnSpeechEnd()

```csharp
public void OnSpeechEnd()
```

### OnUnselect()

```csharp
public void OnUnselect()
```

### SetDefaultZValue(float)

```csharp
public void SetDefaultZValue(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### SetModel(RabbitModel)

```csharp
public void SetModel(RabbitModel m)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `m` | `Global.RabbitModel` |  |

### Speech(RabbitConversationType, float, float)

```csharp
public void Speech(RabbitConversationType type, float speechProb = 0.6, float speechTime = 3)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Rabbit.RabbitConversationType` |  |
| `speechProb` | `System.Single` |  |
| `speechTime` | `System.Single` |  |

### StopFire()

```csharp
public void StopFire()
```

### UpdateDirection()

```csharp
protected void UpdateDirection()
```

### UpdateViewPosition()

```csharp
protected void UpdateViewPosition()
```
