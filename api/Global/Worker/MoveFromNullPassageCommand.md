---
uid: Global.MoveFromNullPassageCommand
canonical_path: /api/Global/Worker/MoveFromNullPassageCommand
---

# Class MoveFromNullPassageCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MoveFromNullPassageCommand : WorkerCommand
```

#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Misc/UnitCommand) → [WorkerCommand](/api/Global/Misc/WorkerCommand) → MoveFromNullPassageCommand

## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/Global/Misc/WorkerCommand#makemanagecreature-creaturemodel-agentmodel-skilltypeinfo-sprite), [MakeReturnCreature(CreatureModel)](/api/Global/Misc/WorkerCommand#makereturncreature-creaturemodel), [MakeSuppressCommand(UnitModel)](/api/Global/Misc/WorkerCommand#makesuppresscommand-unitmodel), [MakeMove(MapNode)](/api/Global/Misc/WorkerCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Misc/WorkerCommand#makemove-movableobjectnode), [MakePanicPursueAgent(UnitModel)](/api/Global/Misc/WorkerCommand#makepanicpursueagent-unitmodel), [MakeUnconPursueAgent(UnitModel)](/api/Global/Misc/WorkerCommand#makeunconpursueagent-unitmodel), [MakeFollowAgent(MovableObjectNode)](/api/Global/Misc/WorkerCommand#makefollowagent-movableobjectnode), [MakeOfficerSpecialAction(OfficerSpecialAction)](/api/Global/Misc/WorkerCommand#makeofficerspecialaction-officerspecialaction), [actor](/api/Global/Misc/UnitCommand#actor), [isFinished](/api/Global/Misc/UnitCommand#isfinished), [isRemoved](/api/Global/Misc/UnitCommand#isremoved), [OnInit(WorkerModel)](/api/Global/Misc/UnitCommand#oninit-workermodel), [OnInit(UnitModel)](/api/Global/Misc/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Misc/UnitCommand#oninit-standingitemmodel), [OnDestroy()](/api/Global/Misc/UnitCommand#ondestroy), [Finish()](/api/Global/Misc/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MoveFromNullPassageCommand()

```csharp
public MoveFromNullPassageCommand()
```

## Fields

### currentTargetNode

```csharp
private MapNode currentTargetNode
```
#INC


#### Field Value

**Type:** Global.MapNode

## Methods

### Execute()

```csharp
public override void Execute()
```
#INC


### OnStart()

```csharp
public override void OnStart()
```
#INC
#code-generated


### OnStop()

```csharp
public override void OnStop()
```
#INC

