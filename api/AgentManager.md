# Class AgentManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentManager : IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AgentManager()

```csharp
public AgentManager()
```

## Fields

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

## Properties

### instance

```csharp
public static AgentManager instance { get; }
```

#### Property Value

**Type:** Global.AgentManager

## Methods

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

### Init()

```csharp
public void Init()
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
