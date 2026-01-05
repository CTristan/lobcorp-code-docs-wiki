# Class DummyAttackAnimator

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DummyAttackAnimator
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DummyAttackAnimator

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DummyAttackAnimator()

```csharp
public DummyAttackAnimator()
```

## Methods

### EndAttack()

```csharp
public void EndAttack()
```

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `duration` | `System.Int32` |  |
