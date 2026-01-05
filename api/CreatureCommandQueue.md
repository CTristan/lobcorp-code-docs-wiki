# Class CreatureCommandQueue

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureCommandQueue
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureCommandQueue

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CreatureCommandQueue(CreatureModel)

```csharp
public CreatureCommandQueue(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

## Methods

### AddFirst(CreatureCommand)

```csharp
public void AddFirst(CreatureCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.CreatureCommand` |  |

### AddLast(CreatureCommand)

```csharp
public void AddLast(CreatureCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.CreatureCommand` |  |

### Clear()

```csharp
public void Clear()
```

### Execute(CreatureModel)

```csharp
public void Execute(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### GetCurrentCmd()

```csharp
public CreatureCommand GetCurrentCmd()
```

#### Returns

**Type:** Global.CreatureCommand

### SetAgentCommand(CreatureCommand)

```csharp
public void SetAgentCommand(CreatureCommand cmd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.CreatureCommand` |  |
