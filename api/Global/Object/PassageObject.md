---
uid: Global.PassageObject
canonical_path: /api/Global/Object/PassageObject
---

# Class PassageObject

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PassageObject : MonoBehaviour, IObserver, IMouseCommandTarget, IMouseOnPointListener
```

A [room](/api/Global/Model/PassageObjectModel), as it appears in-game.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → PassageObject

## Derived
[PassageWayObject](/api/Global/Object/PassageWayObject)

## Implements
[IObserver](/api/Global/Misc/IObserver), [IMouseCommandTarget](/api/Global/Misc/IMouseCommandTarget), [IMouseOnPointListener](/api/Global/Misc/IMouseOnPointListener)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PassageObject()

```csharp
public PassageObject()
```

## Fields

### _black

```csharp
protected bool _black
```
#INC


#### Field Value

**Type:** System.Boolean

### _sefiraDisabled

```csharp
protected bool _sefiraDisabled
```
#INC


#### Field Value

**Type:** System.Boolean

### doorList

```csharp
private List<PassageDoor> doorList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{PassageDoor}

### elevatorList

```csharp
private List<ElevatorPassageObject> elevatorList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{ElevatorPassageObject}

### Height

```csharp
public float Height
```
#INC


#### Field Value

**Type:** System.Single

### LightObjects

```csharp
public GameObject LightObjects
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### model

```csharp
public PassageObjectModel model
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### mouseFocus

```csharp
public GameObject mouseFocus
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### overlayShader

```csharp
public Image overlayShader
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### sefiraFrame

```csharp
public SpriteRenderer sefiraFrame
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### shader

```csharp
[HideInInspector]
public SpriteRenderer shader
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### shaderObject

```csharp
public GameObject shaderObject
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### type

```csharp
public SpaceObjectType type
```
#INC


#### Field Value

**Type:** Global.SpaceObjectType

## Properties

### FocusScript

```csharp
private UnitMouseEventFocus FocusScript { get; }
```

#### Property Value

**Type:** Global.UnitMouseEventFocus

## Methods

### AddBloodMapObject(BloodMapObjectModel)

```csharp
public void AddBloodMapObject(BloodMapObjectModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.BloodMapObjectModel` |  |

### Awake()

```csharp
private void Awake()
```
#INC
#code-generated


### GenRabbitFilter()

```csharp
public GameObject GenRabbitFilter()
```
#INC


#### Returns

**Type:** UnityEngine.GameObject

### GetCommandTargetModel()

```csharp
public IMouseCommandTargetModel GetCommandTargetModel()
```
#INC


#### Returns

**Type:** Global.IMouseCommandTargetModel

### GetDoorPassage(string)

```csharp
public PassageDoor GetDoorPassage(string id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns

**Type:** Global.PassageDoor

### GetElevatorPassage(string)

```csharp
public ElevatorPassageObject GetElevatorPassage(string nodeId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `nodeId` | `System.String` |  |

#### Returns

**Type:** Global.ElevatorPassageObject

### HasPointListener()

```csharp
public bool HasPointListener()
```
#INC


#### Returns

**Type:** System.Boolean

### Init(PassageObjectModel)

```csharp
public void Init(PassageObjectModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.PassageObjectModel` |  |

### IsRabbitExecuting()

```csharp
public bool IsRabbitExecuting()
```
#INC


#### Returns

**Type:** System.Boolean

### OnNotice(string, params object[])

```csharp
public virtual void OnNotice(string notice, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnPointEnter()

```csharp
public void OnPointEnter()
```
#INC


### OnPointerClick()

```csharp
public void OnPointerClick()
```
#INC


### OnPointExit()

```csharp
public void OnPointExit()
```
#INC


### OnStageStart()

```csharp
public virtual void OnStageStart()
```
#INC


### OverlayShaderActivate(bool)

```csharp
public void OverlayShaderActivate(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetAplphaRecursive(float)

```csharp
public void SetAplphaRecursive(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### SetBlackOut()

```csharp
public void SetBlackOut()
```
#INC


### SetOverlayShader(Sprite)

```csharp
public void SetOverlayShader(Sprite sprite)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sprite` | `UnityEngine.Sprite` |  |

### SetOverlayShaderAlpha(float)

```csharp
public void SetOverlayShaderAlpha(float alpha)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `alpha` | `System.Single` |  |

### SetPassageFilter(Texture2D, string, string, int)

```csharp
public GameObject SetPassageFilter(Texture2D sp, string name, string anim = "Normal", int sortOrder = 2)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sp` | `UnityEngine.Texture2D` |  |
| `name` | `System.String` |  |
| `anim` | `System.String` |  |
| `sortOrder` | `System.Int32` |  |

#### Returns

**Type:** UnityEngine.GameObject

### SetShader(float)

```csharp
public void SetShader(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### SetWhite()

```csharp
public void SetWhite()
```
#INC


### Start()

```csharp
private void Start()
```
#INC


### Update()

```csharp
protected virtual void Update()
```
#INC


### UpdateViewPosition()

```csharp
public void UpdateViewPosition()
```
#INC

