---
uid: Poly2Tri.ITriangulatable
canonical_path: /api/Poly2Tri/ITriangulatable
---

# Interface ITriangulatable

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface ITriangulatable
```

## Properties

### Bounds

```csharp
Rect2D Bounds { get; }
```

#### Property Value

**Type:** Poly2Tri.Rect2D

### DisplayFlipX

```csharp
bool DisplayFlipX { get; set; }
```

#### Property Value

**Type:** System.Boolean

### DisplayFlipY

```csharp
bool DisplayFlipY { get; set; }
```

#### Property Value

**Type:** System.Boolean

### DisplayRotate

```csharp
float DisplayRotate { get; set; }
```

#### Property Value

**Type:** System.Single

### FileName

```csharp
string FileName { get; set; }
```

#### Property Value

**Type:** System.String

### MaxX

```csharp
double MaxX { get; }
```

#### Property Value

**Type:** System.Double

### MaxY

```csharp
double MaxY { get; }
```

#### Property Value

**Type:** System.Double

### MinX

```csharp
double MinX { get; }
```

#### Property Value

**Type:** System.Double

### MinY

```csharp
double MinY { get; }
```

#### Property Value

**Type:** System.Double

### Precision

```csharp
double Precision { get; set; }
```

#### Property Value

**Type:** System.Double

### Triangles

```csharp
IList<DelaunayTriangle> Triangles { get; }
```

#### Property Value

**Type:** System.Collections.Generic.IList{Poly2Tri.DelaunayTriangle}

### TriangulationMode

```csharp
TriangulationMode TriangulationMode { get; }
```

#### Property Value

**Type:** Poly2Tri.TriangulationMode

## Methods

### AddTriangle(DelaunayTriangle)

```csharp
void AddTriangle(DelaunayTriangle t)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `t` | `Poly2Tri.DelaunayTriangle` |  |

### AddTriangles(IEnumerable<DelaunayTriangle>)

```csharp
void AddTriangles(IEnumerable<DelaunayTriangle> list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.Generic.IEnumerable{Poly2Tri.DelaunayTriangle}` |  |

### ClearTriangles()

```csharp
void ClearTriangles()
```

### Prepare(TriangulationContext)

```csharp
void Prepare(TriangulationContext tcx)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `tcx` | `Poly2Tri.TriangulationContext` |  |
