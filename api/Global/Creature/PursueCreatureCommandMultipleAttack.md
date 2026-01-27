---
uid: Global.PursueCreatureCommandMultipleAttack
canonical_path: /api/Global/Creature/PursueCreatureCommandMultipleAttack
---

# Class PursueCreatureCommandMultipleAttack

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PursueCreatureCommandMultipleAttack : CreatureCommand
```

Command to an abnormality to chase a target, attack, and then never move again I guess? #INC 

Doesn't seem used.

#unused #maybe_unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureCommand](/api/Global/Misc/CreatureCommand) → PursueCreatureCommandMultipleAttack

## Inherited Members
[actor](/api/Global/Misc/CreatureCommand#actor), [cmdQueue](/api/Global/Misc/CreatureCommand#cmdqueue), [isFinished](/api/Global/Misc/CreatureCommand#isfinished), [endCmd](/api/Global/Misc/CreatureCommand#endcmd), [OnInit(CreatureModel, CreatureCommandQueue)](/api/Global/Misc/CreatureCommand#oninit-creaturemodel-creaturecommandqueue), [OnStop()](/api/Global/Misc/CreatureCommand#onstop), [Finish()](/api/Global/Misc/CreatureCommand#finish), [SetEndCommand(OnCommandEnd)](/api/Global/Misc/CreatureCommand#setendcommand-oncommandend), [MakeMove(MapNode)](/api/Global/Misc/CreatureCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Misc/CreatureCommand#makemove-movableobjectnode), [MakePursue(WorkerModel)](/api/Global/Misc/CreatureCommand#makepursue-workermodel), [MakePursueAlter(WorkerModel)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel), [MakePursueAlter(WorkerModel, float)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel-float), [MakePursueAlter(WorkerModel, RwbpType, int, int)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel-rwbptype-int-int), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PursueCreatureCommandMultipleAttack(WorkerModel)

```csharp
public PursueCreatureCommandMultipleAttack(WorkerModel mainTarget)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mainTarget` | `Global.WorkerModel` |  |

### PursueCreatureCommandMultipleAttack(WorkerModel, float)

```csharp
public PursueCreatureCommandMultipleAttack(WorkerModel mainTarget, float damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mainTarget` | `Global.WorkerModel` |  |
| `damage` | `System.Single` |  |

### PursueCreatureCommandMultipleAttack(WorkerModel, float, float)

```csharp
public PursueCreatureCommandMultipleAttack(WorkerModel mainTarget, float damage, float range)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mainTarget` | `Global.WorkerModel` |  |
| `damage` | `System.Single` |  |
| `range` | `System.Single` |  |

## Fields

### attackDelay

```csharp
private Timer attackDelay
```
#INC


#### Field Value

**Type:** Global.Timer

### canMove

```csharp
private bool canMove
```
#INC


#### Field Value

**Type:** System.Boolean

### damage

```csharp
private float damage
```
#INC


#### Field Value

**Type:** System.Single

### elapsedTime

```csharp
private float elapsedTime
```
#INC


#### Field Value

**Type:** System.Single

### maxWaitTime

```csharp
private const float maxWaitTime = 10
```
#INC


#### Field Value

**Type:** System.Single

### range

```csharp
private float range
```
#INC


#### Field Value

**Type:** System.Single

### targetWorker

```csharp
private WorkerModel targetWorker
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### waitingTime

```csharp
private float waitingTime
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### CheckPursueTarget()

```csharp
private void CheckPursueTarget()
```
#INC


### Execute()

```csharp
public override void Execute()
```
#INC


### GetTargetsInRange()

```csharp
public List<UnitModel> GetTargetsInRange()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GiveDamage()

```csharp
public void GiveDamage()
```
#INC


### OnDestroy()

```csharp
public override void OnDestroy()
```
#INC


### OnStart()

```csharp
public override void OnStart()
```
#INC
#code-generated


### SetRange(float)

```csharp
public void SetRange(float range)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
