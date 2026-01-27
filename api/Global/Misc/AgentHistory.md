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
Stores a list of statistics about an [agent](/api/Global/Worker/AgentModel) -- damage taken, works succeeded, deaths and panics witnessed. This is odd, because I'm pretty sure the only one of these that would ever get used are the damages...

There seems to be an unused 'promotionVal' thing which may have served as EXP?

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentHistory

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentHistory()

```csharp
public AgentHistory()
```
#INC
#code-generated


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
#INC


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
#INC


### AddWorkCubeCount(RwbpType, int)

```csharp
public void AddWorkCubeCount(RwbpType type, int val)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `val` | `System.Int32` |  |

### AddWorkDay()

```csharp
public void AddWorkDay()
```
#INC


### AddWorkFail()

```csharp
public void AddWorkFail()
```
#INC


### AddWorkSuccess()

```csharp
public void AddWorkSuccess()
```
#INC


### CreatureAttack(int)

```csharp
public void CreatureAttack(int damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |

### Disposition()

```csharp
public void Disposition()
```
#INC


### EndOneDay()

```csharp
public void EndOneDay()
```
#INC


### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### MentalDamage(float)

```csharp
public void MentalDamage(float damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Single` |  |

### PanicWorkerAttack(int)

```csharp
public void PanicWorkerAttack(int damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |

### PhysicalDamage(float)

```csharp
public void PhysicalDamage(float damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Single` |  |

### SuccessCreatureSuppress()

```csharp
public void SuccessCreatureSuppress()
```
#INC


### SuccessWorkerSuppress()

```csharp
public void SuccessWorkerSuppress()
```
#INC


### Suppress(int)

```csharp
public void Suppress(int damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |

### WitnessDeathByCreature()

```csharp
public void WitnessDeathByCreature()
```
#INC


### WitnessDeathByWorker()

```csharp
public void WitnessDeathByWorker()
```
#INC


### WitnessPanicByCreature()

```csharp
public void WitnessPanicByCreature()
```
#INC


### WorkerAttack(int)

```csharp
public void WorkerAttack(int damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |
