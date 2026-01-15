---
uid: Spine.Unity.SkeletonAnimator.MecanimTranslator
canonical_path: /api/Spine/Unity/SkeletonAnimator/MecanimTranslator
---

# Class SkeletonAnimator.MecanimTranslator

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkeletonAnimator.MecanimTranslator
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkeletonAnimator.MecanimTranslator

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MecanimTranslator()

```csharp
public MecanimTranslator()
```

## Fields

### animationTable

```csharp
private readonly Dictionary<int, Animation> animationTable
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,Spine.Animation}

### animator

```csharp
private Animator animator
```

#### Field Value

**Type:** UnityEngine.Animator

### autoReset

```csharp
public bool autoReset
```

#### Field Value

**Type:** System.Boolean

### clipInfoCache

```csharp
private readonly List<AnimatorClipInfo> clipInfoCache
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.AnimatorClipInfo}

### clipNameHashCodeTable

```csharp
private readonly Dictionary<AnimationClip, int> clipNameHashCodeTable
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{UnityEngine.AnimationClip,System.Int32}

### layerMixModes

```csharp
public SkeletonAnimator.MecanimTranslator.MixMode[] layerMixModes
```

#### Field Value

**Type:** Spine.Unity.SkeletonAnimator.MecanimTranslator.MixMode[]

### nextClipInfoCache

```csharp
private readonly List<AnimatorClipInfo> nextClipInfoCache
```

#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.AnimatorClipInfo}

### previousAnimations

```csharp
private readonly List<Animation> previousAnimations
```

#### Field Value

**Type:** System.Collections.Generic.List{Spine.Animation}

## Properties

### Animator

```csharp
public Animator Animator { get; }
```

#### Property Value

**Type:** UnityEngine.Animator

## Methods

### AnimationTime(float, float, bool)

```csharp
private static float AnimationTime(float normalizedTime, float clipLength, bool reversed)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `normalizedTime` | `System.Single` |  |
| `clipLength` | `System.Single` |  |
| `reversed` | `System.Boolean` |  |

#### Returns

**Type:** System.Single

### AnimationTime(float, float, bool, bool)

```csharp
private static float AnimationTime(float normalizedTime, float clipLength, bool loop, bool reversed)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `normalizedTime` | `System.Single` |  |
| `clipLength` | `System.Single` |  |
| `loop` | `System.Boolean` |  |
| `reversed` | `System.Boolean` |  |

#### Returns

**Type:** System.Single

### Apply(Skeleton)

```csharp
public void Apply(Skeleton skeleton)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |

### GetAnimatorClipInfos(int, out int, out int, out IList<AnimatorClipInfo>, out IList<AnimatorClipInfo>)

```csharp
private void GetAnimatorClipInfos(int layer, out int clipInfoCount, out int nextClipInfoCount, out IList<AnimatorClipInfo> clipInfo, out IList<AnimatorClipInfo> nextClipInfo)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `layer` | `System.Int32` |  |
| `clipInfoCount` | `System.Int32` |  |
| `nextClipInfoCount` | `System.Int32` |  |
| `clipInfo` | `System.Collections.Generic.IList{UnityEngine.AnimatorClipInfo}` |  |
| `nextClipInfo` | `System.Collections.Generic.IList{UnityEngine.AnimatorClipInfo}` |  |

### Initialize(Animator, SkeletonDataAsset)

```csharp
public void Initialize(Animator animator, SkeletonDataAsset skeletonDataAsset)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animator` | `UnityEngine.Animator` |  |
| `skeletonDataAsset` | `Spine.Unity.SkeletonDataAsset` |  |

### NameHashCode(AnimationClip)

```csharp
private int NameHashCode(AnimationClip clip)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `clip` | `UnityEngine.AnimationClip` |  |

#### Returns

**Type:** System.Int32
