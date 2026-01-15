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

## Fields

### _instance

```csharp
private static AgentManager _instance
```

#### Field Value

**Type:** Global.AgentManager

### agentList

```csharp
private List<AgentModel> agentList
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentModel}

### agentListSpare

```csharp
public List<AgentModel> agentListSpare
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentModel}

### agentMaxCount

```csharp
public const int agentMaxCount = 50
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.AgentModel` |  |

### AddAgentModelCustom(AgentData)

```csharp
public AgentModel AddAgentModelCustom(AgentData genData)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### AddSpareAgentModel()

```csharp
public AgentModel AddSpareAgentModel()
```

#### Returns

**Type:** Global.AgentModel

### BuyAgent()

```csharp
public AgentModel BuyAgent()
```

#### Returns

**Type:** Global.AgentModel

### Clear()

```csharp
public void Clear()
```

### DeactivateAgent(AgentModel)

```csharp
private void DeactivateAgent(AgentModel unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.AgentModel` |  |

### DeleteAgentPermanently(ref Dictionary<string, object>, AgentModel)

```csharp
public void DeleteAgentPermanently(ref Dictionary<string, object> dic, AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `agent` | `Global.AgentModel` |  |

### DeletedContain(long)

```csharp
public bool DeletedContain(long id)
```

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

#### Returns

**Type:** System.Collections.Generic.IList{AgentModel}

### GetAgentSpareList()

```csharp
public IList<AgentModel> GetAgentSpareList()
```

#### Returns

**Type:** System.Collections.Generic.IList{AgentModel}

### GetAllAgentCount()

```csharp
public int GetAllAgentCount()
```

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

#### Returns

**Type:** Global.AgentName

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSpareAgent(long)

```csharp
public AgentModel GetSpareAgent(long id)
```

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

#### Returns

**Type:** System.Single

### HasSavedataTargetAgent(long, List<Dictionary<string, object>>, out Dictionary<string, object>)

```csharp
private bool HasSavedataTargetAgent(long id, List<Dictionary<string, object>> agentDataList, out Dictionary<string, object> agentData)
```

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

### InitValues()

```csharp
private void InitValues()
```

### LoadCustomAgentData()

```csharp
public void LoadCustomAgentData()
```

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### LoadDelAgentData()

```csharp
public void LoadDelAgentData()
```

### OnChangeAgentSefira(AgentModel, string)

```csharp
private void OnChangeAgentSefira(AgentModel agentModel, string oldSefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agentModel` | `Global.AgentModel` |  |
| `oldSefira` | `System.String` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
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

### RemoveAgent(AgentModel)

```csharp
private void RemoveAgent(AgentModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.AgentModel` |  |

### RemoveAgent(long)

```csharp
public void RemoveAgent(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### RemoveAllDlcEquipment()

```csharp
public bool RemoveAllDlcEquipment()
```

#### Returns

**Type:** System.Boolean

### RemoveCustomAgentData()

```csharp
public void RemoveCustomAgentData()
```

### RemoveDelAgentData()

```csharp
public void RemoveDelAgentData()
```

### SaveCustomAgentData()

```csharp
private void SaveCustomAgentData()
```

### SaveDelAgentData()

```csharp
private void SaveDelAgentData()
```

### TryGetValue<T>(Dictionary<string, object>, string, ref T)

```csharp
private static bool TryGetValue<T>(Dictionary<string, object> dic, string name, ref T field)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `name` | `System.String` |  |
| `field` | `{T}` |  |

#### Returns

**Type:** System.Boolean
