---
uid: Spine.Unity.WaitForSpineTrackEntryEnd
canonical_path: /api/Spine/Unity/WaitForSpineTrackEntryEnd
---

# Class WaitForSpineTrackEntryEnd

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WaitForSpineTrackEntryEnd : IEnumerator
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WaitForSpineTrackEntryEnd

## Implements
[IEnumerator](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WaitForSpineTrackEntryEnd(TrackEntry)

```csharp
public WaitForSpineTrackEntryEnd(TrackEntry trackEntry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackEntry` | `Spine.TrackEntry` |  |

## Fields

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

## Methods

### HandleEnd(TrackEntry)

```csharp
private void HandleEnd(TrackEntry trackEntry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackEntry` | `Spine.TrackEntry` |  |

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

### NowWaitFor(TrackEntry)

```csharp
public WaitForSpineTrackEntryEnd NowWaitFor(TrackEntry trackEntry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackEntry` | `Spine.TrackEntry` |  |

#### Returns

**Type:** Spine.Unity.WaitForSpineTrackEntryEnd

### SafeSubscribe(TrackEntry)

```csharp
private void SafeSubscribe(TrackEntry trackEntry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackEntry` | `Spine.TrackEntry` |  |
