---
uid: Global.Sefira
canonical_path: /api/Global/Misc/Sefira
---

# Class Sefira

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Sefira
```
Represents a department.

Holds all of its [rooms](/api/Global/Model/PassageObjectModel), its [clerks](/api/Global/Worker/OfficerModel), its [agents](/api/Global/Worker/AgentModel), and its [abnormalities](/api/Global/Model/CreatureModel).

During management, it also keeps track of the escaped abnormalities in the department, the actions for clerks to take, the IDs of working and non-working agents #verify , as well as various information about the state of the department.

Generally, Central 1 does all the functions for Central 2.

## Methods
### Core
#### public void OnStageStart_first()
Initializes the department before the start of the management phase.

If there are no agents, disables the department.

Initializes the list of all rooms, the list of big rooms, the clerks, and the passages to recover health in.
Resets:
- The clerk benefit level
- Some timers #INC 
- The penalty for all agents being dead
Then updates the clerk benefit level to reflect the number of living clerks.
#### public void OnStageStart()
Called once the management phase begins.

Sets the recovery rate and whether its upgraded based on completed research, then updates the current captain.
#### public void OnFixedUpdate()
Updates the clerk benefit level, checks if all agents are dead, checks if recovery should be active, then heals employees if needed.

Slows the recovery rate if there is an abnormality in a main room, or halts if Netzach's 'Regenerator Distinguisher Modification' research has not been acquired.

Does not heal employees affected by [Queen Bee's debuff](/api/Global/UnitBuf/QueenBeeBuf) or during [Netzach's core suppression](/api/Global/Script/NetzachCoreScript).
#### public bool IsSefiraClosed()
Returns if this department is 'closed', i.e. disabled and all of its agents are dead.
#### public int GetCurrentAbilityLevel()
Return 1 if this department is opened and -1 otherwise.
#### public void LoadData(Dictionary<string, object> dic)
Sets a flag indicating if this is activated, and sets the opened level of the department.
#### public Dictionary<string, object> GetSaveData()
Creates a dictionary storing if this department is open, and its opened level.
#### public void AddOpenLevel()
Increments the opened level.
#### public void SetOpenLevel(int level)
Sets the opened level.
#### public void Activate()
Sets a flag indicating this department is open.
### Rooms and Nodes
#### public void ResetPassageData()
Resets the lists of rooms.
#### public void AddPassage(PassageObjectModel passage)
Adds a room to the department.
#### public MapNode GetDepartNodeByRandom(int index)
Gets a random node in a big room.
#### public MapNode GetRandomWayPoint()
Gets a random hallway in the department. #verify 
#### private void InitPassages()
Calls OnStageStart for every room.
#### private void InitDepartList()
Adds all of the opened big rooms to the department.
#### private void InitRecovoerPassages()
Adds all big rooms to the list of rooms to recover health in. Then, if [Netzach's core suppression](/api/Global/Misc/NetzachBossBase) is completed, adds all hallways and elevators to the list of additional health recovery rooms (these recover at a lower rate). #verify 
### Agents
#### public void AddAgent(AgentModel add)
Adds the agent to this department, if that agent isn't already added.
#### public void RemoveAgent(AgentModel unit)
Removes an agent from the department.
#### public void ClearAgent()
Clears the list of agent in this department.
#### public void ReturnAgentsToSefira()
When the recall button is clicked, notifies listeners of OnClickRecallButton and tells each agent to return to the main room.

Does not call agents:
- who are dead or panicking
- who are actively working
- who are assigned to work, if [Malkuth's core suppression](/api/Global/Misc/MalkutBossBase) is active (including day 47)

For Central 1, also tells Central 2 to do this.
#### private void UpdateAgentDeadState()
Checks if all agents are dead and applies the penalty if requires.

Skips the check if:
- This department is the active core suppression
- This is Central 2

Central 1 checks for Central 2.
#### private void ActivateAgentDeadPenalty()
Runs the penalty for all agents in a department dying.

Instructs all living clerks in the department to kill themselves, gives all abnormalities the -50% work success penalty, and disables each room (which makes them dark).

Central 1 also tells Central 2 to activate its penalty.
#### public void OnAgentReturnControll()
When an agent is no longer uncontrollable, checks and reactivates this department if there is a controllable agent. #verify 
#### public void OnAgentCannotControll(AgentModel deadAgent)
When an agent panics or otherwise becomes uncontrollable, disables this department.

If this is the last department to fall, force-enable play-speed settings and tells [Angela to yap](/api/Global/Misc/AngelaConversation). Also, sets a flag that all agents are dead and disables emergency score ticking down.
#### public bool CheckAgentControll()
Returns true if there is a controllable agent in this department and false otherwise.
#### public int GetAliveAgentCnt()
Returns the number of living agents (including panicked and uncontrollable ones).
#### public void EnterAgent(MovableObjectNode unit)
When an agent enters the department, adds them to the list of employees in this department. Central 2 adds it to Central 1.
#### public void ExitAgent(MovableObjectNode unit)
When an agent leaves the department, removes them from the list of employees in the department. Central 2 removes it from Central 1.
### Clerks
#### public void AddUnit(OfficerModel add)
Adds a clerk to the department and increments the clerk count.
#### private void AssignOfficerDept()
Assigns each officer in the facility to a department in a round-robin fashion.
#### private void InitOfficerGroup()
Spawns clerks in the department, assigns them a room #INC , and randomly distributes them around the department.
#### public void ClearOfficer()
Clears the list of clerks and sets the clerk count to 0.
#### public void ResetSpecaialAction(OfficerSpecialAction osa)
Resets the given clerk action.
#### private void UpdateOfficerAliveLevel()
Sets the department's clerk benefits level depending on the number of living clerks: 

$=$ 0% : 0
$\leq$ 40% : 1
$\leq$ 80% : 2
$>$ 80% : 3

Also, tells the [GlobalBulletManager](/api/GlobalBullet/GlobalBulletManager) to update the bullet count for Chesed's clerk benefit and [CreatureInfoWindow](/api/Global/Misc/CreatureInfoWindow) to check if Binah's clerk benefit (EGO discount) has changed.
#### public int GetOfficerAliveLevel()
Returns the clerk benefits level of this department.
#### public bool CheckOfficerControll()
Returns true if there are any clerks which aren't dead or panicked.

### Abnormalities
#### public void ClearCreature()
Clears the list of abnormalities.
#### public bool IsAnyCreatureEscaped()
Returns true if there are any breaching abnormalities. #verify 
#### public bool CheckEscapedCreature()
Returns true if there are no breaching abnormalities. #verify 
#### public void OnSuppressedCreature(CreatureModel target)
Removes the target from the list of breaching abnormalities, and sets a flag that no abnormalities are breaching.
#### public void OnEscapeCreature(CreatureModel target)
If the target isn't already in the list of breaching abnormalities, adds them, then sets a flag that there is an abnormality breaching.
#### public List\<CreatureModel> GetEscapedCreatures()
Returns the list of breaching abnormalities.
### Mostly Unused
#### public void CheckAgentStateForEmergency()
Checks the rate of dead agents to send update the emergency level; but does so incorrectly... Called, but none of this code ever does anything except to calculate the death and panic rates, and all it *would* do is call empty code.
#### private void ActivateAgentEmptyPenalty()
It's in OnFixedUpdate, but the condition can never activate for this to be called. #verify 
#### public CreatureModel GetIdleCreature()
Called by a clerk action which should never be possible.
#verify
#### public void EndCreatureWork(CreatureModel cm)
Called by a clerk action which should never be possible.
#verify
#### public MapNode GetOtherDepartNode(int index)
Called by a clerk action which should never be possible.
#verify 
#### public void OnAgentGetPanic(AgentModel panicAgent)
Empty, but called.
### Unused
###### public void SetSefiraPassage(PassageObjectModel passage)
Sets the main room to the given room.
###### public void AddDepartmentPassage(PassageObjectModel passage)
###### public MapNode[] GetDepartNodeToArray(int index)
###### private void UpdateAgentEmptyState()
###### public AgentModel[] GetAgentInSefira()
###### public OfficerSpecialAction GetRandomSpecialAction()
###### public bool IsAgentInEsacpedCreaturePassage(AgentModel checkTarget, out CreatureModel targetCreature)
###### public bool IsAgentInDeadAgentPassage(AgentModel checkTarget)
###### public int GetAliveOfficerCnt()
###### public void InitCreatureArray()


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Sefira

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Sefira(string, int, string, SefiraEnum)

```csharp
public Sefira(string name, int index, string indexString, SefiraEnum sefiraEnum)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `index` | `System.Int32` |  |
| `indexString` | `System.String` |  |
| `sefiraEnum` | `Global.SefiraEnum` |  |

