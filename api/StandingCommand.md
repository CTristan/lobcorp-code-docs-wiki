# Class StandingCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StandingCommand : UnitCommand
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/UnitCommand) → StandingCommand

## Inherited Members
[actor](/api/UnitCommand#actor), [isFinished](/api/UnitCommand#isfinished), [isRemoved](/api/UnitCommand#isremoved), [OnInit(WorkerModel)](/api/UnitCommand#oninit-workermodel), [OnInit(UnitModel)](/api/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/UnitCommand#oninit-standingitemmodel), [OnStart()](/api/UnitCommand#onstart), [Execute()](/api/UnitCommand#execute), [OnStop()](/api/UnitCommand#onstop), [OnDestroy()](/api/UnitCommand#ondestroy), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### StandingCommand()

```csharp
public StandingCommand()
```

## Methods

### Finish()

```csharp
public virtual void Finish()
```

### MoveCommand(MapNode)

```csharp
public static MoveItemCommand MoveCommand(MapNode mapNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mapNode` | `Global.MapNode` |  |

#### Returns

**Type:** Global.MoveItemCommand

### MoveCommand(MapNode, OnCommandEnd)

```csharp
public static MoveItemCommand MoveCommand(MapNode mapNode, StandingCommand.OnCommandEnd end)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mapNode` | `Global.MapNode` |  |
| `end` | `Global.StandingCommand.OnCommandEnd` |  |

#### Returns

**Type:** Global.MoveItemCommand

### MoveCommand(MovableObjectNode)

```csharp
public static MoveItemCommand MoveCommand(MovableObjectNode movable)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `movable` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.MoveItemCommand

### MoveCommand(MovableObjectNode, OnCommandEnd)

```csharp
public static MoveItemCommand MoveCommand(MovableObjectNode movable, StandingCommand.OnCommandEnd end)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `movable` | `Global.MovableObjectNode` |  |
| `end` | `Global.StandingCommand.OnCommandEnd` |  |

#### Returns

**Type:** Global.MoveItemCommand

### SetEndCommand(OnCommandEnd)

```csharp
public virtual void SetEndCommand(StandingCommand.OnCommandEnd cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.StandingCommand.OnCommandEnd` |  |
