# Class ManageCreatureAgentCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ManageCreatureAgentCommand : WorkerCommand
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/UnitCommand) → [WorkerCommand](/api/WorkerCommand) → ManageCreatureAgentCommand

## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/WorkerCommand#makemanagecreature-creaturemodel-agentmodel-skilltypeinfo-sprite), [MakeReturnCreature(CreatureModel)](/api/WorkerCommand#makereturncreature-creaturemodel), [MakeSuppressCommand(UnitModel)](/api/WorkerCommand#makesuppresscommand-unitmodel), [MakeMove(MapNode)](/api/WorkerCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/WorkerCommand#makemove-movableobjectnode), [MakePanicPursueAgent(UnitModel)](/api/WorkerCommand#makepanicpursueagent-unitmodel), [MakeUnconPursueAgent(UnitModel)](/api/WorkerCommand#makeunconpursueagent-unitmodel), [MakeFollowAgent(MovableObjectNode)](/api/WorkerCommand#makefollowagent-movableobjectnode), [MakeOfficerSpecialAction(OfficerSpecialAction)](/api/WorkerCommand#makeofficerspecialaction-officerspecialaction), [actor](/api/UnitCommand#actor), [isFinished](/api/UnitCommand#isfinished), [isRemoved](/api/UnitCommand#isremoved), [OnInit(UnitModel)](/api/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/UnitCommand#oninit-standingitemmodel), [OnStart()](/api/UnitCommand#onstart), [OnStop()](/api/UnitCommand#onstop), [Finish()](/api/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ManageCreatureAgentCommand(CreatureModel, AgentModel, SkillTypeInfo, Sprite)

```csharp
public ManageCreatureAgentCommand(CreatureModel targetCreature, AgentModel self, SkillTypeInfo skill, Sprite skillSprite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetCreature` | `Global.CreatureModel` |  |
| `self` | `Global.AgentModel` |  |
| `skill` | `Global.SkillTypeInfo` |  |
| `skillSprite` | `UnityEngine.Sprite` |  |

### ManageCreatureAgentCommand(CreatureModel, AgentModel[], SkillTypeInfo)

```csharp
public ManageCreatureAgentCommand(CreatureModel targetCreature, AgentModel[] coopAgents, SkillTypeInfo skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetCreature` | `Global.CreatureModel` |  |
| `coopAgents` | `Global.AgentModel[]` |  |
| `skill` | `Global.SkillTypeInfo` |  |

## Methods

### Cancle()

```csharp
public void Cancle()
```

### Execute()

```csharp
public override void Execute()
```

### OnDestroy()

```csharp
public override void OnDestroy()
```

### OnInit(WorkerModel)

```csharp
public override void OnInit(WorkerModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.WorkerModel` |  |
