# Class ViscusSnakeBuf.InfectionCheckInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ViscusSnakeBuf.InfectionCheckInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ViscusSnakeBuf.InfectionCheckInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### InfectionCheckInfo(WorkerModel)

```csharp
public InfectionCheckInfo(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

## Fields

### worker

```csharp
public WorkerModel worker
```

#### Field Value

**Type:** Global.WorkerModel

## Properties

### IsExpired

```csharp
public bool IsExpired { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### FixedUpdate()

```csharp
public void FixedUpdate()
```
