# Class Sefira

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Sefira
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Sefira

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Sefira(string, int, string, SefiraEnum)

```csharp
public Sefira(string name, int index, string indexString, SefiraEnum sefiraEnum)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `index` | `System.Int32` |  |
| `indexString` | `System.String` |  |
| `sefiraEnum` | `Global.SefiraEnum` |  |

## Fields

### agentDeadPenalty

```csharp
public const float agentDeadPenalty = 50
```

#### Field Value

**Type:** System.Single

### agentList

```csharp
public List<AgentModel> agentList
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentModel}

### connectedPassageList

```csharp
public List<PassageObjectModel> connectedPassageList
```

#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

### creatureList

```csharp
public List<CreatureModel> creatureList
```

#### Field Value

**Type:** System.Collections.Generic.List{CreatureModel}

### departPassageList

```csharp
public List<PassageObjectModel> departPassageList
```

#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

### index

```csharp
public int index
```

#### Field Value

**Type:** System.Int32

### indexString

```csharp
public string indexString
```

#### Field Value

**Type:** System.String

### isolateManagement

```csharp
public SefiraIsolateManagement isolateManagement
```

#### Field Value

**Type:** Global.SefiraIsolateManagement

### isRecoverActivated

```csharp
public bool isRecoverActivated
```

#### Field Value

**Type:** System.Boolean

### name

```csharp
public string name
```

#### Field Value

**Type:** System.String

### officerList

```csharp
public List<OfficerModel> officerList
```

#### Field Value

**Type:** System.Collections.Generic.List{OfficerModel}

### officerSpecialAction

```csharp
public OfficerSpecialActionList officerSpecialAction
```

#### Field Value

**Type:** Global.OfficerSpecialActionList

### openedDepartmentList

```csharp
public List<PassageObjectModel> openedDepartmentList
```

#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

### OpenMax

```csharp
public const int OpenMax = 5
```

#### Field Value

**Type:** System.Int32

### OpenMin

```csharp
public const int OpenMin = 0
```

#### Field Value

**Type:** System.Int32

### passageList

```csharp
public List<PassageObjectModel> passageList
```

#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

### recoverTime

```csharp
public const float recoverTime = 10
```

#### Field Value

**Type:** System.Single

### sefiraPassage

```csharp
public PassageObjectModel sefiraPassage
```

#### Field Value

**Type:** Global.PassageObjectModel

## Properties

### activated

```csharp
public bool activated { get; }
```

#### Property Value

**Type:** System.Boolean

### activatedEmptyCounter

```csharp
public bool activatedEmptyCounter { get; }
```

#### Property Value

**Type:** System.Boolean

### agentDeadPenaltyActivated

```csharp
public bool agentDeadPenaltyActivated { get; }
```

#### Property Value

**Type:** System.Boolean

### agentEmptyElapsedTime

```csharp
public float agentEmptyElapsedTime { get; }
```

#### Property Value

**Type:** System.Single

### allocateMax

```csharp
public int allocateMax { get; }
```

#### Property Value

**Type:** System.Int32

### openLevel

```csharp
public int openLevel { get; }
```

#### Property Value

**Type:** System.Int32

### recoverElapsedTime

```csharp
public float recoverElapsedTime { get; }
```

#### Property Value

**Type:** System.Single

### sefiraEnum

```csharp
public SefiraEnum sefiraEnum { get; }
```

#### Property Value

**Type:** Global.SefiraEnum

## Methods

### Activate()

```csharp
public void Activate()
```

### AddAgent(AgentModel)

