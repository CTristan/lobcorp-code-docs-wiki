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

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ElevatorUsable

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ElevatorUsable(object, MovableObjectNode)

```csharp
public ElevatorUsable(object model, MovableObjectNode movableItem)
```

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

#### Field Value

**Type:** Global.MapNode

### dir

```csharp
public MoveDirection dir
```

#### Field Value

**Type:** Global.MoveDirection

### model

```csharp
public object model
```

#### Field Value

**Type:** System.Object

### movableObject

```csharp
public MovableObjectNode movableObject
```

#### Field Value

**Type:** Global.MovableObjectNode

## Methods

### GetMovableObject()

```csharp
public MovableObjectNode GetMovableObject()
```

#### Returns

**Type:** Global.MovableObjectNode

### GetTarget()

```csharp
public object GetTarget()
```

#### Returns

**Type:** System.Object

### GetTarget<T>()

```csharp
public object GetTarget<T>()
```

#### Returns

**Type:** System.Object

### ReStartMoving()

```csharp
public void ReStartMoving()
```

### SetDestination()

```csharp
public void SetDestination()
```
