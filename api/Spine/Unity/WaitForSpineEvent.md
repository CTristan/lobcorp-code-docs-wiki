---
uid: Spine.Unity.WaitForSpineEvent
canonical_path: /api/Spine/Unity/WaitForSpineEvent
---

# Class WaitForSpineEvent

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WaitForSpineEvent : IEnumerator
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WaitForSpineEvent

## Implements
[IEnumerator](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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

## Fields

### m_AnimationState

```csharp
private AnimationState m_AnimationState
```

#### Field Value

**Type:** Spine.AnimationState

### m_EventName

```csharp
private string m_EventName
```

#### Field Value

**Type:** System.String

### m_TargetEvent

```csharp
private EventData m_TargetEvent
```

#### Field Value

**Type:** Spine.EventData

### m_unsubscribeAfterFiring

```csharp
private bool m_unsubscribeAfterFiring
```

#### Field Value

**Type:** System.Boolean

### m_WasFired

```csharp
private bool m_WasFired
```

#### Field Value

**Type:** System.Boolean

## Properties

### IEnumerator.Current

```csharp
object IEnumerator.Current { get; }
```

#### Property Value

**Type:** System.Object

### WillUnsubscribeAfterFiring

```csharp
public bool WillUnsubscribeAfterFiring { get; set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### Clear(AnimationState)

```csharp
private void Clear(AnimationState state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Spine.AnimationState` |  |

### HandleAnimationStateEvent(TrackEntry, Event)

```csharp
private void HandleAnimationStateEvent(TrackEntry trackEntry, Event e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackEntry` | `Spine.TrackEntry` |  |
| `e` | `Spine.Event` |  |

### HandleAnimationStateEventByName(TrackEntry, Event)

```csharp
private void HandleAnimationStateEventByName(TrackEntry trackEntry, Event e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackEntry` | `Spine.TrackEntry` |  |
| `e` | `Spine.Event` |  |

### IEnumerator.MoveNext()

```csharp
bool IEnumerator.MoveNext()
```

#### Returns

**Type:** System.Boolean

### IEnumerator.Reset()

```csharp
void IEnumerator.Reset()
```

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

### Subscribe(AnimationState, EventData, bool)

```csharp
private void Subscribe(AnimationState state, EventData eventDataReference, bool unsubscribe)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Spine.AnimationState` |  |
| `eventDataReference` | `Spine.EventData` |  |
| `unsubscribe` | `System.Boolean` |  |

### SubscribeByName(AnimationState, string, bool)

```csharp
private void SubscribeByName(AnimationState state, string eventName, bool unsubscribe)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Spine.AnimationState` |  |
| `eventName` | `System.String` |  |
| `unsubscribe` | `System.Boolean` |  |
