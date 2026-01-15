---
uid: Global.AttackCommand_nothing
canonical_path: /api/Global/Misc/AttackCommandnothing
---

# Class AttackCommand_nothing

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AttackCommand_nothing : AttackCommand_creature
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureCommand](/api/Global/Misc/CreatureCommand) → [AttackCommand_creature](/api/Global/Creature/AttackCommandcreature) → AttackCommand_nothing

## Inherited Members
[target](/api/Global/Creature/AttackCommandcreature#target), [GetTarget()](/api/Global/Creature/AttackCommandcreature#gettarget), [OnStart()](/api/Global/Creature/AttackCommandcreature#onstart), [OnDestroy()](/api/Global/Creature/AttackCommandcreature#ondestroy), [MoveOrAttack()](/api/Global/Creature/AttackCommandcreature#moveorattack), [actor](/api/Global/Misc/CreatureCommand#actor), [cmdQueue](/api/Global/Misc/CreatureCommand#cmdqueue), [isFinished](/api/Global/Misc/CreatureCommand#isfinished), [endCmd](/api/Global/Misc/CreatureCommand#endcmd), [OnStop()](/api/Global/Misc/CreatureCommand#onstop), [Finish()](/api/Global/Misc/CreatureCommand#finish), [SetEndCommand(OnCommandEnd)](/api/Global/Misc/CreatureCommand#setendcommand-oncommandend), [MakeMove(MapNode)](/api/Global/Misc/CreatureCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Misc/CreatureCommand#makemove-movableobjectnode), [MakePursue(WorkerModel)](/api/Global/Misc/CreatureCommand#makepursue-workermodel), [MakePursueAlter(WorkerModel)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel), [MakePursueAlter(WorkerModel, float)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel-float), [MakePursueAlter(WorkerModel, RwbpType, int, int)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel-rwbptype-int-int), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AttackCommand_nothing(UnitModel)

```csharp
public AttackCommand_nothing(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

## Fields

### normalDamageMax_Lv1

```csharp
private const int normalDamageMax_Lv1 = 22
```

#### Field Value

**Type:** System.Int32

### normalDamageMin_Lv1

```csharp
private const int normalDamageMin_Lv1 = 18
```

#### Field Value

**Type:** System.Int32

### script

```csharp
private Nothing script
```

#### Field Value

**Type:** Global.Nothing

### splash

```csharp
private const float splash = 1
```

#### Field Value

**Type:** System.Single

## Properties

### normalDamage_Lv1

```csharp
private static int normalDamage_Lv1 { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### Execute()

```csharp
public override void Execute()
```

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
