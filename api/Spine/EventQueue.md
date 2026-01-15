---
uid: Spine.EventQueue
canonical_path: /api/Spine/EventQueue
---

# Class EventQueue

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
internal class EventQueue
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EventQueue

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EventQueue(AnimationState, Action, Pool<TrackEntry>)

```csharp
internal EventQueue(AnimationState state, Action HandleAnimationsChanged, Pool<TrackEntry> trackEntryPool)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Spine.AnimationState` |  |
| `HandleAnimationsChanged` | `System.Action` |  |
| `trackEntryPool` | `Spine.Pool{Spine.TrackEntry}` |  |

## Fields

### drainDisabled

```csharp
internal bool drainDisabled
```

#### Field Value

**Type:** System.Boolean

### eventQueueEntries

```csharp
private readonly List<EventQueue.EventQueueEntry> eventQueueEntries
```

#### Field Value

**Type:** System.Collections.Generic.List{Spine.EventQueue.EventQueueEntry}

### state

```csharp
private readonly AnimationState state
```

#### Field Value

**Type:** Spine.AnimationState

### trackEntryPool

```csharp
private readonly Pool<TrackEntry> trackEntryPool
```

#### Field Value

**Type:** Spine.Pool{Spine.TrackEntry}

## Methods

### Clear()

```csharp
internal void Clear()
```

### Complete(TrackEntry)

```csharp
internal void Complete(TrackEntry entry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### Dispose(TrackEntry)

```csharp
internal void Dispose(TrackEntry entry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### Drain()

```csharp
internal void Drain()
```

### End(TrackEntry)

```csharp
internal void End(TrackEntry entry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### Event(TrackEntry, Event)

```csharp
internal void Event(TrackEntry entry, Event e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |
| `e` | `Spine.Event` |  |

### Interrupt(TrackEntry)

```csharp
internal void Interrupt(TrackEntry entry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### Start(TrackEntry)

```csharp
internal void Start(TrackEntry entry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

## Events

### AnimationsChanged

```csharp
internal event Action AnimationsChanged
```

#### Returns

**Type:** System.Action
