---
uid: Spine.TranslateTimeline
canonical_path: /api/Spine/TranslateTimeline
---

# Class TranslateTimeline

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TranslateTimeline : CurveTimeline, Timeline
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CurveTimeline](/api/Spine/CurveTimeline) → TranslateTimeline

## Derived
[ScaleTimeline](/api/Spine/ScaleTimeline), [ShearTimeline](/api/Spine/ShearTimeline)

## Implements
[Timeline](/api/Spine/Timeline)

## Inherited Members
[LINEAR](/api/Spine/CurveTimeline#linear), [STEPPED](/api/Spine/CurveTimeline#stepped), [BEZIER](/api/Spine/CurveTimeline#bezier), [BEZIER_SIZE](/api/Spine/CurveTimeline#bezier-size), [curves](/api/Spine/CurveTimeline#curves), [SetLinear(int)](/api/Spine/CurveTimeline#setlinear-int), [SetStepped(int)](/api/Spine/CurveTimeline#setstepped-int), [SetCurve(int, float, float, float, float)](/api/Spine/CurveTimeline#setcurve-int-float-float-float-float), [GetCurvePercent(int, float)](/api/Spine/CurveTimeline#getcurvepercent-int-float), [GetCurveType(int)](/api/Spine/CurveTimeline#getcurvetype-int), [FrameCount](/api/Spine/CurveTimeline#framecount), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TranslateTimeline(int)

```csharp
public TranslateTimeline(int frameCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameCount` | `System.Int32` |  |

## Fields

### boneIndex

```csharp
internal int boneIndex
```

#### Field Value

**Type:** System.Int32

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

### PREV_TIME

```csharp
protected const int PREV_TIME = -3
```

#### Field Value

**Type:** System.Int32

### PREV_X

```csharp
protected const int PREV_X = -2
```

#### Field Value

**Type:** System.Int32

### PREV_Y

```csharp
protected const int PREV_Y = -1
```

#### Field Value

**Type:** System.Int32

### X

```csharp
protected const int X = 1
```

#### Field Value

**Type:** System.Int32

### Y

```csharp
protected const int Y = 2
```

#### Field Value

**Type:** System.Int32

## Properties

### BoneIndex

```csharp
public int BoneIndex { get; set; }
```

#### Property Value

**Type:** System.Int32

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
public void SetFrame(int frameIndex, float time, float x, float y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameIndex` | `System.Int32` |  |
| `time` | `System.Single` |  |
| `x` | `System.Single` |  |
| `y` | `System.Single` |  |
