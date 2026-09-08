---
title: PanicReady
description: 
published: true
date: 2026-09-08T19:02:30.719Z
tags: 
editor: markdown
dateCreated: 2026-07-08T15:12:29.389Z
---

# Class PanicReady
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicReady : PanicAction
```
> This section may have incomplete or incorrect information.
{.is-warning}


Panic behaviour for an [`WorkerModel`](/api/Global/Agents-and-Clerks/WorkerModel) worker getting ready to panic.

Ends by calling [`PanicReadyComplete`](/api/Global/Agents-and-Clerks/WorkerModel#panicreadycomplete), which decides the actual [`PanicAction`](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction) to perform.

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [PanicAction](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction) → PanicReady

## Derived
[BlackLovePanicReady](/api/Global/Abnormalities/Army-in-Black/BlackLovePanicReady)

## Constructors
### PanicReady(WorkerModel)
```csharp
public PanicReady(WorkerModel target)
```
Sets the [`WorkerModel`](/api/Global/Agents-and-Clerks/WorkerModel) this action belongs to and resets the `elapsedTime` timer.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` | The `WorkerModel` this `PanicReady` belongs to. |

## Fields
### actor
```csharp
protected WorkerModel actor
```
The [`WorkerModel`](/api/Global/Agents-and-Clerks/WorkerModel) this `PanicReady` action belongs to.

#### Field Value
**Type:** Global.WorkerModel

### elapsedTime
```csharp
protected float elapsedTime
```
The amount of time that has passed since this `PanicReady` action was created.

#### Field Value
**Type:** System.Single

### waitTime
```csharp
protected float waitTime
```
The amount of time to wait before starting the panic action.

#### Field Value
**Type:** System.Single

## Methods
### Execute()
```csharp
public override void Execute()
```
If the room the `actor` is in is a containment unit, starts navigating them to a random main room (see [`MapGraph::GetSepiraNodeByRandom`](/api/Global/Map/MapGraph#getsepiranodebyrandomstring)^[sic]^) to move them out of the room, then return immediately.

Clears any normal actions this unit would be doing, then increments the `elapsedTime`. If the `elapsedTime` exceeds the `waitTime`, starts the panic action with [`StartPanicAction`](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicReady#startpanicaction).

### Init()
```csharp
public override void Init()
```
If the unit is halted (only used by [`LadyLookingAtWall`](/api/Global/Abnormalities/The-Lady-Facing-the-Wall/LadyLookingAtWall)), releases them.

If the worker is not an [agent](/api/Global/Agents-and-Clerks/Agents/AgentModel) (i.e., is a clerk), sets the wait time to `1f` (this is the same as the default value).

Sets the worker to have the panic face (see [`WorkerModel::SetWorkerFaceType`](/api/Global/Agents-and-Clerks/WorkerModel#setworkerfacetypeworkerfacetype)) and panic animation (see [`WorkerModel::SetPanicAnim`](/api/Global/Agents-and-Clerks/WorkerModel#setpanicanimbool)).

### PanicEnd()
```csharp
public override void PanicEnd()
```
Empty.

### StartPanicAction()
```csharp
public void StartPanicAction()
```
If the actor unit is an [agent](/api/Global/Agents-and-Clerks/Agents/AgentUnit), calls [`AgentUnit::OnChangeWeapon`](/api/Global/Agents-and-Clerks/Agents/AgentUnit).

For any worker, calls [`PanicReadyComplete`](/api/Global/Agents-and-Clerks/WorkerModel#panicreadycomplete).

## Inherited Members
[OnDie()](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction#ondie), [GetAttackSpeedMultiplier()](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction#getattackspeedmultiplier), [GetMovementMultiplier()](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction#getmovementmultiplier), [GetDefenseMultiplier()](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction#getdefensemultiplier), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






