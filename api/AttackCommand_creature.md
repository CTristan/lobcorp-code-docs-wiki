# Class AttackCommand_creature

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AttackCommand_creature : CreatureCommand
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureCommand](/api/CreatureCommand) → AttackCommand_creature

## Inherited Members
[actor](/api/CreatureCommand#actor), [cmdQueue](/api/CreatureCommand#cmdqueue), [isFinished](/api/CreatureCommand#isfinished), [endCmd](/api/CreatureCommand#endcmd), [OnInit(CreatureModel, CreatureCommandQueue)](/api/CreatureCommand#oninit-creaturemodel-creaturecommandqueue), [OnStop()](/api/CreatureCommand#onstop), [Finish()](/api/CreatureCommand#finish), [SetEndCommand(OnCommandEnd)](/api/CreatureCommand#setendcommand-oncommandend), [MakeMove(MapNode)](/api/CreatureCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/CreatureCommand#makemove-movableobjectnode), [MakePursue(WorkerModel)](/api/CreatureCommand#makepursue-workermodel), [MakePursueAlter(WorkerModel)](/api/CreatureCommand#makepursuealter-workermodel), [MakePursueAlter(WorkerModel, float)](/api/CreatureCommand#makepursuealter-workermodel-float), [MakePursueAlter(WorkerModel, RwbpType, int, int)](/api/CreatureCommand#makepursuealter-workermodel-rwbptype-int-int), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AttackCommand_creature(UnitModel)

```csharp
public AttackCommand_creature(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

## Fields

### target

```csharp
protected UnitModel target
```

#### Field Value

**Type:** Global.UnitModel

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

### OnDestroy()

```csharp
public override void OnDestroy()
```

### OnStart()

```csharp
public override void OnStart()
```
