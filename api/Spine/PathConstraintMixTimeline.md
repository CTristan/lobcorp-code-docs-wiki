---
uid: Spine.PathConstraintMixTimeline
canonical_path: /api/Spine/PathConstraintMixTimeline
---

# Class PathConstraintMixTimeline

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PathConstraintMixTimeline : CurveTimeline, Timeline
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CurveTimeline](/api/Spine/CurveTimeline) → PathConstraintMixTimeline

## Implements
[Timeline](/api/Spine/Timeline)

## Inherited Members
[LINEAR](/api/Spine/CurveTimeline#linear), [STEPPED](/api/Spine/CurveTimeline#stepped), [BEZIER](/api/Spine/CurveTimeline#bezier), [BEZIER_SIZE](/api/Spine/CurveTimeline#bezier-size), [curves](/api/Spine/CurveTimeline#curves), [SetLinear(int)](/api/Spine/CurveTimeline#setlinear-int), [SetStepped(int)](/api/Spine/CurveTimeline#setstepped-int), [SetCurve(int, float, float, float, float)](/api/Spine/CurveTimeline#setcurve-int-float-float-float-float), [GetCurvePercent(int, float)](/api/Spine/CurveTimeline#getcurvepercent-int-float), [GetCurveType(int)](/api/Spine/CurveTimeline#getcurvetype-int), [FrameCount](/api/Spine/CurveTimeline#framecount), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PathConstraintMixTimeline(int)

```csharp
public PathConstraintMixTimeline(int frameCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameCount` | `System.Int32` |  |

## Fields

### ENTRIES

```csharp
public const int ENTRIES = 3
```

#### Field Value

**Type:** System.Int32

### frames

```csharp
internal float[] frames
```

#### Field Value

**Type:** System.Single[]

### pathConstraintIndex

```csharp
internal int pathConstraintIndex
```

#### Field Value

**Type:** System.Int32

### PREV_ROTATE

```csharp
private const int PREV_ROTATE = -2
```

#### Field Value

**Type:** System.Int32

### PREV_TIME

```csharp
private const int PREV_TIME = -3
```

#### Field Value

**Type:** System.Int32

### PREV_TRANSLATE

```csharp
private const int PREV_TRANSLATE = -1
```

#### Field Value

**Type:** System.Int32

### ROTATE

```csharp
private const int ROTATE = 1
```

#### Field Value

**Type:** System.Int32

### TRANSLATE

```csharp
private const int TRANSLATE = 2
```

#### Field Value

**Type:** System.Int32

## Properties

### Frames

```csharp
public float[] Frames { get; set; }
```

#### Property Value

**Type:** System.Single[]

### PathConstraintIndex

```csharp
public int PathConstraintIndex { get; set; }
```

#### Property Value

**Type:** System.Int32

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

### SetFrame(int, float, float, float)

```csharp
public void SetFrame(int frameIndex, float time, float rotateMix, float translateMix)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameIndex` | `System.Int32` |  |
| `time` | `System.Single` |  |
| `rotateMix` | `System.Single` |  |
| `translateMix` | `System.Single` |  |
