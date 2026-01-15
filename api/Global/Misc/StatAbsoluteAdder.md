---
uid: Global.StatAbsoluteAdder
canonical_path: /api/Global/Misc/StatAbsoluteAdder
---

# Class StatAbsoluteAdder

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StatAbsoluteAdder : IdentityTransform, StatTransform
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [IdentityTransform](/api/Global/Misc/IdentityTransform) → StatAbsoluteAdder

## Implements
[StatTransform](/api/Global/Misc/StatTransform)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StatAbsoluteAdder(float)

```csharp
public StatAbsoluteAdder(float adder)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `adder` | `System.Single` |  |

## Fields

### adder

```csharp
private float adder
```

#### Field Value

**Type:** System.Single

## Methods

### FloatToFloat(float)

```csharp
public override float FloatToFloat(float v)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `v` | `System.Single` |  |

#### Returns

**Type:** System.Single
