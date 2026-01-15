---
uid: Spine.Animation
canonical_path: /api/Spine/Animation
---

# Class Animation

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Animation
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Animation

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Extension Methods
- [PoseSkeleton(Animation, Skeleton, float, bool)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_PoseSkeleton_Spine_Animation_Spine_Skeleton_System_Single_System_Boolean_)
- [SetKeyedItemsToSetupPose(Animation, Skeleton)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_SetKeyedItemsToSetupPose_Spine_Animation_Spine_Skeleton_)

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

## Fields

### duration

```csharp
internal float duration
```

#### Field Value

**Type:** System.Single

### name

```csharp
internal string name
```

#### Field Value

**Type:** System.String

### timelines

```csharp
internal ExposedList<Timeline> timelines
```

#### Field Value

**Type:** Spine.ExposedList{Spine.Timeline}

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

### BinarySearch(float[], float)

```csharp
internal static int BinarySearch(float[] values, float target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `values` | `System.Single[]` |  |
| `target` | `System.Single` |  |

#### Returns

**Type:** System.Int32

### BinarySearch(float[], float, int)

```csharp
internal static int BinarySearch(float[] values, float target, int step)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `values` | `System.Single[]` |  |
| `target` | `System.Single` |  |
| `step` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### LinearSearch(float[], float, int)

```csharp
internal static int LinearSearch(float[] values, float target, int step)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `values` | `System.Single[]` |  |
| `target` | `System.Single` |  |
| `step` | `System.Int32` |  |

#### Returns

**Type:** System.Int32
