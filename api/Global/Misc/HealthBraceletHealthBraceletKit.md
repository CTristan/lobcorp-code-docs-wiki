---
uid: Global.HealthBracelet.HealthBraceletKit
canonical_path: /api/Global/Misc/HealthBraceletHealthBraceletKit
---

# Class HealthBracelet.HealthBraceletKit

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class HealthBracelet.HealthBraceletKit : CreatureBase.KitEquipEventListener
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase.KitEquipEventListener](/api/Global/Misc/CreatureBaseKitEquipEventListener) → HealthBracelet.HealthBraceletKit

## Inherited Members
[OnEnterRoom(AgentModel, UseSkill)](/api/Global/Misc/CreatureBaseKitEquipEventListener#onenterroom-agentmodel-useskill), [OnAttack(AgentModel, UnitModel)](/api/Global/Misc/CreatureBaseKitEquipEventListener#onattack-agentmodel-unitmodel), [OnTakeDamagePhysical(WorkerModel, float)](/api/Global/Misc/CreatureBaseKitEquipEventListener#ontakedamagephysical-workermodel-float), [OnTakeDamageMental(WorkerModel, float)](/api/Global/Misc/CreatureBaseKitEquipEventListener#ontakedamagemental-workermodel-float), [OnCommandReleaseKitEquip(AgentModel)](/api/Global/Misc/CreatureBaseKitEquipEventListener#oncommandreleasekitequip-agentmodel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### HealthBraceletKit(HealthBracelet)

```csharp
public HealthBraceletKit(HealthBracelet m)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `m` | `Global.HealthBracelet` |  |

## Fields

### _AMOUNT_BUF_FORTITUDE

```csharp
private const int _AMOUNT_BUF_FORTITUDE = 15
```

#### Field Value

**Type:** System.Int32

### _AMOUNT_RECOVERY

```csharp
private const float _AMOUNT_RECOVERY = 2.4
```

#### Field Value

**Type:** System.Single

### _anim

```csharp
private KitEquipCreatureAnim _anim
```

#### Field Value

**Type:** Global.KitEquipCreatureAnim

### _checkMaxHp

```csharp
private bool _checkMaxHp
```

#### Field Value

**Type:** System.Boolean

### _equipElapsedTime

```csharp
private float _equipElapsedTime
```

#### Field Value

**Type:** System.Single

### _FREQ_RECOVERY

```csharp
private const float _FREQ_RECOVERY = 3
```

#### Field Value

**Type:** System.Single

### _model

```csharp
private HealthBracelet _model
```

#### Field Value

**Type:** Global.HealthBracelet

### _recoveryTimer

```csharp
private Timer _recoveryTimer
```

#### Field Value

**Type:** Global.Timer

### _safeTimer

```csharp
private Timer _safeTimer
```

#### Field Value

**Type:** Global.Timer

### _TIME_DEAD

```csharp
private const float _TIME_DEAD = 60
```

#### Field Value

**Type:** System.Single

### _TIME_SAFETY

```csharp
private const float _TIME_SAFETY = 15
```

#### Field Value

**Type:** System.Single

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
