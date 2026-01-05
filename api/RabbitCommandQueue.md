# Class RabbitCommandQueue

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitCommandQueue
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RabbitCommandQueue

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### RabbitCommandQueue(UnitModel)

```csharp
public RabbitCommandQueue(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

## Methods

### AddFirst(UnitCommand)

```csharp
public void AddFirst(UnitCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.UnitCommand` |  |

### AddLast(UnitCommand)

```csharp
public void AddLast(UnitCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.UnitCommand` |  |

### Clear()

```csharp
public void Clear()
```

### Execute(UnitModel)

```csharp
public void Execute(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### GetCurrentCmd()

```csharp
public UnitCommand GetCurrentCmd()
```

#### Returns

**Type:** Global.UnitCommand

### SetCommand(UnitCommand)

```csharp
public void SetCommand(UnitCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.UnitCommand` |  |
