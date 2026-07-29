---
title: MapNode
description: 
published: true
date: 2026-07-29T00:29:33.481Z
tags: 
editor: markdown
dateCreated: 2026-07-08T04:19:45.224Z
---

# Class MapNode
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MapNode
```

A node, usually on the [map](/api/Global/Map/MapGraph), representing a location. `MapNodes` with [`MapEdges`](/api/Global/Map/MapEdge) between them are connected.

See also [Movement](/Movement) for an overview of the movement systems.

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MapNode

## Constructors
### MapNode(string, Vector3, string)
```csharp
public MapNode(string id, Vector3 pos, string areaName)
```
Creates a new `MapNode` with the given ID, position, and area.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` | The ID of this node. |
| `pos` | `UnityEngine.Vector3` | The position of this node. |
| `areaName` | `System.String` | The name of the area this node belongs to, usually a string containing a number from 1 to 12 corresponding to a department. |

### MapNode(string, Vector3, string, PassageObjectModel)
```csharp
public MapNode(string id, Vector3 pos, string areaName, PassageObjectModel attachedPassage)
```
Creates a new `MapNode` with the given ID, position, area, and attached room.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` | The ID of this node. |
| `pos` | `UnityEngine.Vector3` | The position of this node. |
| `areaName` | `System.String` | The name of the area this node belongs to, usually a string containing a number from 1 to 12 corresponding to a department. |
| `attachedPassage` | `Global.PassageObjectModel` | The room this node is in (attached to). |

## Fields
### \_activate
```csharp
private bool _activate
```
Flag indicating whether this node is active. Deactivated nodes will not be pathed through.

#### Field Value
**Type:** System.Boolean

### \_teleportDirectionCondition
```csharp
private UnitDirection _teleportDirectionCondition
```
A direction (`LEFT` or `RIGHT`) that a unit must be facing to be teleported by the Rabbit Protocol (see [`SetTeleport`](/api/Global/Map/MapNode#setteleportlist-unitdirection)).

#### Field Value
**Type:** Global.UnitDirection

### \_teleportTo
```csharp
private List<MapNode> _teleportTo
```
A list of teleport destinations for the Rabbit Protocol portals. See [`SetTeleport`](/api/Global/Map/MapNode#setteleportlist-unitdirection).

#### Field Value
**Type:** System.Collections.Generic.List{MapNode}

### areaName
```csharp
private string areaName
```
The name of the area this node belongs to, usually a string containing a number from `"1"` to `"12"` corresponding to a department.

#### Field Value
**Type:** System.String

### attachedElevator
```csharp
private ElevatorPassageModel attachedElevator
```
Only applicable to elevator nodes. For all other nodes, has a value of `null`.

The [invisible elevator](/api/Global/Map/Elevators/ElevatorPassageModel) connected to this node. Elevator nodes are attached to a passage of type `VERTICAL` which is never visited. See also [Movement: Rooms, PassageObjectModels, and Elevators](/Movement#rooms-passageobjectmodels-and-elevators).

#### Field Value
**Type:** Global.ElevatorPassageModel

### attachedPassage
```csharp
private PassageObjectModel attachedPassage
```
The room ([`PassageObjectModel`](/api/Global/Map/Rooms-and-Hallways/PassageObjectModel)) this `MapNode` is in.

#### Field Value
**Type:** Global.PassageObjectModel

### closed
```csharp
public bool closed
```
Only applicable to nodes with [doors](/api/Global/Map/Rooms-and-Hallways/DoorObjectModel). Flag indicating if the door is closed.

#### Field Value
**Type:** System.Boolean

### connectedCreature
```csharp
public CreatureModel connectedCreature
```
Only applicable to nodes attached to containment units ([`IsolateRooms`](/api/Global/Departments/Containment-Units/IsolateRoom)).

Contains the [Abnormality](/api/Global/Abnormalities/CreatureModel) in the attached containment unit.

#### Field Value
**Type:** Global.CreatureModel

### door
```csharp
private DoorObjectModel door
```
Only applicable to nodes with doors ([`DoorObjectModel`](/api/Global/Map/Rooms-and-Hallways/DoorObjectModel)).

The door attached to this node.

#### Field Value
**Type:** Global.DoorObjectModel

### edges
```csharp
private List<MapEdge> edges
```
The list of [edges](/api/Global/Map/MapEdge) connected to this `MapNode`.

#### Field Value
**Type:** System.Collections.Generic.List{MapEdge}

### id
```csharp
private string id
```
A string identifying this node.

See also [a map of nodes by ID](/map/facility_mapnodes.webp) (warning: very large image).

#### Field Value
**Type:** System.String

### isTemporary
```csharp
public bool isTemporary
```
Flag indicating if this `MapNode` is temporary (i.e., constructed for pathing).

Used only by [`MovableObjectNode::MoveToMovableNode`](/api/Global/Movement/MovableObjectNode#movetomovablenodemovableobjectnode-bool) and [`MovableObjectNode::UpdateNodeEdge`](/api/Global/Movement/MovableObjectNode#updatenodeedgemapnode-mapedge).

#### Field Value
**Type:** System.Boolean

### pos
```csharp
private Vector3 pos
```
The position of this `MapNode`.

(To check: Is this in Unity or game units?)

#### Field Value
**Type:** UnityEngine.Vector3

### rabbitUnpassable
```csharp
public bool rabbitUnpassable
```
Flag indicating if this node is blocked with a portal when the [Rabbit Protocol](/api/Rabbit/RabbitProtocolWindow) begins.

#### Field Value
**Type:** System.Boolean

### zNodes
```csharp
private List<MapNode> zNodes
```
Unused.

#### Field Value
**Type:** System.Collections.Generic.List{MapNode}

## Properties
### activate
```csharp
public bool activate { get; set; }
```
Public accessor for [`_activate`](/api/Global/Map/MapNode#_activate). Indicates if this node is active or not.

#### Property Value
**Type:** System.Boolean

## Methods
### AddEdge(MapEdge)
```csharp
public void AddEdge(MapEdge edge)
```
Adds `edge` to the list of [`MapEdges`](/api/Global/Map/MapEdge) connected to this `MapNode`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `edge` | `Global.MapEdge` | The edge to add to this `MapNode`. |

### AddZNode(MapNode)
```csharp
public void AddZNode(MapNode node)
```
Unused.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### AttachElevator(ElevatorPassageModel)
```csharp
public void AttachElevator(ElevatorPassageModel elevator)
```
Sets the attached elevator ([`attachedElevator`](/api/Global/Map/MapNode#attachedelevator)) to the given [invisible elevator](/api/Global/Map/Elevators/ElevatorPassageModel).

See also [Movement: Rooms, PassageObjectModels, and Elevators](/Movement#rooms-passageobjectmodels-and-elevators).

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `elevator` | `Global.ElevatorPassageModel` | The elevator to attach to this `MapNode`. |

### ClearTeleportNode()
```csharp
public void ClearTeleportNode()
```
Removes all teleport nodes added by the Rabbit Protocol.

Also, notifies listeners of `RemoveTeleportNode`, of which there is only one: [`SefiraMapLayer`](/api/Global/Game-Layers/SefiraMapLayer#onnoticestring-params-object).

### CompareByX(MapNode, MapNode)
```csharp
public static int CompareByX(MapNode a, MapNode b)
```
Compares the `x` values of `a` and `b`.

Returns 1 if `a.x > b.x`, -1 if `a.x < b.x`, and 0 otherwise.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `a` | `Global.MapNode` | The first `MapNode` to compare. |
| `b` | `Global.MapNode` | The second `MapNode` to compare. |

#### Returns
**Type:** System.Int32

### GetAreaName()
```csharp
public string GetAreaName()
```
Returns the [area](/api/Global/Map/MapNode#areaname) this `MapNode` belongs to.

Usually a string containing a number from `"1"` to `"12"` corresponding to a department.

#### Returns
**Type:** System.String

### GetAttachedPassage()
```csharp
public PassageObjectModel GetAttachedPassage()
```
Returns the [room](/api/Global/Map/Rooms-and-Hallways/PassageObjectModel) this node is in.

#### Returns
**Type:** Global.PassageObjectModel

### GetDoor()
```csharp
public DoorObjectModel GetDoor()
```
Returns the [door](/api/Global/Map/Rooms-and-Hallways/DoorObjectModel) at this node, or else `null`.

#### Returns
**Type:** Global.DoorObjectModel

### GetEdgeByNode(MapNode)
```csharp
public MapEdge GetEdgeByNode(MapNode node)
```
Unused.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns
**Type:** Global.MapEdge

### GetEdges()
```csharp
public MapEdge[] GetEdges()
```
Returns an array of all edges ([`MapEdges`](/api/Global/Map/MapEdge)) attached to this `MapNode`.

#### Returns
**Type:** Global.MapEdge[]

### GetElevator()
```csharp
public ElevatorPassageModel GetElevator()
```
Returns the attached elevator ([`attachedElevator`](/api/Global/Map/MapNode#attachedelevator)) or else `null`.

The attached elevator is non-null if and only if this node is an elevator node.

#### Returns
**Type:** Global.ElevatorPassageModel

### GetId()
```csharp
public string GetId()
```
Returns the string ID of this `MapNode`.

#### Returns
**Type:** System.String

### GetPosition()
```csharp
public Vector3 GetPosition()
```
Returns the position of this `MapNode`.

#### Returns
**Type:** UnityEngine.Vector3

### GetTeleportNode(MapNode, bool)
```csharp
public MapNode GetTeleportNode(MapNode next, bool elevatorEnter = false)
```
Unused.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `next` | `Global.MapNode` |  |
| `elevatorEnter` | `System.Boolean` |  |

#### Returns
**Type:** Global.MapNode

### GetTeleportNode(MovableObjectNode, bool)
```csharp
public MapNode GetTeleportNode(MovableObjectNode mv, bool elevatorEnter = false)
```
Returns a random teleport destination (a `MapNode`) for the Rabbit Protocol portal teleport, or `null` when inapplicable or the `MovableObjectNode` unit is facing the wrong way.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `mv` | `Global.MovableObjectNode` | The `MovableObjectNode` unit that may be teleported. |
| `elevatorEnter` | `System.Boolean` | Flag indicating whether the unit is attempting to use the elevator at this `MapNode`. |

#### Returns
**Type:** Global.MapNode

### GetTeleportNodes()
```csharp
public MapNode[] GetTeleportNodes()
```
Unused.

#### Returns
**Type:** Global.MapNode[]

### GetZNodes()
```csharp
public MapNode[] GetZNodes()
```
Unused.

#### Returns
**Type:** Global.MapNode[]

### RemoveEdge(MapEdge)
```csharp
public void RemoveEdge(MapEdge edge)
```
Removes the given `edge` from this `MapNode`'s list of edges.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `edge` | `Global.MapEdge` | The `MapEdge` edge to remove. |

### SetDoor(DoorObjectModel)
```csharp
public void SetDoor(DoorObjectModel door)
```
Sets the [door](/api/Global/Map/Rooms-and-Hallways/DoorObjectModel) at this `MapNode` to the given `door` (default is `null`).

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `door` | `Global.DoorObjectModel` | The door to place at this `MapNode`. |

### SetPosition(Vector3)
```csharp
public void SetPosition(Vector3 pos)
```
Unused.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |

### SetTeleport(List\<MapNode>, UnitDirection)
```csharp
public void SetTeleport(List<MapNode> teleportTo, UnitDirection dir)
```
Sets the teleport destinations for the Rabbit Protocol portal at this `MapNode` when a unit is facing the direction `dir` (`LEFT`, `RIGHT`, `ELEVATOR`, or `OTHER`).

See also [RabbitManager::CreateRabbitSquad](/api/Global/Rabbits/RabbitManager#createrabbitsquadsefiraenum-int).

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `teleportTo` | `System.Collections.Generic.List{MapNode}` | The list of teleport desinations (`MapNodes`). |
| `dir` | `Global.UnitDirection` | The facing direction required for the Rabbit Protocol portal (`LEFT`, `RIGHT`, `ELEVATOR`, or `OTHER`). |

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








