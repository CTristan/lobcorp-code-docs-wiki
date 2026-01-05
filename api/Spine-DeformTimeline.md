# Class DeformTimeline

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeformTimeline : CurveTimeline, Timeline
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CurveTimeline](/api/Spine-CurveTimeline) → DeformTimeline

## Inherited Members
[LINEAR](/api/Spine-CurveTimeline#linear), [STEPPED](/api/Spine-CurveTimeline#stepped), [BEZIER](/api/Spine-CurveTimeline#bezier), [BEZIER_SIZE](/api/Spine-CurveTimeline#bezier-size), [SetLinear(int)](/api/Spine-CurveTimeline#setlinear-int), [SetStepped(int)](/api/Spine-CurveTimeline#setstepped-int), [SetCurve(int, float, float, float, float)](/api/Spine-CurveTimeline#setcurve-int-float-float-float-float), [GetCurvePercent(int, float)](/api/Spine-CurveTimeline#getcurvepercent-int-float), [GetCurveType(int)](/api/Spine-CurveTimeline#getcurvetype-int), [FrameCount](/api/Spine-CurveTimeline#framecount), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DeformTimeline(int)

```csharp
public DeformTimeline(int frameCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameCount` | `System.Int32` |  |

## Properties

### Attachment

```csharp
public VertexAttachment Attachment { get; set; }
```

#### Property Value

**Type:** Spine.VertexAttachment

### Frames

```csharp
public float[] Frames { get; set; }
```

#### Property Value

**Type:** System.Single[]

### PropertyId

```csharp
public override int PropertyId { get; }
```

#### Property Value

**Type:** System.Int32

### SlotIndex

```csharp
public int SlotIndex { get; set; }
```

#### Property Value

**Type:** System.Int32

### Vertices

```csharp
public float[][] Vertices { get; set; }
```

#### Property Value

**Type:** System.Single[][]

## Methods

### Apply(Skeleton, float, float, ExposedList<Event>, float, MixPose, MixDirection)

```csharp
public override void Apply(Skeleton skeleton, float lastTime, float time, ExposedList<Event> firedEvents, float alpha, MixPose pose, MixDirection direction)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `lastTime` | `System.Single` |  |
| `time` | `System.Single` |  |
| `firedEvents` | `Spine.ExposedList{Spine.Event}` |  |
| `alpha` | `System.Single` |  |
| `pose` | `Spine.MixPose` |  |
| `direction` | `Spine.MixDirection` |  |

### SetFrame(int, float, float[])

```csharp
public void SetFrame(int frameIndex, float time, float[] vertices)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameIndex` | `System.Int32` |  |
| `time` | `System.Single` |  |
| `vertices` | `System.Single[]` |  |
