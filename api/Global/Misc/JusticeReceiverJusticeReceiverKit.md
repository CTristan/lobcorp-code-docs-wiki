---
uid: Global.JusticeReceiver.JusticeReceiverKit
canonical_path: /api/Global/Misc/JusticeReceiverJusticeReceiverKit
---

# Class JusticeReceiver.JusticeReceiverKit

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class JusticeReceiver.JusticeReceiverKit : CreatureBase.KitEquipEventListener
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase.KitEquipEventListener](/api/Global/Misc/CreatureBaseKitEquipEventListener) → JusticeReceiver.JusticeReceiverKit

## Inherited Members
[OnEnterRoom(AgentModel, UseSkill)](/api/Global/Misc/CreatureBaseKitEquipEventListener#onenterroom-agentmodel-useskill), [OnAttack(AgentModel, UnitModel)](/api/Global/Misc/CreatureBaseKitEquipEventListener#onattack-agentmodel-unitmodel), [OnTakeDamagePhysical(WorkerModel, float)](/api/Global/Misc/CreatureBaseKitEquipEventListener#ontakedamagephysical-workermodel-float), [OnTakeDamageMental(WorkerModel, float)](/api/Global/Misc/CreatureBaseKitEquipEventListener#ontakedamagemental-workermodel-float), [OnCommandReleaseKitEquip(AgentModel)](/api/Global/Misc/CreatureBaseKitEquipEventListener#oncommandreleasekitequip-agentmodel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### JusticeReceiverKit(JusticeReceiver)

```csharp
public JusticeReceiverKit(JusticeReceiver m)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `m` | `Global.JusticeReceiver` |  |

## Fields

### _AMOUNT_JUSTICE

```csharp
private const int _AMOUNT_JUSTICE = 15
```

#### Field Value

**Type:** System.Int32

### _AMOUNT_PRUDENCE

```csharp
private const int _AMOUNT_PRUDENCE = -10
```

#### Field Value

**Type:** System.Int32

### _anim

```csharp
private KitEquipCreatureAnim _anim
```

#### Field Value

**Type:** Global.KitEquipCreatureAnim

### _equipAgent

```csharp
private AgentModel _equipAgent
```

#### Field Value

**Type:** Global.AgentModel

### _equipElapsedTime

```csharp
private float _equipElapsedTime
```

#### Field Value

**Type:** System.Single

### _LIMIT_USED_TIME

```csharp
private const float _LIMIT_USED_TIME = 30
```

#### Field Value

**Type:** System.Single

### _model

```csharp
private JusticeReceiver _model
```

#### Field Value

**Type:** Global.JusticeReceiver

### _SOUND_SRC_DEAD1

```csharp
private const string _SOUND_SRC_DEAD1 = "creature/JusticeReceiver/Justice_Dead1"
```

#### Field Value

**Type:** System.String

### _SOUND_SRC_DEAD2

```csharp
private const string _SOUND_SRC_DEAD2 = "creature/JusticeReceiver/Justice_Dead2"
```

#### Field Value

**Type:** System.String

## Methods

### MakeAgentDeadSound(int)

```csharp
private void MakeAgentDeadSound(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

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
