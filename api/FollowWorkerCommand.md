# Class FollowWorkerCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FollowWorkerCommand : WorkerCommand
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/UnitCommand) → [WorkerCommand](/api/WorkerCommand) → FollowWorkerCommand

## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/WorkerCommand#makemanagecreature-creaturemodel-agentmodel-skilltypeinfo-sprite), [MakeReturnCreature(CreatureModel)](/api/WorkerCommand#makereturncreature-creaturemodel), [MakeSuppressCommand(UnitModel)](/api/WorkerCommand#makesuppresscommand-unitmodel), [MakeMove(MapNode)](/api/WorkerCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/WorkerCommand#makemove-movableobjectnode), [MakePanicPursueAgent(UnitModel)](/api/WorkerCommand#makepanicpursueagent-unitmodel), [MakeUnconPursueAgent(UnitModel)](/api/WorkerCommand#makeunconpursueagent-unitmodel), [MakeFollowAgent(MovableObjectNode)](/api/WorkerCommand#makefollowagent-movableobjectnode), [MakeOfficerSpecialAction(OfficerSpecialAction)](/api/WorkerCommand#makeofficerspecialaction-officerspecialaction), [actor](/api/UnitCommand#actor), [isFinished](/api/UnitCommand#isfinished), [isRemoved](/api/UnitCommand#isremoved), [OnInit(UnitModel)](/api/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/UnitCommand#oninit-standingitemmodel), [OnStop()](/api/UnitCommand#onstop), [Finish()](/api/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### FollowWorkerCommand(MovableObjectNode)

```csharp
public FollowWorkerCommand(MovableObjectNode target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.MovableObjectNode` |  |

## Fields

### elapsedTime

```csharp
public float elapsedTime
```

#### Field Value

**Type:** System.Single

### targetMovable

```csharp
public MovableObjectNode targetMovable
```

#### Field Value

**Type:** Global.MovableObjectNode

## Methods

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

### OnStart()

```csharp
public override void OnStart()
```
