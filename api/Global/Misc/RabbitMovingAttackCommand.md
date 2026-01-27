---
uid: Global.RabbitMovingAttackCommand
canonical_path: /api/Global/Misc/RabbitMovingAttackCommand
---

# Class RabbitMovingAttackCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitMovingAttackCommand : UnitCommand
```

Rabbit AI.

Attempts to fire at everything hostile in the room, prioritizing larger groups, then moves to a target node. If there is no target node, moves to the next moving target. #INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Misc/UnitCommand) → RabbitMovingAttackCommand

## Inherited Members
[actor](/api/Global/Misc/UnitCommand#actor), [isFinished](/api/Global/Misc/UnitCommand#isfinished), [isRemoved](/api/Global/Misc/UnitCommand#isremoved), [OnInit(WorkerModel)](/api/Global/Misc/UnitCommand#oninit-workermodel), [OnInit(UnitModel)](/api/Global/Misc/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Misc/UnitCommand#oninit-standingitemmodel), [OnDestroy()](/api/Global/Misc/UnitCommand#ondestroy), [Finish()](/api/Global/Misc/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RabbitMovingAttackCommand(MapNode)

```csharp
public RabbitMovingAttackCommand(MapNode targetNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |

### RabbitMovingAttackCommand(MovableObjectNode)

```csharp
public RabbitMovingAttackCommand(MovableObjectNode movableNode)
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

### AttackOrMove()

```csharp
private void AttackOrMove()
```
#INC


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


### Shot()

```csharp
private void Shot()
```
#INC

