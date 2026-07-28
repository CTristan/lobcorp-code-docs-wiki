---
title: PathResult
description: 
published: true
date: 2026-07-28T19:20:52.803Z
tags: 
editor: markdown
dateCreated: 2026-07-08T04:40:16.482Z
---

# Class PathResult
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PathResult
```

A path for something to follow, in terms of node edges to travel between. This is the most common type of path for a unit to follow. (See also [`PathMoveBy`](/api/Global/Movement/PathMoveBy) for the rare exceptions).

Stores the edges and which directions to go in for each leg of the path, as well as the individual leg cost and total cost (roughly, total distance) of the path.

Note that [`GraphAstar`](/api/Global/Movement/Pathing/GraphAstar) never returns a null `PathResult`, so an empty `PathResult` (with no edges or edge directions) represents "no path found".

See also [Movement](/Movement) for an overview of the movement systems.

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PathResult

## Constructors
### PathResult(MapEdge[], EdgeDirection[], float)
```csharp
public PathResult(MapEdge[] pathEdges, EdgeDirection[] edgeDirections, float totalCost)
```
Constructs a new `PathResult` with the given edges, directions, and total cost.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `pathEdges` | `Global.MapEdge[]` | The edges of this path. |
| `edgeDirections` | `Global.EdgeDirection[]` | The direction to travel along each edge of the path. |
| `totalCost` | `System.Single` | The total distance to travel along the whole path. |

## Fields
### edgeDirections
```csharp
public EdgeDirection[] edgeDirections
```
The direction of each edge, either `FORWARD` or `BACKWARD`, depending on whether the path goes from `node1` to `node2` of the edge or the opposite, respectively.

#### Field Value
**Type:** Global.EdgeDirection[]

### pathEdges
```csharp
public MapEdge[] pathEdges
```
An array of [`MapEdges`](/api/Global/Map/MapEdge) in this path.

#### Field Value
**Type:** Global.MapEdge[]

### totalCost
```csharp
public float totalCost
```
The total distance across the entire path, generally the sum of the cost of its edges.

#### Field Value
**Type:** System.Single

### zValues
```csharp
public float[] zValues
```
Unused.

#### Field Value
**Type:** System.Single[]

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







