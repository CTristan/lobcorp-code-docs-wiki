---
uid: Global.WorkerManualMover
canonical_path: /api/Global/Misc/WorkerManualMover
---

# Class WorkerManualMover

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerManualMover
```
Presumably something for taking control of a particular employee, but unused.

#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerManualMover

## Derived
[OfficerManualMover](/api/Global/Worker/OfficerManualMover)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerManualMover()

```csharp
public WorkerManualMover()
```
#INC
#code-generated


### WorkerManualMover(WorkerModel, Vector3, MapNode, float, float)

```csharp
public WorkerManualMover(WorkerModel target, Vector3 pos, MapNode initial, float scale, float unitTime)
```
#INC


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
#INC


#### Field Value

**Type:** System.Int32

### halt

```csharp
public bool halt
```
#INC


#### Field Value

**Type:** System.Boolean

### isMoved

```csharp
public bool isMoved
```
#INC


#### Field Value

**Type:** System.Boolean

### isMoving

```csharp
public bool isMoving
```
#INC


#### Field Value

**Type:** System.Boolean

### movedPos

```csharp
public Vector3 movedPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### originNode

```csharp
public MapNode originNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### scale

```csharp
public float scale
```
#INC


#### Field Value

**Type:** System.Single

### targetModel

```csharp
public WorkerModel targetModel
```
#INC


#### Field Value

**Type:** Global.WorkerModel

### unitObject

```csharp
public object unitObject
```
#INC


#### Field Value

**Type:** System.Object

### unitTime

```csharp
public float unitTime
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### Halt()

```csharp
public virtual void Halt()
```
#INC


### MoveToNode()

```csharp
public virtual void MoveToNode()
```
#INC


### MoveToVector()

```csharp
public virtual void MoveToVector()
```
#INC


### MovingEnd()

```csharp
public virtual void MovingEnd()
```
#INC


### MovingProcess()

```csharp
public virtual void MovingProcess()
```
#INC

