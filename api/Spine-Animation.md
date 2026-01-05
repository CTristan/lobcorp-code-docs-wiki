# Class Animation

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Animation
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Animation

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Animation(string, ExposedList<Timeline>, float)

```csharp
public Animation(string name, ExposedList<Timeline> timelines, float duration)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `timelines` | `Spine.ExposedList{Spine.Timeline}` |  |
| `duration` | `System.Single` |  |

## Properties

### Duration

```csharp
public float Duration { get; set; }
```

#### Property Value

**Type:** System.Single

### Name

```csharp
public string Name { get; }
```

#### Property Value

**Type:** System.String

### Timelines

```csharp
public ExposedList<Timeline> Timelines { get; set; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.Timeline}

## Methods

### Apply(Skeleton, float, float, bool, ExposedList<Event>, float, MixPose, MixDirection)

```csharp
public void Apply(Skeleton skeleton, float lastTime, float time, bool loop, ExposedList<Event> events, float alpha, MixPose pose, MixDirection direction)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `lastTime` | `System.Single` |  |
| `time` | `System.Single` |  |
| `loop` | `System.Boolean` |  |
| `events` | `Spine.ExposedList{Spine.Event}` |  |
| `alpha` | `System.Single` |  |
| `pose` | `Spine.MixPose` |  |
| `direction` | `Spine.MixDirection` |  |
