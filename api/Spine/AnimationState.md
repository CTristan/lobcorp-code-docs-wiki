---
uid: Spine.AnimationState
canonical_path: /api/Spine/AnimationState
---

# Class AnimationState

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AnimationState
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AnimationState

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AnimationState(AnimationStateData)

```csharp
public AnimationState(AnimationStateData data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Spine.AnimationStateData` |  |

## Fields

### animationsChanged

```csharp
private bool animationsChanged
```

#### Field Value

**Type:** System.Boolean

### data

```csharp
private AnimationStateData data
```

#### Field Value

**Type:** Spine.AnimationStateData

### Dip

```csharp
internal const int Dip = 2
```

#### Field Value

**Type:** System.Int32

### DipMix

```csharp
internal const int DipMix = 3
```

#### Field Value

**Type:** System.Int32

### EmptyAnimation

```csharp
private static readonly Animation EmptyAnimation
```

#### Field Value

**Type:** Spine.Animation

### events

```csharp
private readonly ExposedList<Event> events
```

#### Field Value

**Type:** Spine.ExposedList{Spine.Event}

### First

```csharp
internal const int First = 1
```

#### Field Value

**Type:** System.Int32

### mixingTo

```csharp
private readonly ExposedList<TrackEntry> mixingTo
```

#### Field Value

**Type:** Spine.ExposedList{Spine.TrackEntry}

### propertyIDs

```csharp
private readonly HashSet<int> propertyIDs
```

#### Field Value

**Type:** System.Collections.Generic.HashSet{System.Int32}

### queue

```csharp
private readonly EventQueue queue
```

#### Field Value

**Type:** Spine.EventQueue

### Subsequent

```csharp
internal const int Subsequent = 0
```

#### Field Value

**Type:** System.Int32

### timeScale

```csharp
private float timeScale
```

#### Field Value

**Type:** System.Single

### trackEntryPool

```csharp
private Pool<TrackEntry> trackEntryPool
```

#### Field Value

**Type:** Spine.Pool{Spine.TrackEntry}

### tracks

```csharp
private readonly ExposedList<TrackEntry> tracks
```

#### Field Value

**Type:** Spine.ExposedList{Spine.TrackEntry}

## Properties

### Data

```csharp
public AnimationStateData Data { get; }
```

#### Property Value

**Type:** Spine.AnimationStateData

### TimeScale

```csharp
public float TimeScale { get; set; }
```

#### Property Value

**Type:** System.Single

### Tracks

```csharp
public ExposedList<TrackEntry> Tracks { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.TrackEntry}

## Methods

### AddAnimation(int, Animation, bool, float)

```csharp
public TrackEntry AddAnimation(int trackIndex, Animation animation, bool loop, float delay)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackIndex` | `System.Int32` |  |
| `animation` | `Spine.Animation` |  |
| `loop` | `System.Boolean` |  |
| `delay` | `System.Single` |  |

#### Returns

**Type:** Spine.TrackEntry

### AddAnimation(int, string, bool, float)

```csharp
public TrackEntry AddAnimation(int trackIndex, string animationName, bool loop, float delay)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackIndex` | `System.Int32` |  |
| `animationName` | `System.String` |  |
| `loop` | `System.Boolean` |  |
| `delay` | `System.Single` |  |

#### Returns

**Type:** Spine.TrackEntry

### AddEmptyAnimation(int, float, float)

```csharp
public TrackEntry AddEmptyAnimation(int trackIndex, float mixDuration, float delay)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackIndex` | `System.Int32` |  |
| `mixDuration` | `System.Single` |  |
| `delay` | `System.Single` |  |

#### Returns

**Type:** Spine.TrackEntry

### AnimationsChanged()

```csharp
private void AnimationsChanged()
```

### Apply(Skeleton)

```csharp
public bool Apply(Skeleton skeleton)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |

#### Returns

**Type:** System.Boolean

### ApplyMixingFrom(TrackEntry, Skeleton, MixPose)

```csharp
private float ApplyMixingFrom(TrackEntry to, Skeleton skeleton, MixPose currentPose)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `to` | `Spine.TrackEntry` |  |
| `skeleton` | `Spine.Skeleton` |  |
| `currentPose` | `Spine.MixPose` |  |

#### Returns

**Type:** System.Single

### ApplyRotateTimeline(RotateTimeline, Skeleton, float, float, MixPose, float[], int, bool)

```csharp
private static void ApplyRotateTimeline(RotateTimeline rotateTimeline, Skeleton skeleton, float time, float alpha, MixPose pose, float[] timelinesRotation, int i, bool firstFrame)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rotateTimeline` | `Spine.RotateTimeline` |  |
| `skeleton` | `Spine.Skeleton` |  |
| `time` | `System.Single` |  |
| `alpha` | `System.Single` |  |
| `pose` | `Spine.MixPose` |  |
| `timelinesRotation` | `System.Single[]` |  |
| `i` | `System.Int32` |  |
| `firstFrame` | `System.Boolean` |  |

### ClearTrack(int)

```csharp
public void ClearTrack(int trackIndex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackIndex` | `System.Int32` |  |

### ClearTracks()

```csharp
public void ClearTracks()
```

### DisposeNext(TrackEntry)

```csharp
private void DisposeNext(TrackEntry entry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### ExpandToIndex(int)

```csharp
private TrackEntry ExpandToIndex(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Spine.TrackEntry

### GetCurrent(int)

```csharp
public TrackEntry GetCurrent(int trackIndex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackIndex` | `System.Int32` |  |

#### Returns

**Type:** Spine.TrackEntry

### NewTrackEntry(int, Animation, bool, TrackEntry)

```csharp
private TrackEntry NewTrackEntry(int trackIndex, Animation animation, bool loop, TrackEntry last)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackIndex` | `System.Int32` |  |
| `animation` | `Spine.Animation` |  |
| `loop` | `System.Boolean` |  |
| `last` | `Spine.TrackEntry` |  |

#### Returns

**Type:** Spine.TrackEntry

### OnComplete(TrackEntry)

```csharp
internal void OnComplete(TrackEntry entry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### OnDispose(TrackEntry)

```csharp
internal void OnDispose(TrackEntry entry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### OnEnd(TrackEntry)

```csharp
internal void OnEnd(TrackEntry entry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### OnEvent(TrackEntry, Event)

```csharp
internal void OnEvent(TrackEntry entry, Event e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |
| `e` | `Spine.Event` |  |

### OnInterrupt(TrackEntry)

```csharp
internal void OnInterrupt(TrackEntry entry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### OnStart(TrackEntry)

```csharp
internal void OnStart(TrackEntry entry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |

### QueueEvents(TrackEntry, float)

```csharp
private void QueueEvents(TrackEntry entry, float animationTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `entry` | `Spine.TrackEntry` |  |
| `animationTime` | `System.Single` |  |

### SetAnimation(int, Animation, bool)

```csharp
public TrackEntry SetAnimation(int trackIndex, Animation animation, bool loop)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackIndex` | `System.Int32` |  |
| `animation` | `Spine.Animation` |  |
| `loop` | `System.Boolean` |  |

#### Returns

**Type:** Spine.TrackEntry

### SetAnimation(int, string, bool)

```csharp
public TrackEntry SetAnimation(int trackIndex, string animationName, bool loop)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackIndex` | `System.Int32` |  |
| `animationName` | `System.String` |  |
| `loop` | `System.Boolean` |  |

#### Returns

**Type:** Spine.TrackEntry

### SetCurrent(int, TrackEntry, bool)

```csharp
private void SetCurrent(int index, TrackEntry current, bool interrupt)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `current` | `Spine.TrackEntry` |  |
| `interrupt` | `System.Boolean` |  |

### SetEmptyAnimation(int, float)

```csharp
public TrackEntry SetEmptyAnimation(int trackIndex, float mixDuration)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackIndex` | `System.Int32` |  |
| `mixDuration` | `System.Single` |  |

#### Returns

**Type:** Spine.TrackEntry

### SetEmptyAnimations(float)

```csharp
public void SetEmptyAnimations(float mixDuration)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mixDuration` | `System.Single` |  |

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String

### Update(float)

```csharp
public void Update(float delta)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `delta` | `System.Single` |  |

### UpdateMixingFrom(TrackEntry, float)

```csharp
private bool UpdateMixingFrom(TrackEntry to, float delta)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `to` | `Spine.TrackEntry` |  |
| `delta` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

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
