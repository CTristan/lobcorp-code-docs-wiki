# Class WorkerPortraitSetter

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

[`[UnityEngine.RequireComponent]`](#)

```csharp
[RequireComponent(typeof(CanvasGroup))]
public class WorkerPortraitSetter : MonoBehaviour
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → WorkerPortraitSetter

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### WorkerPortraitSetter()

```csharp
public WorkerPortraitSetter()
```

## Fields

### Body

```csharp
public Image Body
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CoatBack

```csharp
public Image CoatBack
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CoatLeft

```csharp
public Image CoatLeft
```

#### Field Value

**Type:** UnityEngine.UI.Image

### CoatRight

```csharp
public Image CoatRight
```

#### Field Value

**Type:** UnityEngine.UI.Image

### Eye

```csharp
public Image Eye
```

#### Field Value

**Type:** UnityEngine.UI.Image

### Eyebrow

```csharp
public Image Eyebrow
```

#### Field Value

**Type:** UnityEngine.UI.Image

### FistRenderer

```csharp
public Image FistRenderer
```

#### Field Value

**Type:** UnityEngine.UI.Image

### FrontHair

```csharp
public Image FrontHair
```

#### Field Value

**Type:** UnityEngine.UI.Image

### Head

```csharp
public Image Head
```

#### Field Value

**Type:** UnityEngine.UI.Image

### LeftDownArm

```csharp
public Image LeftDownArm
```

#### Field Value

**Type:** UnityEngine.UI.Image

### LeftDownLeg

```csharp
public Image LeftDownLeg
```

#### Field Value

**Type:** UnityEngine.UI.Image

### LeftHand

```csharp
public Image LeftHand
```

#### Field Value

**Type:** UnityEngine.UI.Image

### LeftUpArm

```csharp
public Image LeftUpArm
```

#### Field Value

**Type:** UnityEngine.UI.Image

### LeftUpLeg

```csharp
public Image LeftUpLeg
```

#### Field Value

**Type:** UnityEngine.UI.Image

### log

```csharp
public bool log
```

#### Field Value

**Type:** System.Boolean

### Mouth

```csharp
public Image Mouth
```

#### Field Value

**Type:** UnityEngine.UI.Image

### OneHandedRenderer

```csharp
public Image OneHandedRenderer
```

#### Field Value

**Type:** UnityEngine.UI.Image

### RearHair

```csharp
public Image RearHair
```

#### Field Value

**Type:** UnityEngine.UI.Image

### RightDownArm

```csharp
public Image RightDownArm
```

#### Field Value

**Type:** UnityEngine.UI.Image

### RightDownLeg

```csharp
public Image RightDownLeg
```

#### Field Value

**Type:** UnityEngine.UI.Image

### RightHand

```csharp
public Image RightHand
```

#### Field Value

**Type:** UnityEngine.UI.Image

### RightUpArm

```csharp
public Image RightUpArm
```

#### Field Value

**Type:** UnityEngine.UI.Image

### RightUpLeg

```csharp
public Image RightUpLeg
```

#### Field Value

**Type:** UnityEngine.UI.Image

### Symbol

```csharp
public Image Symbol
```

#### Field Value

**Type:** UnityEngine.UI.Image

### TwoHandedRenderer

```csharp
public Image TwoHandedRenderer
```

#### Field Value

**Type:** UnityEngine.UI.Image

### WeaponMask

```csharp
public GameObject[] WeaponMask
```

#### Field Value

**Type:** UnityEngine.GameObject[]

### WeaponSet

```csharp
public bool WeaponSet
```

#### Field Value

**Type:** System.Boolean

## Properties

### CanvasGroup

```csharp
public CanvasGroup CanvasGroup { get; }
```

#### Property Value

**Type:** UnityEngine.CanvasGroup

## Methods

### SetActive(bool)

```csharp
public void SetActive(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetAgentArmor()

```csharp
public void SetAgentArmor()
```

### SetArmor(EquipmentTypeInfo)

```csharp
public void SetArmor(EquipmentTypeInfo armor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `armor` | `Global.EquipmentTypeInfo` |  |

### SetCustomizing(AgentData, WorkerFaceType)

```csharp
public void SetCustomizing(AgentData data, WorkerFaceType face = WorkerFaceType.DEFAULT)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Customizing.AgentData` |  |
| `face` | `WorkerSprite.WorkerFaceType` |  |

### SetSprite(Image, Sprite)

```csharp
public void SetSprite(Image region, Sprite sprite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `UnityEngine.UI.Image` |  |
| `sprite` | `UnityEngine.Sprite` |  |

### SetUniqueWeapon(UniqueWeaponSpriteUnit)

```csharp
public void SetUniqueWeapon(UniqueWeaponSpriteUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `WorkerSprite.UniqueWeaponSpriteUnit` |  |

### SetWeapon(WeaponModel)

```csharp
public void SetWeapon(WeaponModel weapon)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `weapon` | `Global.WeaponModel` |  |

### SetWorker(WorkerModel)

```csharp
public void SetWorker(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |
