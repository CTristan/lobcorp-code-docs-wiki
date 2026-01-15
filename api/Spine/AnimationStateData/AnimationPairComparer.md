---
uid: Spine.AnimationStateData.AnimationPairComparer
canonical_path: /api/Spine/AnimationStateData/AnimationPairComparer
---

# Class AnimationStateData.AnimationPairComparer

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
private class AnimationStateData.AnimationPairComparer : IEqualityComparer<AnimationStateData.AnimationPair>
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AnimationStateData.AnimationPairComparer

## Implements
[IEqualityComparer<AnimationStateData.AnimationPair>](https://learn.microsoft.com/dotnet/api/system.collections.generic.iequalitycomparer-1)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AnimationPairComparer()

```csharp
public AnimationPairComparer()
```

## Fields

### Instance

```csharp
internal static readonly AnimationStateData.AnimationPairComparer Instance
```

#### Field Value

**Type:** Spine.AnimationStateData.AnimationPairComparer

## Methods

### IEqualityComparer<AnimationPair>.Equals(AnimationPair, AnimationPair)

```csharp
bool IEqualityComparer<AnimationStateData.AnimationPair>.Equals(AnimationStateData.AnimationPair x, AnimationStateData.AnimationPair y)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `Spine.AnimationStateData.AnimationPair` |  |
| `y` | `Spine.AnimationStateData.AnimationPair` |  |

#### Returns

**Type:** System.Boolean

### IEqualityComparer<AnimationPair>.GetHashCode(AnimationPair)

```csharp
int IEqualityComparer<AnimationStateData.AnimationPair>.GetHashCode(AnimationStateData.AnimationPair obj)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `obj` | `Spine.AnimationStateData.AnimationPair` |  |

#### Returns

**Type:** System.Int32