## Fields

### _abilityCheckTimer

```csharp
private Timer _abilityCheckTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _activated

```csharp
private bool _activated
```
#INC


#### Field Value

**Type:** System.Boolean

### _activatedEmptyCounter

```csharp
private bool _activatedEmptyCounter
```
#INC


#### Field Value

**Type:** System.Boolean

### _agentCheckTimer

```csharp
private Timer _agentCheckTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _agentDeadCheckTimer

```csharp
private Timer _agentDeadCheckTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _agentDeadPenaltyActivated

```csharp
private bool _agentDeadPenaltyActivated
```
#INC


#### Field Value

**Type:** System.Boolean

### _agentEmptyElapsedTime

```csharp
private float _agentEmptyElapsedTime
```
#INC


#### Field Value

**Type:** System.Single

### _allocateMax

```csharp
private int _allocateMax
```
#INC


#### Field Value

**Type:** System.Int32

### _checkPassages

```csharp
private List<PassageObjectModel> _checkPassages
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

### _currentOfficerAliveLevel

```csharp
private int _currentOfficerAliveLevel
```
#INC


#### Field Value

**Type:** System.Int32

### _enteredAgentList

```csharp
private List<AgentModel> _enteredAgentList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentModel}

### _maxOfficer

```csharp
private int _maxOfficer
```
#INC


#### Field Value

**Type:** System.Int32

### _openLevel

```csharp
private int _openLevel
```
#INC


#### Field Value

**Type:** System.Int32

### _recoverAdditionalPassages

```csharp
private List<PassageObjectModel> _recoverAdditionalPassages
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

