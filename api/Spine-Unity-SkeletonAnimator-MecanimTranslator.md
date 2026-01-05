# Class SkeletonAnimator.MecanimTranslator

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine-Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkeletonAnimator.MecanimTranslator
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkeletonAnimator.MecanimTranslator

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### MecanimTranslator()

```csharp
public MecanimTranslator()
```

## Fields

### autoReset

```csharp
public bool autoReset
```

#### Field Value

**Type:** System.Boolean

### layerMixModes

```csharp
public SkeletonAnimator.MecanimTranslator.MixMode[] layerMixModes
```

#### Field Value

**Type:** Spine.Unity.SkeletonAnimator.MecanimTranslator.MixMode[]

## Properties

### Animator

```csharp
public Animator Animator { get; }
```

#### Property Value

**Type:** UnityEngine.Animator

## Methods

### Apply(Skeleton)

```csharp
public void Apply(Skeleton skeleton)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |

### Initialize(Animator, SkeletonDataAsset)

```csharp
public void Initialize(Animator animator, SkeletonDataAsset skeletonDataAsset)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animator` | `UnityEngine.Animator` |  |
| `skeletonDataAsset` | `Spine.Unity.SkeletonDataAsset` |  |
