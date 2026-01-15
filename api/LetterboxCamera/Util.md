---
uid: LetterboxCamera.Util
canonical_path: /api/LetterboxCamera/Util
---

# Class Util

**Namespace:** [LetterboxCamera](/api/LetterboxCamera)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class Util
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Util

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Methods

### AsNegative(float)

```csharp
public static float AsNegative(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

#### Returns

**Type:** System.Single

### AsPositive(float)

```csharp
public static float AsPositive(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

#### Returns

**Type:** System.Single

### BezierCurve(float[], float)

```csharp
public static float BezierCurve(float[] p, float t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `System.Single[]` |  |
| `t` | `System.Single` |  |

#### Returns

**Type:** System.Single

### BezierCurve(Vector3[], float)

```csharp
public static Vector3 BezierCurve(Vector3[] p, float t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `UnityEngine.Vector3[]` |  |
| `t` | `System.Single` |  |

#### Returns

**Type:** UnityEngine.Vector3

### CalculateReflectedVelocity(Vector3, Vector3)

```csharp
public static Vector3 CalculateReflectedVelocity(Vector3 originalVelocity, Vector3 normalOfCollision)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `originalVelocity` | `UnityEngine.Vector3` |  |
| `normalOfCollision` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** UnityEngine.Vector3

### Clamp(float, float, float)

```csharp
public static float Clamp(float min, float max, float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `min` | `System.Single` |  |
| `max` | `System.Single` |  |
| `value` | `System.Single` |  |

#### Returns

**Type:** System.Single

### Clamp(int, int, int)

```csharp
public static int Clamp(int min, int max, int value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `min` | `System.Int32` |  |
| `max` | `System.Int32` |  |
| `value` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### ColorToHex(Color32)

```csharp
public static string ColorToHex(Color32 color)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `color` | `UnityEngine.Color32` |  |

#### Returns

**Type:** System.String

### DegreesToVector(float)

```csharp
public static Vector2 DegreesToVector(float _angle)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_angle` | `System.Single` |  |

#### Returns

**Type:** UnityEngine.Vector2

### Difference(float, float)

```csharp
public static float Difference(float a, float b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `System.Single` |  |
| `b` | `System.Single` |  |

#### Returns

**Type:** System.Single

### Difference(int, int)

```csharp
public static int Difference(int a, int b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `System.Int32` |  |
| `b` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### DirectionVector(Vector3, Vector3)

```csharp
public static Vector3 DirectionVector(Vector3 origin, Vector3 target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `UnityEngine.Vector3` |  |
| `target` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** UnityEngine.Vector3

### Error(object, string)

```csharp
public static void Error(object sender, string error)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sender` | `System.Object` |  |
| `error` | `System.String` |  |

### GetMemberName<T>(Expression<Func<T>>)

```csharp
public static string GetMemberName<T>(Expression<Func<T>> expression)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `expression` | `System.Linq.Expressions.Expression{System.Func{{T}}}` |  |

#### Returns

**Type:** System.String

### GrootWhatAreYouDoing()

```csharp
public static string GrootWhatAreYouDoing()
```

#### Returns

**Type:** System.String

### HexToColor(string)

```csharp
public static Color HexToColor(string hex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `hex` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Color

### IndexToFlags(int)

```csharp
public static int IndexToFlags(int _index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_index` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### IsOdd(int)

```csharp
public static bool IsOdd(int value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### IsPointOnMainCamera(Vector3)

```csharp
public static bool IsPointOnMainCamera(Vector3 _point)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_point` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** System.Boolean

### Lerp(float, float, float)

```csharp
public static float Lerp(float p1, float p2, float t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p1` | `System.Single` |  |
| `p2` | `System.Single` |  |
| `t` | `System.Single` |  |

#### Returns

**Type:** System.Single

### Lerp(Vector3, Vector3, float)

```csharp
public static Vector3 Lerp(Vector3 p1, Vector3 p2, float t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p1` | `UnityEngine.Vector3` |  |
| `p2` | `UnityEngine.Vector3` |  |
| `t` | `System.Single` |  |

#### Returns

**Type:** UnityEngine.Vector3

### NullError(object, string, string)

```csharp
public static void NullError(object sender, string variableName, string extraNotes = "")
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sender` | `System.Object` |  |
| `variableName` | `System.String` |  |
| `extraNotes` | `System.String` |  |

### Percent(float, float, float)

```csharp
public static float Percent(float min, float max, float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `min` | `System.Single` |  |
| `max` | `System.Single` |  |
| `value` | `System.Single` |  |

#### Returns

**Type:** System.Single

### PercentUnclampled(float, float, float)

```csharp
public static float PercentUnclampled(float min, float max, float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `min` | `System.Single` |  |
| `max` | `System.Single` |  |
| `value` | `System.Single` |  |

#### Returns

**Type:** System.Single

### RectContainsRect(Vector2, Vector2, Vector2, Vector2)

```csharp
public static bool RectContainsRect(Vector2 extremeMinA, Vector2 extremeMaxA, Vector2 extremeMinB, Vector2 extremeMaxB)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `extremeMinA` | `UnityEngine.Vector2` |  |
| `extremeMaxA` | `UnityEngine.Vector2` |  |
| `extremeMinB` | `UnityEngine.Vector2` |  |
| `extremeMaxB` | `UnityEngine.Vector2` |  |

#### Returns

**Type:** System.Boolean

### ReflectOnXandYAxis(Vector3)

```csharp
public static Vector3 ReflectOnXandYAxis(Vector3 _vector)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_vector` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** UnityEngine.Vector3

### ReflectOnXAxis(Vector3)

```csharp
public static Vector3 ReflectOnXAxis(Vector3 _vector)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_vector` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** UnityEngine.Vector3

### ReflectOnYAxis(Vector3)

```csharp
public static Vector3 ReflectOnYAxis(Vector3 _vector)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_vector` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** UnityEngine.Vector3

### VectorToDegrees(Vector2)

```csharp
public static float VectorToDegrees(Vector2 _vector)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `_vector` | `UnityEngine.Vector2` |  |

#### Returns

**Type:** System.Single

### XYplaneUpDirection()

```csharp
public static Vector3 XYplaneUpDirection()
```

#### Returns

**Type:** UnityEngine.Vector3
