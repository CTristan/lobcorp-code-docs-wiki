---
uid: Global.WorkerManager
canonical_path: /api/Global/Worker/WorkerManager
---

# Class WorkerManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerManager
```
Manages workers.

Holds an [AgentManager](/api/Global/IOBserver/AgentManager) and [OfficerManager](/api/Global/Misc/OfficerManager).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerManager()

```csharp
public WorkerManager()
```
#INC
#code-generated


## Fields

### _instance

```csharp
private static WorkerManager _instance
```
#INC


#### Field Value

**Type:** Global.WorkerManager

### agentManager

```csharp
private AgentManager agentManager
```
#INC


#### Field Value

**Type:** Global.AgentManager

### nextInstId

```csharp
private long nextInstId
```
#INC


#### Field Value

**Type:** System.Int64

### officerManager

```csharp
private OfficerManager officerManager
```
#INC


#### Field Value

**Type:** Global.OfficerManager

### workerList

```csharp
private List<WorkerModel> workerList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### GetWorkerList()

```csharp
public List<WorkerModel> GetWorkerList()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{WorkerModel}

### RemoveWorker(WorkerModel)

```csharp
public void RemoveWorker(WorkerModel worker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### RemoveWorkers(WorkerModel[])

```csharp
public void RemoveWorkers(WorkerModel[] workers)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `workers` | `Global.WorkerModel[]` |  |