### _recoverElapsedTime

```csharp
private float _recoverElapsedTime
```
#INC


#### Field Value

**Type:** System.Single

### _recoverPassages

```csharp
private List<PassageObjectModel> _recoverPassages
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

### _recoverSpeedUp

```csharp
private bool _recoverSpeedUp
```
#INC


#### Field Value

**Type:** System.Boolean

### _recoverUpgrade

```csharp
private bool _recoverUpgrade
```
#INC


#### Field Value

**Type:** System.Boolean

### _sefiraEnum

```csharp
private SefiraEnum _sefiraEnum
```
#INC


#### Field Value

**Type:** Global.SefiraEnum

### agentDeadPenalty

```csharp
public const float agentDeadPenalty = 50
```
#INC


#### Field Value

**Type:** System.Single

### agentList

```csharp
public List<AgentModel> agentList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentModel}

### connectedPassageList

```csharp
public List<PassageObjectModel> connectedPassageList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

### creatureAry

```csharp
private CreatureModel[] creatureAry
```
#INC


#### Field Value

**Type:** Global.CreatureModel[]

### creatureList

```csharp
public List<CreatureModel> creatureList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureModel}

### deadRate

```csharp
private int deadRate
```
#INC


#### Field Value

**Type:** System.Int32

### departPassageList

```csharp
public List<PassageObjectModel> departPassageList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

### escapedCreatures

```csharp
private List<CreatureModel> escapedCreatures
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureModel}

### idleList

