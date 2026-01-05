# Class CreatureManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureManager : IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Fields

### creatureListNode

```csharp
public GameObject creatureListNode
```

#### Field Value

**Type:** UnityEngine.GameObject

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `infoModel` | `Global.CreatureObserveInfoModel` |  |

### AddCreature(long, SefiraIsolate, string)

```csharp
public CreatureModel AddCreature(long metadataId, SefiraIsolate roomData, string sefiraNum)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `sefira` | `System.String` |  |

### ChangeCreaturePos(CreatureModel, CreatureModel)

```csharp
public void ChangeCreaturePos(CreatureModel caller, CreatureModel changed)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `caller` | `Global.CreatureModel` |  |
| `changed` | `Global.CreatureModel` |  |

### Clear()

```csharp
public void Clear()
```

### FindCreature(long)

```csharp
public CreatureModel FindCreature(long metaId)
```

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

#### Returns

**Type:** System.Int32

### GetCreatureList()

```csharp
public CreatureModel[] GetCreatureList()
```

#### Returns

**Type:** Global.CreatureModel[]

### GetHiddenProgressByObserveLevel()

```csharp
public int GetHiddenProgressByObserveLevel()
```

#### Returns

**Type:** System.Int32

### GetMaxHiddenProgressByObserveLevel()

```csharp
public int GetMaxHiddenProgressByObserveLevel()
```

#### Returns

**Type:** System.Int32

### GetNearSuppressedCreatures(MovableObjectNode)

```csharp
public CreatureModel[] GetNearSuppressedCreatures(MovableObjectNode node)
```

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

#### Returns

**Type:** System.Collections.Generic.List{CreatureObserveInfoModel}

### GetObserveLevel(long)

```csharp
public int GetObserveLevel(long metadataId)
```

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

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSaveObserveData()

```csharp
public Dictionary<string, object> GetSaveObserveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSaveSpecialSkillTable()

```csharp
public Dictionary<string, object> GetSaveSpecialSkillTable()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSefiraMaxWorkCount(Sefira)

```csharp
public int GetSefiraMaxWorkCount(Sefira s)
```

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

### IsCreatureActivated(long)

```csharp
public bool IsCreatureActivated(long metaId)
```

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

#### Returns

**Type:** System.Boolean

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### LoadObserveData(Dictionary<string, object>)

```csharp
public void LoadObserveData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### LoadScriptSaveData()

```csharp
public void LoadScriptSaveData()
```

### LoadSpecialSkillTable(Dictionary<string, object>)

```csharp
public void LoadSpecialSkillTable(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### OnAddCreatureWorkCountInSefira(Sefira)

```csharp
public void OnAddCreatureWorkCountInSefira(Sefira s)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `Global.Sefira` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```

### OnGameInit()

```csharp
public void OnGameInit()
```

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageEnd()

```csharp
public void OnStageEnd()
```

### OnStageRelease()

```csharp
public void OnStageRelease()
```

### OnStageStart()

```csharp
public void OnStageStart()
```

### PickOtherSefiraCreatureByRandom(CreatureModel)

```csharp
public CreatureModel PickOtherSefiraCreatureByRandom(CreatureModel exclude)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### RegisterCreature(CreatureModel)

```csharp
public void RegisterCreature(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### RemoveCreatureInSefira(CreatureModel, string)

```csharp
public void RemoveCreatureInSefira(CreatureModel creature, string sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `sefira` | `System.String` |  |

### RemoveSriptSaveData()

```csharp
public void RemoveSriptSaveData()
```

### ReplaceAllDlcCreature()

```csharp
public bool ReplaceAllDlcCreature()
```

#### Returns

**Type:** System.Boolean

### ReplaceCommand(CreatureModel, CreatureModel)

```csharp
public void ReplaceCommand(CreatureModel old, CreatureModel replaced)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `old` | `Global.CreatureModel` |  |
| `replaced` | `Global.CreatureModel` |  |

### ReplaceCreature(long, CreatureModel)

```csharp
public CreatureModel ReplaceCreature(long metadataId, CreatureModel exist)
```

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

### ResetProbReductionCounterAll()

```csharp
public void ResetProbReductionCounterAll()
```

### ResetSpecialSkillTable()

```csharp
public void ResetSpecialSkillTable()
```

### UnRegisterCreature(CreatureModel)

```csharp
public void UnRegisterCreature(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |
