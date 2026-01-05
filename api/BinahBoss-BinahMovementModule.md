# Class BinahMovementModule

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahMovementModule
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BinahMovementModule

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BinahMovementModule(BinahCoreScript)

```csharp
public BinahMovementModule(BinahCoreScript coreScript)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `coreScript` | `Global.BinahCoreScript` |  |

## Properties

### CoreScript

```csharp
public BinahCoreScript CoreScript { get; }
```

#### Property Value

**Type:** Global.BinahCoreScript

### CurrentMoveState

```csharp
public BinahMoveState CurrentMoveState { get; }
```

#### Property Value

**Type:** BinahBoss.BinahMoveState

## Methods

### Arrived()

```csharp
public void Arrived()
```

### Execute()

```csharp
public void Execute()
```

### Move()

```csharp
public void Move()
```

### RelaseMovement()

```csharp
public void RelaseMovement()
```

### StopByAction()

```csharp
public void StopByAction()
```

### StopByTime(float)

```csharp
public void StopByTime(float stopTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `stopTime` | `System.Single` |  |