```csharp
private List<int> idleList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.Int32}

### index

```csharp
public int index
```
#INC


#### Field Value

**Type:** System.Int32

### indexString

```csharp
public string indexString
```
#INC


#### Field Value

**Type:** System.String

### isolateManagement

```csharp
public SefiraIsolateManagement isolateManagement
```
#INC


#### Field Value

**Type:** Global.SefiraIsolateManagement

### isRecoverActivated

```csharp
public bool isRecoverActivated
```
#INC


#### Field Value

**Type:** System.Boolean

### isWorking

```csharp
private bool[] isWorking
```
#INC


#### Field Value

**Type:** System.Boolean[]

### name

```csharp
public string name
```
#INC


#### Field Value

**Type:** System.String

### officerCnt

```csharp
private int officerCnt
```
#INC


#### Field Value

**Type:** System.Int32

### officerList

```csharp
public List<OfficerModel> officerList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{OfficerModel}

### officerSpecialAction

```csharp
public OfficerSpecialActionList officerSpecialAction
```
#INC


#### Field Value

**Type:** Global.OfficerSpecialActionList

### openedDepartmentList

```csharp
public List<PassageObjectModel> openedDepartmentList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

### OpenMax

```csharp
public const int OpenMax = 5
```
#INC


#### Field Value

**Type:** System.Int32

### OpenMin

```csharp
public const int OpenMin = 0
```
#INC


#### Field Value

**Type:** System.Int32

### panicRate

```csharp
private int panicRate
```
#INC


#### Field Value

**Type:** System.Int32

### passageList

```csharp
public List<PassageObjectModel> passageList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{PassageObjectModel}

### recoverTime

```csharp
public const float recoverTime = 10
```
#INC


#### Field Value

**Type:** System.Single

### SefiraClosed

```csharp
private bool SefiraClosed
```
#INC


#### Field Value

**Type:** System.Boolean

### sefiraPassage

```csharp
public PassageObjectModel sefiraPassage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### workingList

```csharp
private List<int> workingList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.Int32}

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

### regenerationMentalValue

```csharp
private float regenerationMentalValue { get; }
```

#### Property Value

**Type:** System.Single

### regenerationValue

```csharp
private float regenerationValue { get; }
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
#INC


### ActivateAgentDeadPanelty()

```csharp
private void ActivateAgentDeadPanelty()
```
#INC


### ActivateAgentEmptyPenalty()

```csharp
private void ActivateAgentEmptyPenalty()
```
#INC


### AddAgent(AgentModel)

```csharp
public void AddAgent(AgentModel add)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `add` | `Global.AgentModel` |  |

### AddDepartmentPassage(PassageObjectModel)

