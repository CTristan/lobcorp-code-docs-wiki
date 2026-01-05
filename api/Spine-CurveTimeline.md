# Class CurveTimeline

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public abstract class CurveTimeline : Timeline
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CurveTimeline

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CurveTimeline(int)

```csharp
public CurveTimeline(int frameCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameCount` | `System.Int32` |  |

## Fields

### BEZIER

```csharp
protected const float BEZIER = 2
```

#### Field Value

**Type:** System.Single

### BEZIER_SIZE

```csharp
protected const int BEZIER_SIZE = 19
```

#### Field Value

**Type:** System.Int32

### LINEAR

```csharp
protected const float LINEAR = 0
```

#### Field Value

**Type:** System.Single

### STEPPED

```csharp
protected const float STEPPED = 1
```

#### Field Value

**Type:** System.Single

## Properties

### FrameCount

```csharp
public int FrameCount { get; }
```

#### Property Value

**Type:** System.Int32

### PropertyId

```csharp
public abstract int PropertyId { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### Apply(Skeleton, float, float, ExposedList<Event>, float, MixPose, MixDirection)

```csharp
public abstract void Apply(Skeleton skeleton, float lastTime, float time, ExposedList<Event> firedEvents, float alpha, MixPose pose, MixDirection direction)
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

### GetCurvePercent(int, float)

```csharp
public float GetCurvePercent(int frameIndex, float percent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameIndex` | `System.Int32` |  |
| `percent` | `System.Single` |  |

#### Returns

**Type:** System.Single

### GetCurveType(int)

```csharp
public float GetCurveType(int frameIndex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameIndex` | `System.Int32` |  |

#### Returns

**Type:** System.Single

### SetCurve(int, float, float, float, float)

```csharp
public void SetCurve(int frameIndex, float cx1, float cy1, float cx2, float cy2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameIndex` | `System.Int32` |  |
| `cx1` | `System.Single` |  |
| `cy1` | `System.Single` |  |
| `cx2` | `System.Single` |  |
| `cy2` | `System.Single` |  |

### SetLinear(int)

```csharp
public void SetLinear(int frameIndex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameIndex` | `System.Int32` |  |

### SetStepped(int)

```csharp
public void SetStepped(int frameIndex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `frameIndex` | `System.Int32` |  |
