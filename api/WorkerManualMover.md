# Class WorkerManualMover

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerManualMover
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerManualMover

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### WorkerManualMover()

```csharp
public WorkerManualMover()
```

### WorkerManualMover(WorkerModel, Vector3, MapNode, float, float)

```csharp
public WorkerManualMover(WorkerModel target, Vector3 pos, MapNode initial, float scale, float unitTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `pos` | `UnityEngine.Vector3` |  |
| `initial` | `Global.MapNode` |  |
| `scale` | `System.Single` |  |
| `unitTime` | `System.Single` |  |

## Fields

### currentCnt

```csharp
public int currentCnt
```

#### Field Value

**Type:** System.Int32

### halt

```csharp
public bool halt
```

#### Field Value

**Type:** System.Boolean

### isMoved

```csharp
public bool isMoved
```

#### Field Value

**Type:** System.Boolean

### isMoving

```csharp
public bool isMoving
```

#### Field Value

**Type:** System.Boolean

### movedPos

```csharp
public Vector3 movedPos
```

#### Field Value

**Type:** UnityEngine.Vector3

### originNode

```csharp
public MapNode originNode
```

#### Field Value

**Type:** Global.MapNode

### scale

```csharp
public float scale
```

#### Field Value

**Type:** System.Single

### targetModel

```csharp
public WorkerModel targetModel
```

#### Field Value

**Type:** Global.WorkerModel

### unitObject

```csharp
public object unitObject
```

#### Field Value

**Type:** System.Object

### unitTime

```csharp
public float unitTime
```

#### Field Value

**Type:** System.Single

## Methods

### Halt()

```csharp
public virtual void Halt()
```

### MoveToNode()

```csharp
public virtual void MoveToNode()
```

### MoveToVector()

```csharp
public virtual void MoveToVector()
```

### MovingEnd()

```csharp
public virtual void MovingEnd()
```

### MovingProcess()

```csharp
public virtual void MovingProcess()
```
