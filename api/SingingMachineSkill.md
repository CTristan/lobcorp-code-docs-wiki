# Class SingingMachineSkill

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SingingMachineSkill : CreatureSpecialSkill, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureSpecialSkill](/api/CreatureSpecialSkill) → SingingMachineSkill

## Inherited Members
[model](/api/CreatureSpecialSkill#model), [sefira](/api/CreatureSpecialSkill#sefira), [Activated](/api/CreatureSpecialSkill#activated), [SkillActivate()](/api/CreatureSpecialSkill#skillactivate), [Activate()](/api/CreatureSpecialSkill#activate), [OnNotice(string, params object[])](/api/CreatureSpecialSkill#onnotice-string-params-object), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SingingMachineSkill(CreatureModel)

```csharp
public SingingMachineSkill(CreatureModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

## Fields

### attractTarget

```csharp
public List<WorkerModel> attractTarget
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

### tip_attractAttack

```csharp
public const string tip_attractAttack = "attractAttack"
```

#### Field Value

**Type:** System.String

### tip_attractKillMusic

```csharp
public const string tip_attractKillMusic = "attractKillMusic"
```

#### Field Value

**Type:** System.String

### tip_ifDeadAttract

```csharp
public const string tip_ifDeadAttract = "ifDeadAttract"
```

#### Field Value

**Type:** System.String

### tip_manyAttract

```csharp
public const string tip_manyAttract = "manyAttract"
```

#### Field Value

**Type:** System.String

### tip_panicShake

```csharp
public const string tip_panicShake = "panicShake"
```

#### Field Value

**Type:** System.String

## Methods

### AddAttackTarget(UnitModel)

```csharp
public void AddAttackTarget(UnitModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.UnitModel` |  |

### Attract(List<WorkerModel>)

```csharp
public void Attract(List<WorkerModel> list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.Generic.List{WorkerModel}` |  |

### AttractInitialMovement(WorkerModel)

```csharp
public void AttractInitialMovement(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### AttractSkillActivate(WorkerModel)

```csharp
public void AttractSkillActivate(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### CheckAgentInRange()

```csharp
public void CheckAgentInRange()
```

### CheckTargetState(List<WorkerModel>)

```csharp
public void CheckTargetState(List<WorkerModel> list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.Generic.List{WorkerModel}` |  |

### ContainsAttackTarget(UnitModel)

```csharp
public bool ContainsAttackTarget(UnitModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### ContainsAttractedTargets(WorkerModel)

```csharp
public bool ContainsAttractedTargets(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### DeActivate()

```csharp
public override void DeActivate()
```

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### FreeAttractedAgent(WorkerModel)

```csharp
public void FreeAttractedAgent(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### MakeNote()

```csharp
public void MakeNote()
```

### OnAttractedTargetTerminated(WorkerModel)

```csharp
public void OnAttractedTargetTerminated(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### OnObserveLevelChanged()

```csharp
public override void OnObserveLevelChanged()
```

### OnStageRelease()

```csharp
public override void OnStageRelease()
```

### OnStageStart()

```csharp
public override void OnStageStart()
```

### RemoveAttackTarget(UnitModel)

```csharp
public void RemoveAttackTarget(UnitModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.UnitModel` |  |

### SetSuppressed()

```csharp
public void SetSuppressed()
```

### SetTargetState(WorkerModel)

```csharp
public void SetTargetState(WorkerModel wm)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `wm` | `Global.WorkerModel` |  |

### SkillActivate(WorkerModel)

```csharp
public override void SkillActivate(WorkerModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.WorkerModel` |  |

### StopNote()

```csharp
public void StopNote()
```
