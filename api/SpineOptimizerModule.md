# Class SpineOptimizerModule

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpineOptimizerModule
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpineOptimizerModule

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SpineOptimizerModule(SkeletonRenderer, UnitModel, float)

```csharp
public SpineOptimizerModule(SkeletonRenderer spineRenderer, UnitModel target, float loosenessLevel = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spineRenderer` | `Spine.Unity.SkeletonRenderer` |  |
| `target` | `Global.UnitModel` |  |
| `loosenessLevel` | `System.Single` |  |

## Methods

### Init(SkeletonRenderer, UnitModel, float)

```csharp
public void Init(SkeletonRenderer spineRenderer, UnitModel target, float scale = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spineRenderer` | `Spine.Unity.SkeletonRenderer` |  |
| `target` | `Global.UnitModel` |  |
| `scale` | `System.Single` |  |

### Update()

```csharp
public void Update()
```

### UpdateAnimationQuality()

```csharp
public void UpdateAnimationQuality()
```

### UpdateCheckInCamera()

```csharp
public void UpdateCheckInCamera()
```
