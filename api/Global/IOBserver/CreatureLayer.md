---
uid: Global.CreatureLayer
canonical_path: /api/Global/IOBserver/CreatureLayer
---

# Class CreatureLayer

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureLayer : MonoBehaviour, IObserver
```
Layer which has all the creatures in it, including abnormalities, ordeal creatures, and sephirah bosses.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → CreatureLayer

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureLayer()

```csharp
public CreatureLayer()
```

## Fields

### creatureDic

```csharp
private Dictionary<long, CreatureUnit> creatureDic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int64,CreatureUnit}

### creatureList

```csharp
private List<CreatureUnit> creatureList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureUnit}

### dark

```csharp
private string dark
```
#INC


#### Field Value

**Type:** System.String

### directory

```csharp
private string directory
```
#INC


#### Field Value

**Type:** System.String

### etcDic

```csharp
private Dictionary<long, EtcUnit> etcDic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int64,EtcUnit}

### etcList

```csharp
private List<EtcUnit> etcList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{EtcUnit}

### eventCreatureList

```csharp
private List<CreatureUnit> eventCreatureList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureUnit}

### isolateRoomUI

```csharp
public CreatureLayer.IsolateRoomUI isolateRoomUI
```

#### Field Value

**Type:** Global.CreatureLayer.IsolateRoomUI

### ordealCreatureList

```csharp
private List<CreatureUnit> ordealCreatureList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureUnit}

### sefiraBossList

```csharp
private List<CreatureUnit> sefiraBossList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureUnit}

### tempIntforSprite

```csharp
private List<int> tempIntforSprite
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.Int32}

## Properties

### currentLayer

```csharp
public static CreatureLayer currentLayer { get; private set; }
```
#INC


#### Property Value

**Type:** Global.CreatureLayer

### IsolateRoomUIData

```csharp
public static CreatureLayer.IsolateRoomUI IsolateRoomUIData { get; }
```

#### Property Value

**Type:** Global.CreatureLayer.IsolateRoomUI

## Methods

### AddCreature(CreatureModel)

```csharp
private void AddCreature(CreatureModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### AddEtcUnit(UnitModel)

```csharp
public EtcUnit AddEtcUnit(UnitModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.EtcUnit

### AddEventCreature(EventCreatureModel)

```csharp
private void AddEventCreature(EventCreatureModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EventCreatureModel` |  |

### AddOrdealCreature(OrdealCreatureModel)

```csharp
private void AddOrdealCreature(OrdealCreatureModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.OrdealCreatureModel` |  |

### AddSefiraBossCreature(SefiraBossCreatureModel, string)

```csharp
private void AddSefiraBossCreature(SefiraBossCreatureModel model, string animSrc)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.SefiraBossCreatureModel` |  |
| `animSrc` | `System.String` |  |

### Awake()

```csharp
private void Awake()
```
#INC
#code-generated


### ChangeCreaturePos(CreatureModel, CreatureModel)

```csharp
public void ChangeCreaturePos(CreatureModel caller, CreatureModel changed)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caller` | `Global.CreatureModel` |  |
| `changed` | `Global.CreatureModel` |  |

### Clear()

```csharp
public void Clear()
```
#INC


### ClearEventCreature()

```csharp
public void ClearEventCreature()
```
#INC


### ClearOrdealCreature()

```csharp
public void ClearOrdealCreature()
```
#INC


### ClearSefiraBossCreature()

```csharp
public void ClearSefiraBossCreature()
```
#INC


### GetCreature(long)

```csharp
public CreatureUnit GetCreature(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.CreatureUnit

### GetEtcUnit(long)

```csharp
public EtcUnit GetEtcUnit(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.EtcUnit

### Init()

```csharp
public void Init()
```
#INC


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

### OnSpriteButtonClick(bool)

```csharp
public void OnSpriteButtonClick(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### RemoveCreature(CreatureModel)

```csharp
public void RemoveCreature(CreatureModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### RemoveEtcUnit(UnitModel)

```csharp
public void RemoveEtcUnit(UnitModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |
