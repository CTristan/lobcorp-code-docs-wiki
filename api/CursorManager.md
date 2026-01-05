# Class CursorManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CursorManager : MonoBehaviour
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → CursorManager

## Inherited Members
[Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CursorManager()

```csharp
public CursorManager()
```

## Fields

### BulletCursorSize

```csharp
public Vector2 BulletCursorSize
```

#### Field Value

**Type:** UnityEngine.Vector2

### bullettHotspot

```csharp
public static Vector2 bullettHotspot
```

#### Field Value

**Type:** UnityEngine.Vector2

### CannotAnimCurve

```csharp
public AnimationCurve CannotAnimCurve
```

#### Field Value

**Type:** UnityEngine.AnimationCurve

### CannotAnimFreq

```csharp
public float CannotAnimFreq
```

#### Field Value

**Type:** System.Single

### currentType

```csharp
public MouseCursorType currentType
```

#### Field Value

**Type:** Global.MouseCursorType

### cursorMode

```csharp
public CursorMode cursorMode
```

#### Field Value

**Type:** UnityEngine.CursorMode

### cursorSprite

```csharp
public List<Texture2D> cursorSprite
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Texture2D}

### glowFrequency

```csharp
public float glowFrequency
```

#### Field Value

**Type:** System.Single

### halfHotspot

```csharp
public static Vector2 halfHotspot
```

#### Field Value

**Type:** UnityEngine.Vector2

### TargetAnimCurve

```csharp
[Header("Bullet Target Anim")]
public AnimationCurve TargetAnimCurve
```

#### Field Value

**Type:** UnityEngine.AnimationCurve

### zeroHotspot

```csharp
public static Vector2 zeroHotspot
```

#### Field Value

**Type:** UnityEngine.Vector2

## Properties

### instance

```csharp
public static CursorManager instance { get; }
```

#### Property Value

**Type:** Global.CursorManager

### IsBulletMode

```csharp
public bool IsBulletMode { get; }
```

#### Property Value

**Type:** System.Boolean

### IsCannotDisplaying

```csharp
public bool IsCannotDisplaying { get; }
```

#### Property Value

**Type:** System.Boolean

### IsEnteredTarget

```csharp
public bool IsEnteredTarget { get; set; }
```

#### Property Value

**Type:** System.Boolean

### isGlowing

```csharp
public bool isGlowing { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### ActivateGlowEffect()

```csharp
public void ActivateGlowEffect()
```

### Awake()

```csharp
public void Awake()
```

### CannotAnim()

```csharp
public void CannotAnim()
```

### CannotUpdate()

```csharp
public void CannotUpdate()
```

### CursorSet(int)

```csharp
public void CursorSet(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### CursorSet(MouseCursorType)

```csharp
public void CursorSet(MouseCursorType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.MouseCursorType` |  |

### DeactivateGlowEffect()

```csharp
public void DeactivateGlowEffect()
```

### ForcelyCurserSet(MouseCursorType)

```csharp
public void ForcelyCurserSet(MouseCursorType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.MouseCursorType` |  |

### GetCurrentCusorType()

```csharp
public MouseCursorType GetCurrentCusorType()
```

#### Returns

**Type:** Global.MouseCursorType

### GetCursorType(int)

```csharp
public MouseCursorType GetCursorType(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.MouseCursorType

### GetHotspot(MouseCursorType, Texture2D)

```csharp
public Vector2 GetHotspot(MouseCursorType type, Texture2D tex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.MouseCursorType` |  |
| `tex` | `UnityEngine.Texture2D` |  |

#### Returns

**Type:** UnityEngine.Vector2

### HideCursor()

```csharp
public void HideCursor()
```

### LockCursor()

```csharp
public void LockCursor()
```

### OnEnteredTarget()

```csharp
public void OnEnteredTarget()
```

### OnExitTarget()

```csharp
public void OnExitTarget()
```

### OnStageEnd()

```csharp
public void OnStageEnd()
```

### SetCursorScale(float)

```csharp
public void SetCursorScale(float factor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factor` | `System.Single` |  |

### Start()

```csharp
public void Start()
```

### UnlockCursor()

```csharp
public void UnlockCursor()
```

### Update()

```csharp
public void Update()
```
