# Class AnimationState

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AnimationState
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AnimationState

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AnimationState(AnimationStateData)

```csharp
public AnimationState(AnimationStateData data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Spine.AnimationStateData` |  |

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
