---
title: MovableObjectNode
description: 
published: true
date: 2026-07-25T17:25:51.437Z
tags: 
editor: markdown
dateCreated: 2026-07-08T04:20:18.877Z
---

# Class MovableObjectNode
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MovableObjectNode
```
> This section may have incomplete or incorrect information.
{.is-warning}

Represents an object which can move, for example:
- [Units](/api/Global/Units/UnitModel) (abnormalities, workers, rabbits, projectiles, sephirah bosses, ordeal creatures...)
- Possibly other things, too


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MovableObjectNode

## Constructors
### MovableObjectNode(bool)
```csharp
public MovableObjectNode(bool active)
```
Ignores `active` and creates a new `MovableObjectNode`. `_isActive` will be false.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `active` | `System.Boolean` | Ignored. |

### MovableObjectNode(UnitModel)
```csharp
public MovableObjectNode(UnitModel model)
```
Creates a new `MovableObjectNode` attached to `model`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` | The model this `MovableObjectNode` belongs to. |

## Fields
### \_currentEdge
```csharp
private MapEdge _currentEdge
```
The edge this `MovableObjectNode` is currently on. Can be `null`.

#### Field Value
**Type:** Global.MapEdge

### \_currentNode
```csharp
private MapNode _currentNode
```
The node this `MovableObjectNode` is currently on. Can be `null`.

#### Field Value
**Type:** Global.MapNode

### \_currentPassage
```csharp
private PassageObjectModel _currentPassage
```
The room (see [`PassageObjectModel`](/api/Global/Map/Rooms-and-Hallways/PassageObjectModel)) this `MovableObjectNode` is currently in. Can be `null`.

#### Field Value
**Type:** Global.PassageObjectModel

### \_elevatorWaitElapsedTime
```csharp
private float _elevatorWaitElapsedTime
```
The amount of time this `MovableObjectNode` has spent waiting to transition through an elevator. Set to `0f` when not waiting on an elevator.

#### Field Value
**Type:** System.Single

### \_elevatorWaitTime
```csharp
public const float _elevatorWaitTime = 0.5
```
The amount of time to wait before transitioning through an elevator.

#### Field Value
**Type:** System.Single

### \_isActive
```csharp
private bool _isActive
```
Whether this `MovableObjectNode` is active. Defaults to `false` and **is not initialized** by the constructor `MovableObjectNode(bool active)`.

#### Field Value
**Type:** System.Boolean

### \_isNextElevator
```csharp
private bool _isNextElevator
```
Flag which is `true` if this `MovableObjectNode` is waiting on an elevator.

#### Field Value
**Type:** System.Boolean

### \_teleportable
```csharp
private bool _teleportable
```
Flag which is `true` if this `MovableObjectNode` is allowed to be teleported by the Rabbit Protocol portals.

All units have this flag set to `true` except for [Rabbits](/api/Global/Rabbits/Rabbit-Units/RabbitModel), [Gebura](/api/Global/Core-Suppressions/Gebura-Suppression/GeburahBossBase), [projectiles](/api/Global/Projectiles/ProjectileModel), and sometimes [Big and Will Be Bad Wolf](/api/Global/Abnormalities/Big-and-Will-be-Bad-Wolf/BigBadWolf).

#### Field Value
**Type:** System.Boolean

### blockedTimer
```csharp
public float blockedTimer
```
Mostly unused. Sometimes set to `1f` and decremented in [`MovableObjectNode::ProcessMoveByDistance`](/api/Global/Movement/MovableObjectNode#processmovebydistancefloat), but only ever checked by legacy code. Does not block movement.

#### Field Value
**Type:** System.Single

### currentElevator
```csharp
private ElevatorPassageModel currentElevator
```
Unused.

#### Field Value
**Type:** Global.ElevatorPassageModel

### currentScale
```csharp
public float currentScale
```
The scale of this `MovableObjectNode`, which impacts display size and speed in a given room. Defaults to `1f`.

Determined by the [`scaleFactor`](/api/Global/Map/Rooms-and-Hallways/PassageObjectModel#scalefactor) of the room this `MovableObjectNode` is in. :question: Set to `0` by [King of Greed](/api/Global/Abnormalities/The-King-of-Greed/MagicalGirl_2)'s kill ([`MagicalGirl_2::UniqueEscape`](/api/Global/Abnormalities/The-King-of-Greed/MagicalGirl_2#uniqueescape)).

#### Field Value
**Type:** System.Single

### currentZValue
```csharp
public float currentZValue
```
Unused.

#### Field Value
**Type:** System.Single

### destinationNode
```csharp
private MapNode destinationNode
```
Unused.

#### Field Value
**Type:** Global.MapNode

### destinationNode2
```csharp
private MovableObjectNode destinationNode2
```
Unused.

#### Field Value
**Type:** Global.MovableObjectNode

### edgeDirection
```csharp
public EdgeDirection edgeDirection
```
The direction of this `MovableObjectNode` on the current edge (with `node1->node2` considered `FORWARD`, and `node2->node1` considered `BACKWARD`).

#### Field Value
**Type:** Global.EdgeDirection

### edgePosRate
```csharp
public float edgePosRate
```
The position of this `MovableObjectNode` along the current edge, between `0` and `1`.

A value of `0` indicates this `MovableObjectNode` is at the starting node of this edge, and a value of `1` indicates this `MovableObjectNode` is at the ending node of this edge.

#### Field Value
**Type:** System.Single

### edgePosRateGoal
```csharp
private float edgePosRateGoal
```
The target position of this `MovableObjectNode` along the current edge.

Usually `1f`, except when moving to a position partway through the current edge. This happens often on the last edge of the path when the target is another `MovableObjectNode`.

#### Field Value
**Type:** System.Single

### isIgnoreZValue
```csharp
public bool isIgnoreZValue
```
Unused.

#### Field Value
**Type:** System.Boolean

### lastNode
```csharp
private MapNode lastNode
```
The last non-null, non-temporary node this `MovableObjectNode` has been at. Unused.

#### Field Value
**Type:** Global.MapNode

### model
```csharp
private UnitModel model
```
The [`UnitModel`](/api/Global/Units/UnitModel) this `MovableObjectNode` belongs to. Can be `null`.

#### Field Value
**Type:** Global.UnitModel

### moveDistance
```csharp
private float moveDistance
```
The amount of distance already traveled while following a [`PathMoveBy`](/api/Global/Movement/PathMoveBy).

Incorrectly updated in [`ProcessMoveByDistance`](/api/Global/Movement/MovableObjectNode#processmovebydistancefloat) and will always over-estimate the distance already traveled.

#### Field Value
**Type:** System.Single

### notNullPassage
```csharp
private PassageObjectModel notNullPassage
```
The last non-null room this `MovableObjectNode` has been in.

#### Field Value
**Type:** Global.PassageObjectModel

### passageChangedParam
```csharp
private object passageChangedParam
```
Unused.

#### Field Value
**Type:** System.Object

### pathIndex
```csharp
private int pathIndex
```
The index of the current edge in the path this `MovableObjectNode` is currently following.

#### Field Value
**Type:** System.Int32

### pathInfo
```csharp
private PathResult pathInfo
```
The path this `MovableObjectNode` is currently following. Used by most units.

#### Field Value
**Type:** Global.PathResult

### pathMoveBy
```csharp
private PathMoveBy pathMoveBy
```
A direction and distance to travel, for units that want to travel `LEFT` or `RIGHT` for a certain distance (without pathfinding).

Used by [Amber Dawn](/api/Global/Abnormalities/Ordeals/Amber-Ordeals/Amber-Dawn/BugDawn), [Green Dawn](/api/Global/Abnormalities/Ordeals/Green-Ordeals/Green-Dawn/MachineDawn) and [Green Noon](/api/Global/Abnormalities/Ordeals/Green-Ordeals/Green-Noon/MachineNoon) when spawned by [Green Dusk](/api/Global/Abnormalities/Ordeals/Green-Ordeals/Green-Dusk/MachineDusk), and several unused units.

#### Field Value
**Type:** Global.PathMoveBy

### state
```csharp
private MovableState state
```
Has the value `MovableState.MOVE` when this `MovableObjectNode` is moving, and `MovableState.STOP` when it is not moving.

#### Field Value
**Type:** Global.MovableState

### unitDirection
```csharp
private UnitDirection unitDirection
```
The direction the unit attached to the `MovableObjectNode` is facing. Usually^[when?]^ set to `LEFT` or `RIGHT`.

#### Field Value
**Type:** Global.UnitDirection

### unpassableList
```csharp
private List<PassType> unpassableList
```
Unused. Sometimes contains `SHIELDBEARER`, which is unimplemented.

#### Field Value
**Type:** System.Collections.Generic.List{PassType}

### viewPosition
```csharp
private Vector3 viewPosition
```
Unused.

If the position of this `MovableObjectNode` is fixed by [`EnablePositionSetter`](/api/Global/Movement/MovableObjectNode#enablepositionsettervector3), the position this `MovableObjectNode` is fixed at. Otherwise, `null`.

#### Field Value
**Type:** UnityEngine.Vector3

### viewPositionSet
```csharp
private bool viewPositionSet
```
Unused.

Flag which is true while this `MovableObjectNode` is at a position fixed by [`EnablePositionSetter`](/api/Global/Movement/MovableObjectNode#enablepositionsettervector3).

#### Field Value
**Type:** System.Boolean

## Properties
### currentEdge
```csharp
public MapEdge currentEdge { get; }
```
Get-only property for `_currentEdge`, this edge this `MovableObjectNode` is currently on. Can return `null`.

#### Property Value
**Type:** Global.MapEdge

### currentNode
```csharp
public MapNode currentNode { get; }
```
Get-only property for `_currentNode`, this node this `MovableObjectNode` is currently on. Can return `null`.

#### Property Value
**Type:** Global.MapNode

### currentPassage
```csharp
public PassageObjectModel currentPassage { get; set; }
```
The current room this `MovableObjectNode` is in.

When set to a non-null value, also updates [`notNullPassage`](/api/Global/Movement/MovableObjectNode#notnullpassage).

#### Property Value
**Type:** Global.PassageObjectModel

### isActive
```csharp
public bool isActive { get; }
```
Get-only property for `isActive`, the flag indicating if this `MovableObjectNode` is active.

#### Property Value
**Type:** System.Boolean

### isBlocked
```csharp
public bool isBlocked { get; }
```
Unused except by legacy classes.

Returns `true` if `blockedTimer` is greater than `0`.

#### Property Value
**Type:** System.Boolean

### IsNextElevator
```csharp
public bool IsNextElevator { get; }
```
Get-only property for `_isNextElevator`. True if this `MovableObjectNode` is waiting to transition through an elevator.

#### Property Value
**Type:** System.Boolean

## Methods
### AddUnpassableType(PassType)
```csharp
public void AddUnpassableType(PassType pass)
```
Called but not used by functional code.

Adds a `PassType` to the list of impassable types.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `pass` | `Global.PassType` | The `PassType` to add. |

### Assign(MovableObjectNode)
```csharp
public void Assign(MovableObjectNode src)
```
Copies `src` into this `MovableObjectNode`, including pathing instructions, movement state, position, and edge direction.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `Global.MovableObjectNode` | The `MovableObjectNode` to copy. |

### CanMoveBy(UnitDirection)
```csharp
public bool CanMoveBy(UnitDirection direction)
```
Returns `true` if this unit can move in the given direction.

Always true when this `MovableObjectNode` is on an edge, and always false when this `MovableObjectNode` is not on any edge or node. When on a node, true if [`MoveBy_GetNextEdge`](/api/Global/Movement/MovableObjectNode#moveby_getnextedgemapnode-unitdirection) finds a new edge.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `direction` | `Global.UnitDirection` | The direction to check. |

#### Returns
**Type:** System.Boolean

### CheckConnectedInPassage(MovableObjectNode, MovableObjectNode)
```csharp
public static bool CheckConnectedInPassage(MovableObjectNode n1, MovableObjectNode n2)
```
Returns true if there is a path between `MovableObjectNodes` `n1` and `n2`. They **do not need to be in the same room**.

The check copies `n1` into a test node, tries to path from the test node to `n2` (see [`MoveToMovableNode(MovableObjectNode, bool)`](/api/Global/Movement/MovableObjectNode#movetomovablenodemovableobjectnode-bool)) and returns true if the test node is now moving.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `n1` | `Global.MovableObjectNode` | The first node. |
| `n2` | `Global.MovableObjectNode` | The second node. |

#### Returns
**Type:** System.Boolean

### CheckInRange(MovableObjectNode)
```csharp
public bool CheckInRange(MovableObjectNode other)
```
Unused.

Checks if this `MovableObjectNode` is within 3 units of `other`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `other` | `Global.MovableObjectNode` |  |

#### Returns
**Type:** System.Boolean

### CheckInRange(MovableObjectNode, float)
```csharp
public bool CheckInRange(MovableObjectNode other, float range)
```
Returns `true` if there is a path from this `MovableObjectNode` to `other` with a distance less than `range`. Distance is calculated by [`GetDistance(MovableObjectNode, float)`](/api/Global/Movement/MovableObjectNode#getdistancemovableobjectnode-float).

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `other` | `Global.MovableObjectNode` | The `MovableObjectNode` to check. |
| `range` | `System.Single` | The maximum distance the other node can be. |

#### Returns
**Type:** System.Boolean

### CheckPassable(MapEdge, EdgeDirection, float, float)
```csharp
private bool CheckPassable(MapEdge edge, EdgeDirection edgeDir, float oldEdgePosRate, float newEdgePosRate)
```
Always returns true.

Meant to check if any agent is blocking with a shield, but this was never implemented.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `edge` | `Global.MapEdge` | The edge to check. |
| `edgeDir` | `Global.EdgeDirection` | The direction to check passability. |
| `oldEdgePosRate` | `System.Single` | The current position of this node. |
| `newEdgePosRate` | `System.Single` | The target position of this node. |

#### Returns
**Type:** System.Boolean

### CheckPassInNode()
```csharp
private bool CheckPassInNode()
```
Unused.

Returns true.

#### Returns
**Type:** System.Boolean

### DisablePositionSetter()
```csharp
public void DisablePositionSetter()
```
Unused.

Disables a fixed position for this `MovableObjectNode`.

### EnablePositionSetter(Vector3)
```csharp
public void EnablePositionSetter(Vector3 position)
```
Unused.

Enables a fixed position for this `MovableObjectNode`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `position` | `UnityEngine.Vector3` | The position to fix this node to. |

### EnterElevator(MapNode, MapNode)
```csharp
public void EnterElevator(MapNode elevatorNode, MapNode nextNode)
```
Unused.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `elevatorNode` | `Global.MapNode` |  |
| `nextNode` | `Global.MapNode` |  |

### Equal(MovableObjectNode)
```csharp
public bool Equal(MovableObjectNode src)
```
Unused.

If the exact position of `src` matches this `MovableObjectNode`'s position, returns true.

###### Details
If `src` and `MovableObjectNode` are on the same edge, have the same edge position, and have the same edge direction, returns true.

Otherwise, if `src` and `MovableObjectNode` are on the same node, returns true.

Otherwise returns false.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `Global.MovableObjectNode` | The node to check position-equality of. |

#### Returns
**Type:** System.Boolean

### EqualPosition(MapNode)
```csharp
public bool EqualPosition(MapNode node)
```
Unused.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns
**Type:** System.Boolean

### ExitElevator(MapNode)
```csharp
public void ExitElevator(MapNode node)
```
Unused.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### GetCurrentEdge()
```csharp
public MapEdge GetCurrentEdge()
```
Returns `currentEdge`, the edge this `MovableObjectNode` is on.

#### Returns
**Type:** Global.MapEdge

### GetCurrentNode()
```csharp
public MapNode GetCurrentNode()
```
Returns `currentNode`, the node this `MovableObjectNode` is on.

#### Returns
**Type:** Global.MapNode

### GetCurrentStandingSefira()
```csharp
public Sefira GetCurrentStandingSefira()
```
Returns the [department](/api/Global/Departments/Sefira) this `MovableObjectNode` is currently in.

Used by [`The Claw`](/api/Global/Abnormalities/Ordeals/White-Ordeals/The-Claw/FixerClaw), the [Rabbit Protocol](/api/Rabbit/RabbitProtocolWindow), [`CreatureUnit::OnClicked`](/api/Global/Abnormalities/CreatureUnit#onclicked), and [`RabbitManager::CheckUnitRabbitExecution`](/api/Global/Rabbits/RabbitManager#checkunitrabbitexecutionunitmodel).

###### Details
If the current room is not null, returns the department that room belongs to.

If the current room is null, but this node is on an edge, instead returns the department of the room attached to that edge's first node. If that room is null, tries instead with that edge's second node.

If the current room and current edge are null, or the edge is not attached to any non-null rooms, returns `null`. Also returns `null` if any of the prior code throws an exception.

#### Returns
**Type:** Global.Sefira

### GetCurrentViewPosition()
```csharp
public Vector3 GetCurrentViewPosition()
```
Gets the current position of this node.

Returns the position of the current node (if not null), or else the current position along the current edge (if not null). Otherwise, returns `(0, 0, 0)`.

#### Returns
**Type:** UnityEngine.Vector3

### GetDirection()
```csharp
public UnitDirection GetDirection()
```
Returns `unitDirection`, which is usually^[when?]^ `LEFT` or `RIGHT`.

#### Returns
**Type:** Global.UnitDirection

### GetDistance(MapNode, float)
```csharp
public float GetDistance(MapNode other, float limit)
```
Returns the length of the shortest path from this node to `other` if it is less than `limit`, or else `-1`.

Calculates with [`GetDistance(MovableObjectNode, float)`](/api/Global/Movement/MovableObjectNode#getdistancemovableobjectnode-float), which uses [`GraphAstar::Distance`](/api/Global/Movement/Pathing/GraphAstar#distancemapnode-mapnode-float) (the length of the shortest path).

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `other` | `Global.MapNode` | The `MapNode` to check the distance to. |
| `limit` | `System.Single` | The maximum allowed distance (exclusive). |

#### Returns
**Type:** System.Single

### GetDistance(MovableObjectNode, float)
```csharp
public float GetDistance(MovableObjectNode other, float limit)
```
Returns the length of the shortest path from this node to `other` if it is less than `limit`, or else `-1`.

Calculates with [`GraphAstar::Distance`](/api/Global/Movement/Pathing/GraphAstar#distancemapnode-mapnode-float) (the length of the shortest path).

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `other` | `Global.MovableObjectNode` | The `MovableObjectNode` to check the distance to. |
| `limit` | `System.Single` | The maximum allowed distance (exclusive). |

#### Returns
**Type:** System.Single

### GetDistance(MovableObjectNode, MovableObjectNode)
```csharp
public static float GetDistance(MovableObjectNode node1, MovableObjectNode node2)
```
Returns the distance from `node1` to `node2`, or else `100000f` if the nodes are not in the same room. Also returns `100000f` if either node is in `null`.

Note that this distance is scaled by `1.3333334f / node1.currentScale` compared to the values reported by `GetCurrentViewPosition`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node1` | `Global.MovableObjectNode` | The first node. |
| `node2` | `Global.MovableObjectNode` | The second node. |

#### Returns
**Type:** System.Single

### GetDistanceDouble(MovableObjectNode)
```csharp
public float GetDistanceDouble(MovableObjectNode mov)
```
Returns the squared distance between this `MovableObjectNode` and `mov`.

Note that each distance is multiplied by `1.3333334f` compared to the distance computed from the positions using `GetCurrentViewPosition`. The result is `1.3333334f` squared times the squared distance between their view positions.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` | The `MovableObjectNode` to compute the distance to. |

#### Returns
**Type:** System.Single

### GetEdgeDirection()
```csharp
public EdgeDirection GetEdgeDirection()
```
Returns the direction along the current edge, either `FORWARD` or `BACKWARD`.

#### Returns
**Type:** Global.EdgeDirection

### GetPassage()
```csharp
public PassageObjectModel GetPassage()
```
Returns `currentPassage`, the room this `MovableObjectNode` is currently in.

#### Returns
**Type:** Global.PassageObjectModel

### GetPassageCheckPrev()
```csharp
public PassageObjectModel GetPassageCheckPrev()
```
Gets the last non-null room this `MovableObjectNode` has been in, including its current room.

If no such room exists, logs the error `"Cannot find pasage"` and returns `null`.

#### Returns
**Type:** Global.PassageObjectModel

### GetSideMovableNode(UnitDirection, float)
```csharp
public MovableObjectNode GetSideMovableNode(UnitDirection direction, float distance)
```
Returns a new `MovableObjectNode` which is `distance` units away in the direction of `direction`. For example, [Snow White's Apple](/api/Global/Abnormalities/Snow-White's-Apple/SnowWhite)'s vines are spawned by making new movable nodes `0.5f` units to the side of the left and rightmost vines.

###### Details
Uses [`MoveBy_GetNextEdge`](/api/Global/Movement/MovableObjectNode#moveby_getnextedgemapnode-unitdirection) to calculate the edge in the direction given by `direction`.

The method loops until broken. Effectively, it tracks a node and an edge position, of which normally only one should be non-null.

If the node is not null, then it will attempt to get the next edge to travel along, and if it succeeds it will set the node back to `null`.

If instead the edge is not null, it will check if there is enough movement remaining to travel along that edge; if there is, it will set the node to the other side of the edge and set the edge to `null`. It will also subtract the length of that edge from the remaining movement.

It repeats this until out of movement (or until there is no edge in the given direction), then returns a new `MovableObjectNode` with the final node or edge position.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `direction` | `Global.UnitDirection` | The direction of the new node. |
| `distance` | `System.Single` | The target distance of the new node from this one. |

#### Returns
**Type:** Global.MovableObjectNode

### GetState()
```csharp
public MovableState GetState()
```
Returns `state`, the current movement state of this `MovableObjectNode`.

#### Returns
**Type:** Global.MovableState

### GetUnit()
```csharp
public UnitModel GetUnit()
```
Returns the `UnitModel` attached to this `MovableObjectNode`. Can be `null`.

#### Returns
**Type:** Global.UnitModel

### GetViewPositionInEdge(MapEdge, EdgeDirection, float)
```csharp
public static Vector3 GetViewPositionInEdge(MapEdge edge, EdgeDirection edgeDirection, float edgePosRate)
```
Returns a position partway along `edge` in the direction specified by `edgeDirection`, with `0` being the initial node and `1` being the final node.

###### Details

A direction of `FORWARD` will interpret `node1` as the initial node and `node2` as the final node, and opposite for `BACKWARD`. The position is linearly interpolated from the position of `node1` and `node2` with Unity's `Mathf.Lerp` function.

Will throw an exception if either node is `null`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `edge` | `Global.MapEdge` | The `MapEdge`. |
| `edgeDirection` | `Global.EdgeDirection` | The `EdgeDirection`, either `FORWARD` or `BACKWARD`. |
| `edgePosRate` | `System.Single` | The position along the edge, normalized between `0` and `1`. |

#### Returns
**Type:** UnityEngine.Vector3

### InElevator()
```csharp
public bool InElevator()
```
Returns `true` if the current room is an elevator (has `PassageType` `VERTICAL`), and false otherwise. A `MovableObjectNode` **should never be in an elevator**, so this should always return `false` (see [`ProcessMoveByDistance(float)`](/api/Global/Movement/MovableObjectNode#processmovebydistancefloat)).

#### Returns
**Type:** System.Boolean

### InteractWithDoor(DoorObjectModel)
```csharp
private void InteractWithDoor(DoorObjectModel door)
```
Unused.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `door` | `Global.DoorObjectModel` |  |

### IsMoving()
```csharp
public bool IsMoving()
```
Returns `true` if state is `MOVE`.

#### Returns
**Type:** System.Boolean

### MoveBy(UnitDirection, float)
```csharp
public void MoveBy(UnitDirection direction, float value)
```
Instructs this `MovableObjectNode` to move in the direction `direction` for a distance of `value` units.

Used by [Amber Dawn](/api/Global/Abnormalities/Ordeals/Amber-Ordeals/Amber-Dawn/BugDawn)'s attack, and [Green Dawn](/api/Global/Abnormalities/Ordeals/Green-Ordeals/Green-Dawn/MachineDawn) and [Green Noon](/api/Global/Abnormalities/Ordeals/Green-Ordeals/Green-Noon/MachineNoon) when initially spawned by [Green Dusk](/api/Global/Abnormalities/Ordeals/Green-Ordeals/Green-Dusk/MachineDusk).

###### Details
Creates a [`PathMoveBy`](/api/Global/Movement/PathMoveBy) path to be used by [`ProcessMoveByDistance`](/api/Global/Movement/MovableObjectNode#processmovebydistancefloat) with the given `direction` and `value`.

If currently on an edge, sets the current `edgeDirection` and `edgePosRate` based on the given `direction` and the `x` coordinates of the nodes of the current edge.

If currently on a node, and there is no edge in that direction, immediately stops moving.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `direction` | `Global.UnitDirection` | The direction (`LEFT` or `RIGHT`) to move in. |
| `value` | `System.Single` | The target distance to travel. |

### MoveBy_GetNextEdge(MapNode, UnitDirection)
```csharp
private static MapEdge MoveBy_GetNextEdge(MapNode node, UnitDirection direction)
```
Finds the next edge connected to the given `MapNode` in the direction of `direction` (`LEFT` or `RIGHT`), or `null` otherwise.

###### Details
Checks each of the nodes connected to `node` and makes a list of all the ones `LEFT` or `RIGHT` of the starting node (lower or greater `x` value, respectively). Then, the first one that is not a door and is sufficiently horizontal is selected.

To decide if an edge is sufficiently horizontal, the vector from `node` to the other node of the edge is normalized. If the magnitude of the normalized `y` component is less than `0.2f`, this edge is sufficiently horizontal. This corresponds to an incline of at most about `11.5` degrees in either direction.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` | The starting `MapNode`. |
| `direction` | `Global.UnitDirection` | The direction to search. |

#### Returns
**Type:** Global.MapEdge

### MoveToMovableNode(MovableObjectNode, bool)
```csharp
public void MoveToMovableNode(MovableObjectNode targetNode, bool checkRabbit = false)
```
Moves this `MovableObjectNode` to `targetNode` by making a [`PathResult`](/api/Global/Movement/Pathing/PathResult) to follow.

##### Details
Stops moving, then depending on the location of this `MovableObjectNode` and the `target` finds a path between them.

###### Target on MapNode
If the target is on a `MapNode`, moves to that `MapNode` with [`MoveToNode`](/api/Global/Movement/MovableObjectNode#movetonodemapnode-bool).

###### This Unit on MapNode
Otherwise, if this `MovableObjectNode` is on a node, creates a new temporary `MapNode` at the `targetNode` and connects it to either node on the edge `targetNode` is on (:question: this may have incorrect behavior when `targetNode.currentEdge` is `null`). Then a path (`PathResult`) is calculated between the new node and this `MovableObjectNode` using [`GraphAstar::SearchPath`](/api/Global/Movement/Pathing/GraphAstar#searchpathmapnode-mapnode-bool).

If a path exists (`pathEdges.Length > 0`), replaces the last edge, direction, and position in the path with that of `targetNode`. Then initializes movement by setting the path, state, and `pathIndex`.

Either way, removes the new edges.

###### Neither Unit on MapNode, Edge is Null
If neither this `MovableObjectNode` or the target are on a node, and this `MovableObjectNode` is not on an edge, returns immediately.

###### Neither Unit on MapNode, Edge is Same
If both this `MovableObjectNode` and the `targetNode` are on the same edge, sets the direction, `edgePosRate`, and `edgePosRateGoal` to the target's on a new path with only that edge, then starts moving.

###### Neither Unit on MapNode, Edge is Different
If neither this `MovableObjectNode` or the `targetNode` are on a node, and this unit is on a non-null edge different than the `targetNode`, first creates a new temporary `MapNode` at this unit connected to both nodes on this edge. This unit is copied into a new `MovableObjectNode`, the new one is moved to be on the new temporary node, and is then moved recursively with this function. The new edges are then removed.

There is some code to handle if there is already a path this node is following, but :interrobang: this cannot ever run, since this method sets the `pathInfo` to `null` at the beginning.

Finally, this `MovableObjectNode` is copied from the new `MovableObjectMode` with its new path to `targetNode`. (:question: This includes copying the current location to the temporary node and edge!)


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MovableObjectNode` | The target `MovableObjectNode` to path to. |
| `checkRabbit` | `System.Boolean` | Flag indicating whether to check for the Rabbits' portals (see [`GraphAstar::SearchPath`](/api/Global/Movement/Pathing/GraphAstar#searchpathmapnode-mapnode-bool)). |

### MoveToNode(MapNode, bool)
```csharp
public void MoveToNode(MapNode targetNode, bool checkRabbit = false)
```
Stops moving, then moves this `MovableObjectNode` to the `targetNode` by making a [`PathResult`](/api/Global/Movement/Pathing/PathResult) to follow.

##### Details
Calculates the path differently depending on the location of this `MovableObjectNode`.

###### This Unit on MapNode
If this unit is on a `MapNode`, moves to `targetNode` with [`GraphAstar::SearchPath`](/api/Global/Movement/Pathing/GraphAstar#searchpathmapnode-mapnode-bool). Then, initializes movement to follow the resulting path.

###### This Unit Not on MapNode, Edge is Null
Returns immediately without creating a path.

###### This Unit Not on MapNode, Edge is Not Null
Calculates the two paths from each node on this edge to `targetNode` using [`GraphAstar::SearchPath`](/api/Global/Movement/Pathing/GraphAstar#searchpathmapnode-mapnode-bool). If the first one (from `node1`) is not null, calculates the total cost as the cost of that path plus the cost of traveling to `node1` of this edge. Similarly calculates this cost for the path from `node2`.

If the path from `node1` is not null and has a lower or equal cost to the other one, copies that path and inserts a new initial edge and direction to move to `node1`. Then sets the new path as the path to follow.

If otherwise the path from `node2` is better, does exactly the same thing with that path instead.

Either way, initializes movement.

If both paths were `null` (:question: this cannot happen) returns without creating a path.

:question: Even if no valid path was found (both `PathResults` are empty), the unit will still move to the closest `MapNode`.

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` | The `MapNode` to path to. |
| `checkRabbit` | `System.Boolean` | Flag indicating whether to check for the Rabbits' portals (see [`GraphAstar::SearchPath`](/api/Global/Movement/Pathing/GraphAstar#searchpathmapnode-mapnode-bool)). |

### ProcessMoveByDistance(float)
```csharp
private void ProcessMoveByDistance(float distance)
```
Processes movement for this `MovableObjectNode`, following a path if one exists. Moves `distance` units along the path (see also [`ProcessMoveNode`](/api/Global/Movement/MovableObjectNode#processmovenodefloat)).

##### Details


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `distance` | `System.Single` | The amount of distance to move this `MovableObjectNode` by. |

### ProcessMoveNode(float)
```csharp
public void ProcessMoveNode(float movement)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `movement` | `System.Single` |  |

### RemoveUnpassableType(PassType)
```csharp
public void RemoveUnpassableType(PassType pass)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `pass` | `Global.PassType` |  |

### ReportUnitName()
```csharp
public void ReportUnitName()
```


### SetActive(bool)
```csharp
public void SetActive(bool active)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `active` | `System.Boolean` |  |

### SetCurrentEdge(MapEdge, float, EdgeDirection)
```csharp
public void SetCurrentEdge(MapEdge srcEdge, float srcEdgePosRate, EdgeDirection srcDirection)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `srcEdge` | `Global.MapEdge` |  |
| `srcEdgePosRate` | `System.Single` |  |
| `srcDirection` | `Global.EdgeDirection` |  |

### SetCurrentEdge(MovableObjectNode)
```csharp
public void SetCurrentEdge(MovableObjectNode mov)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

### SetCurrentNode(MapNode)
```csharp
public void SetCurrentNode(MapNode node)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### SetDirection(UnitDirection)
```csharp
public void SetDirection(UnitDirection direction)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `direction` | `Global.UnitDirection` |  |

### SetPassageChangedParam(object)
```csharp
public void SetPassageChangedParam(object target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `System.Object` |  |

### SetTeleportable(bool)
```csharp
public void SetTeleportable(bool b)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `b` | `System.Boolean` |  |

### StopMoving()
```csharp
public void StopMoving()
```


### TrySetCurrentNode(MapNode)
```csharp
private void TrySetCurrentNode(MapNode node)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### UpdateCurrentPassage()
```csharp
private void UpdateCurrentPassage()
```


### UpdateNodeEdge(MapNode, MapEdge)
```csharp
private void UpdateNodeEdge(MapNode node, MapEdge edge)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |
| `edge` | `Global.MapEdge` |  |

### Wait()
```csharp
public void Wait()
```


## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








