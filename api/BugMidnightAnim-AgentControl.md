# Class BugMidnightAnim.AgentControl

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugMidnightAnim.AgentControl
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BugMidnightAnim.AgentControl

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AgentControl()

```csharp
public AgentControl()
```

## Fields

### distance_x

```csharp
public float distance_x
```

#### Field Value

**Type:** System.Single

### distance_y

```csharp
public float distance_y
```

#### Field Value

**Type:** System.Single

### initalPosition

```csharp
public Vector2 initalPosition
```

#### Field Value

**Type:** UnityEngine.Vector2

### targetPosition

```csharp
public Vector2 targetPosition
```

#### Field Value

**Type:** UnityEngine.Vector2

### targetWorker

```csharp
public WorkerModel targetWorker
```

#### Field Value

**Type:** Global.WorkerModel

### targetWorkerUnit

```csharp
public WorkerUnit targetWorkerUnit
```

#### Field Value

**Type:** Global.WorkerUnit

## Methods

### ChangeLayer(int)

```csharp
public void ChangeLayer(int layer = 0)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `layer` | `System.Int32` |  |

### FixedExecute(float, float, float)

```csharp
public void FixedExecute(float elap, float yCurveVal, float max)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `elap` | `System.Single` |  |
| `yCurveVal` | `System.Single` |  |
| `max` | `System.Single` |  |
