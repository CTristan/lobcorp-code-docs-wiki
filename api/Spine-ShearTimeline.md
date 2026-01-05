# Class ShearTimeline

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ShearTimeline : TranslateTimeline, Timeline
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CurveTimeline](/api/Spine-CurveTimeline) → [TranslateTimeline](/api/Spine-TranslateTimeline) → ShearTimeline

## Inherited Members
[ENTRIES](/api/Spine-TranslateTimeline#entries), [PREV_TIME](/api/Spine-TranslateTimeline#prev-time), [PREV_X](/api/Spine-TranslateTimeline#prev-x), [PREV_Y](/api/Spine-TranslateTimeline#prev-y), [X](/api/Spine-TranslateTimeline#x), [Y](/api/Spine-TranslateTimeline#y), [SetFrame(int, float, float, float)](/api/Spine-TranslateTimeline#setframe-int-float-float-float), [BoneIndex](/api/Spine-TranslateTimeline#boneindex), [Frames](/api/Spine-TranslateTimeline#frames), [LINEAR](/api/Spine-CurveTimeline#linear), [STEPPED](/api/Spine-CurveTimeline#stepped), [BEZIER](/api/Spine-CurveTimeline#bezier), [BEZIER_SIZE](/api/Spine-CurveTimeline#bezier-size), [SetLinear(int)](/api/Spine-CurveTimeline#setlinear-int), [SetStepped(int)](/api/Spine-CurveTimeline#setstepped-int), [SetCurve(int, float, float, float, float)](/api/Spine-CurveTimeline#setcurve-int-float-float-float-float), [GetCurvePercent(int, float)](/api/Spine-CurveTimeline#getcurvepercent-int-float), [GetCurveType(int)](/api/Spine-CurveTimeline#getcurvetype-int), [FrameCount](/api/Spine-CurveTimeline#framecount), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ShearTimeline(int)

```csharp
public ShearTimeline(int frameCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameCount` | `System.Int32` |  |

## Properties

### PropertyId

```csharp
public override int PropertyId { get; }
```

#### Property Value

**Type:** System.Int32

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
