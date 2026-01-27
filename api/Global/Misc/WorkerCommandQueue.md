---
uid: Global.WorkerCommandQueue
canonical_path: /api/Global/Misc/WorkerCommandQueue
---

# Class WorkerCommandQueue

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerCommandQueue
```
Holds a list of [worker commands](/api/Global/Misc/WorkerCommand) to be completed.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerCommandQueue

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerCommandQueue(WorkerModel)

```csharp
public WorkerCommandQueue(WorkerModel actor)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.WorkerModel` |  |

## Fields

### actor

```csharp
private WorkerModel actor
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### queue

```csharp
private LinkedList<WorkerCommand> queue
```
#INC


#### Field Value

**Type:** System.Collections.Generic.LinkedList{WorkerCommand}

## Methods

### AddFirst(WorkerCommand)

```csharp
public void AddFirst(WorkerCommand cmd)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.WorkerCommand` |  |

### AddLast(WorkerCommand)

```csharp
public void AddLast(WorkerCommand cmd)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.WorkerCommand` |  |

### Clear()

```csharp
public void Clear()
```
#INC


### ClearQueue(List<WorkerCommand>)

```csharp
private void ClearQueue(List<WorkerCommand> copied)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `copied` | `System.Collections.Generic.List{WorkerCommand}` |  |

### Execute(WorkerModel)

```csharp
public void Execute(WorkerModel agent)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.WorkerModel` |  |

### GetCurrentCmd()

```csharp
public WorkerCommand GetCurrentCmd()
```
#INC


#### Returns

**Type:** Global.WorkerCommand

### SetAgentCommand(WorkerCommand)

```csharp
public void SetAgentCommand(WorkerCommand cmd)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.WorkerCommand` |  |
