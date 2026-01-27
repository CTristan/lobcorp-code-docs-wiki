---
uid: Global.UnconAuthorNoteAttackCommand
canonical_path: /api/Global/Worker/UnconAuthorNoteAttackCommand
---

# Class UnconAuthorNoteAttackCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnconAuthorNoteAttackCommand : WorkerCommand, WorkerAttackCommand
```
#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Misc/UnitCommand) → [WorkerCommand](/api/Global/Misc/WorkerCommand) → UnconAuthorNoteAttackCommand

## Implements
[WorkerAttackCommand](/api/Global/Misc/WorkerAttackCommand)

## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/Global/Misc/WorkerCommand#makemanagecreature-creaturemodel-agentmodel-skilltypeinfo-sprite), [MakeReturnCreature(CreatureModel)](/api/Global/Misc/WorkerCommand#makereturncreature-creaturemodel), [MakeSuppressCommand(UnitModel)](/api/Global/Misc/WorkerCommand#makesuppresscommand-unitmodel), [MakeMove(MapNode)](/api/Global/Misc/WorkerCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Misc/WorkerCommand#makemove-movableobjectnode), [MakePanicPursueAgent(UnitModel)](/api/Global/Misc/WorkerCommand#makepanicpursueagent-unitmodel), [MakeUnconPursueAgent(UnitModel)](/api/Global/Misc/WorkerCommand#makeunconpursueagent-unitmodel), [MakeFollowAgent(MovableObjectNode)](/api/Global/Misc/WorkerCommand#makefollowagent-movableobjectnode), [MakeOfficerSpecialAction(OfficerSpecialAction)](/api/Global/Misc/WorkerCommand#makeofficerspecialaction-officerspecialaction), [actor](/api/Global/Misc/UnitCommand#actor), [isFinished](/api/Global/Misc/UnitCommand#isfinished), [isRemoved](/api/Global/Misc/UnitCommand#isremoved), [OnInit(UnitModel)](/api/Global/Misc/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Misc/UnitCommand#oninit-standingitemmodel), [OnDestroy()](/api/Global/Misc/UnitCommand#ondestroy), [Finish()](/api/Global/Misc/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UnconAuthorNoteAttackCommand(AuthorNote, WorkerModel)

```csharp
public UnconAuthorNoteAttackCommand(AuthorNote note, WorkerModel target)
```
#INC


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
#INC


#### Field Value

**Type:** System.Single

### missTargetTime

```csharp
public float missTargetTime
```
#INC


#### Field Value

**Type:** System.Single

### note

```csharp
private AuthorNote note
```
#INC


#### Field Value

**Type:** Global.AuthorNote

### range

```csharp
private float range
```
#INC


#### Field Value

**Type:** System.Single

### target

```csharp
private WorkerModel target
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### workerActor

```csharp
private WorkerModel workerActor
```
#INC


#### Field Value

**Type:** Global.WorkerModel

## Methods

### CheckRanage()

```csharp
private void CheckRanage()
```
#INC


### Execute()

```csharp
public override void Execute()
```
#INC


### GiveDamage()

```csharp
public void GiveDamage()
```
#INC


### OnInit(WorkerModel)

```csharp
public override void OnInit(WorkerModel agent)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.WorkerModel` |  |

### OnKillTarget()

```csharp
private void OnKillTarget()
```
#INC


### OnStart()

```csharp
public override void OnStart()
```
#INC


### OnStop()

```csharp
public override void OnStop()
```
#INC

