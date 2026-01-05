# Class MoveCreatureCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MoveCreatureCommand : CreatureCommand
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureCommand](/api/CreatureCommand) → MoveCreatureCommand

## Inherited Members
[actor](/api/CreatureCommand#actor), [cmdQueue](/api/CreatureCommand#cmdqueue), [isFinished](/api/CreatureCommand#isfinished), [endCmd](/api/CreatureCommand#endcmd), [OnInit(CreatureModel, CreatureCommandQueue)](/api/CreatureCommand#oninit-creaturemodel-creaturecommandqueue), [OnDestroy()](/api/CreatureCommand#ondestroy), [Finish()](/api/CreatureCommand#finish), [SetEndCommand(OnCommandEnd)](/api/CreatureCommand#setendcommand-oncommandend), [MakeMove(MapNode)](/api/CreatureCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/CreatureCommand#makemove-movableobjectnode), [MakePursue(WorkerModel)](/api/CreatureCommand#makepursue-workermodel), [MakePursueAlter(WorkerModel)](/api/CreatureCommand#makepursuealter-workermodel), [MakePursueAlter(WorkerModel, float)](/api/CreatureCommand#makepursuealter-workermodel-float), [MakePursueAlter(WorkerModel, RwbpType, int, int)](/api/CreatureCommand#makepursuealter-workermodel-rwbptype-int-int), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### MoveCreatureCommand(MapNode)

```csharp
public MoveCreatureCommand(MapNode targetNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |

### MoveCreatureCommand(MovableObjectNode)

```csharp
public MoveCreatureCommand(MovableObjectNode movableNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `movableNode` | `Global.MovableObjectNode` |  |

## Fields

### targetMovable

```csharp
public MovableObjectNode targetMovable
```

#### Field Value

**Type:** Global.MovableObjectNode

### targetNode

```csharp
public MapNode targetNode
```

#### Field Value

**Type:** Global.MapNode

## Methods

### Execute()

```csharp
public override void Execute()
```

### OnStart()

```csharp
public override void OnStart()
```

### OnStop()

```csharp
public override void OnStop()
```
