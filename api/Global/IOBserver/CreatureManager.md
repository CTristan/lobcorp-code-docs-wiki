---
uid: Global.CreatureManager
canonical_path: /api/Global/IOBserver/CreatureManager
---

# Class CreatureManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureManager : IObserver, ISerializablePlayData
```

Manages all abnormalities currently in the facility.

Controls adding, moving, and removing creatures in departments; loading, saving, resetting, and getting observation levels; calculating how complete the codex is; calling creatures during stage start, release, end, fixed update, and initialization; loading abnormality script data; resetting overload penalties for WAWs and ALEPHs; and a few other utilities.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureManager

## Implements
[IObserver](/api/Global/Misc/IObserver), [ISerializablePlayData](/api/Global/Misc/ISerializablePlayData)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureManager()

```csharp
private CreatureManager()
```
#INC
#code-generated


## Fields

### _instance

```csharp
private static CreatureManager _instance
```
#INC


#### Field Value

**Type:** Global.CreatureManager

### creatureList

```csharp
private List<CreatureModel> creatureList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureModel}

### creatureListNode

```csharp
public GameObject creatureListNode
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### nextInstId

```csharp
private long nextInstId
```
#INC


#### Field Value

**Type:** System.Int64

### observeInfoList

```csharp
private Dictionary<long, CreatureObserveInfoModel> observeInfoList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int64,CreatureObserveInfoModel}

### specialSkillTable

```csharp
private Dictionary<long, CreatureSpecialSkillTipTable> specialSkillTable
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int64,CreatureSpecialSkillTipTable}

## Properties

### instance

```csharp
public static CreatureManager instance { get; }
```

#### Property Value

**Type:** Global.CreatureManager

## Methods

### AddChildObserveInfo(CreatureObserveInfoModel)

```csharp
public void AddChildObserveInfo(CreatureObserveInfoModel infoModel)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `infoModel` | `Global.CreatureObserveInfoModel` |  |

### AddCreature(long, SefiraIsolate, string)

```csharp
public CreatureModel AddCreature(long metadataId, SefiraIsolate roomData, string sefiraNum)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metadataId` | `System.Int64` |  |
| `roomData` | `Global.SefiraIsolate` |  |
| `sefiraNum` | `System.String` |  |

#### Returns

**Type:** Global.CreatureModel

### AddCreatureInSefira(CreatureModel, string)

```csharp
public void AddCreatureInSefira(CreatureModel creature, string sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `sefira` | `System.String` |  |

### BuildCreatureModel(CreatureModel, long, SefiraIsolate, string)

```csharp
private void BuildCreatureModel(CreatureModel model, long metadataId, SefiraIsolate roomData, string sefiraNum)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |
| `metadataId` | `System.Int64` |  |
| `roomData` | `Global.SefiraIsolate` |  |
| `sefiraNum` | `System.String` |  |

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


### FindCreature(long)

```csharp
public CreatureModel FindCreature(long metaId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metaId` | `System.Int64` |  |

#### Returns

**Type:** Global.CreatureModel

### GetCreature(long)

