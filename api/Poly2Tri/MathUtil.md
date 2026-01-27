---
uid: Poly2Tri.MathUtil
canonical_path: /api/Poly2Tri/MathUtil
---

# Class MathUtil

**Namespace:** [Poly2Tri](/api/Poly2Tri)
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

## Fields

### EPSILON

```csharp
public static double EPSILON
```

#### Field Value

**Type:** System.Double

## Methods

### AreValuesEqual(double, double)

```csharp
public static bool AreValuesEqual(double val1, double val2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val1` | `System.Double` |  |
| `val2` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

### AreValuesEqual(double, double, double)

```csharp
public static bool AreValuesEqual(double val1, double val2, double tolerance)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val1` | `System.Double` |  |
| `val2` | `System.Double` |  |
| `tolerance` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

### Clamp(double, double, double)

```csharp
public static double Clamp(double a, double low, double high)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `System.Double` |  |
| `low` | `System.Double` |  |
| `high` | `System.Double` |  |

#### Returns

**Type:** System.Double

### IsValueBetween(double, double, double, double)

```csharp
public static bool IsValueBetween(double val, double min, double max, double tolerance)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Double` |  |
| `min` | `System.Double` |  |
| `max` | `System.Double` |  |
| `tolerance` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

### Jenkins32Hash(byte[], uint)

```csharp
public static uint Jenkins32Hash(byte[] data, uint nInitialValue)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Byte[]` |  |
| `nInitialValue` | `System.UInt32` |  |

#### Returns

**Type:** System.UInt32

### RoundWithPrecision(double, double)

```csharp
public static double RoundWithPrecision(double f, double precision)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `f` | `System.Double` |  |
| `precision` | `System.Double` |  |

#### Returns

**Type:** System.Double

### Swap<T>(ref T, ref T)

```csharp
public static void Swap<T>(ref T a, ref T b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `{T}` |  |
| `b` | `{T}` |  |
