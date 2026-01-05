# Class SingingMachineAttackCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SingingMachineAttackCommand : WorkerCommand
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/UnitCommand) → [WorkerCommand](/api/WorkerCommand) → SingingMachineAttackCommand

## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/WorkerCommand#makemanagecreature-creaturemodel-agentmodel-skilltypeinfo-sprite), [MakeReturnCreature(CreatureModel)](/api/WorkerCommand#makereturncreature-creaturemodel), [MakeSuppressCommand(UnitModel)](/api/WorkerCommand#makesuppresscommand-unitmodel), [MakeMove(MapNode)](/api/WorkerCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/WorkerCommand#makemove-movableobjectnode), [MakePanicPursueAgent(UnitModel)](/api/WorkerCommand#makepanicpursueagent-unitmodel), [MakeUnconPursueAgent(UnitModel)](/api/WorkerCommand#makeunconpursueagent-unitmodel), [MakeFollowAgent(MovableObjectNode)](/api/WorkerCommand#makefollowagent-movableobjectnode), [MakeOfficerSpecialAction(OfficerSpecialAction)](/api/WorkerCommand#makeofficerspecialaction-officerspecialaction), [actor](/api/UnitCommand#actor), [isFinished](/api/UnitCommand#isfinished), [isRemoved](/api/UnitCommand#isremoved), [OnInit(WorkerModel)](/api/UnitCommand#oninit-workermodel), [OnInit(UnitModel)](/api/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/UnitCommand#oninit-standingitemmodel), [OnStop()](/api/UnitCommand#onstop), [Finish()](/api/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SingingMachineAttackCommand(WorkerModel, SingingMachine, SpriteRenderer, SpriteRenderer)

```csharp
public SingingMachineAttackCommand(WorkerModel target, SingingMachine ownerMachine, SpriteRenderer deadBackHairRenderer, SpriteRenderer deadFrontHairRenderer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `ownerMachine` | `Global.SingingMachine` |  |
| `deadBackHairRenderer` | `UnityEngine.SpriteRenderer` |  |
| `deadFrontHairRenderer` | `UnityEngine.SpriteRenderer` |  |

## Methods

### Execute()

```csharp
public override void Execute()
```

### GetTarget()

```csharp
public UnitModel GetTarget()
```

#### Returns

**Type:** Global.UnitModel

### GiveDamage()

```csharp
public virtual void GiveDamage()
```

### OnAnimCalled(int)

```csharp
public void OnAnimCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnDestroy()

```csharp
public override void OnDestroy()
```

### OnStart()

```csharp
public override void OnStart()
```
