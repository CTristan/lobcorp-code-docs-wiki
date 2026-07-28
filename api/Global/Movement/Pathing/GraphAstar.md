---
title: GraphAstar
description: 
published: true
date: 2026-07-28T17:23:26.527Z
tags: 
editor: markdown
dateCreated: 2026-07-08T04:40:11.313Z
---

# Class GraphAstar
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GraphAstar
```

Used to find the shortest paths between two [`MapNodes`](/api/Global/Map/MapNode) on the [map](/api/Global/Map/MapGraph) using the [A* algorithm](https://wikipedia.org/wiki/A*_search_algorithm).

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GraphAstar

## Methods
### ComputeHeuristic(Vector2, Vector2)
```csharp
public static float ComputeHeuristic(Vector2 a, Vector2 b)
```
Calculates the distance between `a` and `b`, an estimate of the cost from `a` to `b`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `a` | `UnityEngine.Vector2` | The first vector. |
| `b` | `UnityEngine.Vector2` | The second vector. |

#### Returns
**Type:** System.Single

### Distance(MapNode, MapNode, float)
```csharp
public static float Distance(MapNode startPoint, MapNode endPoint, float limit)
```
Uses a modified version of the [A* algorithm](https://wikipedia.org/wiki/A*_search_algorithm) to calculate the distance between `startPoint` and `endPoint` if it is less than `limit`. Returns `-1f` if no path with a cost less than `limit` exists.

Note that the heuristic is implicitly used by the priority queue, since `PathScores` implement `IComparable`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `startPoint` | `Global.MapNode` | The node to start from. |
| `endPoint` | `Global.MapNode` | The node to end at. |
| `limit` | `System.Single` | The maximum distance allowed for a valid path (inclusive). |

#### Returns
**Type:** System.Single

### SearchPath(MapNode, MapNode, bool)
```csharp
public static PathResult SearchPath(MapNode startPoint, MapNode endPoint, bool isRabbit = false)
```
Uses a modified version of the [A* algorithm](https://wikipedia.org/wiki/A*_search_algorithm) to calculate a path between `startPoint` and `endPoint`. Returns an empty (but not `null`) [`PathResult`](/api/Global/Movement/Pathing/PathResult) if no path exists. `isRabbit` controls whether Rabbit Protocol portals should block movement.

Note that the heuristic is implicitly used by the priority queue, since `PathScores` implement `IComparable`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `startPoint` | `Global.MapNode` | The node to start from. |
| `endPoint` | `Global.MapNode` | The node to end at. |
| `isRabbit` | `System.Boolean` | Flag indicating whether the Rabbit Protocol portals should block movement. |

#### Returns
**Type:** Global.PathResult

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







