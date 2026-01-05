# Interface ISkeletonAnimation

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine-Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface ISkeletonAnimation
```

## Properties

### Skeleton

```csharp
Skeleton Skeleton { get; }
```

#### Property Value

**Type:** Spine.Skeleton

## Methods

### LateUpdate()

```csharp
void LateUpdate()
```

## Events

### UpdateComplete

```csharp
event UpdateBonesDelegate UpdateComplete
```

#### Returns

**Type:** Spine.Unity.UpdateBonesDelegate

### UpdateLocal

```csharp
event UpdateBonesDelegate UpdateLocal
```

#### Returns

**Type:** Spine.Unity.UpdateBonesDelegate

### UpdateWorld

```csharp
event UpdateBonesDelegate UpdateWorld
```

#### Returns

**Type:** Spine.Unity.UpdateBonesDelegate
