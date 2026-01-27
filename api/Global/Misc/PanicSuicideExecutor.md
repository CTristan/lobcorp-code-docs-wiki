---
uid: Global.PanicSuicideExecutor
canonical_path: /api/Global/Misc/PanicSuicideExecutor
---

# Class PanicSuicideExecutor

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicSuicideExecutor : PanicAction
```

Panic behaviour for an [agent](/api/Global/Worker/AgentModel) to commit suicide after a certain amount of time.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [PanicAction](/api/Global/Action/PanicAction) → PanicSuicideExecutor

## Inherited Members
[GetAttackSpeedMultiplier()](/api/Global/Action/PanicAction#getattackspeedmultiplier), [GetMovementMultiplier()](/api/Global/Action/PanicAction#getmovementmultiplier), [GetDefenseMultiplier()](/api/Global/Action/PanicAction#getdefensemultiplier), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PanicSuicideExecutor(AgentModel)

```csharp
public PanicSuicideExecutor(AgentModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

## Fields

### _suicideCooltime

```csharp
private int _suicideCooltime
```
#INC


#### Field Value

**Type:** System.Int32

### _suicideExecuted

```csharp
private bool _suicideExecuted
```
#INC


#### Field Value

**Type:** System.Boolean

### _suicideTimer

```csharp
private Timer _suicideTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### actor

```csharp
private AgentModel actor
```
#INC


#### Field Value

**Type:** Global.AgentModel

### suicideWDmg

```csharp
public const int suicideWDmg = 20
```
#INC


#### Field Value

**Type:** System.Int32

## Methods

### Execute()

```csharp
public override void Execute()
```
#INC


### ExecuteSuicide()

```csharp
private void ExecuteSuicide()
```
#INC


### Init()

```csharp
public override void Init()
```
#INC
#code-generated


### OnAgentAnimEvent(int)

```csharp
public void OnAgentAnimEvent(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnDie()

```csharp
public override void OnDie()
```
#INC


### PanicEnd()

```csharp
public override void PanicEnd()
```
#INC

