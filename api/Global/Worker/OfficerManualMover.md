---
uid: Global.OfficerManualMover
canonical_path: /api/Global/Worker/OfficerManualMover
---

# Class OfficerManualMover

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OfficerManualMover : WorkerManualMover
```

Clerk mover.

#unused #maybe_unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [WorkerManualMover](/api/Global/Misc/WorkerManualMover) → OfficerManualMover

## Inherited Members
[targetModel](/api/Global/Misc/WorkerManualMover#targetmodel), [unitObject](/api/Global/Misc/WorkerManualMover#unitobject), [movedPos](/api/Global/Misc/WorkerManualMover#movedpos), [originNode](/api/Global/Misc/WorkerManualMover#originnode), [scale](/api/Global/Misc/WorkerManualMover#scale), [unitTime](/api/Global/Misc/WorkerManualMover#unittime), [isMoving](/api/Global/Misc/WorkerManualMover#ismoving), [isMoved](/api/Global/Misc/WorkerManualMover#ismoved), [halt](/api/Global/Misc/WorkerManualMover#halt), [currentCnt](/api/Global/Misc/WorkerManualMover#currentcnt), [MovingProcess()](/api/Global/Misc/WorkerManualMover#movingprocess), [MovingEnd()](/api/Global/Misc/WorkerManualMover#movingend), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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
#INC


### MoveToNode()

```csharp
public override void MoveToNode()
```
#INC


### MoveToVector()

```csharp
public override void MoveToVector()
```
#INC
#code-generated

