---
uid: Global.PathResult
canonical_path: /api/Global/Misc/PathResult
---

# Class PathResult

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PathResult
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PathResult

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PathResult(MapEdge[], EdgeDirection[], float)

```csharp
public PathResult(MapEdge[] pathEdges, EdgeDirection[] edgeDirections, float totalCost)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pathEdges` | `Global.MapEdge[]` |  |
| `edgeDirections` | `Global.EdgeDirection[]` |  |
| `totalCost` | `System.Single` |  |

## Fields

### edgeDirections

```csharp
public EdgeDirection[] edgeDirections
```

#### Field Value

**Type:** Global.EdgeDirection[]

### pathEdges

```csharp
public MapEdge[] pathEdges
```

#### Field Value

**Type:** Global.MapEdge[]

### totalCost

```csharp
public float totalCost
```

#### Field Value

**Type:** System.Single

### zValues

```csharp
public float[] zValues
```

#### Field Value

**Type:** System.Single[]
