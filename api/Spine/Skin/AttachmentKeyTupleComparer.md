---
uid: Spine.Skin.AttachmentKeyTupleComparer
canonical_path: /api/Spine/Skin/AttachmentKeyTupleComparer
---

# Class Skin.AttachmentKeyTupleComparer

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
private class Skin.AttachmentKeyTupleComparer : IEqualityComparer<Skin.AttachmentKeyTuple>
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Skin.AttachmentKeyTupleComparer

## Implements
[IEqualityComparer<Skin.AttachmentKeyTuple>](https://learn.microsoft.com/dotnet/api/system.collections.generic.iequalitycomparer-1)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AttachmentKeyTupleComparer()

```csharp
public AttachmentKeyTupleComparer()
```

## Fields

### Instance

```csharp
internal static readonly Skin.AttachmentKeyTupleComparer Instance
```

#### Field Value

**Type:** Spine.Skin.AttachmentKeyTupleComparer

## Methods

### IEqualityComparer<AttachmentKeyTuple>.Equals(AttachmentKeyTuple, AttachmentKeyTuple)

```csharp
bool IEqualityComparer<Skin.AttachmentKeyTuple>.Equals(Skin.AttachmentKeyTuple o1, Skin.AttachmentKeyTuple o2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o1` | `Spine.Skin.AttachmentKeyTuple` |  |
| `o2` | `Spine.Skin.AttachmentKeyTuple` |  |

#### Returns

**Type:** System.Boolean

### IEqualityComparer<AttachmentKeyTuple>.GetHashCode(AttachmentKeyTuple)

```csharp
int IEqualityComparer<Skin.AttachmentKeyTuple>.GetHashCode(Skin.AttachmentKeyTuple o)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `o` | `Spine.Skin.AttachmentKeyTuple` |  |

#### Returns

**Type:** System.Int32
