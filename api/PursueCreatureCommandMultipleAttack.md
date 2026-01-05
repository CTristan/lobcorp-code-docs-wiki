# Class PursueCreatureCommandMultipleAttack

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PursueCreatureCommandMultipleAttack : CreatureCommand
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureCommand](/api/CreatureCommand) → PursueCreatureCommandMultipleAttack

## Inherited Members
[actor](/api/CreatureCommand#actor), [cmdQueue](/api/CreatureCommand#cmdqueue), [isFinished](/api/CreatureCommand#isfinished), [endCmd](/api/CreatureCommand#endcmd), [OnInit(CreatureModel, CreatureCommandQueue)](/api/CreatureCommand#oninit-creaturemodel-creaturecommandqueue), [OnStop()](/api/CreatureCommand#onstop), [Finish()](/api/CreatureCommand#finish), [SetEndCommand(OnCommandEnd)](/api/CreatureCommand#setendcommand-oncommandend), [MakeMove(MapNode)](/api/CreatureCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/CreatureCommand#makemove-movableobjectnode), [MakePursue(WorkerModel)](/api/CreatureCommand#makepursue-workermodel), [MakePursueAlter(WorkerModel)](/api/CreatureCommand#makepursuealter-workermodel), [MakePursueAlter(WorkerModel, float)](/api/CreatureCommand#makepursuealter-workermodel-float), [MakePursueAlter(WorkerModel, RwbpType, int, int)](/api/CreatureCommand#makepursuealter-workermodel-rwbptype-int-int), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### PursueCreatureCommandMultipleAttack(WorkerModel)

```csharp
public PursueCreatureCommandMultipleAttack(WorkerModel mainTarget)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mainTarget` | `Global.WorkerModel` |  |

### PursueCreatureCommandMultipleAttack(WorkerModel, float)

```csharp
public PursueCreatureCommandMultipleAttack(WorkerModel mainTarget, float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mainTarget` | `Global.WorkerModel` |  |
| `damage` | `System.Single` |  |

### PursueCreatureCommandMultipleAttack(WorkerModel, float, float)

```csharp
public PursueCreatureCommandMultipleAttack(WorkerModel mainTarget, float damage, float range)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mainTarget` | `Global.WorkerModel` |  |
| `damage` | `System.Single` |  |
| `range` | `System.Single` |  |

## Methods

### Execute()

```csharp
public override void Execute()
```

### GetTargetsInRange()

```csharp
public List<UnitModel> GetTargetsInRange()
```

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GiveDamage()

```csharp
public void GiveDamage()
```

### OnDestroy()

```csharp
public override void OnDestroy()
```

### OnStart()

```csharp
public override void OnStart()
```

### SetRange(float)

```csharp
public void SetRange(float range)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
