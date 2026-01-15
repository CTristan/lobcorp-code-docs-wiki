---
uid: Global.CreatureCommand
canonical_path: /api/Global/Misc/CreatureCommand
---

# Class CreatureCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureCommand
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureCommand

## Derived
[AttackCommand_creature](/api/Global/Creature/AttackCommandcreature), [MoveCreatureCommand](/api/Global/Creature/MoveCreatureCommand), [PursueCreatureCommand](/api/Global/Creature/PursueCreatureCommand), [PursueCreatureCommandAlter](/api/Global/Creature/PursueCreatureCommandAlter), [PursueCreatureCommandMultipleAttack](/api/Global/Creature/PursueCreatureCommandMultipleAttack)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureCommand()

```csharp
public CreatureCommand()
```

## Fields

### actor

```csharp
public CreatureModel actor
```

#### Field Value

**Type:** Global.CreatureModel

### cmdQueue

```csharp
public CreatureCommandQueue cmdQueue
```

#### Field Value

**Type:** Global.CreatureCommandQueue

### endCmd

```csharp
public CreatureCommand.OnCommandEnd endCmd
```

#### Field Value

**Type:** Global.CreatureCommand.OnCommandEnd

### isFinished

```csharp
public bool isFinished
```

#### Field Value

**Type:** System.Boolean

## Methods

### Execute()

```csharp
public virtual void Execute()
```

### Finish()

```csharp
public virtual void Finish()
```

### MakeMove(MapNode)

```csharp
public static CreatureCommand MakeMove(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** Global.CreatureCommand

### MakeMove(MovableObjectNode)

```csharp
public static CreatureCommand MakeMove(MovableObjectNode movable)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `movable` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.CreatureCommand

### MakePursue(WorkerModel)

```csharp
public static CreatureCommand MakePursue(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns

**Type:** Global.CreatureCommand

### MakePursueAlter(WorkerModel)

```csharp
public static CreatureCommand MakePursueAlter(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

#### Returns

**Type:** Global.CreatureCommand

### MakePursueAlter(WorkerModel, float)

```csharp
public static CreatureCommand MakePursueAlter(WorkerModel target, float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `damage` | `System.Single` |  |

#### Returns

**Type:** Global.CreatureCommand

### MakePursueAlter(WorkerModel, RwbpType, int, int)

```csharp
public static CreatureCommand MakePursueAlter(WorkerModel target, RwbpType dmgType, int dmgMin, int dmgMax)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `dmgType` | `Global.RwbpType` |  |
| `dmgMin` | `System.Int32` |  |
| `dmgMax` | `System.Int32` |  |

#### Returns

**Type:** Global.CreatureCommand

### OnDestroy()

```csharp
public virtual void OnDestroy()
```

### OnInit(CreatureModel, CreatureCommandQueue)

```csharp
public virtual void OnInit(CreatureModel creature, CreatureCommandQueue cmdQueue)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `cmdQueue` | `Global.CreatureCommandQueue` |  |

### OnStart()

```csharp
public virtual void OnStart()
```

### OnStop()

```csharp
public virtual void OnStop()
```

### SetEndCommand(OnCommandEnd)

```csharp
public virtual void SetEndCommand(CreatureCommand.OnCommandEnd cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.CreatureCommand.OnCommandEnd` |  |
