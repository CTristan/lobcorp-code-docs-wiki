---
uid: Poly2Tri.AdvancingFrontNode
canonical_path: /api/Poly2Tri/AdvancingFrontNode
---

# Class AdvancingFrontNode

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AdvancingFrontNode
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AdvancingFrontNode

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AdvancingFrontNode(TriangulationPoint)

```csharp
public AdvancingFrontNode(TriangulationPoint point)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `point` | `Poly2Tri.TriangulationPoint` |  |

## Fields

### Next

```csharp
public AdvancingFrontNode Next
```

#### Field Value

**Type:** Poly2Tri.AdvancingFrontNode

### Point

```csharp
public TriangulationPoint Point
```

#### Field Value

**Type:** Poly2Tri.TriangulationPoint

### Prev

```csharp
public AdvancingFrontNode Prev
```

#### Field Value

**Type:** Poly2Tri.AdvancingFrontNode

### Triangle

```csharp
public DelaunayTriangle Triangle
```

#### Field Value

**Type:** Poly2Tri.DelaunayTriangle

### Value

```csharp
public double Value
```

#### Field Value

**Type:** System.Double

## Properties

### HasNext

```csharp
public bool HasNext { get; }
```

#### Property Value

**Type:** System.Boolean

### HasPrev

```csharp
public bool HasPrev { get; }
```

#### Property Value

**Type:** System.Boolean
