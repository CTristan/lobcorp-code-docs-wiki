# Class RabbitManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RabbitManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### RabbitManager()

```csharp
public RabbitManager()
```

## Properties

### instance

```csharp
public static RabbitManager instance { get; }
```

#### Property Value

**Type:** Global.RabbitManager

## Methods

### CheckUnitRabbitExecution(UnitModel)

```csharp
public bool CheckUnitRabbitExecution(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### ClearSquad(SefiraEnum, bool)

```csharp
public void ClearSquad(SefiraEnum sefira, bool eliminated = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `eliminated` | `System.Boolean` |  |

### CreateRabbitSquad(SefiraEnum, int)

```csharp
public void CreateRabbitSquad(SefiraEnum sefira, int count)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `count` | `System.Int32` |  |

### ExistsSquad(SefiraEnum)

```csharp
public bool ExistsSquad(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Boolean

### IsAnyRabbitEnabled()

```csharp
public bool IsAnyRabbitEnabled()
```

#### Returns

**Type:** System.Boolean

### OnCleared(bool)

```csharp
public void OnCleared(bool eliminated)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eliminated` | `System.Boolean` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```

### OnGameInit()

```csharp
public void OnGameInit()
```

### OnRabbitDead(RabbitModel)

```csharp
public void OnRabbitDead(RabbitModel rabbit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rabbit` | `Global.RabbitModel` |  |

### OnStageEnd()

```csharp
public void OnStageEnd()
```

### OnStageRelease()

```csharp
public void OnStageRelease()
```

### OnStageStart()

```csharp
public void OnStageStart()
```

### OnStartSession()

```csharp
public void OnStartSession()
```

### RegisterRabbit(RabbitModel)

```csharp
public void RegisterRabbit(RabbitModel rabbit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rabbit` | `Global.RabbitModel` |  |

### SendBossClear()

```csharp
public void SendBossClear()
```
