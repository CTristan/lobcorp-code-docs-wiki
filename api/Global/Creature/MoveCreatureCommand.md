---
uid: Global.MoveCreatureCommand
canonical_path: /api/Global/Creature/MoveCreatureCommand
---

# Class MoveCreatureCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MoveCreatureCommand : CreatureCommand
```

Tells a creature to move to a target node.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureCommand](/api/Global/Misc/CreatureCommand) → MoveCreatureCommand

## Inherited Members
[actor](/api/Global/Misc/CreatureCommand#actor), [cmdQueue](/api/Global/Misc/CreatureCommand#cmdqueue), [isFinished](/api/Global/Misc/CreatureCommand#isfinished), [endCmd](/api/Global/Misc/CreatureCommand#endcmd), [OnInit(CreatureModel, CreatureCommandQueue)](/api/Global/Misc/CreatureCommand#oninit-creaturemodel-creaturecommandqueue), [OnDestroy()](/api/Global/Misc/CreatureCommand#ondestroy), [Finish()](/api/Global/Misc/CreatureCommand#finish), [SetEndCommand(OnCommandEnd)](/api/Global/Misc/CreatureCommand#setendcommand-oncommandend), [MakeMove(MapNode)](/api/Global/Misc/CreatureCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Misc/CreatureCommand#makemove-movableobjectnode), [MakePursue(WorkerModel)](/api/Global/Misc/CreatureCommand#makepursue-workermodel), [MakePursueAlter(WorkerModel)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel), [MakePursueAlter(WorkerModel, float)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel-float), [MakePursueAlter(WorkerModel, RwbpType, int, int)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel-rwbptype-int-int), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MoveCreatureCommand(MapNode)

```csharp
public MoveCreatureCommand(MapNode targetNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |

### MoveCreatureCommand(MovableObjectNode)

```csharp
public MoveCreatureCommand(MovableObjectNode movableNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `movableNode` | `Global.MovableObjectNode` |  |

## Fields

### targetMovable

```csharp
public MovableObjectNode targetMovable
```
#INC


#### Field Value

**Type:** Global.MovableObjectNode

### targetNode

```csharp
public MapNode targetNode
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

