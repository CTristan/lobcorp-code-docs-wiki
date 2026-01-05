# Class JusticeReceiver.JusticeReceiverKit

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class JusticeReceiver.JusticeReceiverKit : CreatureBase.KitEquipEventListener
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase.KitEquipEventListener](/api/CreatureBase-KitEquipEventListener) → JusticeReceiver.JusticeReceiverKit

## Inherited Members
[OnEnterRoom(AgentModel, UseSkill)](/api/CreatureBase-KitEquipEventListener#onenterroom-agentmodel-useskill), [OnAttack(AgentModel, UnitModel)](/api/CreatureBase-KitEquipEventListener#onattack-agentmodel-unitmodel), [OnTakeDamagePhysical(WorkerModel, float)](/api/CreatureBase-KitEquipEventListener#ontakedamagephysical-workermodel-float), [OnTakeDamageMental(WorkerModel, float)](/api/CreatureBase-KitEquipEventListener#ontakedamagemental-workermodel-float), [OnCommandReleaseKitEquip(AgentModel)](/api/CreatureBase-KitEquipEventListener#oncommandreleasekitequip-agentmodel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### JusticeReceiverKit(JusticeReceiver)

```csharp
public JusticeReceiverKit(JusticeReceiver m)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `m` | `Global.JusticeReceiver` |  |

## Methods

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