```csharp
public void AddAgent(AgentModel add)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `add` | `Global.AgentModel` |  |

### AddDepartmentPassage(PassageObjectModel)

```csharp
public void AddDepartmentPassage(PassageObjectModel passage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### AddOpenLevel()

```csharp
public void AddOpenLevel()
```

### AddPassage(PassageObjectModel)

```csharp
public void AddPassage(PassageObjectModel passage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### AddUnit(OfficerModel)

```csharp
public void AddUnit(OfficerModel add)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `add` | `Global.OfficerModel` |  |

### CheckAgentControll()

```csharp
public bool CheckAgentControll()
```

#### Returns

**Type:** System.Boolean

### CheckAgentStateForEmergency()

```csharp
public void CheckAgentStateForEmergency()
```

### CheckEscapedCreature()

```csharp
public bool CheckEscapedCreature()
```

#### Returns

**Type:** System.Boolean

### CheckOfficerControll()

```csharp
public bool CheckOfficerControll()
```

#### Returns

**Type:** System.Boolean

### ClearAgent()

```csharp
public void ClearAgent()
```

### ClearCreature()

```csharp
public void ClearCreature()
```

### ClearOfficer()

```csharp
public void ClearOfficer()
```

### EndCreatureWork(CreatureModel)

```csharp
public void EndCreatureWork(CreatureModel cm)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cm` | `Global.CreatureModel` |  |

### EnterAgent(MovableObjectNode)

```csharp
public void EnterAgent(MovableObjectNode unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.MovableObjectNode` |  |

### ExitAgent(MovableObjectNode)

```csharp
public void ExitAgent(MovableObjectNode unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.MovableObjectNode` |  |

### GetAgentInSefira()

```csharp
public AgentModel[] GetAgentInSefira()
```

#### Returns

**Type:** Global.AgentModel[]

### GetAliveAgentCnt()

```csharp
public int GetAliveAgentCnt()
```

#### Returns

**Type:** System.Int32

### GetAliveOfficerCnt()

```csharp
public int GetAliveOfficerCnt()
```

#### Returns

**Type:** System.Int32

### GetCurrentAbilityLevel()

```csharp
public int GetCurrentAbilityLevel()
```

#### Returns

**Type:** System.Int32

### GetDepartNodeByRandom(int)

```csharp
public MapNode GetDepartNodeByRandom(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.MapNode

### GetDepartNodeToArray(int)

```csharp
public MapNode[] GetDepartNodeToArray(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.MapNode[]

### GetEscapedCreatures()

```csharp
public List<CreatureModel> GetEscapedCreatures()
```

#### Returns

**Type:** System.Collections.Generic.List{CreatureModel}

### GetIdleCreature()

```csharp
public CreatureModel GetIdleCreature()
```

#### Returns

**Type:** Global.CreatureModel

### GetOfficerAliveLevel()

```csharp
public int GetOfficerAliveLevel()
```

#### Returns

**Type:** System.Int32

### GetOtherDepartNode(int)

```csharp
public MapNode GetOtherDepartNode(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.MapNode

### GetRandomSpecialAction()

```csharp
public OfficerSpecialAction GetRandomSpecialAction()
```

#### Returns

**Type:** Global.OfficerSpecialAction

### GetRandomWayPoint()

```csharp
public MapNode GetRandomWayPoint()
```

#### Returns

**Type:** Global.MapNode

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### InitCreatureArray()

```csharp
public void InitCreatureArray()
```

### IsAgentInDeadAgentPassage(AgentModel)

```csharp
public bool IsAgentInDeadAgentPassage(AgentModel checkTarget)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `checkTarget` | `Global.AgentModel` |  |

#### Returns

**Type:** System.Boolean

### IsAgentInEsacpedCreaturePassage(AgentModel, out CreatureModel)

```csharp
public bool IsAgentInEsacpedCreaturePassage(AgentModel checkTarget, out CreatureModel targetCreature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `checkTarget` | `Global.AgentModel` |  |
| `targetCreature` | `Global.CreatureModel` |  |

#### Returns

**Type:** System.Boolean

### IsAnyCreatureEscaped()

```csharp
public bool IsAnyCreatureEscaped()
```

#### Returns

**Type:** System.Boolean

### IsSefiraClosed()

```csharp
public bool IsSefiraClosed()
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

### OnAgentCannotControll(AgentModel)

```csharp
public void OnAgentCannotControll(AgentModel deadAgent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `deadAgent` | `Global.AgentModel` |  |

### OnAgentGetPanic(AgentModel)

```csharp
public void OnAgentGetPanic(AgentModel panicAgent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `panicAgent` | `Global.AgentModel` |  |

### OnAgentReturnControll()

```csharp
public void OnAgentReturnControll()
```

### OnEscapeCreature(CreatureModel)

```csharp
public void OnEscapeCreature(CreatureModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```

### OnStageStart()

```csharp
public void OnStageStart()
```

### OnStageStart_first()

```csharp
public void OnStageStart_first()
```

### OnSuppressedCreature(CreatureModel)

```csharp
public void OnSuppressedCreature(CreatureModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |

### RemoveAgent(AgentModel)

```csharp
public void RemoveAgent(AgentModel unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.AgentModel` |  |

### ResetPassageData()

```csharp
public void ResetPassageData()
```

### ResetSpecaialAction(OfficerSpecialAction)

```csharp
public void ResetSpecaialAction(OfficerSpecialAction osa)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `osa` | `Global.OfficerSpecialAction` |  |

### ReturnAgentsToSefira()

```csharp
public void ReturnAgentsToSefira()
```

### SendEmergencyScore(int, bool)

```csharp
public void SendEmergencyScore(int val, bool isAdd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Int32` |  |
| `isAdd` | `System.Boolean` |  |

### SetOpenLevel(int)

```csharp
public void SetOpenLevel(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### SetSefiraPassage(PassageObjectModel)

```csharp
public void SetSefiraPassage(PassageObjectModel passage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |
