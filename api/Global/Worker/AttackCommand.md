---
uid: Global.AttackCommand
canonical_path: /api/Global/Worker/AttackCommand
---

# Class AttackCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AttackCommand : WorkerCommand
```

Represents a command to an employee to suppress something.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Misc/UnitCommand) → [WorkerCommand](/api/Global/Misc/WorkerCommand) → AttackCommand

## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/Global/Misc/WorkerCommand#makemanagecreature-creaturemodel-agentmodel-skilltypeinfo-sprite), [MakeReturnCreature(CreatureModel)](/api/Global/Misc/WorkerCommand#makereturncreature-creaturemodel), [MakeSuppressCommand(UnitModel)](/api/Global/Misc/WorkerCommand#makesuppresscommand-unitmodel), [MakeMove(MapNode)](/api/Global/Misc/WorkerCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Misc/WorkerCommand#makemove-movableobjectnode), [MakePanicPursueAgent(UnitModel)](/api/Global/Misc/WorkerCommand#makepanicpursueagent-unitmodel), [MakeUnconPursueAgent(UnitModel)](/api/Global/Misc/WorkerCommand#makeunconpursueagent-unitmodel), [MakeFollowAgent(MovableObjectNode)](/api/Global/Misc/WorkerCommand#makefollowagent-movableobjectnode), [MakeOfficerSpecialAction(OfficerSpecialAction)](/api/Global/Misc/WorkerCommand#makeofficerspecialaction-officerspecialaction), [actor](/api/Global/Misc/UnitCommand#actor), [isFinished](/api/Global/Misc/UnitCommand#isfinished), [isRemoved](/api/Global/Misc/UnitCommand#isremoved), [OnInit(UnitModel)](/api/Global/Misc/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Misc/UnitCommand#oninit-standingitemmodel), [OnStop()](/api/Global/Misc/UnitCommand#onstop), [Finish()](/api/Global/Misc/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AttackCommand(UnitModel)

```csharp
public AttackCommand(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

## Fields

### damage

```csharp
private int damage
```
#INC


#### Field Value

**Type:** System.Int32

### postDelay

```csharp
private float postDelay
```
#INC


#### Field Value

**Type:** System.Single

### preDelay

```csharp
private float preDelay
```
#INC


#### Field Value

**Type:** System.Single

### range

```csharp
private float range
```
#INC


#### Field Value

**Type:** System.Single

### retreat

```csharp
private bool retreat
```
#INC


#### Field Value

**Type:** System.Boolean

### retreatDelay

```csharp
private float retreatDelay
```
#INC


#### Field Value

**Type:** System.Single

### retreatDuration

```csharp
private float retreatDuration
```
#INC


#### Field Value

**Type:** System.Single

### target

```csharp
private UnitModel target
```
#INC


#### Field Value

**Type:** Global.UnitModel

## Methods

### CheckRange()

```csharp
private bool CheckRange()
```
#INC


#### Returns

**Type:** System.Boolean

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

### OnStart()

```csharp
public override void OnStart()
```
#INC

