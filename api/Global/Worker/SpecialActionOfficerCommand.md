---
uid: Global.SpecialActionOfficerCommand
canonical_path: /api/Global/Worker/SpecialActionOfficerCommand
---

# Class SpecialActionOfficerCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpecialActionOfficerCommand : WorkerCommand
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Misc/UnitCommand) → [WorkerCommand](/api/Global/Misc/WorkerCommand) → SpecialActionOfficerCommand

## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/Global/Misc/WorkerCommand#makemanagecreature-creaturemodel-agentmodel-skilltypeinfo-sprite), [MakeReturnCreature(CreatureModel)](/api/Global/Misc/WorkerCommand#makereturncreature-creaturemodel), [MakeSuppressCommand(UnitModel)](/api/Global/Misc/WorkerCommand#makesuppresscommand-unitmodel), [MakeMove(MapNode)](/api/Global/Misc/WorkerCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Misc/WorkerCommand#makemove-movableobjectnode), [MakePanicPursueAgent(UnitModel)](/api/Global/Misc/WorkerCommand#makepanicpursueagent-unitmodel), [MakeUnconPursueAgent(UnitModel)](/api/Global/Misc/WorkerCommand#makeunconpursueagent-unitmodel), [MakeFollowAgent(MovableObjectNode)](/api/Global/Misc/WorkerCommand#makefollowagent-movableobjectnode), [MakeOfficerSpecialAction(OfficerSpecialAction)](/api/Global/Misc/WorkerCommand#makeofficerspecialaction-officerspecialaction), [actor](/api/Global/Misc/UnitCommand#actor), [isFinished](/api/Global/Misc/UnitCommand#isfinished), [isRemoved](/api/Global/Misc/UnitCommand#isremoved), [OnInit(UnitModel)](/api/Global/Misc/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Misc/UnitCommand#oninit-standingitemmodel), [Finish()](/api/Global/Misc/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SpecialActionOfficerCommand(OfficerSpecialAction)

```csharp
public SpecialActionOfficerCommand(OfficerSpecialAction action)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `Global.OfficerSpecialAction` |  |

## Fields

### action

```csharp
private OfficerSpecialAction action
```

#### Field Value

**Type:** Global.OfficerSpecialAction

### animatorId

```csharp
private long animatorId
```

#### Field Value

**Type:** System.Int64

### arrival

```csharp
private bool arrival
```

#### Field Value

**Type:** System.Boolean

### cnt

```csharp
private int cnt
```

#### Field Value

**Type:** System.Int32

### cntMax

```csharp
private int cntMax
```

#### Field Value

**Type:** System.Int32

### elapsedTime

```csharp
private float elapsedTime
```

#### Field Value

**Type:** System.Single

### endMotion

```csharp
private bool endMotion
```

#### Field Value

**Type:** System.Boolean

### initialPos

```csharp
private Vector3 initialPos
```

#### Field Value

**Type:** UnityEngine.Vector3

### initialScale

```csharp
private Vector3 initialScale
```

#### Field Value

**Type:** UnityEngine.Vector3

### motionTime

```csharp
private float motionTime
```

#### Field Value

**Type:** System.Single

### moveAnim

```csharp
private bool moveAnim
```

#### Field Value

**Type:** System.Boolean

### moveZ

```csharp
private bool moveZ
```

#### Field Value

**Type:** System.Boolean

### reference

```csharp
private Vector3 reference
```

#### Field Value

**Type:** UnityEngine.Vector3

### scaling

```csharp
private bool scaling
```

#### Field Value

**Type:** System.Boolean

### small

```csharp
private bool small
```

#### Field Value

**Type:** System.Boolean

### startReturnAction

```csharp
private bool startReturnAction
```

#### Field Value

**Type:** System.Boolean

### startSpecialAction

```csharp
private bool startSpecialAction
```

#### Field Value

**Type:** System.Boolean

### unitScale

```csharp
private float unitScale
```

#### Field Value

**Type:** System.Single

## Methods

### Execute()

```csharp
public override void Execute()
```

### Loop()

```csharp
private void Loop()
```

### MannualMoving(Vector3, bool, bool, bool, bool)

```csharp
private void MannualMoving(Vector3 pos, bool moveZ, bool moveAnim, bool scaling, bool small)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `moveZ` | `System.Boolean` |  |
| `moveAnim` | `System.Boolean` |  |
| `scaling` | `System.Boolean` |  |
| `small` | `System.Boolean` |  |

### OnDestroy()

```csharp
public override void OnDestroy()
```

### OnInit(WorkerModel)

```csharp
public override void OnInit(WorkerModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.WorkerModel` |  |

### OnStart()

```csharp
public override void OnStart()
```

### OnStop()

```csharp
public override void OnStop()
```
