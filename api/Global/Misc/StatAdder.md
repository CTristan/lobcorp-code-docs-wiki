---
uid: Global.StatAdder
canonical_path: /api/Global/Misc/StatAdder
---

# Class StatAdder

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StatAdder : IdentityTransform, StatTransform
```

Returns the sum of the input float and a fixed value.

#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [IdentityTransform](/api/Global/Misc/IdentityTransform) → StatAdder

## Implements
[StatTransform](/api/Global/Misc/StatTransform)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StatAdder(float)

```csharp
public StatAdder(float adder)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `adder` | `System.Single` |  |

## Fields

### adder

```csharp
private float adder
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### FloatToFloat(float)

```csharp
public override float FloatToFloat(float v)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `v` | `System.Single` |  |

#### Returns

**Type:** System.Single
