---
uid: Global.DesireHeart.DesireHeartKit
canonical_path: /api/Global/Misc/DesireHeartDesireHeartKit
---

# Class DesireHeart.DesireHeartKit

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DesireHeart.DesireHeartKit : CreatureBase.KitEquipEventListener
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase.KitEquipEventListener](/api/Global/Misc/CreatureBaseKitEquipEventListener) → DesireHeart.DesireHeartKit

## Inherited Members
[OnEnterRoom(AgentModel, UseSkill)](/api/Global/Misc/CreatureBaseKitEquipEventListener#onenterroom-agentmodel-useskill), [OnTakeDamagePhysical(WorkerModel, float)](/api/Global/Misc/CreatureBaseKitEquipEventListener#ontakedamagephysical-workermodel-float), [OnTakeDamageMental(WorkerModel, float)](/api/Global/Misc/CreatureBaseKitEquipEventListener#ontakedamagemental-workermodel-float), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DesireHeartKit(DesireHeart)

```csharp
public DesireHeartKit(DesireHeart m)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `m` | `Global.DesireHeart` |  |

## Fields

### _attacked

```csharp
private bool _attacked
```

#### Field Value

**Type:** System.Boolean

### _equipElapsedTime

```csharp
private float _equipElapsedTime
```

#### Field Value

**Type:** System.Single

### anim

```csharp
private KitEquipCreatureAnim anim
```

#### Field Value

**Type:** Global.KitEquipCreatureAnim

### model

```csharp
private DesireHeart model
```

#### Field Value

**Type:** Global.DesireHeart

## Methods

### OnAttack(AgentModel, UnitModel)

```csharp
public override void OnAttack(AgentModel actor, UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |
| `target` | `Global.UnitModel` |  |

### OnCommandReleaseKitEquip(AgentModel)

```csharp
public override void OnCommandReleaseKitEquip(AgentModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

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
