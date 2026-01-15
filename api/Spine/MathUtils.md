---
uid: Spine.MathUtils
canonical_path: /api/Spine/MathUtils
---

# Class MathUtils

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class MathUtils
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MathUtils

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Fields

### DegFull

```csharp
private const float DegFull = 360
```

#### Field Value

**Type:** System.Single

### DegRad

```csharp
public const float DegRad = 0.017453292
```

#### Field Value

**Type:** System.Single

### DegToIndex

```csharp
private const float DegToIndex = 45.511112
```

#### Field Value

**Type:** System.Single

### PI

```csharp
public const float PI = 3.1415927
```

#### Field Value

**Type:** System.Single

### PI2

```csharp
public const float PI2 = 6.2831855
```

#### Field Value

**Type:** System.Single

### RadDeg

```csharp
public const float RadDeg = 57.295776
```

#### Field Value

**Type:** System.Single

### RadFull

```csharp
private const float RadFull = 6.2831855
```

#### Field Value

**Type:** System.Single

### RadToIndex

```csharp
private const float RadToIndex = 2607.5945
```

#### Field Value

**Type:** System.Single

### sin

```csharp
private static float[] sin
```

#### Field Value

**Type:** System.Single[]

### SIN_BITS

```csharp
private const int SIN_BITS = 14
```

#### Field Value

**Type:** System.Int32

### SIN_COUNT

```csharp
private const int SIN_COUNT = 16384
```

#### Field Value

**Type:** System.Int32

### SIN_MASK

```csharp
private const int SIN_MASK = 16383
```

#### Field Value

**Type:** System.Int32

## Methods

### Atan2(float, float)

```csharp
public static float Atan2(float y, float x)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `y` | `System.Single` |  |
| `x` | `System.Single` |  |

#### Returns

**Type:** System.Single

### Clamp(float, float, float)

```csharp
public static float Clamp(float value, float min, float max)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |
| `min` | `System.Single` |  |
| `max` | `System.Single` |  |

#### Returns

**Type:** System.Single

### Cos(float)

```csharp
public static float Cos(float radians)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `radians` | `System.Single` |  |

#### Returns

**Type:** System.Single

### CosDeg(float)

```csharp
public static float CosDeg(float degrees)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `degrees` | `System.Single` |  |

#### Returns

**Type:** System.Single

### Sin(float)

```csharp
public static float Sin(float radians)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `radians` | `System.Single` |  |

#### Returns

**Type:** System.Single

### SinDeg(float)

```csharp
public static float SinDeg(float degrees)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `degrees` | `System.Single` |  |

#### Returns

**Type:** System.Single
