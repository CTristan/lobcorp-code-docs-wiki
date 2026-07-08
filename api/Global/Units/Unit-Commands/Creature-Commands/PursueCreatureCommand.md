---
uid: Global.PursueCreatureCommand
canonical_path: /api/Global/Creature/PursueCreatureCommand
---
# Class PursueCreatureCommand
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PursueCreatureCommand : CreatureCommand
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}


Command to an abnormality to pursue a worker.

Targets the closest agent. Attacks if close enough, otherwise moves after that agent.

Seems unused... maybe they all just use [PursueCreatureCommandAlter](/api/Global/Creature/PursueCreatureCommandAlter)?





## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureCommand](/api/Global/Misc/CreatureCommand) → PursueCreatureCommand

## Constructors
### PursueCreatureCommand(WorkerModel)
```csharp
public PursueCreatureCommand(WorkerModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

## Fields
### elapsedTime
```csharp
private float elapsedTime
```


#### Field Value
**Type:** System.Single

### targetWorker
```csharp
private WorkerModel targetWorker
```


#### Field Value
**Type:** Global.WorkerModel

## Methods
### CheckPursueTarget()
```csharp
private void CheckPursueTarget()
```


### Execute()
```csharp
public override void Execute()
```


### OnDestroy()
```csharp
public override void OnDestroy()
```


### OnStart()
```csharp
public override void OnStart()
```


## Inherited Members
[actor](/api/Global/Misc/CreatureCommand#actor), [cmdQueue](/api/Global/Misc/CreatureCommand#cmdqueue), [isFinished](/api/Global/Misc/CreatureCommand#isfinished), [endCmd](/api/Global/Misc/CreatureCommand#endcmd), [OnInit(CreatureModel, CreatureCommandQueue)](/api/Global/Misc/CreatureCommand#oninit-creaturemodel-creaturecommandqueue), [OnStop()](/api/Global/Misc/CreatureCommand#onstop), [Finish()](/api/Global/Misc/CreatureCommand#finish), [SetEndCommand(OnCommandEnd)](/api/Global/Misc/CreatureCommand#setendcommand-oncommandend), [MakeMove(MapNode)](/api/Global/Misc/CreatureCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Misc/CreatureCommand#makemove-movableobjectnode), [MakePursue(WorkerModel)](/api/Global/Misc/CreatureCommand#makepursue-workermodel), [MakePursueAlter(WorkerModel)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel), [MakePursueAlter(WorkerModel, float)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel-float), [MakePursueAlter(WorkerModel, RwbpType, int, int)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel-rwbptype-int-int), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)




