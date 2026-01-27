---
uid: Global.AgentManager
canonical_path: /api/Global/IOBserver/AgentManager
---

# Class AgentManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentManager : IObserver, ISerializablePlayData
```
Maintains the lists of abstract [agents](/api/Global/Worker/AgentModel), including saving, loading, adding, removing, buying, and deleting.

Also, has a helper function to calculate survival rate. Also also, has a helper function to remove backer equipment.

See also [AgentLayer](/api/Global/IOBserver/AgentLayer), which manages [AgentUnits](/api/Global/Worker/AgentUnit) in-game


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentManager

## Implements
[IObserver](/api/Global/Misc/IObserver), [ISerializablePlayData](/api/Global/Misc/ISerializablePlayData)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentManager()

```csharp
public AgentManager()
```
#INC
#code-generated


## Fields

### _instance

```csharp
private static AgentManager _instance
```
#INC


#### Field Value

**Type:** Global.AgentManager

### agentList

```csharp
private List<AgentModel> agentList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentModel}

### agentListSpare

```csharp
public List<AgentModel> agentListSpare
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentModel}

### agentMaxCount

```csharp
public const int agentMaxCount = 50
```
#INC


#### Field Value

**Type:** System.Int32

### customAgent

```csharp
public List<AgentManager.CustomizedAgentData> customAgent
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentManager.CustomizedAgentData}

### deletedAgent

```csharp
public List<AgentManager.PermanetlyDeletedAgent> deletedAgent
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentManager.PermanetlyDeletedAgent}

### nextInstId

```csharp
private int nextInstId
```
#INC


#### Field Value

**Type:** System.Int32

## Properties

### AgentDataSrc

```csharp
private string AgentDataSrc { get; }
```

#### Property Value

**Type:** System.String

### CustomAgentData

```csharp
private string CustomAgentData { get; }
```

#### Property Value

**Type:** System.String

### DeletedAgentData

```csharp
private string DeletedAgentData { get; }
```

#### Property Value

**Type:** System.String

### instance

```csharp
public static AgentManager instance { get; }
```

#### Property Value

**Type:** Global.AgentManager

## Methods

### ActivateAgent(AgentModel)

```csharp
private void ActivateAgent(AgentModel unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.AgentModel` |  |

### AddAgentModelCustom(AgentData)

```csharp
public AgentModel AddAgentModelCustom(AgentData genData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `genData` | `Customizing.AgentData` |  |

#### Returns

**Type:** Global.AgentModel

### AddCustomAgent(AgentModel)

```csharp
public AgentManager.CustomizedAgentData AddCustomAgent(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

#### Returns

**Type:** Global.AgentManager.CustomizedAgentData

### AddPermantelyDeleteAgent(AgentModel)

```csharp
public void AddPermantelyDeleteAgent(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### AddSpareAgentModel()

```csharp
public AgentModel AddSpareAgentModel()
```
#INC


#### Returns

**Type:** Global.AgentModel

### BuyAgent()

```csharp
public AgentModel BuyAgent()
```
#INC


#### Returns

**Type:** Global.AgentModel

### Clear()

```csharp
public void Clear()
```
#INC


### DeactivateAgent(AgentModel)

```csharp
private void DeactivateAgent(AgentModel unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.AgentModel` |  |

### DeleteAgentPermanently(ref Dictionary<string, object>, AgentModel)

```csharp
public void DeleteAgentPermanently(ref Dictionary<string, object> dic, AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `agent` | `Global.AgentModel` |  |

### DeletedContain(long)

```csharp
public bool DeletedContain(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean

### GetAgent(long)

```csharp
public AgentModel GetAgent(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.AgentModel

### GetAgentList()

```csharp
public IList<AgentModel> GetAgentList()
```
#INC


#### Returns

**Type:** System.Collections.Generic.IList{AgentModel}

### GetAgentSpareList()

```csharp
public IList<AgentModel> GetAgentSpareList()
```
#INC


#### Returns

**Type:** System.Collections.Generic.IList{AgentModel}

### GetAllAgentCount()

```csharp
public int GetAllAgentCount()
```
#INC


#### Returns

**Type:** System.Int32

### GetCustomAgentData(long)

```csharp
public AgentManager.CustomizedAgentData GetCustomAgentData(long instId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instId` | `System.Int64` |  |

#### Returns

**Type:** Global.AgentManager.CustomizedAgentData

### GetNearAgents(MovableObjectNode)

```csharp
public AgentModel[] GetNearAgents(MovableObjectNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.AgentModel[]

### GetRandomAgentName()

```csharp
private static AgentName GetRandomAgentName()
```
#INC


#### Returns

**Type:** Global.AgentName

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSpareAgent(long)

```csharp
public AgentModel GetSpareAgent(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.AgentModel

### GetSurvivalRate()

```csharp
public float GetSurvivalRate()
```
#INC


#### Returns

**Type:** System.Single

### HasSavedataTargetAgent(long, List<Dictionary<string, object>>, out Dictionary<string, object>)

```csharp
private bool HasSavedataTargetAgent(long id, List<Dictionary<string, object>> agentDataList, out Dictionary<string, object> agentData)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
| `agentDataList` | `System.Collections.Generic.List{System.Collections.Generic.Dictionary{System.String,System.Object}}` |  |
| `agentData` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

#### Returns

**Type:** System.Boolean

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


### LoadCustomAgentData()

```csharp
public void LoadCustomAgentData()
```
#INC


### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### LoadDelAgentData()

```csharp
public void LoadDelAgentData()
```
#INC


### OnChangeAgentSefira(AgentModel, string)

```csharp
private void OnChangeAgentSefira(AgentModel agentModel, string oldSefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agentModel` | `Global.AgentModel` |  |
| `oldSefira` | `System.String` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
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


### RemoveAgent(AgentModel)

```csharp
private void RemoveAgent(AgentModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.AgentModel` |  |

### RemoveAgent(long)

```csharp
public void RemoveAgent(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### RemoveAllDlcEquipment()

```csharp
public bool RemoveAllDlcEquipment()
```
#INC


#### Returns

**Type:** System.Boolean

### RemoveCustomAgentData()

```csharp
public void RemoveCustomAgentData()
```
#INC


### RemoveDelAgentData()

```csharp
public void RemoveDelAgentData()
```
#INC


### SaveCustomAgentData()

```csharp
private void SaveCustomAgentData()
```
#INC


### SaveDelAgentData()

```csharp
private void SaveDelAgentData()
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
