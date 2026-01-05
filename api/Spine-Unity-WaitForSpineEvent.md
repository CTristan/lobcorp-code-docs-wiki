# Class WaitForSpineEvent

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine-Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WaitForSpineEvent : IEnumerator
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WaitForSpineEvent

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### WaitForSpineEvent(AnimationState, EventData, bool)

```csharp
public WaitForSpineEvent(AnimationState state, EventData eventDataReference, bool unsubscribeAfterFiring = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Spine.AnimationState` |  |
| `eventDataReference` | `Spine.EventData` |  |
| `unsubscribeAfterFiring` | `System.Boolean` |  |

### WaitForSpineEvent(AnimationState, string, bool)

```csharp
public WaitForSpineEvent(AnimationState state, string eventName, bool unsubscribeAfterFiring = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Spine.AnimationState` |  |
| `eventName` | `System.String` |  |
| `unsubscribeAfterFiring` | `System.Boolean` |  |

### WaitForSpineEvent(SkeletonAnimation, EventData, bool)

```csharp
public WaitForSpineEvent(SkeletonAnimation skeletonAnimation, EventData eventDataReference, bool unsubscribeAfterFiring = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonAnimation` | `Spine.Unity.SkeletonAnimation` |  |
| `eventDataReference` | `Spine.EventData` |  |
| `unsubscribeAfterFiring` | `System.Boolean` |  |

### WaitForSpineEvent(SkeletonAnimation, string, bool)

```csharp
public WaitForSpineEvent(SkeletonAnimation skeletonAnimation, string eventName, bool unsubscribeAfterFiring = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skeletonAnimation` | `Spine.Unity.SkeletonAnimation` |  |
| `eventName` | `System.String` |  |
| `unsubscribeAfterFiring` | `System.Boolean` |  |

## Properties

### WillUnsubscribeAfterFiring

```csharp
public bool WillUnsubscribeAfterFiring { get; set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### NowWaitFor(AnimationState, EventData, bool)

```csharp
public WaitForSpineEvent NowWaitFor(AnimationState state, EventData eventDataReference, bool unsubscribeAfterFiring = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Spine.AnimationState` |  |
| `eventDataReference` | `Spine.EventData` |  |
| `unsubscribeAfterFiring` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Unity.WaitForSpineEvent

### NowWaitFor(AnimationState, string, bool)

```csharp
public WaitForSpineEvent NowWaitFor(AnimationState state, string eventName, bool unsubscribeAfterFiring = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Spine.AnimationState` |  |
| `eventName` | `System.String` |  |
| `unsubscribeAfterFiring` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Unity.WaitForSpineEvent
