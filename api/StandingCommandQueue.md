# Class StandingCommandQueue

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StandingCommandQueue
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StandingCommandQueue

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### StandingCommandQueue(StandingItemModel)

```csharp
public StandingCommandQueue(StandingItemModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.StandingItemModel` |  |

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
