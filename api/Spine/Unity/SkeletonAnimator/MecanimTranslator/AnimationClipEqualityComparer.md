---
uid: Spine.Unity.SkeletonAnimator.MecanimTranslator.AnimationClipEqualityComparer
canonical_path: /api/Spine/Unity/SkeletonAnimator/MecanimTranslator/AnimationClipEqualityComparer
---

# Class SkeletonAnimator.MecanimTranslator.AnimationClipEqualityComparer

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
private class SkeletonAnimator.MecanimTranslator.AnimationClipEqualityComparer : IEqualityComparer<AnimationClip>
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkeletonAnimator.MecanimTranslator.AnimationClipEqualityComparer

## Implements
[IEqualityComparer<AnimationClip>](https://learn.microsoft.com/dotnet/api/system.collections.generic.iequalitycomparer-1)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AnimationClipEqualityComparer()

```csharp
public AnimationClipEqualityComparer()
```

## Fields

### Instance

```csharp
internal static readonly IEqualityComparer<AnimationClip> Instance
```

#### Field Value

**Type:** System.Collections.Generic.IEqualityComparer{UnityEngine.AnimationClip}

## Methods

### Equals(AnimationClip, AnimationClip)

```csharp
public bool Equals(AnimationClip x, AnimationClip y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `UnityEngine.AnimationClip` |  |
| `y` | `UnityEngine.AnimationClip` |  |

#### Returns

**Type:** System.Boolean

### GetHashCode(AnimationClip)

```csharp
public int GetHashCode(AnimationClip o)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `UnityEngine.AnimationClip` |  |

#### Returns

**Type:** System.Int32
