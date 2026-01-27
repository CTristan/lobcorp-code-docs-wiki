---
uid: Global.PanicOfficer
canonical_path: /api/Global/Misc/PanicOfficer
---

# Class PanicOfficer

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicOfficer : PanicAction
```

Clerks' panic behaviour. #INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [PanicAction](/api/Global/Action/PanicAction) → PanicOfficer

## Inherited Members
[OnDie()](/api/Global/Action/PanicAction#ondie), [GetAttackSpeedMultiplier()](/api/Global/Action/PanicAction#getattackspeedmultiplier), [GetMovementMultiplier()](/api/Global/Action/PanicAction#getmovementmultiplier), [GetDefenseMultiplier()](/api/Global/Action/PanicAction#getdefensemultiplier), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PanicOfficer(WorkerModel)

```csharp
public PanicOfficer(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

## Fields

### _retryTimer

```csharp
private Timer _retryTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _returnPanicTimer

```csharp
private Timer _returnPanicTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _state

```csharp
private PanicOfficer.OfficerPanicState _state
```

#### Field Value

**Type:** Global.PanicOfficer.OfficerPanicState

### actor

```csharp
private WorkerModel actor
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### suicideProb

```csharp
private const float suicideProb = 0.1
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### Execute()

```csharp
public override void Execute()
```
#INC


### Init()

```csharp
public override void Init()
```
#INC
#code-generated


### PanicEnd()

```csharp
public override void PanicEnd()
```
#INC


### TrySuicide()

```csharp
public void TrySuicide()
```
#INC

