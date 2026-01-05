# Class OfficerManualMover

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OfficerManualMover : WorkerManualMover
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [WorkerManualMover](/api/WorkerManualMover) → OfficerManualMover

## Inherited Members
[targetModel](/api/WorkerManualMover#targetmodel), [unitObject](/api/WorkerManualMover#unitobject), [movedPos](/api/WorkerManualMover#movedpos), [originNode](/api/WorkerManualMover#originnode), [scale](/api/WorkerManualMover#scale), [unitTime](/api/WorkerManualMover#unittime), [isMoving](/api/WorkerManualMover#ismoving), [isMoved](/api/WorkerManualMover#ismoved), [halt](/api/WorkerManualMover#halt), [currentCnt](/api/WorkerManualMover#currentcnt), [MovingProcess()](/api/WorkerManualMover#movingprocess), [MovingEnd()](/api/WorkerManualMover#movingend), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### OfficerManualMover()

```csharp
public OfficerManualMover()
```

## Properties

### model

```csharp
public OfficerModel model { get; }
```

#### Property Value

**Type:** Global.OfficerModel

### unit

```csharp
public OfficerUnit unit { get; }
```

#### Property Value

**Type:** Global.OfficerUnit

## Methods

### Halt()

```csharp
public override void Halt()
```

### MoveToNode()

```csharp
public override void MoveToNode()
```

### MoveToVector()

```csharp
public override void MoveToVector()
```
