# Class AgentHistory.History

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentHistory.History
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentHistory.History

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### History()

```csharp
public History()
```

## Fields

### workCubeCounts

```csharp
public Dictionary<RwbpType, int> workCubeCounts
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{RwbpType,System.Int32}

## Properties

### creatureDamage

```csharp
public int creatureDamage { get; set; }
```

#### Property Value

**Type:** System.Int32

### deathByCreature

```csharp
public int deathByCreature { get; set; }
```

#### Property Value

**Type:** System.Int32

### deathByWorker

```csharp
public int deathByWorker { get; set; }
```

#### Property Value

**Type:** System.Int32

### disposal

```csharp
public int disposal { get; set; }
```

#### Property Value

**Type:** System.Int32

### panic

```csharp
public int panic { get; set; }
```

#### Property Value

**Type:** System.Int32

### panicByCreature

```csharp
public int panicByCreature { get; set; }
```

#### Property Value

**Type:** System.Int32

### panicWorkerDamage

```csharp
public int panicWorkerDamage { get; set; }
```

#### Property Value

**Type:** System.Int32

### promotionVal

```csharp
public int promotionVal { get; set; }
```

#### Property Value

**Type:** System.Int32

### suppressDamage

```csharp
public int suppressDamage { get; set; }
```

#### Property Value

**Type:** System.Int32

### takeMentalDamage

```csharp
public int takeMentalDamage { get; set; }
```

#### Property Value

**Type:** System.Int32

### takePhysicalDamage

```csharp
public int takePhysicalDamage { get; set; }
```

#### Property Value

**Type:** System.Int32

### workerDamage

```csharp
public int workerDamage { get; set; }
```

#### Property Value

**Type:** System.Int32

### workFail

```csharp
public int workFail { get; set; }
```

#### Property Value

**Type:** System.Int32

### workSuccess

```csharp
public int workSuccess { get; set; }
```

#### Property Value

**Type:** System.Int32

## Methods

### AddPanic()

```csharp
public void AddPanic()
```

### AddWorkCount(RwbpType, int)

```csharp
public void AddWorkCount(RwbpType type, int val)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `val` | `System.Int32` |  |

### AddWorkFail()

```csharp
public void AddWorkFail()
```

### AddWorkSuccess()

```csharp
public void AddWorkSuccess()
```

### Clear()

```csharp
public void Clear()
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

### GetWorkCount(RwbpType)

```csharp
public int GetWorkCount(RwbpType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

#### Returns

**Type:** System.Int32

### MentalDamage(int)

```csharp
public void MentalDamage(int damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |

### PanicWorkerAttack(int)

```csharp
public void PanicWorkerAttack(int damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |

### PhysicalDamage(int)

```csharp
public void PhysicalDamage(int damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |

### PromotionValAdd(int)

```csharp
public void PromotionValAdd(int val)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Int32` |  |

### PromotionValReset()

```csharp
public void PromotionValReset()
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

### WorkResult(bool)

```csharp
public void WorkResult(bool result)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `result` | `System.Boolean` |  |
