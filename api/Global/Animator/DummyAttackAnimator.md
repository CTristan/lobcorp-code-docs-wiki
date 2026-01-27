---
uid: Global.DummyAttackAnimator
canonical_path: /api/Global/Animator/DummyAttackAnimator
---

# Class DummyAttackAnimator

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DummyAttackAnimator
```
Default animator for attacking?
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DummyAttackAnimator

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DummyAttackAnimator()

```csharp
public DummyAttackAnimator()
```

## Fields

### _animationEndCallback

```csharp
private DummyAttackAnimator.Callback _animationEndCallback
```

#### Field Value

**Type:** Global.DummyAttackAnimator.Callback

### _attackDuration

```csharp
private float _attackDuration
```
#INC


#### Field Value

**Type:** System.Single

### timer

```csharp
private Timer timer
```
#INC


#### Field Value

**Type:** Global.Timer

## Methods

### EndAttack()

```csharp
public void EndAttack()
```
#INC


### EndAttackCycle()

```csharp
private void EndAttackCycle()
```
#INC


### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```
#INC


### PlayAttackAnimation(Callback)

```csharp
public void PlayAttackAnimation(DummyAttackAnimator.Callback animationEndCallback)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animationEndCallback` | `Global.DummyAttackAnimator.Callback` |  |

### SetAttackDuraction(int)

```csharp
public void SetAttackDuraction(int duration)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `duration` | `System.Int32` |  |