```csharp
public CreatureModel GetCreature(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.CreatureModel

### GetCreatureCount()

```csharp
public int GetCreatureCount()
```
#INC


#### Returns

**Type:** System.Int32

### GetCreatureList()

```csharp
public CreatureModel[] GetCreatureList()
```
#INC


#### Returns

**Type:** Global.CreatureModel[]

### GetHiddenProgressByObserveLevel()

```csharp
public int GetHiddenProgressByObserveLevel()
```
#INC


#### Returns

**Type:** System.Int32

### GetMaxHiddenProgressByObserveLevel()

```csharp
public int GetMaxHiddenProgressByObserveLevel()
```
#INC


#### Returns

**Type:** System.Int32

### GetNearSuppressedCreatures(MovableObjectNode)

```csharp
public CreatureModel[] GetNearSuppressedCreatures(MovableObjectNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.CreatureModel[]

### GetObserveInfo(long)

```csharp
public CreatureObserveInfoModel GetObserveInfo(long metadataId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metadataId` | `System.Int64` |  |

#### Returns

**Type:** Global.CreatureObserveInfoModel

### GetObserveInfoList()

```csharp
public List<CreatureObserveInfoModel> GetObserveInfoList()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{CreatureObserveInfoModel}

### GetObserveLevel(long)

```csharp
public int GetObserveLevel(long metadataId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metadataId` | `System.Int64` |  |

#### Returns

**Type:** System.Int32

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSaveObserveData()

```csharp
public Dictionary<string, object> GetSaveObserveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSaveSpecialSkillTable()

```csharp
public Dictionary<string, object> GetSaveSpecialSkillTable()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSefiraMaxWorkCount(Sefira)

```csharp
public int GetSefiraMaxWorkCount(Sefira s)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `Global.Sefira` |  |

#### Returns

**Type:** System.Int32

### GetSefiraWorkCount(Sefira)

```csharp
public int GetSefiraWorkCount(Sefira s)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `Global.Sefira` |  |

#### Returns

**Type:** System.Int32

### Init()

```csharp
public void Init()
```
#INC


### InitValues()

```csharp
private void InitValues()
```
#INC


### IsCreatureActivated(long)

```csharp
public bool IsCreatureActivated(long metaId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metaId` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean

### IsMaxHiddenProgress()

```csharp
public bool IsMaxHiddenProgress()
```
#INC


#### Returns

**Type:** System.Boolean

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### LoadObserveData(Dictionary<string, object>)

```csharp
public void LoadObserveData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### LoadScriptSaveData()

```csharp
public void LoadScriptSaveData()
```
#INC


### LoadSpecialSkillTable(Dictionary<string, object>)

```csharp
public void LoadSpecialSkillTable(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### OnAddCreatureWorkCountInSefira(Sefira)

```csharp
public void OnAddCreatureWorkCountInSefira(Sefira s)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `Global.Sefira` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```
#INC


### OnGameInit()

```csharp
public void OnGameInit()
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

### OnStageEnd()

```csharp
public void OnStageEnd()
```
#INC


### OnStageRelease()

```csharp
public void OnStageRelease()
```
#INC


### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### PickOtherSefiraCreatureByRandom(CreatureModel)

```csharp
public CreatureModel PickOtherSefiraCreatureByRandom(CreatureModel exclude)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `exclude` | `Global.CreatureModel` |  |

#### Returns

**Type:** Global.CreatureModel

### RegisterByReplace(CreatureModel)

```csharp
public void RegisterByReplace(CreatureModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### RegisterCreature(CreatureModel)

```csharp
public void RegisterCreature(CreatureModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### RemoveCreatureInSefira(CreatureModel, string)

```csharp
public void RemoveCreatureInSefira(CreatureModel creature, string sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `sefira` | `System.String` |  |

### RemoveSriptSaveData()

```csharp
public void RemoveSriptSaveData()
```
#INC


### ReplaceAllDlcCreature()

```csharp
public bool ReplaceAllDlcCreature()
```
#INC


#### Returns

**Type:** System.Boolean

### ReplaceBuildCreatureModel(CreatureModel, long, CreatureModel)

```csharp
private void ReplaceBuildCreatureModel(CreatureModel model, long metadataId, CreatureModel old)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |
| `metadataId` | `System.Int64` |  |
| `old` | `Global.CreatureModel` |  |

### ReplaceCommand(CreatureModel, CreatureModel)

```csharp
public void ReplaceCommand(CreatureModel old, CreatureModel replaced)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `old` | `Global.CreatureModel` |  |
| `replaced` | `Global.CreatureModel` |  |

### ReplaceCreature(long, CreatureModel)

```csharp
public CreatureModel ReplaceCreature(long metadataId, CreatureModel exist)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metadataId` | `System.Int64` |  |
| `exist` | `Global.CreatureModel` |  |

#### Returns

**Type:** Global.CreatureModel

### ResetObserveData()

```csharp
public void ResetObserveData()
```
#INC


### ResetProbReductionCounterAll()

```csharp
public void ResetProbReductionCounterAll()
```
#INC


### ResetSpecialSkillTable()

```csharp
public void ResetSpecialSkillTable()
```
#INC


### TryGetValue<T>(Dictionary<string, object>, string, ref T)

```csharp
private static bool TryGetValue<T>(Dictionary<string, object> dic, string name, ref T field)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `name` | `System.String` |  |
| `field` | `{T}` |  |

#### Returns

**Type:** System.Boolean

### UnRegisterCreature(CreatureModel)

```csharp
public void UnRegisterCreature(CreatureModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |
