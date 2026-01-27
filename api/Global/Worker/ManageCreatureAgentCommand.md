---
uid: Global.ManageCreatureAgentCommand
canonical_path: /api/Global/Worker/ManageCreatureAgentCommand
---

# Class ManageCreatureAgentCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ManageCreatureAgentCommand : WorkerCommand
```

Commands an [agent](/api/Global/Worker/AgentUnit) to attack a target creature.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Misc/UnitCommand) → [WorkerCommand](/api/Global/Misc/WorkerCommand) → ManageCreatureAgentCommand

## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/Global/Misc/WorkerCommand#makemanagecreature-creaturemodel-agentmodel-skilltypeinfo-sprite), [MakeReturnCreature(CreatureModel)](/api/Global/Misc/WorkerCommand#makereturncreature-creaturemodel), [MakeSuppressCommand(UnitModel)](/api/Global/Misc/WorkerCommand#makesuppresscommand-unitmodel), [MakeMove(MapNode)](/api/Global/Misc/WorkerCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Misc/WorkerCommand#makemove-movableobjectnode), [MakePanicPursueAgent(UnitModel)](/api/Global/Misc/WorkerCommand#makepanicpursueagent-unitmodel), [MakeUnconPursueAgent(UnitModel)](/api/Global/Misc/WorkerCommand#makeunconpursueagent-unitmodel), [MakeFollowAgent(MovableObjectNode)](/api/Global/Misc/WorkerCommand#makefollowagent-movableobjectnode), [MakeOfficerSpecialAction(OfficerSpecialAction)](/api/Global/Misc/WorkerCommand#makeofficerspecialaction-officerspecialaction), [actor](/api/Global/Misc/UnitCommand#actor), [isFinished](/api/Global/Misc/UnitCommand#isfinished), [isRemoved](/api/Global/Misc/UnitCommand#isremoved), [OnInit(UnitModel)](/api/Global/Misc/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Misc/UnitCommand#oninit-standingitemmodel), [OnStart()](/api/Global/Misc/UnitCommand#onstart), [OnStop()](/api/Global/Misc/UnitCommand#onstop), [Finish()](/api/Global/Misc/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ManageCreatureAgentCommand(CreatureModel, AgentModel, SkillTypeInfo, Sprite)

```csharp
public ManageCreatureAgentCommand(CreatureModel targetCreature, AgentModel self, SkillTypeInfo skill, Sprite skillSprite)
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetCreature` | `Global.CreatureModel` |  |
| `coopAgents` | `Global.AgentModel[]` |  |
| `skill` | `Global.SkillTypeInfo` |  |

## Fields

### coopAgents

```csharp
private AgentModel[] coopAgents
```
#INC


#### Field Value

**Type:** Global.AgentModel[]

### skill

```csharp
private SkillTypeInfo skill
```
#INC


#### Field Value

**Type:** Global.SkillTypeInfo

### skillSprite

```csharp
private Sprite skillSprite
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### targetCreature

```csharp
private CreatureModel targetCreature
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### useSkill

```csharp
private UseSkill useSkill
```
#INC


#### Field Value

**Type:** Global.UseSkill

### waiting

```csharp
private bool waiting
```
#INC


#### Field Value

**Type:** System.Boolean

## Methods

### Cancle()

```csharp
public void Cancle()
```
#INC


### CheckStarting(AgentModel)

```csharp
private void CheckStarting(AgentModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### Execute()

```csharp
public override void Execute()
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
