# Class SpecialEventManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpecialEventManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpecialEventManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SpecialEventManager()

```csharp
public SpecialEventManager()
```

## Properties

### instance

```csharp
public static SpecialEventManager instance { get; }
```

#### Property Value

**Type:** Global.SpecialEventManager

## Methods

### ActivateEvent(EventBase)

```csharp
public bool ActivateEvent(EventBase _event)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_event` | `Global.EventBase` |  |

#### Returns

**Type:** System.Boolean

### AddCreature(long, MapNode, EventBase)

```csharp
public EventCreatureModel AddCreature(long metadataId, MapNode pos, EventBase eventBase)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metadataId` | `System.Int64` |  |
| `pos` | `Global.MapNode` |  |
| `eventBase` | `Global.EventBase` |  |

#### Returns

**Type:** Global.EventCreatureModel

### CheckEventContains(EventType, out EventBase)

```csharp
public bool CheckEventContains(EventBase.EventType type, out EventBase script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.EventBase.EventType` |  |
| `script` | `Global.EventBase` |  |

#### Returns

**Type:** System.Boolean

### ClearCreatures()

```csharp
public void ClearCreatures()
```

### GetEventCreatureList()

```csharp
public EventCreatureModel[] GetEventCreatureList()
```

#### Returns

**Type:** Global.EventCreatureModel[]

### OnEventEnd(EventBase)

```csharp
public void OnEventEnd(EventBase _event)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_event` | `Global.EventBase` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```

### OnGameInit()

```csharp
public void OnGameInit()
```

### OnStageRelease()

```csharp
public void OnStageRelease()
```
