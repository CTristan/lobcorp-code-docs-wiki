# Class WorkerManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### WorkerManager()

```csharp
public WorkerManager()
```

## Properties

### instance

```csharp
public static WorkerManager instance { get; }
```

#### Property Value

**Type:** Global.WorkerManager

## Methods

### AddWorker(WorkerModel)

```csharp
public void AddWorker(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### GetWorkerList()

```csharp
public List<WorkerModel> GetWorkerList()
```

#### Returns

**Type:** System.Collections.Generic.List{WorkerModel}

### RemoveWorker(WorkerModel)

```csharp
public void RemoveWorker(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### RemoveWorkers(WorkerModel[])

```csharp
public void RemoveWorkers(WorkerModel[] workers)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `workers` | `Global.WorkerModel[]` |  |
