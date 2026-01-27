---
uid: Global.CameraMover
canonical_path: /api/Global/Camera/Mover/CameraMover
---

# Class CameraMover

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CameraMover : MonoBehaviour
```
Thing which controls camera movement; seems to include both automatic movement and player movement.
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → CameraMover

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CameraMover()

```csharp
public CameraMover()
```

## Fields

### _currentRangeLevel

```csharp
private int _currentRangeLevel
```
#INC


#### Field Value

**Type:** System.Int32

### _instance

```csharp
private static CameraMover _instance
```
#INC


#### Field Value

**Type:** Global.CameraMover

### _kether_ortho_inv

```csharp
private float _kether_ortho_inv
```
#INC


#### Field Value

**Type:** System.Single

### _kether_ortho_min

```csharp
private float _kether_ortho_min
```
#INC


#### Field Value

**Type:** System.Single

### _kether_x

```csharp
private MinMax _kether_x
```
#INC


#### Field Value

**Type:** Global.MinMax

### _kether_y_max

```csharp
private MinMax _kether_y_max
```
#INC


#### Field Value

**Type:** Global.MinMax

### _kether_y_min

```csharp
private MinMax _kether_y_min
```
#INC


#### Field Value

**Type:** Global.MinMax

### _movable

```csharp
private bool _movable
```
#INC


#### Field Value

**Type:** System.Boolean

### _target

```csharp
private IScrollTarget _target
```
#INC


#### Field Value

**Type:** Global.IScrollTarget

### agentTarget

```csharp
public long agentTarget
```
#INC


#### Field Value

**Type:** System.Int64

### attached

```csharp
private bool attached
```
#INC


#### Field Value

**Type:** System.Boolean

### attachTarget

```csharp
private MovableObjectNode attachTarget
```
#INC


#### Field Value

**Type:** Global.MovableObjectNode

### CameraMax

```csharp
public Vector3 CameraMax
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### CameraMin

```csharp
public Vector3 CameraMin
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### creatureTarget

```csharp
public long creatureTarget
```
#INC


#### Field Value

**Type:** System.Int64

### DefaultOrtho

```csharp
public float DefaultOrtho
```
#INC


#### Field Value

**Type:** System.Single

### DefaultPos

```csharp
public Vector3 DefaultPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### Diference

```csharp
private Vector3 Diference
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### Drag

```csharp
private bool Drag
```
#INC


#### Field Value

**Type:** System.Boolean

### dragedPos

```csharp
private Vector3 dragedPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### endCall

```csharp
public CameraMover.OnCameraMoveEndEvent endCall
```

#### Field Value

**Type:** Global.CameraMover.OnCameraMoveEndEvent

### escapeButton

```csharp
public GameObject escapeButton
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### isObserving

```csharp
private bool isObserving
```
#INC


#### Field Value

**Type:** System.Boolean

### moveScript

```csharp
public CameraMover.CameraForcelyMove moveScript
```

#### Field Value

**Type:** Global.CameraMover.CameraForcelyMove

### ObserveOrthoSize

```csharp
private const float ObserveOrthoSize = 4
```
#INC


#### Field Value

**Type:** System.Single

### observeTarget

```csharp
private CreatureModel observeTarget
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### Origin

```csharp
private Vector3 Origin
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### player

```csharp
public GameObject player
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### Range

```csharp
public List<CameraMover.CameraMoveRange> Range
```

#### Field Value

**Type:** System.Collections.Generic.List{CameraMover.CameraMoveRange}

### recoil

```csharp
public RecoilEffect recoil
```
#INC


#### Field Value

**Type:** Global.RecoilEffect

### ResetCamera

```csharp
private Vector3 ResetCamera
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### roomXCorrection

```csharp
private const float roomXCorrection = -1
```
#INC


#### Field Value

**Type:** System.Single

### roomYCorrection

```csharp
private const float roomYCorrection = -1.7
```
#INC


#### Field Value

**Type:** System.Single

### saveOrtho

```csharp
private float saveOrtho
```
#INC


#### Field Value

**Type:** System.Single

### scrollSpeed

```csharp
public float scrollSpeed
```
#INC


#### Field Value

**Type:** System.Single

### targetCamera

```csharp
public Camera targetCamera
```
#INC


#### Field Value

**Type:** UnityEngine.Camera

## Properties

### CameraOrthographicSize

```csharp
public float CameraOrthographicSize { get; set; }
```

#### Property Value

**Type:** System.Single

### CameraPos

```csharp
private Vector3 CameraPos { get; set; }
```

#### Property Value

**Type:** UnityEngine.Vector3

### currentRange

```csharp
private CameraMover.CameraMoveRange currentRange { get; }
```

#### Property Value

**Type:** Global.CameraMover.CameraMoveRange

### currentRangeLevel

```csharp
public int currentRangeLevel { get; }
```

#### Property Value

**Type:** System.Int32

### instance

```csharp
public static CameraMover instance { get; }
```

#### Property Value

**Type:** Global.CameraMover

### movable

```csharp
private bool movable { get; set; }
```

#### Property Value

**Type:** System.Boolean

### orthoMax

```csharp
private float orthoMax { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### AttachToMovable(MovableObjectNode)

```csharp
public void AttachToMovable(MovableObjectNode mov)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

### Awake()

```csharp
private void Awake()
```
#INC


### CameraMoveEvent(Vector3, float)

```csharp
public void CameraMoveEvent(Vector3 dest, float ortho)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dest` | `UnityEngine.Vector3` |  |
| `ortho` | `System.Single` |  |

### CameraMoveEvent(Vector3, float, float)

```csharp
public void CameraMoveEvent(Vector3 dest, float ortho, float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dest` | `UnityEngine.Vector3` |  |
| `ortho` | `System.Single` |  |
| `time` | `System.Single` |  |

### DecoupleToMovable()

```csharp
public void DecoupleToMovable()
```
#INC


### DeRegistration()

```csharp
public void DeRegistration()
```
#INC


### GenObserveMovement(CreatureModel)

```csharp
public void GenObserveMovement(CreatureModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |

### GetMovementClamped(Vector3)

```csharp
public Vector3 GetMovementClamped(Vector3 input)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** UnityEngine.Vector3

### IsMovable()

```csharp
public bool IsMovable()
```
#INC


#### Returns

**Type:** System.Boolean

### LateUpdate()

```csharp
private void LateUpdate()
```
#INC


### OnCameraMoveEnd()

```csharp
public void OnCameraMoveEnd()
```
#INC


### OnObserveCameraMoveEnd()

```csharp
private void OnObserveCameraMoveEnd()
```
#INC


### OnObserveEnded()

```csharp
public void OnObserveEnded()
```
#INC


### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### PlayRecoil(Queue<Vector3>, float)

```csharp
private IEnumerator PlayRecoil(Queue<Vector3> queue, float maxTime)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `queue` | `System.Collections.Generic.Queue{UnityEngine.Vector3}` |  |
| `maxTime` | `System.Single` |  |

#### Returns

**Type:** System.Collections.IEnumerator

### Recoil(int)

```csharp
public void Recoil(int level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### Recoil(int, float)

```csharp
public void Recoil(int level, float maxTime)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |
| `maxTime` | `System.Single` |  |

### Recoil(int, float, int, float)

```csharp
public void Recoil(int level, float maxTime, int recoilCount, float scale)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |
| `maxTime` | `System.Single` |  |
| `recoilCount` | `System.Int32` |  |
| `scale` | `System.Single` |  |

### Registration(IScrollTarget)

```csharp
public void Registration(IScrollTarget target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.IScrollTarget` |  |

### Registration(IScrollTarget, bool)

```csharp
public void Registration(IScrollTarget target, bool cursorSet)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.IScrollTarget` |  |
| `cursorSet` | `System.Boolean` |  |

### ReleaseMove()

```csharp
public void ReleaseMove()
```
#INC


### SetEndCall(OnCameraMoveEndEvent)

```csharp
public void SetEndCall(CameraMover.OnCameraMoveEndEvent call)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `call` | `Global.CameraMover.OnCameraMoveEndEvent` |  |

### SetSettingToDefault()

```csharp
public void SetSettingToDefault()
```
#INC


### SetSettingToStart()

```csharp
public void SetSettingToStart()
```
#INC


### SetTutorialCam()

```csharp
public void SetTutorialCam()
```
#INC


### Start()

```csharp
private void Start()
```
#INC


### StopMove()

```csharp
public void StopMove()
```
#INC


### Update()

```csharp
private void Update()
```
#INC

