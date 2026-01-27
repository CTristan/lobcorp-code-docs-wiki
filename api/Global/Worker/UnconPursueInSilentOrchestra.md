---
uid: Global.UnconPursueInSilentOrchestra
canonical_path: /api/Global/Worker/UnconPursueInSilentOrchestra
---

# Class UnconPursueInSilentOrchestra

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnconPursueInSilentOrchestra : WorkerCommand
```

Unused uncontrollable effect for [The Silent Orchestra](/api/Global/Misc/SilentOrchestra).
#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Misc/UnitCommand) → [WorkerCommand](/api/Global/Misc/WorkerCommand) → UnconPursueInSilentOrchestra

## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/Global/Misc/WorkerCommand#makemanagecreature-creaturemodel-agentmodel-skilltypeinfo-sprite), [MakeReturnCreature(CreatureModel)](/api/Global/Misc/WorkerCommand#makereturncreature-creaturemodel), [MakeSuppressCommand(UnitModel)](/api/Global/Misc/WorkerCommand#makesuppresscommand-unitmodel), [MakeMove(MapNode)](/api/Global/Misc/WorkerCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Misc/WorkerCommand#makemove-movableobjectnode), [MakePanicPursueAgent(UnitModel)](/api/Global/Misc/WorkerCommand#makepanicpursueagent-unitmodel), [MakeUnconPursueAgent(UnitModel)](/api/Global/Misc/WorkerCommand#makeunconpursueagent-unitmodel), [MakeFollowAgent(MovableObjectNode)](/api/Global/Misc/WorkerCommand#makefollowagent-movableobjectnode), [MakeOfficerSpecialAction(OfficerSpecialAction)](/api/Global/Misc/WorkerCommand#makeofficerspecialaction-officerspecialaction), [actor](/api/Global/Misc/UnitCommand#actor), [isFinished](/api/Global/Misc/UnitCommand#isfinished), [isRemoved](/api/Global/Misc/UnitCommand#isremoved), [OnInit(UnitModel)](/api/Global/Misc/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Misc/UnitCommand#oninit-standingitemmodel), [OnStop()](/api/Global/Misc/UnitCommand#onstop), [Finish()](/api/Global/Misc/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UnconPursueInSilentOrchestra(UnitModel, SilentOrchestra)

```csharp
public UnconPursueInSilentOrchestra(UnitModel target, SilentOrchestra orchestra)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `orchestra` | `Global.SilentOrchestra` |  |

## Fields

### attackRange

```csharp
public float attackRange
```
#INC


#### Field Value

**Type:** System.Single

### currentTarget

```csharp
private UnitModel currentTarget
```
#INC


#### Field Value

**Type:** Global.UnitModel

### miss

```csharp
private float miss
```
#INC


#### Field Value

**Type:** System.Single

### orchestra

```csharp
private SilentOrchestra orchestra
```
#INC


#### Field Value

**Type:** Global.SilentOrchestra

### randomMoveTimer

```csharp
private Timer randomMoveTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### uncon

```csharp
private Uncontrollable_SilentOrchestra uncon
```
#INC


#### Field Value

**Type:** Global.Uncontrollable_SilentOrchestra

## Properties

### workerActor

```csharp
private WorkerModel workerActor { get; }
```

#### Property Value

**Type:** Global.WorkerModel

## Methods

### CheckRange()

```csharp
private void CheckRange()
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


### OnDestroy()

```csharp
public override void OnDestroy()
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
public void OnKillTarget()
```
#INC


### OnStart()

```csharp
public override void OnStart()
```
#INC


### RandomMove()

```csharp
private void RandomMove()
```
#INC

