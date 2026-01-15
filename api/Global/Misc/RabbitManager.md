---
uid: Global.RabbitManager
canonical_path: /api/Global/Misc/RabbitManager
---

# Class RabbitManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RabbitManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RabbitManager()

```csharp
public RabbitManager()
```

## Fields

### _instance

```csharp
private static RabbitManager _instance
```

#### Field Value

**Type:** Global.RabbitManager

### _rabbits

```csharp
private List<RabbitModel> _rabbits
```

#### Field Value

**Type:** System.Collections.Generic.List{RabbitModel}

### _rabbitSquads

```csharp
private Dictionary<SefiraEnum, RabbitSquad> _rabbitSquads
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{SefiraEnum,RabbitSquad}

### _rabbitTeams

```csharp
private List<RabbitTeam> _rabbitTeams
```

#### Field Value

**Type:** System.Collections.Generic.List{RabbitTeam}

### almostCount

```csharp
private int almostCount
```

#### Field Value

**Type:** System.Int32

### halfCount

```csharp
private int halfCount
```

#### Field Value

**Type:** System.Int32

### nextInstId

```csharp
private long nextInstId
```

#### Field Value

**Type:** System.Int64

### rabbitCount

```csharp
private int rabbitCount
```

#### Field Value

**Type:** System.Int32

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

### CreateRabbitTeam(SefiraEnum, RabbitOperationArea)

```csharp
private RabbitTeam CreateRabbitTeam(SefiraEnum sefira, RabbitOperationArea area)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `area` | `Global.RabbitOperationArea` |  |

#### Returns

**Type:** Global.RabbitTeam

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
