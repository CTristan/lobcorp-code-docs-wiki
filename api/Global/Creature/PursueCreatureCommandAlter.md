---
uid: Global.PursueCreatureCommandAlter
canonical_path: /api/Global/Creature/PursueCreatureCommandAlter
---

# Class PursueCreatureCommandAlter

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PursueCreatureCommandAlter : CreatureCommand
```

Command to pursue a nearby worker.

Attacks if close enough, and otherwise moves towards the target worker.
Every second, checks if there is a valid target within 5 units, and switches targets to them (sort of randomly); otherwise, starts roaming.

Ends when this creature is no longer breaching or the target is dead #verify.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureCommand](/api/Global/Misc/CreatureCommand) → PursueCreatureCommandAlter

## Inherited Members
[actor](/api/Global/Misc/CreatureCommand#actor), [cmdQueue](/api/Global/Misc/CreatureCommand#cmdqueue), [isFinished](/api/Global/Misc/CreatureCommand#isfinished), [endCmd](/api/Global/Misc/CreatureCommand#endcmd), [OnInit(CreatureModel, CreatureCommandQueue)](/api/Global/Misc/CreatureCommand#oninit-creaturemodel-creaturecommandqueue), [OnStop()](/api/Global/Misc/CreatureCommand#onstop), [Finish()](/api/Global/Misc/CreatureCommand#finish), [SetEndCommand(OnCommandEnd)](/api/Global/Misc/CreatureCommand#setendcommand-oncommandend), [MakeMove(MapNode)](/api/Global/Misc/CreatureCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Misc/CreatureCommand#makemove-movableobjectnode), [MakePursue(WorkerModel)](/api/Global/Misc/CreatureCommand#makepursue-workermodel), [MakePursueAlter(WorkerModel)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel), [MakePursueAlter(WorkerModel, float)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel-float), [MakePursueAlter(WorkerModel, RwbpType, int, int)](/api/Global/Misc/CreatureCommand#makepursuealter-workermodel-rwbptype-int-int), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PursueCreatureCommandAlter(WorkerModel)

```csharp
public PursueCreatureCommandAlter(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### PursueCreatureCommandAlter(WorkerModel, float)

```csharp
public PursueCreatureCommandAlter(WorkerModel target, float damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `damage` | `System.Single` |  |

### PursueCreatureCommandAlter(WorkerModel, RwbpType, int, int)

```csharp
public PursueCreatureCommandAlter(WorkerModel target, RwbpType dmgType, int dmgMin, int dmgMax)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `dmgType` | `Global.RwbpType` |  |
| `dmgMin` | `System.Int32` |  |
| `dmgMax` | `System.Int32` |  |

## Fields

### changeTargetTimer

```csharp
private Timer changeTargetTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### damage

```csharp
private float damage
```
#INC


#### Field Value

**Type:** System.Single

### dmgMax

```csharp
private int dmgMax
```
#INC


#### Field Value

**Type:** System.Int32

### dmgMin

```csharp
private int dmgMin
```
#INC


#### Field Value

**Type:** System.Int32

### dmgType

```csharp
private RwbpType dmgType
```
#INC


#### Field Value

**Type:** Global.RwbpType

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

