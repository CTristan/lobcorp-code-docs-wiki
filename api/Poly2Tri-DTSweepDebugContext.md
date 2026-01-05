# Class DTSweepDebugContext

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DTSweepDebugContext : TriangulationDebugContext
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [TriangulationDebugContext](/api/Poly2Tri-TriangulationDebugContext) → DTSweepDebugContext

## Inherited Members
[_tcx](/api/Poly2Tri-TriangulationDebugContext#tcx), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DTSweepDebugContext(DTSweepContext)

```csharp
public DTSweepDebugContext(DTSweepContext tcx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.DTSweepContext` |  |

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
