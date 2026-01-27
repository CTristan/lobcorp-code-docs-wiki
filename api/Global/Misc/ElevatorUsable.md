---
uid: Global.ElevatorUsable
canonical_path: /api/Global/Misc/ElevatorUsable
---

# Class ElevatorUsable

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ElevatorUsable
```
Possibly handles where [elevators](/api/Global/Model/ElevatorPassageModel) go to?
#unused #maybe_unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ElevatorUsable

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ElevatorUsable(object, MovableObjectNode)

```csharp
public ElevatorUsable(object model, MovableObjectNode movableItem)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `System.Object` |  |
| `movableItem` | `Global.MovableObjectNode` |  |

## Fields

### dest

```csharp
public MapNode dest
```
#INC


#### Field Value

**Type:** Global.MapNode

### dir

```csharp
public MoveDirection dir
```
#INC


#### Field Value

**Type:** Global.MoveDirection

### model

```csharp
public object model
```
#INC


#### Field Value

**Type:** System.Object

### movableObject

```csharp
public MovableObjectNode movableObject
```
#INC


#### Field Value

**Type:** Global.MovableObjectNode

## Methods

### GetMovableObject()

```csharp
public MovableObjectNode GetMovableObject()
```
#INC


#### Returns

**Type:** Global.MovableObjectNode

### GetTarget()

```csharp
public object GetTarget()
```
#INC


#### Returns

**Type:** System.Object

### GetTarget<T>()

```csharp
public object GetTarget<T>()
```
#INC


#### Returns

**Type:** System.Object

### ReStartMoving()

```csharp
public void ReStartMoving()
```
#INC


### SetDestination()

```csharp
public void SetDestination()
```
#INC

