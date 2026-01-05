# Class MoveItemCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MoveItemCommand : StandingCommand
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/UnitCommand) → [StandingCommand](/api/StandingCommand) → MoveItemCommand

## Inherited Members
[MoveCommand(MovableObjectNode)](/api/StandingCommand#movecommand-movableobjectnode), [MoveCommand(MapNode)](/api/StandingCommand#movecommand-mapnode), [MoveCommand(MovableObjectNode, OnCommandEnd)](/api/StandingCommand#movecommand-movableobjectnode-oncommandend), [MoveCommand(MapNode, OnCommandEnd)](/api/StandingCommand#movecommand-mapnode-oncommandend), [Finish()](/api/StandingCommand#finish), [SetEndCommand(OnCommandEnd)](/api/StandingCommand#setendcommand-oncommandend), [actor](/api/UnitCommand#actor), [isFinished](/api/UnitCommand#isfinished), [isRemoved](/api/UnitCommand#isremoved), [OnInit(WorkerModel)](/api/UnitCommand#oninit-workermodel), [OnInit(UnitModel)](/api/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/UnitCommand#oninit-standingitemmodel), [OnDestroy()](/api/UnitCommand#ondestroy), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### MoveItemCommand(MapNode)

```csharp
public MoveItemCommand(MapNode targetNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |

### MoveItemCommand(MovableObjectNode)

```csharp
public MoveItemCommand(MovableObjectNode targetMovable)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |

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
