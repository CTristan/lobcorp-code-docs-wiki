---
uid: Global.AgentHistory
canonical_path: /api/Global/Misc/AgentHistory
---

# Class AgentHistory

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentHistory
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentHistory

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentHistory()

```csharp
public AgentHistory()
```

## Properties

### oneday

```csharp
private AgentHistory.History oneday { get; set; }
```

#### Property Value

**Type:** Global.AgentHistory.History

### Oneday

```csharp
public AgentHistory.History Oneday { get; }
```

#### Property Value

**Type:** Global.AgentHistory.History

### total

```csharp
private AgentHistory.History total { get; set; }
```

#### Property Value

**Type:** Global.AgentHistory.History

### Total

```csharp
public AgentHistory.History Total { get; }
```

#### Property Value

**Type:** Global.AgentHistory.History

### workDay

```csharp
private int workDay { get; set; }
```

#### Property Value

**Type:** System.Int32

### WorkDay

```csharp
public int WorkDay { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### AddPanic()

```csharp
public void AddPanic()
```

### AddWorkCubeCount(RwbpType, int)

```csharp
public void AddWorkCubeCount(RwbpType type, int val)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `val` | `System.Int32` |  |

### AddWorkDay()

```csharp
public void AddWorkDay()
```

### AddWorkFail()

```csharp
public void AddWorkFail()
```

### AddWorkSuccess()

```csharp
public void AddWorkSuccess()
```

### CreatureAttack(int)

```csharp
public void CreatureAttack(int damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |

### Disposition()

```csharp
public void Disposition()
```

### EndOneDay()

```csharp
public void EndOneDay()
```

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### MentalDamage(float)

```csharp
public void MentalDamage(float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Single` |  |

### PanicWorkerAttack(int)

```csharp
public void PanicWorkerAttack(int damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |

### PhysicalDamage(float)

```csharp
public void PhysicalDamage(float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Single` |  |

### SuccessCreatureSuppress()

```csharp
public void SuccessCreatureSuppress()
```

### SuccessWorkerSuppress()

```csharp
public void SuccessWorkerSuppress()
```

### Suppress(int)

```csharp
public void Suppress(int damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |

### WitnessDeathByCreature()

```csharp
public void WitnessDeathByCreature()
```

### WitnessDeathByWorker()

```csharp
public void WitnessDeathByWorker()
```

### WitnessPanicByCreature()

```csharp
public void WitnessPanicByCreature()
```

### WorkerAttack(int)

```csharp
public void WorkerAttack(int damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |
