---
uid: Global.StandingCommandQueue
canonical_path: /api/Global/Misc/StandingCommandQueue
---

# Class StandingCommandQueue

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StandingCommandQueue
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StandingCommandQueue

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StandingCommandQueue(StandingItemModel)

```csharp
public StandingCommandQueue(StandingItemModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.StandingItemModel` |  |

## Fields

### actor

```csharp
private StandingItemModel actor
```

#### Field Value

**Type:** Global.StandingItemModel

### queue

```csharp
private LinkedList<StandingCommand> queue
```

#### Field Value

**Type:** System.Collections.Generic.LinkedList{StandingCommand}

## Methods

### AddFirst(StandingCommand)

```csharp
public void AddFirst(StandingCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.StandingCommand` |  |

### AddLast(StandingCommand)

```csharp
public void AddLast(StandingCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.StandingCommand` |  |

### Clear()

```csharp
public void Clear()
```

### ClearQueue()

```csharp
private void ClearQueue()
```

### Execute(StandingItemModel)

```csharp
public void Execute(StandingItemModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.StandingItemModel` |  |

### GetCurrentCmd()

```csharp
public StandingCommand GetCurrentCmd()
```

#### Returns

**Type:** Global.StandingCommand

### SetCommand(StandingCommand)

```csharp
public void SetCommand(StandingCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.StandingCommand` |  |
