---
uid: Poly2Tri.SplitComplexPolygonNode
canonical_path: /api/Poly2Tri/SplitComplexPolygonNode
---

# Class SplitComplexPolygonNode

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SplitComplexPolygonNode
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SplitComplexPolygonNode

## Inherited Members
[Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SplitComplexPolygonNode()

```csharp
public SplitComplexPolygonNode()
```

### SplitComplexPolygonNode(Point2D)

```csharp
public SplitComplexPolygonNode(Point2D pos)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `Poly2Tri.Point2D` |  |

## Fields

### mConnected

```csharp
private List<SplitComplexPolygonNode> mConnected
```

#### Field Value

**Type:** System.Collections.Generic.List{Poly2Tri.SplitComplexPolygonNode}

### mPosition

```csharp
private Point2D mPosition
```

#### Field Value

**Type:** Poly2Tri.Point2D

## Properties

### NumConnected

```csharp
public int NumConnected { get; }
```

#### Property Value

**Type:** System.Int32

### Position

```csharp
public Point2D Position { get; set; }
```

#### Property Value

**Type:** Poly2Tri.Point2D

### this[int]

```csharp
public SplitComplexPolygonNode this[int index] { get; }
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Property Value

**Type:** Poly2Tri.SplitComplexPolygonNode

## Methods

### AddConnection(SplitComplexPolygonNode)

```csharp
public void AddConnection(SplitComplexPolygonNode toMe)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `toMe` | `Poly2Tri.SplitComplexPolygonNode` |  |

### ClearConnections()

```csharp
public void ClearConnections()
```

### Equals(object)

```csharp
public override bool Equals(object obj)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `obj` | `System.Object` |  |

#### Returns

**Type:** System.Boolean

### Equals(SplitComplexPolygonNode)

```csharp
public bool Equals(SplitComplexPolygonNode pn)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pn` | `Poly2Tri.SplitComplexPolygonNode` |  |

#### Returns

**Type:** System.Boolean

### GetHashCode()

```csharp
public override int GetHashCode()
```

#### Returns

**Type:** System.Int32

### GetRightestConnection(Point2D)

```csharp
public SplitComplexPolygonNode GetRightestConnection(Point2D incomingDir)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `incomingDir` | `Poly2Tri.Point2D` |  |

#### Returns

**Type:** Poly2Tri.SplitComplexPolygonNode

### GetRightestConnection(SplitComplexPolygonNode)

```csharp
public SplitComplexPolygonNode GetRightestConnection(SplitComplexPolygonNode incoming)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `incoming` | `Poly2Tri.SplitComplexPolygonNode` |  |

#### Returns

**Type:** Poly2Tri.SplitComplexPolygonNode

### IsConnectedTo(SplitComplexPolygonNode)

```csharp
private bool IsConnectedTo(SplitComplexPolygonNode me)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `me` | `Poly2Tri.SplitComplexPolygonNode` |  |

#### Returns

**Type:** System.Boolean

### IsRighter(double, double, double, double)

```csharp
private bool IsRighter(double sinA, double cosA, double sinB, double cosB)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sinA` | `System.Double` |  |
| `cosA` | `System.Double` |  |
| `sinB` | `System.Double` |  |
| `cosB` | `System.Double` |  |

#### Returns

**Type:** System.Boolean

### remainder(int, int)

```csharp
private int remainder(int x, int modulus)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Int32` |  |
| `modulus` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### RemoveConnection(SplitComplexPolygonNode)

```csharp
public void RemoveConnection(SplitComplexPolygonNode fromMe)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fromMe` | `Poly2Tri.SplitComplexPolygonNode` |  |

### RemoveConnectionByIndex(int)

```csharp
private void RemoveConnectionByIndex(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String

## Operators

### operator !=(SplitComplexPolygonNode, SplitComplexPolygonNode)

```csharp
public static bool operator !=(SplitComplexPolygonNode lhs, SplitComplexPolygonNode rhs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.SplitComplexPolygonNode` |  |
| `rhs` | `Poly2Tri.SplitComplexPolygonNode` |  |

#### Returns

**Type:** System.Boolean

### operator ==(SplitComplexPolygonNode, SplitComplexPolygonNode)

```csharp
public static bool operator ==(SplitComplexPolygonNode lhs, SplitComplexPolygonNode rhs)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lhs` | `Poly2Tri.SplitComplexPolygonNode` |  |
| `rhs` | `Poly2Tri.SplitComplexPolygonNode` |  |

#### Returns

**Type:** System.Boolean
