---
uid: Poly2Tri.DTSweepDebugContext
canonical_path: /api/Poly2Tri/DTSweepDebugContext
---

# Class DTSweepDebugContext

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DTSweepDebugContext : TriangulationDebugContext
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [TriangulationDebugContext](/api/Poly2Tri/TriangulationDebugContext) → DTSweepDebugContext

## Inherited Members
[_tcx](/api/Poly2Tri/TriangulationDebugContext#tcx), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DTSweepDebugContext(DTSweepContext)

```csharp
public DTSweepDebugContext(DTSweepContext tcx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |

## Fields

### _activeConstraint

```csharp
private DTSweepConstraint _activeConstraint
```

#### Field Value

**Type:** Poly2Tri.DTSweepConstraint

### _activeNode

```csharp
private AdvancingFrontNode _activeNode
```

#### Field Value

**Type:** Poly2Tri.AdvancingFrontNode

### _activePoint

```csharp
private TriangulationPoint _activePoint
```

#### Field Value

**Type:** Poly2Tri.TriangulationPoint

### _primaryTriangle

```csharp
private DelaunayTriangle _primaryTriangle
```

#### Field Value

**Type:** Poly2Tri.DelaunayTriangle

### _secondaryTriangle

```csharp
private DelaunayTriangle _secondaryTriangle
```

#### Field Value

**Type:** Poly2Tri.DelaunayTriangle

## Properties

### ActiveConstraint

```csharp
public DTSweepConstraint ActiveConstraint { get; set; }
```

#### Property Value

**Type:** Poly2Tri.DTSweepConstraint

### ActiveNode

```csharp
public AdvancingFrontNode ActiveNode { get; set; }
```

#### Property Value

**Type:** Poly2Tri.AdvancingFrontNode

### ActivePoint

```csharp
public TriangulationPoint ActivePoint { get; set; }
```

#### Property Value

**Type:** Poly2Tri.TriangulationPoint

### IsDebugContext

```csharp
public bool IsDebugContext { get; }
```

#### Property Value

**Type:** System.Boolean

### PrimaryTriangle

```csharp
public DelaunayTriangle PrimaryTriangle { get; set; }
```

#### Property Value

**Type:** Poly2Tri.DelaunayTriangle

### SecondaryTriangle

```csharp
public DelaunayTriangle SecondaryTriangle { get; set; }
```

#### Property Value

**Type:** Poly2Tri.DelaunayTriangle

## Methods

### Clear()

```csharp
public override void Clear()
```
