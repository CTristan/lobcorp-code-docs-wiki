# Class WorkerCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerCommand : UnitCommand
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/UnitCommand) → WorkerCommand

## Inherited Members
[actor](/api/UnitCommand#actor), [isFinished](/api/UnitCommand#isfinished), [isRemoved](/api/UnitCommand#isremoved), [OnInit(WorkerModel)](/api/UnitCommand#oninit-workermodel), [OnInit(UnitModel)](/api/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/UnitCommand#oninit-standingitemmodel), [OnStart()](/api/UnitCommand#onstart), [Execute()](/api/UnitCommand#execute), [OnStop()](/api/UnitCommand#onstop), [OnDestroy()](/api/UnitCommand#ondestroy), [Finish()](/api/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetAgent` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.WorkerCommand
