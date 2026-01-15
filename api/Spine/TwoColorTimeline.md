---
uid: Spine.TwoColorTimeline
canonical_path: /api/Spine/TwoColorTimeline
---

# Class TwoColorTimeline

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TwoColorTimeline : CurveTimeline, Timeline
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CurveTimeline](/api/Spine/CurveTimeline) → TwoColorTimeline

## Implements
[Timeline](/api/Spine/Timeline)

## Inherited Members
[LINEAR](/api/Spine/CurveTimeline#linear), [STEPPED](/api/Spine/CurveTimeline#stepped), [BEZIER](/api/Spine/CurveTimeline#bezier), [BEZIER_SIZE](/api/Spine/CurveTimeline#bezier-size), [curves](/api/Spine/CurveTimeline#curves), [SetLinear(int)](/api/Spine/CurveTimeline#setlinear-int), [SetStepped(int)](/api/Spine/CurveTimeline#setstepped-int), [SetCurve(int, float, float, float, float)](/api/Spine/CurveTimeline#setcurve-int-float-float-float-float), [GetCurvePercent(int, float)](/api/Spine/CurveTimeline#getcurvepercent-int-float), [GetCurveType(int)](/api/Spine/CurveTimeline#getcurvetype-int), [FrameCount](/api/Spine/CurveTimeline#framecount), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TwoColorTimeline(int)

```csharp
public TwoColorTimeline(int frameCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameCount` | `System.Int32` |  |

## Fields

### A

```csharp
protected const int A = 4
```

#### Field Value

**Type:** System.Int32

### B

```csharp
protected const int B = 3
```

#### Field Value

**Type:** System.Int32

### B2

```csharp
protected const int B2 = 7
```

#### Field Value

**Type:** System.Int32

### ENTRIES

```csharp
public const int ENTRIES = 8
```

#### Field Value

**Type:** System.Int32

### frames

```csharp
internal float[] frames
```

#### Field Value

**Type:** System.Single[]

### G

```csharp
protected const int G = 2
```

#### Field Value

**Type:** System.Int32

### G2

```csharp
protected const int G2 = 6
```

#### Field Value

**Type:** System.Int32

### PREV_A

```csharp
protected const int PREV_A = -4
```

#### Field Value

**Type:** System.Int32

### PREV_B

```csharp
protected const int PREV_B = -5
```

#### Field Value

**Type:** System.Int32

### PREV_B2

```csharp
protected const int PREV_B2 = -1
```

#### Field Value

**Type:** System.Int32

### PREV_G

```csharp
protected const int PREV_G = -6
```

#### Field Value

**Type:** System.Int32

### PREV_G2

```csharp
protected const int PREV_G2 = -2
```

#### Field Value

**Type:** System.Int32

### PREV_R

```csharp
protected const int PREV_R = -7
```

#### Field Value

**Type:** System.Int32

### PREV_R2

```csharp
protected const int PREV_R2 = -3
```

#### Field Value

**Type:** System.Int32

### PREV_TIME

```csharp
protected const int PREV_TIME = -8
```

#### Field Value

**Type:** System.Int32

### R

```csharp
protected const int R = 1
```

#### Field Value

**Type:** System.Int32

### R2

```csharp
protected const int R2 = 5
```

#### Field Value

**Type:** System.Int32

### slotIndex

```csharp
internal int slotIndex
```

#### Field Value

**Type:** System.Int32

## Properties

### Frames

```csharp
public float[] Frames { get; }
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

### SetFrame(int, float, float, float, float, float, float, float, float)

```csharp
public void SetFrame(int frameIndex, float time, float r, float g, float b, float a, float r2, float g2, float b2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameIndex` | `System.Int32` |  |
| `time` | `System.Single` |  |
| `r` | `System.Single` |  |
| `g` | `System.Single` |  |
| `b` | `System.Single` |  |
| `a` | `System.Single` |  |
| `r2` | `System.Single` |  |
| `g2` | `System.Single` |  |
| `b2` | `System.Single` |  |
