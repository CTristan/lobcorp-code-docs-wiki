---
title: MapEdge
description: 
published: true
date: 2026-07-29T01:09:25.249Z
tags: 
editor: markdown
dateCreated: 2026-07-08T04:19:37.352Z
---

# Class MapEdge
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MapEdge
```
A connection between [`MapNodes`](/api/Global/Map/MapNode) on the [map](/api/Global/Map/MapGraph), representing a path between them.

See also [Movement](/Movement) for an overview of the movement systems.

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MapEdge

## Constructors
### MapEdge(MapNode, MapNode, string)
```csharp
public MapEdge(MapNode node1, MapNode node2, string type)
```
Creates a new edge between `node1` and `node2` of type `type`. Calculates the cost of the edge as the distance from `node1` to `node2`, with a minimum of `0.01f`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node1` | `Global.MapNode` | The first node of the edge. |
| `node2` | `Global.MapNode` | The second node of the edge. |
| `type` | `System.String` | The type of the edge, either `"road"` or `"door"`. |

### MapEdge(MapNode, MapNode, string, float)
```csharp
public MapEdge(MapNode node1, MapNode node2, string type, float cost)
```
Creates a new edge between `node1` and `node2` of type `type`, with the cost `cost`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node1` | `Global.MapNode` | The first node of the edge. |
| `node2` | `Global.MapNode` | The second node of the edge. |
| `type` | `System.String` | The type of the edge, either `"road"` or `"door"`. |
| `cost` | `System.Single` | The cost of the new edge. |

## Fields
### activated
```csharp
public bool activated
```
Unused.

#### Field Value
**Type:** System.Boolean

### cost
```csharp
public float cost
```
The cost of this edge, usually the distance from `node1` to `node2` with a minimum of `0.01f`.

#### Field Value
**Type:** System.Single

### name
```csharp
public string name
```
Unused.

#### Field Value
**Type:** System.String

### node1
```csharp
public MapNode node1
```
The first node in this edge.

#### Field Value
**Type:** Global.MapNode

### node2
```csharp
public MapNode node2
```
The second node in this edge.

#### Field Value
**Type:** Global.MapNode

### type
```csharp
public string type
```
The type of this edge, either `"road"` (for edges in the same room) or `"door"` (for edges which connect to another room).

Used by `UpdateViewPosition` on a number of classes (e.g., [`WorkerUnit::UpdateViewPosition`](/api/Global/Agents-and-Clerks/WorkerUnit#updateviewposition)), as well as by [`MovableObjectNode::MoveBy_GetNextEdge`](/api/Global/Movement/MovableObjectNode#moveby_getnextedgemapnode-unitdirection).

#### Field Value
**Type:** System.String

## Methods
### AddEdgeInNode()
```csharp
public void AddEdgeInNode()
```
Unused.

### ConnectedNode(MapNode)
```csharp
public MapNode ConnectedNode(MapNode node)
```
Returns the opposite node from `node`. Returns `node2` if `node==node1` and `node1` if `node==node2`, and `null` otherwise.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` | The node opposite the desired node on this edge. |

#### Returns
**Type:** Global.MapNode

### ConnectedNodeIgoreActivate(MapNode)
```csharp
public MapNode ConnectedNodeIgoreActivate(MapNode node)
```
Does the exact same thing as [`ConnectedNode`](/api/Global/Map/MapEdge#connectednodemapnode). Returns the opposite node on this edge.

Only used by [`MapGraph::LoadMap`](/api/Global/Map/MapGraph#loadmapxmlnode-xmlnode).

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` | The node opposite the desired node on this edge.  |

#### Returns
**Type:** Global.MapNode

### GetGoalNode(EdgeDirection)
```csharp
public MapNode GetGoalNode(EdgeDirection direction)
```
Gets the second [`MapNode`](/api/Global/Map/MapNode) in the given direction (`FORWARD` or `BACKWARD`), corresponding to an `edgePosRate` of `1f`. (See also [Movement](/Movement).)

Returns `node2` if direction is `FORWARD` and `node1` otherwise.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `direction` | `Global.EdgeDirection` | The direction along the edge. |

#### Returns
**Type:** Global.MapNode

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








