---
uid: Spine.EventQueue.EventQueueEntry
canonical_path: /api/Spine/EventQueue/EventQueueEntry
---

# Struct EventQueue.EventQueueEntry

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
private struct EventQueue.EventQueueEntry
```

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.valuetype.equals), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.valuetype.gethashcode), [ToString()](https://learn.microsoft.com/dotnet/api/system.valuetype.tostring), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### EventQueueEntry(EventType, TrackEntry, Event)

```csharp
public EventQueueEntry(EventQueue.EventType eventType, TrackEntry trackEntry, Event e = null)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventType` | `Spine.EventQueue.EventType` |  |
| `trackEntry` | `Spine.TrackEntry` |  |
| `e` | `Spine.Event` |  |

## Fields

### e

```csharp
public Event e
```

#### Field Value

**Type:** Spine.Event

### entry

```csharp
public TrackEntry entry
```

#### Field Value

**Type:** Spine.TrackEntry

### type

```csharp
public EventQueue.EventType type
```

#### Field Value

**Type:** Spine.EventQueue.EventType
