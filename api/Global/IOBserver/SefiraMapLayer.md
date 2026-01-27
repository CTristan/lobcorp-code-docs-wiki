---
uid: Global.SefiraMapLayer
canonical_path: /api/Global/IOBserver/SefiraMapLayer
---

# Class SefiraMapLayer

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraMapLayer : MonoBehaviour, IObserver
```

Game layer which holds and manages the rooms and doors.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → SefiraMapLayer

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SefiraMapLayer()

```csharp
public SefiraMapLayer()
```

## Fields

### _instance

```csharp
private static SefiraMapLayer _instance
```
#INC


#### Field Value

**Type:** Global.SefiraMapLayer

### _teleportDoorObjects

```csharp
private Dictionary<string, GameObject> _teleportDoorObjects
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,UnityEngine.GameObject}

### bloodNode

```csharp
public GameObject bloodNode
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### nowLoading

```csharp
public bool nowLoading
```
#INC


#### Field Value

**Type:** System.Boolean

### sefiraDic

```csharp
private Dictionary<string, SefiraObject> sefiraDic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,SefiraObject}

### sefiras

```csharp
public SefiraObject[] sefiras
```
#INC


#### Field Value

**Type:** Global.SefiraObject[]

### teleportRoot

```csharp
public GameObject teleportRoot
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### waitingForLoading

```csharp
private List<PassageObjectModel> waitingForLoading
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

## Properties

### instance

```csharp
public static SefiraMapLayer instance { get; }
```

#### Property Value

**Type:** Global.SefiraMapLayer

## Methods

### AddBloodMapObject(BloodMapObjectModel)

```csharp
private void AddBloodMapObject(BloodMapObjectModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.BloodMapObjectModel` |  |

### AddPassageDoor(PassageObjectModel, DoorObjectModel)

```csharp
private void AddPassageDoor(PassageObjectModel model, DoorObjectModel doorModel)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.PassageObjectModel` |  |
| `doorModel` | `Global.DoorObjectModel` |  |

### AddPassageObject(PassageObjectModel)

```csharp
private void AddPassageObject(PassageObjectModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.PassageObjectModel` |  |

### AddRabbitTeleport(MapNode, UnitDirection)

```csharp
private void AddRabbitTeleport(MapNode node, UnitDirection dir)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |
| `dir` | `Global.UnitDirection` |  |

### Awake()

```csharp
private void Awake()
```
#INC
#code-generated


### DisableMapLayer()

```csharp
private void DisableMapLayer()
```
#INC


### EnableMapLayer()

```csharp
private void EnableMapLayer()
```
#INC


### GetPassageObject(PassageObjectModel)

```csharp
public PassageObject GetPassageObject(PassageObjectModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.PassageObjectModel` |  |

#### Returns

**Type:** Global.PassageObject

### GetSefiraObject(string)

```csharp
public SefiraObject GetSefiraObject(string sefiraName)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraName` | `System.String` |  |

#### Returns

**Type:** Global.SefiraObject

### InitAreaActivate()

```csharp
private void InitAreaActivate()
```
#INC


### LoadLayer()

```csharp
private void LoadLayer()
```
#INC


### LoadLayerAsync()

```csharp
public void LoadLayerAsync()
```
#INC


### LoadLayerCoroutine()

```csharp
private IEnumerator LoadLayerCoroutine()
```
#INC


#### Returns

**Type:** System.Collections.IEnumerator

### OnDisable()

```csharp
private void OnDisable()
```
#INC


### OnEnable()

```csharp
private void OnEnable()
```
#INC


### OnInitGameManager()

```csharp
private void OnInitGameManager()
```
#INC


### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### RemoveBlood()

```csharp
private void RemoveBlood()
```
#INC


### RemoveDynamicPassages()

```csharp
private void RemoveDynamicPassages()
```
#INC


### RemoveRabbitTeleport(MapNode)

```csharp
private void RemoveRabbitTeleport(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### RemoveRabbitTeleportAll()

```csharp
private void RemoveRabbitTeleportAll()
```
#INC


### SetAreaActive(string, string, bool)

```csharp
public void SetAreaActive(string sefiraName, string groupName, bool b)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraName` | `System.String` |  |
| `groupName` | `System.String` |  |
| `b` | `System.Boolean` |  |

### SetPassageAlpha(PassageObjectModel, int)

```csharp
private void SetPassageAlpha(PassageObjectModel model, int value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.PassageObjectModel` |  |
| `value` | `System.Int32` |  |

### SetPassageBlackOut(PassageObjectModel)

```csharp
private void SetPassageBlackOut(PassageObjectModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.PassageObjectModel` |  |

### SetPassageWhite()

```csharp
public void SetPassageWhite()
```
#INC


### SetPassageWhite(PassageObjectModel)

```csharp
private void SetPassageWhite(PassageObjectModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.PassageObjectModel` |  |

### SetSefiraActive(string, bool)

```csharp
public void SetSefiraActive(string sefiraName, bool b)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefiraName` | `System.String` |  |
| `b` | `System.Boolean` |  |

### Start()

```csharp
private void Start()
```
#INC


### Update()

```csharp
private void Update()
```
#INC

