# Class TriangulationContext

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public abstract class TriangulationContext
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TriangulationContext

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### TriangulationContext()

```csharp
protected TriangulationContext()
```

## Fields

### Points

```csharp
public readonly List<TriangulationPoint> Points
```

#### Field Value

**Type:** System.Collections.Generic.List{Poly2Tri.TriangulationPoint}

### Triangles

```csharp
public readonly List<DelaunayTriangle> Triangles
```

#### Field Value

**Type:** System.Collections.Generic.List{Poly2Tri.DelaunayTriangle}

## Properties

### Algorithm

```csharp
public abstract TriangulationAlgorithm Algorithm { get; }
```

#### Property Value

**Type:** Poly2Tri.TriangulationAlgorithm

### DebugContext

```csharp
public TriangulationDebugContext DebugContext { get; protected set; }
```

#### Property Value

**Type:** Poly2Tri.TriangulationDebugContext

### DTDebugContext

```csharp
public DTSweepDebugContext DTDebugContext { get; }
```

#### Property Value

**Type:** Poly2Tri.DTSweepDebugContext

### IsDebugEnabled

```csharp
public virtual bool IsDebugEnabled { get; protected set; }
```

#### Property Value

**Type:** System.Boolean

### StepCount

```csharp
public int StepCount { get; }
```

#### Property Value

**Type:** System.Int32

### Triangulatable

```csharp
public ITriangulatable Triangulatable { get; }
```

#### Property Value

**Type:** Poly2Tri.ITriangulatable

### TriangulationMode

```csharp
public TriangulationMode TriangulationMode { get; protected set; }
```

#### Property Value

**Type:** Poly2Tri.TriangulationMode

## Methods

### Clear()

```csharp
public virtual void Clear()
```

### Done()

```csharp
public void Done()
```

### NewConstraint(TriangulationPoint, TriangulationPoint)

```csharp
public abstract TriangulationConstraint NewConstraint(TriangulationPoint a, TriangulationPoint b)
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
public virtual void PrepareTriangulation(ITriangulatable t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `Poly2Tri.ITriangulatable` |  |

### Update(string)

```csharp
public void Update(string message)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `message` | `System.String` |  |
