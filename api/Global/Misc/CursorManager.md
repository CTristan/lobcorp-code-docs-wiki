---
uid: Global.CursorManager
canonical_path: /api/Global/Misc/CursorManager
---

# Class CursorManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CursorManager : MonoBehaviour
```
Manages the cursor.

Specifically manages how the cursor is drawn, and how it changes during hover-over and bullet mode.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → CursorManager

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CursorManager()

```csharp
public CursorManager()
```

## Fields

### _cannotAnimTimer

```csharp
private UnscaledTimer _cannotAnimTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### _currentHotspot

```csharp
private Vector2 _currentHotspot
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### _instance

```csharp
private static CursorManager _instance
```
#INC


#### Field Value

**Type:** Global.CursorManager

### _isEnteredTarget

```csharp
private bool _isEnteredTarget
```
#INC


#### Field Value

**Type:** System.Boolean

### _isGlowing

```csharp
private bool _isGlowing
```
#INC


#### Field Value

**Type:** System.Boolean

### _prevCursorType

```csharp
private MouseCursorType _prevCursorType
```
#INC


#### Field Value

**Type:** Global.MouseCursorType

### _targetAnimFreq

```csharp
private const float _targetAnimFreq = 1
```
#INC


#### Field Value

**Type:** System.Single

### _targetAnimTimer

```csharp
private UnscaledTimer _targetAnimTimer
```
#INC


#### Field Value

**Type:** Global.UnscaledTimer

### BulletCursorSize

```csharp
public Vector2 BulletCursorSize
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### bullettHotspot

```csharp
public static Vector2 bullettHotspot
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### CannotAnimCurve

```csharp
public AnimationCurve CannotAnimCurve
```
#INC


#### Field Value

**Type:** UnityEngine.AnimationCurve

### CannotAnimFreq

```csharp
public float CannotAnimFreq
```
#INC


#### Field Value

**Type:** System.Single

### currentCursorTexture

```csharp
private Texture2D currentCursorTexture
```
#INC


#### Field Value

**Type:** UnityEngine.Texture2D

### currentType

```csharp
public MouseCursorType currentType
```
#INC


#### Field Value

**Type:** Global.MouseCursorType

### cursorMode

```csharp
public CursorMode cursorMode
```
#INC


#### Field Value

**Type:** UnityEngine.CursorMode

### cursorSprite

```csharp
public List<Texture2D> cursorSprite
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Texture2D}

### glowElapsed

```csharp
private float glowElapsed
```
#INC


#### Field Value

**Type:** System.Single

### glowFrequency

```csharp
public float glowFrequency
```
#INC


#### Field Value

**Type:** System.Single

### glowStartSave

```csharp
private MouseCursorType glowStartSave
```
#INC


#### Field Value

**Type:** Global.MouseCursorType

### halfHotspot

```csharp
public static Vector2 halfHotspot
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### isAlterMode

```csharp
private bool isAlterMode
```
#INC


#### Field Value

**Type:** System.Boolean

### isLock

```csharp
private bool isLock
```
#INC


#### Field Value

**Type:** System.Boolean

### mousePosition

```csharp
private Vector2 mousePosition
```
#INC


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
#INC


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
#INC


### Awake()

```csharp
public void Awake()
```
#INC
#code-generated


### CannotAnim()

```csharp
public void CannotAnim()
```
#INC


### CannotEnded()

```csharp
private void CannotEnded()
```
#INC


### CannotUpdate()

```csharp
public void CannotUpdate()
```
#INC


### ChangeDrawMode(bool)

```csharp
private void ChangeDrawMode(bool isGui)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isGui` | `System.Boolean` |  |

### CheckCursorChangable(MouseCursorType)

```csharp
private bool CheckCursorChangable(MouseCursorType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.MouseCursorType` |  |

#### Returns

**Type:** System.Boolean

### CursorSet(int)

```csharp
public void CursorSet(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### CursorSet(MouseCursorType)

```csharp
public void CursorSet(MouseCursorType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.MouseCursorType` |  |

### DeactivateGlowEffect()

```csharp
public void DeactivateGlowEffect()
```
#INC


### ForcelyCurserSet(MouseCursorType)

```csharp
public void ForcelyCurserSet(MouseCursorType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.MouseCursorType` |  |

### GetCurrentCusorType()

```csharp
public MouseCursorType GetCurrentCusorType()
```
#INC


#### Returns

**Type:** Global.MouseCursorType

### GetCursorType(int)

```csharp
public MouseCursorType GetCursorType(int index)
```
#INC


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
#INC


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
#INC


### LockCursor()

```csharp
public void LockCursor()
```
#INC


### OnEnteredTarget()

```csharp
public void OnEnteredTarget()
```
#INC


### OnExitTarget()

```csharp
public void OnExitTarget()
```
#INC


### OnStageEnd()

```csharp
public void OnStageEnd()
```
#INC


### SetCursorScale(float)

```csharp
public void SetCursorScale(float factor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factor` | `System.Single` |  |

### Start()

```csharp
public void Start()
```
#INC


### UnlockCursor()

```csharp
public void UnlockCursor()
```
#INC


### Update()

```csharp
public void Update()
```
#INC