```csharp
public void AddDepartmentPassage(PassageObjectModel passage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### AddOpenLevel()

```csharp
public void AddOpenLevel()
```
#INC


### AddPassage(PassageObjectModel)

```csharp
public void AddPassage(PassageObjectModel passage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### AddUnit(OfficerModel)

```csharp
public void AddUnit(OfficerModel add)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `add` | `Global.OfficerModel` |  |

### AssignOfficerDept()

```csharp
private void AssignOfficerDept()
```
#INC


### CheckAgentControll()

```csharp
public bool CheckAgentControll()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckAgentStateForEmergency()

```csharp
public void CheckAgentStateForEmergency()
```
#INC


### CheckEscapedCreature()

```csharp
public bool CheckEscapedCreature()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckOfficerControll()

```csharp
public bool CheckOfficerControll()
```
#INC


#### Returns

**Type:** System.Boolean

### ClearAgent()

```csharp
public void ClearAgent()
```
#INC


### ClearCreature()

```csharp
public void ClearCreature()
```
#INC


### ClearOfficer()

```csharp
public void ClearOfficer()
```
#INC


### EndCreatureWork(CreatureModel)

```csharp
public void EndCreatureWork(CreatureModel cm)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cm` | `Global.CreatureModel` |  |

### EnterAgent(MovableObjectNode)

```csharp
public void EnterAgent(MovableObjectNode unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.MovableObjectNode` |  |

### ExitAgent(MovableObjectNode)

```csharp
public void ExitAgent(MovableObjectNode unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.MovableObjectNode` |  |

### GetAgentInSefira()

```csharp
public AgentModel[] GetAgentInSefira()
```
#INC


#### Returns

**Type:** Global.AgentModel[]

### GetAliveAgentCnt()

```csharp
public int GetAliveAgentCnt()
```
#INC


#### Returns

**Type:** System.Int32

### GetAliveOfficerCnt()

```csharp
public int GetAliveOfficerCnt()
```
#INC


#### Returns

**Type:** System.Int32

### GetCurrentAbilityLevel()

```csharp
public int GetCurrentAbilityLevel()
```
#INC


#### Returns

**Type:** System.Int32

### GetDepartNodeByRandom(int)

```csharp
public MapNode GetDepartNodeByRandom(int index)
```
#INC


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
#INC


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
#INC


#### Returns

**Type:** System.Collections.Generic.List{CreatureModel}

### GetIdleCreature()

```csharp
public CreatureModel GetIdleCreature()
```
#INC


#### Returns

**Type:** Global.CreatureModel

### GetOfficerAliveLevel()

```csharp
public int GetOfficerAliveLevel()
```
#INC


#### Returns

**Type:** System.Int32

### GetOtherDepartNode(int)

```csharp
public MapNode GetOtherDepartNode(int index)
```
#INC


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
#INC


#### Returns

**Type:** Global.OfficerSpecialAction

### GetRandomWayPoint()

```csharp
public MapNode GetRandomWayPoint()
```
#INC


#### Returns

**Type:** Global.MapNode

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### InitCreatureArray()

```csharp
public void InitCreatureArray()
```
#INC


### InitDepartList()

```csharp
private void InitDepartList()
```
#INC


### InitOfficerGroup()

```csharp
private void InitOfficerGroup()
```
#INC


### InitPassages()

```csharp
private void InitPassages()
```
#INC


### InitRecovoerPassages()

```csharp
private void InitRecovoerPassages()
```
#INC


### IsAgentInDeadAgentPassage(AgentModel)

```csharp
public bool IsAgentInDeadAgentPassage(AgentModel checkTarget)
```
#INC


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
#INC


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
#INC


#### Returns

**Type:** System.Boolean

### IsSefiraClosed()

```csharp
public bool IsSefiraClosed()
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

### OnAgentCannotControll(AgentModel)

```csharp
public void OnAgentCannotControll(AgentModel deadAgent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `deadAgent` | `Global.AgentModel` |  |

### OnAgentGetPanic(AgentModel)

```csharp
public void OnAgentGetPanic(AgentModel panicAgent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `panicAgent` | `Global.AgentModel` |  |

### OnAgentReturnControll()

```csharp
public void OnAgentReturnControll()
```
#INC


### OnEscapeCreature(CreatureModel)

```csharp
public void OnEscapeCreature(CreatureModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```
#INC


### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### OnStageStart_first()

```csharp
public void OnStageStart_first()
```
#INC


### OnSuppressedCreature(CreatureModel)

```csharp
public void OnSuppressedCreature(CreatureModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |

### RemoveAgent(AgentModel)

```csharp
public void RemoveAgent(AgentModel unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.AgentModel` |  |

### ResetPassageData()

```csharp
public void ResetPassageData()
```
#INC


### ResetSpecaialAction(OfficerSpecialAction)

```csharp
public void ResetSpecaialAction(OfficerSpecialAction osa)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `osa` | `Global.OfficerSpecialAction` |  |

### ReturnAgentsToSefira()

```csharp
public void ReturnAgentsToSefira()
```
#INC


### SendEmergencyScore(int, bool)

```csharp
public void SendEmergencyScore(int val, bool isAdd)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Int32` |  |
| `isAdd` | `System.Boolean` |  |

### SetOpenLevel(int)

```csharp
public void SetOpenLevel(int level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

### SetSefiraPassage(PassageObjectModel)

```csharp
public void SetSefiraPassage(PassageObjectModel passage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### UpdateAgentDeadState()

```csharp
private void UpdateAgentDeadState()
```
#INC


### UpdateAgentEmptyState()

```csharp
private void UpdateAgentEmptyState()
```
#INC


### UpdateOfficerAliveLevel()

```csharp
private void UpdateOfficerAliveLevel()
```
#INC


### UpdateSefiraAce()

```csharp
private void UpdateSefiraAce()
```
#INC

