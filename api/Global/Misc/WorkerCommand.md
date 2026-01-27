---
uid: Global.WorkerCommand
canonical_path: /api/Global/Misc/WorkerCommand
---

# Class WorkerCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerCommand : UnitCommand
```

Parent class for commands to employees, which are instructions to change their current behaviour.

Holds many static commands.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Misc/UnitCommand) → WorkerCommand

## Derived
[AttackCommand](/api/Global/Worker/AttackCommand), [AttackOfficerCommand](/api/Global/Worker/AttackOfficerCommand), [FollowWorkerCommand](/api/Global/Worker/FollowWorkerCommand), [ManageCreatureAgentCommand](/api/Global/Worker/ManageCreatureAgentCommand), [MoveFromNullPassageCommand](/api/Global/Worker/MoveFromNullPassageCommand), [MoveWorkerCommand](/api/Global/Worker/MoveWorkerCommand), [PanicPursueWorkerCommand](/api/Global/Worker/PanicPursueWorkerCommand), [ReturnCreatureWorkerCommand](/api/Global/Worker/ReturnCreatureWorkerCommand), [ReturnKitCreatureCommand](/api/Global/Worker/ReturnKitCreatureCommand), [SingingMachineAttackCommand](/api/Global/Worker/SingingMachineAttackCommand), [SpecialActionOfficerCommand](/api/Global/Worker/SpecialActionOfficerCommand), [SuppressWorkerCommand](/api/Global/Worker/SuppressWorkerCommand), [UnconAuthorNoteAttackCommand](/api/Global/Worker/UnconAuthorNoteAttackCommand), [UnconPursueInSilentOrchestra](/api/Global/Worker/UnconPursueInSilentOrchestra), [UnconPursueWorkerCommand](/api/Global/Worker/UnconPursueWorkerCommand)

## Inherited Members
[actor](/api/Global/Misc/UnitCommand#actor), [isFinished](/api/Global/Misc/UnitCommand#isfinished), [isRemoved](/api/Global/Misc/UnitCommand#isremoved), [OnInit(WorkerModel)](/api/Global/Misc/UnitCommand#oninit-workermodel), [OnInit(UnitModel)](/api/Global/Misc/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Misc/UnitCommand#oninit-standingitemmodel), [OnStart()](/api/Global/Misc/UnitCommand#onstart), [Execute()](/api/Global/Misc/UnitCommand#execute), [OnStop()](/api/Global/Misc/UnitCommand#onstop), [OnDestroy()](/api/Global/Misc/UnitCommand#ondestroy), [Finish()](/api/Global/Misc/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerCommand()

```csharp
public WorkerCommand()
```

## Methods

### MakeFollowAgent(MovableObjectNode)

```csharp
public static WorkerCommand MakeFollowAgent(MovableObjectNode targetNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.WorkerCommand

### MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)

```csharp
public static WorkerCommand MakeManageCreature(CreatureModel targetCreature, AgentModel agent, SkillTypeInfo skill, Sprite skillSprite)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetCreature` | `Global.CreatureModel` |  |
| `agent` | `Global.AgentModel` |  |
| `skill` | `Global.SkillTypeInfo` |  |
| `skillSprite` | `UnityEngine.Sprite` |  |

#### Returns

**Type:** Global.WorkerCommand

### MakeMove(MapNode)

```csharp
public static WorkerCommand MakeMove(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** Global.WorkerCommand

### MakeMove(MovableObjectNode)

```csharp
public static WorkerCommand MakeMove(MovableObjectNode movable)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `movable` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.WorkerCommand

### MakeOfficerSpecialAction(OfficerSpecialAction)

```csharp
public static WorkerCommand MakeOfficerSpecialAction(OfficerSpecialAction action)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `Global.OfficerSpecialAction` |  |

#### Returns

**Type:** Global.WorkerCommand

### MakePanicPursueAgent(UnitModel)

```csharp
public static WorkerCommand MakePanicPursueAgent(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.WorkerCommand

### MakeReturnCreature(CreatureModel)

```csharp
public static WorkerCommand MakeReturnCreature(CreatureModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |

#### Returns

**Type:** Global.WorkerCommand

### MakeSuppressCommand(UnitModel)

```csharp
public static WorkerCommand MakeSuppressCommand(UnitModel targetObject)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetObject` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.WorkerCommand

### MakeUnconPursueAgent(UnitModel)

```csharp
public static WorkerCommand MakeUnconPursueAgent(UnitModel targetAgent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetAgent` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.WorkerCommand
