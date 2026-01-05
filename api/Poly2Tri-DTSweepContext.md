# Class DTSweepContext

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DTSweepContext : TriangulationContext
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [TriangulationContext](/api/Poly2Tri-TriangulationContext) → DTSweepContext

## Inherited Members
[Triangles](/api/Poly2Tri-TriangulationContext#triangles), [Points](/api/Poly2Tri-TriangulationContext#points), [Done()](/api/Poly2Tri-TriangulationContext#done), [Update(string)](/api/Poly2Tri-TriangulationContext#update-string), [DebugContext](/api/Poly2Tri-TriangulationContext#debugcontext), [TriangulationMode](/api/Poly2Tri-TriangulationContext#triangulationmode), [Triangulatable](/api/Poly2Tri-TriangulationContext#triangulatable), [StepCount](/api/Poly2Tri-TriangulationContext#stepcount), [DTDebugContext](/api/Poly2Tri-TriangulationContext#dtdebugcontext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DTSweepContext()

```csharp
public DTSweepContext()
```

## Fields

### Basin

```csharp
public DTSweepBasin Basin
```

#### Field Value

**Type:** Poly2Tri.DTSweepBasin

### EdgeEvent

```csharp
public DTSweepEdgeEvent EdgeEvent
```

#### Field Value

**Type:** Poly2Tri.DTSweepEdgeEvent

### Front

```csharp
public AdvancingFront Front
```

#### Field Value

**Type:** Poly2Tri.AdvancingFront

## Properties

### Algorithm

```csharp
public override TriangulationAlgorithm Algorithm { get; }
```

#### Property Value

**Type:** Poly2Tri.TriangulationAlgorithm

### Head

```csharp
public TriangulationPoint Head { get; set; }
```

#### Property Value

**Type:** Poly2Tri.TriangulationPoint

### IsDebugEnabled

```csharp
public override bool IsDebugEnabled { get; protected set; }
```

#### Property Value

**Type:** System.Boolean

### Tail

```csharp
public TriangulationPoint Tail { get; set; }
```

#### Property Value

**Type:** Poly2Tri.TriangulationPoint

## Methods

### AddNode(AdvancingFrontNode)

```csharp
public void AddNode(AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### Clear()

```csharp
public override void Clear()
```

### CreateAdvancingFront()

```csharp
public void CreateAdvancingFront()
```

### FinalizeTriangulation()

```csharp
public void FinalizeTriangulation()
```

### LocateNode(TriangulationPoint)

```csharp
public AdvancingFrontNode LocateNode(TriangulationPoint point)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `point` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** Poly2Tri.AdvancingFrontNode

### MapTriangleToNodes(DelaunayTriangle)

```csharp
public void MapTriangleToNodes(DelaunayTriangle t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `Poly2Tri.DelaunayTriangle` |  |

### MeshClean(DelaunayTriangle)

```csharp
public void MeshClean(DelaunayTriangle triangle)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `triangle` | `Poly2Tri.DelaunayTriangle` |  |

### NewConstraint(TriangulationPoint, TriangulationPoint)

```csharp
public override TriangulationConstraint NewConstraint(TriangulationPoint a, TriangulationPoint b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Poly2Tri.TriangulationPoint` |  |
| `b` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** Poly2Tri.TriangulationConstraint

### PrepareTriangulation(ITriangulatable)

```csharp
public override void PrepareTriangulation(ITriangulatable t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `Poly2Tri.ITriangulatable` |  |

### RemoveFromList(DelaunayTriangle)

```csharp
public void RemoveFromList(DelaunayTriangle triangle)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `triangle` | `Poly2Tri.DelaunayTriangle` |  |

### RemoveNode(AdvancingFrontNode)

```csharp
public void RemoveNode(AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |
