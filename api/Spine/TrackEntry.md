---
uid: Spine.TrackEntry
canonical_path: /api/Spine/TrackEntry
---

# Class TrackEntry

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TrackEntry : Pool<TrackEntry>.IPoolable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TrackEntry

## Implements
[Pool<TrackEntry>.IPoolable](Spine.Pool-1.html)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TrackEntry()

```csharp
public TrackEntry()
```

## Fields

### alpha

```csharp
internal float alpha
```

#### Field Value

**Type:** System.Single

### animation

```csharp
internal Animation animation
```

#### Field Value

**Type:** Spine.Animation

### animationEnd

```csharp
internal float animationEnd
```

#### Field Value

**Type:** System.Single

### animationLast

```csharp
internal float animationLast
```

#### Field Value

**Type:** System.Single

### animationStart

```csharp
internal float animationStart
```

#### Field Value

**Type:** System.Single

### attachmentThreshold

```csharp
internal float attachmentThreshold
```

#### Field Value

**Type:** System.Single

### delay

```csharp
internal float delay
```

#### Field Value

**Type:** System.Single

### drawOrderThreshold

```csharp
internal float drawOrderThreshold
```

#### Field Value

**Type:** System.Single

### eventThreshold

```csharp
internal float eventThreshold
```

#### Field Value

**Type:** System.Single

### interruptAlpha

```csharp
internal float interruptAlpha
```

#### Field Value

**Type:** System.Single

### loop

```csharp
internal bool loop
```

#### Field Value

**Type:** System.Boolean

### mixDuration

```csharp
internal float mixDuration
```

#### Field Value

**Type:** System.Single

### mixingFrom

```csharp
internal TrackEntry mixingFrom
```

#### Field Value

**Type:** Spine.TrackEntry

### mixTime

```csharp
internal float mixTime
```

#### Field Value

**Type:** System.Single

### next

```csharp
internal TrackEntry next
```

#### Field Value

**Type:** Spine.TrackEntry

### nextAnimationLast

```csharp
internal float nextAnimationLast
```

#### Field Value

**Type:** System.Single

### nextTrackLast

```csharp
internal float nextTrackLast
```

#### Field Value

**Type:** System.Single

### timelineData

```csharp
internal readonly ExposedList<int> timelineData
```

#### Field Value

**Type:** Spine.ExposedList{System.Int32}

### timelineDipMix

```csharp
internal readonly ExposedList<TrackEntry> timelineDipMix
```

#### Field Value

**Type:** Spine.ExposedList{Spine.TrackEntry}

### timelinesRotation

```csharp
internal readonly ExposedList<float> timelinesRotation
```

#### Field Value

**Type:** Spine.ExposedList{System.Single}

### timeScale

```csharp
internal float timeScale
```

#### Field Value

**Type:** System.Single

### totalAlpha

```csharp
internal float totalAlpha
```

#### Field Value

**Type:** System.Single

### trackEnd

```csharp
internal float trackEnd
```

#### Field Value

**Type:** System.Single

### trackIndex

```csharp
internal int trackIndex
```

#### Field Value

**Type:** System.Int32

### trackLast

```csharp
internal float trackLast
```

#### Field Value

**Type:** System.Single

### trackTime

```csharp
internal float trackTime
```

#### Field Value

**Type:** System.Single

## Properties

### Alpha

```csharp
public float Alpha { get; set; }
```

#### Property Value

**Type:** System.Single

### Animation

```csharp
public Animation Animation { get; }
```

#### Property Value

**Type:** Spine.Animation

### AnimationEnd

```csharp
public float AnimationEnd { get; set; }
```

#### Property Value

**Type:** System.Single

### AnimationLast

```csharp
public float AnimationLast { get; set; }
```

#### Property Value

**Type:** System.Single

### AnimationStart

```csharp
public float AnimationStart { get; set; }
```

#### Property Value

**Type:** System.Single

### AnimationTime

```csharp
public float AnimationTime { get; }
```

#### Property Value

**Type:** System.Single

### AttachmentThreshold

```csharp
public float AttachmentThreshold { get; set; }
```

#### Property Value

**Type:** System.Single

### Delay

```csharp
public float Delay { get; set; }
```

#### Property Value

**Type:** System.Single

### DrawOrderThreshold

```csharp
public float DrawOrderThreshold { get; set; }
```

#### Property Value

**Type:** System.Single

### EventThreshold

```csharp
public float EventThreshold { get; set; }
```

#### Property Value

**Type:** System.Single

### IsComplete

```csharp
public bool IsComplete { get; }
```

#### Property Value

**Type:** System.Boolean

### Loop

```csharp
public bool Loop { get; set; }
```

#### Property Value

**Type:** System.Boolean

### MixDuration

```csharp
public float MixDuration { get; set; }
```

#### Property Value

**Type:** System.Single

### MixingFrom

```csharp
public TrackEntry MixingFrom { get; }
```

#### Property Value

**Type:** Spine.TrackEntry

### MixTime

```csharp
public float MixTime { get; set; }
```

#### Property Value

**Type:** System.Single

### Next

```csharp
public TrackEntry Next { get; }
```

#### Property Value

**Type:** Spine.TrackEntry

### TimeScale

```csharp
public float TimeScale { get; set; }
```

#### Property Value

**Type:** System.Single

### TrackEnd

```csharp
public float TrackEnd { get; set; }
```

#### Property Value

**Type:** System.Single

### TrackIndex

```csharp
public int TrackIndex { get; }
```

#### Property Value

**Type:** System.Int32

### TrackTime

```csharp
public float TrackTime { get; set; }
```

#### Property Value

**Type:** System.Single

## Methods

### HasTimeline(int)

```csharp
private bool HasTimeline(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### OnComplete()

```csharp
internal void OnComplete()
```

### OnDispose()

```csharp
internal void OnDispose()
```

### OnEnd()

```csharp
internal void OnEnd()
```

### OnEvent(Event)

```csharp
internal void OnEvent(Event e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `e` | `Spine.Event` |  |

### OnInterrupt()

```csharp
internal void OnInterrupt()
```

### OnStart()

```csharp
internal void OnStart()
```

### Reset()

```csharp
public void Reset()
```

### ResetRotationDirections()

```csharp
public void ResetRotationDirections()
```

### SetTimelineData(TrackEntry, ExposedList<TrackEntry>, HashSet<int>)

```csharp
internal TrackEntry SetTimelineData(TrackEntry to, ExposedList<TrackEntry> mixingToArray, HashSet<int> propertyIDs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `to` | `Spine.TrackEntry` |  |
| `mixingToArray` | `Spine.ExposedList{Spine.TrackEntry}` |  |
| `propertyIDs` | `System.Collections.Generic.HashSet{System.Int32}` |  |

#### Returns

**Type:** Spine.TrackEntry

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String

## Events

### Complete

```csharp
public event AnimationState.TrackEntryDelegate Complete
```

#### Returns

**Type:** Spine.AnimationState.TrackEntryDelegate

### Dispose

```csharp
public event AnimationState.TrackEntryDelegate Dispose
```

#### Returns

**Type:** Spine.AnimationState.TrackEntryDelegate

### End

```csharp
public event AnimationState.TrackEntryDelegate End
```

#### Returns

**Type:** Spine.AnimationState.TrackEntryDelegate

### Event

```csharp
public event AnimationState.TrackEntryEventDelegate Event
```

#### Returns

**Type:** Spine.AnimationState.TrackEntryEventDelegate

### Interrupt

```csharp
public event AnimationState.TrackEntryDelegate Interrupt
```

#### Returns

**Type:** Spine.AnimationState.TrackEntryDelegate

### Start

```csharp
public event AnimationState.TrackEntryDelegate Start
```

#### Returns

**Type:** Spine.AnimationState.TrackEntryDelegate
