# Class WorkerCommandQueue

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerCommandQueue
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerCommandQueue

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### WorkerCommandQueue(WorkerModel)

```csharp
public WorkerCommandQueue(WorkerModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.WorkerModel` |  |

## Methods

### AddFirst(WorkerCommand)

```csharp
public void AddFirst(WorkerCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.WorkerCommand` |  |

### AddLast(WorkerCommand)

```csharp
public void AddLast(WorkerCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.WorkerCommand` |  |

### Clear()

```csharp
public void Clear()
```

### Execute(WorkerModel)

```csharp
public void Execute(WorkerModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.WorkerModel` |  |

### GetCurrentCmd()

```csharp
public WorkerCommand GetCurrentCmd()
```

#### Returns

**Type:** Global.WorkerCommand

### SetAgentCommand(WorkerCommand)

```csharp
public void SetAgentCommand(WorkerCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.WorkerCommand` |  |
