---
uid: Global.GraphAstar
canonical_path: /api/Global/Misc/GraphAstar
---

# Class GraphAstar

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GraphAstar
```
For finding the shortest path between two nodes on the [map](/api/Global/IOBserver/MapGraph).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GraphAstar

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GraphAstar()

```csharp
public GraphAstar()
```

## Methods

### ComputeHeuristic(Vector2, Vector2)

```csharp
public static float ComputeHeuristic(Vector2 a, Vector2 b)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `UnityEngine.Vector2` |  |
| `b` | `UnityEngine.Vector2` |  |

#### Returns

**Type:** System.Single

### Distance(MapNode, MapNode, float)

```csharp
public static float Distance(MapNode startPoint, MapNode endPoint, float limit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `startPoint` | `Global.MapNode` |  |
| `endPoint` | `Global.MapNode` |  |
| `limit` | `System.Single` |  |

#### Returns

**Type:** System.Single

### SearchPath(MapNode, MapNode, bool)

```csharp
public static PathResult SearchPath(MapNode startPoint, MapNode endPoint, bool isRabbit = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `startPoint` | `Global.MapNode` |  |
| `endPoint` | `Global.MapNode` |  |
| `isRabbit` | `System.Boolean` |  |

#### Returns

**Type:** Global.PathResult
