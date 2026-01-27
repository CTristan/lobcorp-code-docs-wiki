---
uid: Global.CreatureCommandQueue
canonical_path: /api/Global/Misc/CreatureCommandQueue
---

# Class CreatureCommandQueue

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureCommandQueue
```
Maintains a queue of [CreatureCommands](/api/Global/Misc/CreatureCommand) to execute.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureCommandQueue

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureCommandQueue(CreatureModel)

```csharp
public CreatureCommandQueue(CreatureModel creature)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

## Fields

### creature

```csharp
private CreatureModel creature
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### queue

```csharp
private LinkedList<CreatureCommand> queue
```
#INC


#### Field Value

**Type:** System.Collections.Generic.LinkedList{CreatureCommand}

## Methods

### AddFirst(CreatureCommand)

```csharp
public void AddFirst(CreatureCommand cmd)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.CreatureCommand` |  |

### AddLast(CreatureCommand)

```csharp
public void AddLast(CreatureCommand cmd)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.CreatureCommand` |  |

### Clear()

```csharp
public void Clear()
```
#INC


### Execute(CreatureModel)

```csharp
public void Execute(CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### GetCurrentCmd()

```csharp
public CreatureCommand GetCurrentCmd()
```
#INC


#### Returns

**Type:** Global.CreatureCommand

### SetAgentCommand(CreatureCommand)

```csharp
public void SetAgentCommand(CreatureCommand cmd)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.CreatureCommand` |  |
