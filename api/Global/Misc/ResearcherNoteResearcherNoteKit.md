---
uid: Global.ResearcherNote.ResearcherNoteKit
canonical_path: /api/Global/Misc/ResearcherNoteResearcherNoteKit
---

# Class ResearcherNote.ResearcherNoteKit

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResearcherNote.ResearcherNoteKit : CreatureBase.KitEquipEventListener
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase.KitEquipEventListener](/api/Global/Misc/CreatureBaseKitEquipEventListener) → ResearcherNote.ResearcherNoteKit

## Inherited Members
[OnAttack(AgentModel, UnitModel)](/api/Global/Misc/CreatureBaseKitEquipEventListener#onattack-agentmodel-unitmodel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ResearcherNoteKit(ResearcherNote)

```csharp
public ResearcherNoteKit(ResearcherNote m)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `m` | `Global.ResearcherNote` |  |

## Fields

### _creatureManaged

```csharp
private bool _creatureManaged
```

#### Field Value

**Type:** System.Boolean

### _equipElapsedTime

```csharp
private float _equipElapsedTime
```

#### Field Value

**Type:** System.Single

### _gainedDamage

```csharp
private float _gainedDamage
```

#### Field Value

**Type:** System.Single

### anim

```csharp
private KitEquipCreatureAnim anim
```

#### Field Value

**Type:** Global.KitEquipCreatureAnim

### damageLimit

```csharp
private const float damageLimit = 60
```

#### Field Value

**Type:** System.Single

### model

```csharp
private ResearcherNote model
```

#### Field Value

**Type:** Global.ResearcherNote

## Methods

### OnCommandReleaseKitEquip(AgentModel)

```csharp
public override void OnCommandReleaseKitEquip(AgentModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

### OnEnterRoom(AgentModel, UseSkill)

```csharp
public override void OnEnterRoom(AgentModel actor, UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |
| `skill` | `Global.UseSkill` |  |

### OnFixedUpdateInKitEquip(AgentModel)

```csharp
public override void OnFixedUpdateInKitEquip(AgentModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

### OnReleaseKitEquip(AgentModel, bool)

```csharp
public override void OnReleaseKitEquip(AgentModel actor, bool stageEnd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |
| `stageEnd` | `System.Boolean` |  |

### OnTakeDamageMental(WorkerModel, float)

```csharp
public override void OnTakeDamageMental(WorkerModel actor, float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.WorkerModel` |  |
| `damage` | `System.Single` |  |

### OnTakeDamagePhysical(WorkerModel, float)

```csharp
public override void OnTakeDamagePhysical(WorkerModel actor, float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.WorkerModel` |  |
| `damage` | `System.Single` |  |

### OnUseKit(AgentModel)

```csharp
public override void OnUseKit(AgentModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

### OnViewInit(CreatureUnit)

```csharp
public override void OnViewInit(CreatureUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |
