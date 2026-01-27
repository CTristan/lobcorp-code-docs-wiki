---
uid: Global.MathUtil
canonical_path: /api/Global/Misc/MathUtil
---

# Class MathUtil

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MathUtil
```
Holds a few mathematical functions. Only the unit step function is used.



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MathUtil

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MathUtil()

```csharp
public MathUtil()
```

## Methods

### Power(float)

```csharp
public static float Power(float power)
```
Returns `power` squared.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `power` | `System.Single` |  |

#### Returns

**Type:** System.Single

### UnitStep(float)

```csharp
public static int UnitStep(float n)
```
If `n` is positive, returns 1, and otherwise returns 0.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `n` | `System.Single` |  |

#### Returns

**Type:** System.Int32
