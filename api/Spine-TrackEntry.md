# Class TrackEntry

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TrackEntry : Pool<TrackEntry>.IPoolable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TrackEntry

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### TrackEntry()

```csharp
public TrackEntry()
```

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

### Reset()

```csharp
public void Reset()
```

### ResetRotationDirections()

```csharp
public void ResetRotationDirections()
```

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
