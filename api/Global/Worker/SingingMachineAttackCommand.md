---
uid: Global.SingingMachineAttackCommand
canonical_path: /api/Global/Worker/SingingMachineAttackCommand
---

# Class SingingMachineAttackCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SingingMachineAttackCommand : WorkerCommand
```

Behaviour for an uncontrollable employee attracted by [Singing Machine](/api/Global/Machine/SingingMachine). Used by  #verify .

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Misc/UnitCommand) → [WorkerCommand](/api/Global/Misc/WorkerCommand) → SingingMachineAttackCommand

## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/Global/Misc/WorkerCommand#makemanagecreature-creaturemodel-agentmodel-skilltypeinfo-sprite), [MakeReturnCreature(CreatureModel)](/api/Global/Misc/WorkerCommand#makereturncreature-creaturemodel), [MakeSuppressCommand(UnitModel)](/api/Global/Misc/WorkerCommand#makesuppresscommand-unitmodel), [MakeMove(MapNode)](/api/Global/Misc/WorkerCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Misc/WorkerCommand#makemove-movableobjectnode), [MakePanicPursueAgent(UnitModel)](/api/Global/Misc/WorkerCommand#makepanicpursueagent-unitmodel), [MakeUnconPursueAgent(UnitModel)](/api/Global/Misc/WorkerCommand#makeunconpursueagent-unitmodel), [MakeFollowAgent(MovableObjectNode)](/api/Global/Misc/WorkerCommand#makefollowagent-movableobjectnode), [MakeOfficerSpecialAction(OfficerSpecialAction)](/api/Global/Misc/WorkerCommand#makeofficerspecialaction-officerspecialaction), [actor](/api/Global/Misc/UnitCommand#actor), [isFinished](/api/Global/Misc/UnitCommand#isfinished), [isRemoved](/api/Global/Misc/UnitCommand#isremoved), [OnInit(WorkerModel)](/api/Global/Misc/UnitCommand#oninit-workermodel), [OnInit(UnitModel)](/api/Global/Misc/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Misc/UnitCommand#oninit-standingitemmodel), [OnStop()](/api/Global/Misc/UnitCommand#onstop), [Finish()](/api/Global/Misc/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SingingMachineAttackCommand(WorkerModel, SingingMachine, SpriteRenderer, SpriteRenderer)

```csharp
public SingingMachineAttackCommand(WorkerModel target, SingingMachine ownerMachine, SpriteRenderer deadBackHairRenderer, SpriteRenderer deadFrontHairRenderer)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `ownerMachine` | `Global.SingingMachine` |  |
| `deadBackHairRenderer` | `UnityEngine.SpriteRenderer` |  |
| `deadFrontHairRenderer` | `UnityEngine.SpriteRenderer` |  |

## Fields

### _attackPreCooltimeTimer

```csharp
private Timer _attackPreCooltimeTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _deadBackHairRenderer

```csharp
private SpriteRenderer _deadBackHairRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### _deadFrontHairRenderer

```csharp
private SpriteRenderer _deadFrontHairRenderer
```
#INC


#### Field Value

**Type:** UnityEngine.SpriteRenderer

### _drag

```csharp
private bool _drag
```
#INC


#### Field Value

**Type:** System.Boolean

### _dragStartTimer

```csharp
private Timer _dragStartTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _finishTimer

```csharp
private Timer _finishTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _insertingTimer

```csharp
private Timer _insertingTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _remainAttackDelay

```csharp
private float _remainAttackDelay
```
#INC


#### Field Value

**Type:** System.Single

### _singingMachine

```csharp
private SingingMachine _singingMachine
```
#INC


#### Field Value

**Type:** Global.SingingMachine

### _target

```csharp
private WorkerModel _target
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### defaultDamage

```csharp
private const float defaultDamage = 16
```
#INC


#### Field Value

**Type:** System.Single

### range

```csharp
private const float range = 3
```
#INC


#### Field Value

**Type:** System.Single

### statDamageBonus

```csharp
private const float statDamageBonus = 3
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### DefaultAction()

```csharp
private void DefaultAction()
```
#INC


### DragAction()

```csharp
private void DragAction()
```
#INC


### Execute()

```csharp
public override void Execute()
```
#INC


### GetTarget()

```csharp
public UnitModel GetTarget()
```
#INC


#### Returns

**Type:** Global.UnitModel

### GiveDamage()

```csharp
public virtual void GiveDamage()
```
#INC


### MoveOrAttack()

```csharp
private void MoveOrAttack()
```
#INC


### OnAnimCalled(int)

```csharp
public void OnAnimCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

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

