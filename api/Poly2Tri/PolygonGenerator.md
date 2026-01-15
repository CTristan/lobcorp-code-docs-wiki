---
uid: Poly2Tri.PolygonGenerator
canonical_path: /api/Poly2Tri/PolygonGenerator
---

# Class PolygonGenerator

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PolygonGenerator
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PolygonGenerator

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PolygonGenerator()

```csharp
public PolygonGenerator()
```

## Fields

### PI_2

```csharp
private static double PI_2
```

#### Field Value

**Type:** System.Double

### RNG

```csharp
private static readonly Random RNG
```

#### Field Value

**Type:** System.Random

## Methods

### RandomCircleSweep(double, int)

```csharp
public static Polygon RandomCircleSweep(double scale, int vertexCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `scale` | `System.Double` |  |
| `vertexCount` | `System.Int32` |  |

#### Returns

**Type:** Poly2Tri.Polygon

### RandomCircleSweep2(double, int)

```csharp
public static Polygon RandomCircleSweep2(double scale, int vertexCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `scale` | `System.Double` |  |
| `vertexCount` | `System.Int32` |  |

#### Returns

**Type:** Poly2Tri.Polygon
