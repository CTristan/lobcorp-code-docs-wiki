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
Manages the [rabbits](/api/Global/Model/RabbitModel), their [teams](/api/Global/Misc/RabbitTeam), and their [squads](/api/Global/Misc/RabbitSquad).

Tracks if rabbits are still alive, and whether there is anything for them to suppress.

Also tells Myo to yap (see [RabbitCaptaionConversation](/api/Rabbit/RabbitCaptaionConversation)).

#INC 


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
#INC


#### Field Value

**Type:** Global.RabbitManager

### _rabbits

```csharp
private List<RabbitModel> _rabbits
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RabbitModel}

### _rabbitSquads

```csharp
private Dictionary<SefiraEnum, RabbitSquad> _rabbitSquads
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{SefiraEnum,RabbitSquad}

### _rabbitTeams

```csharp
private List<RabbitTeam> _rabbitTeams
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{RabbitTeam}

### almostCount

```csharp
private int almostCount
```
#INC


#### Field Value

**Type:** System.Int32

### halfCount

```csharp
private int halfCount
```
#INC


#### Field Value

**Type:** System.Int32

### nextInstId

```csharp
private long nextInstId
```
#INC


#### Field Value

**Type:** System.Int64

### rabbitCount

```csharp
private int rabbitCount
```
#INC


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
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `eliminated` | `System.Boolean` |  |

### CreateRabbitSquad(SefiraEnum, int)

```csharp
public void CreateRabbitSquad(SefiraEnum sefira, int count)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |
| `count` | `System.Int32` |  |

### CreateRabbitTeam(SefiraEnum, RabbitOperationArea)

```csharp
private RabbitTeam CreateRabbitTeam(SefiraEnum sefira, RabbitOperationArea area)
```
#INC


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
#INC


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
#INC


#### Returns

**Type:** System.Boolean

### OnCleared(bool)

```csharp
public void OnCleared(bool eliminated)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eliminated` | `System.Boolean` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```
#INC


### OnGameInit()

```csharp
public void OnGameInit()
```
#INC
#code-generated


### OnRabbitDead(RabbitModel)

```csharp
public void OnRabbitDead(RabbitModel rabbit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rabbit` | `Global.RabbitModel` |  |

### OnStageEnd()

```csharp
public void OnStageEnd()
```
#INC


### OnStageRelease()

```csharp
public void OnStageRelease()
```
#INC


### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### OnStartSession()

```csharp
public void OnStartSession()
```
#INC


### RegisterRabbit(RabbitModel)

```csharp
public void RegisterRabbit(RabbitModel rabbit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rabbit` | `Global.RabbitModel` |  |

### SendBossClear()

```csharp
public void SendBossClear()
```
#INC

