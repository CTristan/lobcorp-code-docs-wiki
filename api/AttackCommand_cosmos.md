# Class AttackCommand_cosmos

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AttackCommand_cosmos : AttackCommand_creature
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureCommand](/api/CreatureCommand) → [AttackCommand_creature](/api/AttackCommand_creature) → AttackCommand_cosmos

## Inherited Members
[target](/api/AttackCommand_creature#target), [GetTarget()](/api/AttackCommand_creature#gettarget), [OnStart()](/api/AttackCommand_creature#onstart), [Execute()](/api/AttackCommand_creature#execute), [OnDestroy()](/api/AttackCommand_creature#ondestroy), [actor](/api/CreatureCommand#actor), [cmdQueue](/api/CreatureCommand#cmdqueue), [isFinished](/api/CreatureCommand#isfinished), [endCmd](/api/CreatureCommand#endcmd), [OnStop()](/api/CreatureCommand#onstop), [Finish()](/api/CreatureCommand#finish), [SetEndCommand(OnCommandEnd)](/api/CreatureCommand#setendcommand-oncommandend), [MakeMove(MapNode)](/api/CreatureCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/CreatureCommand#makemove-movableobjectnode), [MakePursue(WorkerModel)](/api/CreatureCommand#makepursue-workermodel), [MakePursueAlter(WorkerModel)](/api/CreatureCommand#makepursuealter-workermodel), [MakePursueAlter(WorkerModel, float)](/api/CreatureCommand#makepursuealter-workermodel-float), [MakePursueAlter(WorkerModel, RwbpType, int, int)](/api/CreatureCommand#makepursuealter-workermodel-rwbptype-int-int), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AttackCommand_cosmos(UnitModel)

```csharp
public AttackCommand_cosmos(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

## Fields

### hitLeftEffect

```csharp
public const string hitLeftEffect = "Effect/Creature/Cosmos/Cosmos-lateral-left"
```

#### Field Value

**Type:** System.String

### hitLeftUpEffect

```csharp
public const string hitLeftUpEffect = "Effect/Creature/Cosmos/Cosmos-lateral-left-up"
```

#### Field Value

**Type:** System.String

### hitRightEffect

```csharp
public const string hitRightEffect = "Effect/Creature/Cosmos/Cosmos-lateral-right"
```

#### Field Value

**Type:** System.String

### hitRightUpEffect

```csharp
public const string hitRightUpEffect = "Effect/Creature/Cosmos/Cosmos-lateral-right-up"
```

#### Field Value

**Type:** System.String

## Methods

### GiveDamage()

```csharp
public override void GiveDamage()
```

### OnInit(CreatureModel, CreatureCommandQueue)

```csharp
public override void OnInit(CreatureModel creature, CreatureCommandQueue cmdQueue)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `cmdQueue` | `Global.CreatureCommandQueue` |  |

### SetAttackType(int)

```csharp
public void SetAttackType(int attackType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `System.Int32` |  |
