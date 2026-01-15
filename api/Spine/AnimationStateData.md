---
uid: Spine.AnimationStateData
canonical_path: /api/Spine/AnimationStateData
---

# Class AnimationStateData

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AnimationStateData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AnimationStateData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AnimationStateData(SkeletonData)

```csharp
public AnimationStateData(SkeletonData skeletonData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonData` | `Spine.SkeletonData` |  |

## Fields

### animationToMixTime

```csharp
private readonly Dictionary<AnimationStateData.AnimationPair, float> animationToMixTime
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{Spine.AnimationStateData.AnimationPair,System.Single}

### defaultMix

```csharp
internal float defaultMix
```

#### Field Value

**Type:** System.Single

### skeletonData

```csharp
internal SkeletonData skeletonData
```

#### Field Value

**Type:** Spine.SkeletonData

## Properties

### DefaultMix

```csharp
public float DefaultMix { get; set; }
```

#### Property Value

**Type:** System.Single

### SkeletonData

```csharp
public SkeletonData SkeletonData { get; }
```

#### Property Value

**Type:** Spine.SkeletonData

## Methods

### GetMix(Animation, Animation)

```csharp
public float GetMix(Animation from, Animation to)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `from` | `Spine.Animation` |  |
| `to` | `Spine.Animation` |  |

#### Returns

**Type:** System.Single

### SetMix(Animation, Animation, float)

```csharp
public void SetMix(Animation from, Animation to, float duration)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `from` | `Spine.Animation` |  |
| `to` | `Spine.Animation` |  |
| `duration` | `System.Single` |  |

### SetMix(string, string, float)

```csharp
public void SetMix(string fromName, string toName, float duration)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fromName` | `System.String` |  |
| `toName` | `System.String` |  |
| `duration` | `System.Single` |  |
