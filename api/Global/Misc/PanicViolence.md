---
uid: Global.PanicViolence
canonical_path: /api/Global/Misc/PanicViolence
---

# Class PanicViolence

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicViolence : PanicAction
```

Panic behaviour for an [agent](/api/Global/Worker/AgentModel) to indiscriminately attack employees around them.
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [PanicAction](/api/Global/Action/PanicAction) → PanicViolence

## Inherited Members
[OnDie()](/api/Global/Action/PanicAction#ondie), [PanicEnd()](/api/Global/Action/PanicAction#panicend), [GetMovementMultiplier()](/api/Global/Action/PanicAction#getmovementmultiplier), [GetDefenseMultiplier()](/api/Global/Action/PanicAction#getdefensemultiplier), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PanicViolence(AgentModel)

```csharp
public PanicViolence(AgentModel actor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

## Fields

### actor

```csharp
private AgentModel actor
```
#INC


#### Field Value

**Type:** Global.AgentModel

### suicideCooltime

```csharp
private const int suicideCooltime = 60
```
#INC


#### Field Value

**Type:** System.Int32

### suicideTimer

```csharp
private Timer suicideTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### target

```csharp
private UnitModel target
```
#INC


#### Field Value

**Type:** Global.UnitModel

### unit

```csharp
private AgentUnit unit
```
#INC


#### Field Value

**Type:** Global.AgentUnit

## Methods

### Execute()

```csharp
public override void Execute()
```
#INC


### GetAttackSpeedMultiplier()

```csharp
public override float GetAttackSpeedMultiplier()
```
#INC


#### Returns

**Type:** System.Single

### Init()

```csharp
public override void Init()
```
#INC
#code-generated

