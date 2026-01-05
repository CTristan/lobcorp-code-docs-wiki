# Class UnconAuthorNoteAttackCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnconAuthorNoteAttackCommand : WorkerCommand
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/UnitCommand) → [WorkerCommand](/api/WorkerCommand) → UnconAuthorNoteAttackCommand

## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/WorkerCommand#makemanagecreature-creaturemodel-agentmodel-skilltypeinfo-sprite), [MakeReturnCreature(CreatureModel)](/api/WorkerCommand#makereturncreature-creaturemodel), [MakeSuppressCommand(UnitModel)](/api/WorkerCommand#makesuppresscommand-unitmodel), [MakeMove(MapNode)](/api/WorkerCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/WorkerCommand#makemove-movableobjectnode), [MakePanicPursueAgent(UnitModel)](/api/WorkerCommand#makepanicpursueagent-unitmodel), [MakeUnconPursueAgent(UnitModel)](/api/WorkerCommand#makeunconpursueagent-unitmodel), [MakeFollowAgent(MovableObjectNode)](/api/WorkerCommand#makefollowagent-movableobjectnode), [MakeOfficerSpecialAction(OfficerSpecialAction)](/api/WorkerCommand#makeofficerspecialaction-officerspecialaction), [actor](/api/UnitCommand#actor), [isFinished](/api/UnitCommand#isfinished), [isRemoved](/api/UnitCommand#isremoved), [OnInit(UnitModel)](/api/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/UnitCommand#oninit-standingitemmodel), [OnDestroy()](/api/UnitCommand#ondestroy), [Finish()](/api/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### UnconAuthorNoteAttackCommand(AuthorNote, WorkerModel)

```csharp
public UnconAuthorNoteAttackCommand(AuthorNote note, WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `note` | `Global.AuthorNote` |  |
| `target` | `Global.WorkerModel` |  |

## Fields

### elapsedTime

```csharp
public float elapsedTime
```

#### Field Value

**Type:** System.Single

### missTargetTime

```csharp
public float missTargetTime
```

#### Field Value

**Type:** System.Single

## Methods

### Execute()

```csharp
public override void Execute()
```

### GiveDamage()

```csharp
public void GiveDamage()
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

### OnStop()

```csharp
public override void OnStop()
```
