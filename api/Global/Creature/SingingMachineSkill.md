---
uid: Global.SingingMachineSkill
canonical_path: /api/Global/Creature/SingingMachineSkill
---

# Class SingingMachineSkill

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SingingMachineSkill : CreatureSpecialSkill, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureSpecialSkill](/api/Global/IOBserver/CreatureSpecialSkill) → SingingMachineSkill

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[model](/api/Global/IOBserver/CreatureSpecialSkill#model), [sefira](/api/Global/IOBserver/CreatureSpecialSkill#sefira), [Activated](/api/Global/IOBserver/CreatureSpecialSkill#activated), [SkillActivate()](/api/Global/IOBserver/CreatureSpecialSkill#skillactivate), [Activate()](/api/Global/IOBserver/CreatureSpecialSkill#activate), [OnNotice(string, params object[])](/api/Global/IOBserver/CreatureSpecialSkill#onnotice-string-params-object), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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

### attackTargets

```csharp
private List<UnitModel> attackTargets
```

#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

### Attracted

```csharp
private bool Attracted
```

#### Field Value

**Type:** System.Boolean

### attractTarget

```csharp
public List<WorkerModel> attractTarget
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

### elapsed

```csharp
private float elapsed
```

#### Field Value

**Type:** System.Single

### frequency

```csharp
private const float frequency = 5
```

#### Field Value

**Type:** System.Single

### machineNote

```csharp
private GameObject machineNote
```

#### Field Value

**Type:** UnityEngine.GameObject

### machinePos

```csharp
private Vector3 machinePos
```

#### Field Value

**Type:** UnityEngine.Vector3

### musicDuration

```csharp
private float musicDuration
```

#### Field Value

**Type:** System.Single

### musicTimer

```csharp
private float musicTimer
```

#### Field Value

**Type:** System.Single

### NoteEffect

```csharp
private string NoteEffect
```

#### Field Value

**Type:** System.String

### passageModel

```csharp
private PassageObjectModel passageModel
```

#### Field Value

**Type:** Global.PassageObjectModel

### passageNode

```csharp
private MapNode passageNode
```

#### Field Value

**Type:** Global.MapNode

### passageNote

```csharp
private GameObject passageNote
```

#### Field Value

**Type:** UnityEngine.GameObject

### PlayingMusic

```csharp
private bool PlayingMusic
```

#### Field Value

**Type:** System.Boolean

### speech_attract

```csharp
private const string speech_attract = "attract"
```

#### Field Value

**Type:** System.String

### targetList

```csharp
private List<WorkerModel> targetList
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

### waitForAgentWorkEnd

```csharp
private bool waitForAgentWorkEnd
```

#### Field Value

**Type:** System.Boolean

### workedList

```csharp
private List<AgentModel> workedList
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentModel}

### Working

```csharp
private bool Working
```

#### Field Value

**Type:** System.Boolean

### workingAttracted

```csharp
private AgentModel workingAttracted
```

#### Field Value

**Type:** Global.AgentModel

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

### AttractOneWorker(WorkerModel)

```csharp
private void AttractOneWorker(WorkerModel wm)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `wm` | `Global.WorkerModel` |  |

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

### IObserver.OnNotice(string, params object[])

```csharp
void IObserver.OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

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

### SpecialSkill(WorkerModel, int)

```csharp
private void SpecialSkill(WorkerModel target, int type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `type` | `System.Int32` |  |

### StopNote()

```csharp
public void StopNote()
```
