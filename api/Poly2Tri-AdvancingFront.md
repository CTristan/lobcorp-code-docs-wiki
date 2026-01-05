# Class AdvancingFront

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AdvancingFront
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AdvancingFront

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AdvancingFront(AdvancingFrontNode, AdvancingFrontNode)

```csharp
public AdvancingFront(AdvancingFrontNode head, AdvancingFrontNode tail)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `head` | `Poly2Tri.AdvancingFrontNode` |  |
| `tail` | `Poly2Tri.AdvancingFrontNode` |  |

## Fields

### Head

```csharp
public AdvancingFrontNode Head
```

#### Field Value

**Type:** Poly2Tri.AdvancingFrontNode

### Search

```csharp
protected AdvancingFrontNode Search
```

#### Field Value

**Type:** Poly2Tri.AdvancingFrontNode

### Tail

```csharp
public AdvancingFrontNode Tail
```

#### Field Value

**Type:** Poly2Tri.AdvancingFrontNode

## Methods

### AddNode(AdvancingFrontNode)

```csharp
public void AddNode(AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

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

### LocatePoint(TriangulationPoint)

```csharp
public AdvancingFrontNode LocatePoint(TriangulationPoint point)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `point` | `Poly2Tri.TriangulationPoint` |  |

#### Returns

**Type:** Poly2Tri.AdvancingFrontNode

### RemoveNode(AdvancingFrontNode)

```csharp
public void RemoveNode(AdvancingFrontNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Poly2Tri.AdvancingFrontNode` |  |

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
