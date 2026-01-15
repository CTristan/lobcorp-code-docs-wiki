---
uid: Spine.Unity.WaitForSpineAnimationComplete
canonical_path: /api/Spine/Unity/WaitForSpineAnimationComplete
---

# Class WaitForSpineAnimationComplete

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WaitForSpineAnimationComplete : IEnumerator
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WaitForSpineAnimationComplete

## Implements
[IEnumerator](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WaitForSpineAnimationComplete(TrackEntry)

```csharp
public WaitForSpineAnimationComplete(TrackEntry trackEntry)
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

### HandleComplete(TrackEntry)

```csharp
private void HandleComplete(TrackEntry trackEntry)
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
public WaitForSpineAnimationComplete NowWaitFor(TrackEntry trackEntry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackEntry` | `Spine.TrackEntry` |  |

#### Returns

**Type:** Spine.Unity.WaitForSpineAnimationComplete

### SafeSubscribe(TrackEntry)

```csharp
private void SafeSubscribe(TrackEntry trackEntry)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `trackEntry` | `Spine.TrackEntry` |  |
