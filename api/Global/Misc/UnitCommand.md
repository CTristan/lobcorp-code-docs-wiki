---
uid: Global.UnitCommand
canonical_path: /api/Global/Misc/UnitCommand
---

# Class UnitCommand

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnitCommand
```
A behaviour for a unit (agent, clerk, abnormality, rabbit) to use.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → UnitCommand

## Derived
[RabbitMovingAttackCommand](/api/Global/Misc/RabbitMovingAttackCommand), [StandingCommand](/api/Global/Misc/StandingCommand), [WorkerCommand](/api/Global/Misc/WorkerCommand)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UnitCommand()

```csharp
public UnitCommand()
```

## Fields

### actor

```csharp
public UnitModel actor
```
#INC


#### Field Value

**Type:** Global.UnitModel

### isFinished

```csharp
public bool isFinished
```
#INC


#### Field Value

**Type:** System.Boolean

### isRemoved

```csharp
public bool isRemoved
```
#INC


#### Field Value

**Type:** System.Boolean

## Methods

### Execute()

```csharp
public virtual void Execute()
```
#INC


### Finish()

```csharp
public void Finish()
```
#INC


### OnDestroy()

```csharp
public virtual void OnDestroy()
```
#INC


### OnInit(StandingItemModel)

```csharp
public virtual void OnInit(StandingItemModel standing)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `standing` | `Global.StandingItemModel` |  |

### OnInit(UnitModel)

```csharp
public virtual void OnInit(UnitModel actor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnInit(WorkerModel)

```csharp
public virtual void OnInit(WorkerModel worker)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### OnStart()

```csharp
public virtual void OnStart()
```
#INC


### OnStop()

```csharp
public virtual void OnStop()
```
#INC

