---
uid: Global.CreatureBase.KitEquipEventListener
canonical_path: /api/Global/Misc/CreatureBaseKitEquipEventListener
---

# Class CreatureBase.KitEquipEventListener

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureBase.KitEquipEventListener
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureBase.KitEquipEventListener

## Derived
[DesireHeart.DesireHeartKit](/api/Global/Misc/DesireHeartDesireHeartKit), [HealthBracelet.HealthBraceletKit](/api/Global/Misc/HealthBraceletHealthBraceletKit), [JusticeReceiver.JusticeReceiverKit](/api/Global/Misc/JusticeReceiverJusticeReceiverKit), [ResearcherNote.ResearcherNoteKit](/api/Global/Misc/ResearcherNoteResearcherNoteKit), [Yang.YangKit](/api/Global/Misc/YangYangKit)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### KitEquipEventListener()

```csharp
public KitEquipEventListener()
```

## Methods

### OnAttack(AgentModel, UnitModel)

```csharp
public virtual void OnAttack(AgentModel actor, UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |
| `target` | `Global.UnitModel` |  |

### OnCommandReleaseKitEquip(AgentModel)

```csharp
public virtual void OnCommandReleaseKitEquip(AgentModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

### OnEnterRoom(AgentModel, UseSkill)

```csharp
public virtual void OnEnterRoom(AgentModel actor, UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |
| `skill` | `Global.UseSkill` |  |

### OnFixedUpdateInKitEquip(AgentModel)

```csharp
public virtual void OnFixedUpdateInKitEquip(AgentModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

### OnReleaseKitEquip(AgentModel, bool)

```csharp
public virtual void OnReleaseKitEquip(AgentModel actor, bool stageEnd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |
| `stageEnd` | `System.Boolean` |  |

### OnTakeDamageMental(WorkerModel, float)

```csharp
public virtual void OnTakeDamageMental(WorkerModel actor, float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.WorkerModel` |  |
| `damage` | `System.Single` |  |

### OnTakeDamagePhysical(WorkerModel, float)

```csharp
public virtual void OnTakeDamagePhysical(WorkerModel actor, float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.WorkerModel` |  |
| `damage` | `System.Single` |  |

### OnUseKit(AgentModel)

```csharp
public virtual void OnUseKit(AgentModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

### OnViewInit(CreatureUnit)

```csharp
public virtual void OnViewInit(CreatureUnit unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |
