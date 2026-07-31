---
title: DummyAttackAnimator
description: 
published: true
date: 2026-07-31T21:42:05.325Z
tags: 
editor: markdown
dateCreated: 2026-07-08T04:02:03.545Z
---

# Class DummyAttackAnimator
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DummyAttackAnimator
```

When a [`UnitModel`](/api/Global/Units/UnitModel) attacks, after four seconds (ten in the case of [Rabbits](/api/Global/Rabbits/Rabbit-Units/RabbitModel)), this class calls `_animationEndCallback`.

The callback is only ever [`UnitModel::OnEndAttackCycle`](/api/Global/Units/UnitModel#onendattackcycle), which calls [`WeaponModel::OnEndAttackCycle`](/api/Global/EGO/WeaponModel) if this unit has a weapon.



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DummyAttackAnimator

## Constructors
### DummyAttackAnimator()
```csharp
public DummyAttackAnimator()
```
Default constructor.

## Fields
### \_animationEndCallback
```csharp
private DummyAttackAnimator.Callback _animationEndCallback
```
The callback for when the attack ends. **NOTE:** This may not be when the attack actually ends, since this is always called after four seconds (or ten in the case of [Rabbits](/api/Global/Rabbits/Rabbit-Units/RabbitModel)).

The callback is only ever [`UnitModel::OnEndAttackCycle`](/api/Global/Units/UnitModel#onendattackcycle), which calls [`WeaponModel::OnEndAttackCycle`](/api/Global/EGO/WeaponModel) if this unit has a weapon.
#### Field Value
**Type:** Global.DummyAttackAnimator.Callback

### \_attackDuration
```csharp
private float _attackDuration
```
The amount of time to wait after the attack starts before calling `_animationEndCallback`.

Always four seconds, except for [Rabbits](/api/Global/Rabbits/Rabbit-Units/RabbitModel), who set it to ten.

#### Field Value
**Type:** System.Single

### timer
```csharp
private Timer timer
```
Timer to track when the attack animation is supposedly finished.

#### Field Value
**Type:** Global.Timer

## Methods
### EndAttack()
```csharp
public void EndAttack()
```
Stops the timer and prevents the `_animationEndCallback` call.

### EndAttackCycle()
```csharp
private void EndAttackCycle()
```
Calls `_animationEndCallback`.

The callback is only ever [`UnitModel::OnEndAttackCycle`](/api/Global/Units/UnitModel#onendattackcycle), which calls [`WeaponModel::OnEndAttackCycle`](/api/Global/EGO/WeaponModel) if this unit has a weapon.

### OnFixedUpdate()
```csharp
public void OnFixedUpdate()
```
Runs the `timer`, and when it runs out runs [`EndAttackCycle`](/api/Global/Animation/DummyAttackAnimator#endattackcycle).

### PlayAttackAnimation(Callback)
```csharp
public void PlayAttackAnimation(DummyAttackAnimator.Callback animationEndCallback)
```
Starts the timer with the current `_attackDuration` (always four seconds, or ten seconds for [Rabbits](/api/Global/Rabbits/Rabbit-Units/RabbitModel)) and sets `_animationEndCallback` to the provided delegate function.

The callback is only ever [`UnitModel::OnEndAttackCycle`](/api/Global/Units/UnitModel#onendattackcycle), which calls [`WeaponModel::OnEndAttackCycle`](/api/Global/EGO/WeaponModel) if this unit has a weapon.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `animationEndCallback` | `Global.DummyAttackAnimator.Callback` | The function to call once the timer runs out. |

### SetAttackDuraction(int)
```csharp
public void SetAttackDuraction(int duration)
```
Sets the attack duration (`_attackDuration`) to `duration`. Only used by Rabbits ([`RabbitModel::RabbitModel(RwbpType)`](/api/Global/Rabbits/Rabbit-Units/RabbitModel#rabbitmodelrwbptype)), who set it to `10f`.

Default value for `_attackDuration` is `4f`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `duration` | `System.Int32` | The amount of time to wait before calling `_animationEndCallback`. |

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)









