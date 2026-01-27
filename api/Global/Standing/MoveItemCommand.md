---
uid: Global.MoveItemCommand
canonical_path: /api/Global/Standing/MoveItemCommand
---

# Class MoveItemCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MoveItemCommand : StandingCommand
```
#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Misc/UnitCommand) → [StandingCommand](/api/Global/Misc/StandingCommand) → MoveItemCommand

## Inherited Members
[endCmd](/api/Global/Misc/StandingCommand#endcmd), [MoveCommand(MovableObjectNode)](/api/Global/Misc/StandingCommand#movecommand-movableobjectnode), [MoveCommand(MapNode)](/api/Global/Misc/StandingCommand#movecommand-mapnode), [MoveCommand(MovableObjectNode, OnCommandEnd)](/api/Global/Misc/StandingCommand#movecommand-movableobjectnode-oncommandend), [MoveCommand(MapNode, OnCommandEnd)](/api/Global/Misc/StandingCommand#movecommand-mapnode-oncommandend), [Finish()](/api/Global/Misc/StandingCommand#finish), [SetEndCommand(OnCommandEnd)](/api/Global/Misc/StandingCommand#setendcommand-oncommandend), [actor](/api/Global/Misc/UnitCommand#actor), [isFinished](/api/Global/Misc/UnitCommand#isfinished), [isRemoved](/api/Global/Misc/UnitCommand#isremoved), [OnInit(WorkerModel)](/api/Global/Misc/UnitCommand#oninit-workermodel), [OnInit(UnitModel)](/api/Global/Misc/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Misc/UnitCommand#oninit-standingitemmodel), [OnDestroy()](/api/Global/Misc/UnitCommand#ondestroy), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MoveItemCommand(MapNode)

```csharp
public MoveItemCommand(MapNode targetNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |

### MoveItemCommand(MovableObjectNode)

```csharp
public MoveItemCommand(MovableObjectNode targetMovable)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |

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

