---
uid: Global.PanicRoaming
canonical_path: /api/Global/Misc/PanicRoaming
---

# Class PanicRoaming

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicRoaming : PanicAction
```

Panic behaviour for an [agent](/api/Global/Worker/AgentModel) to run wildly.
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [PanicAction](/api/Global/Action/PanicAction) → PanicRoaming

## Inherited Members
[GetAttackSpeedMultiplier()](/api/Global/Action/PanicAction#getattackspeedmultiplier), [GetDefenseMultiplier()](/api/Global/Action/PanicAction#getdefensemultiplier), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PanicRoaming(AgentModel)

```csharp
public PanicRoaming(AgentModel actor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

## Fields

### _dmgTimer

```csharp
private Timer _dmgTimer
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

## Methods

### Execute()

```csharp
public override void Execute()
```
#INC


### GetMovementMultiplier()

```csharp
public override float GetMovementMultiplier()
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

