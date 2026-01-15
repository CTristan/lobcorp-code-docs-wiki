---
uid: Poly2Tri.EdgeIntersectInfo
canonical_path: /api/Poly2Tri/EdgeIntersectInfo
---

# Class EdgeIntersectInfo

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EdgeIntersectInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EdgeIntersectInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EdgeIntersectInfo(Edge, Edge, Point2D)

```csharp
public EdgeIntersectInfo(Edge edgeOne, Edge edgeTwo, Point2D intersectionPoint)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `edgeOne` | `Poly2Tri.Edge` |  |
| `edgeTwo` | `Poly2Tri.Edge` |  |
| `intersectionPoint` | `Poly2Tri.Point2D` |  |

## Properties

### EdgeOne

```csharp
public Edge EdgeOne { get; private set; }
```

#### Property Value

**Type:** Poly2Tri.Edge

### EdgeTwo

```csharp
public Edge EdgeTwo { get; private set; }
```

#### Property Value

**Type:** Poly2Tri.Edge

### IntersectionPoint

```csharp
public Point2D IntersectionPoint { get; private set; }
```

#### Property Value

**Type:** Poly2Tri.Point2D
