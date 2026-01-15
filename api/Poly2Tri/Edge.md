---
uid: Poly2Tri.Edge
canonical_path: /api/Poly2Tri/Edge
---

# Class Edge

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Edge
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Edge

## Derived
[TriangulationConstraint](/api/Poly2Tri/TriangulationConstraint)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Edge()

```csharp
public Edge()
```

### Edge(Point2D, Point2D)

```csharp
public Edge(Point2D edgeStart, Point2D edgeEnd)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `edgeStart` | `Poly2Tri.Point2D` |  |
| `edgeEnd` | `Poly2Tri.Point2D` |  |

## Fields

### mP

```csharp
protected Point2D mP
```

#### Field Value

**Type:** Poly2Tri.Point2D

### mQ

```csharp
protected Point2D mQ
```

#### Field Value

**Type:** Poly2Tri.Point2D

## Properties

### EdgeEnd

```csharp
public Point2D EdgeEnd { get; set; }
```

#### Property Value

**Type:** Poly2Tri.Point2D

### EdgeStart

```csharp
public Point2D EdgeStart { get; set; }
```

#### Property Value

**Type:** Poly2Tri.Point2D
