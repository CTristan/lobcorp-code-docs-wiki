---
title: Movement
description: How units calculate paths and motion
published: true
date: 2026-07-28T18:40:56.662Z
tags: 
editor: markdown
dateCreated: 2026-07-27T21:28:26.739Z
---

# Movement

This page describes Lobotomy Corporation's movement system and provides an overview for the classes and methods involved.

## Basics
### MovableObjectNodes and UnitModels
A [`MovableObjectNode`](/api/Global/Movement/MovableObjectNode) represents an entity that can move[^1]. This class handles the position and movement of entities across the map.

Most of Lobotomy Corporation's moving entities are [`UnitModels`](/api/Global/Units/UnitModel). This includes [Agents](/api/Global/Agents-and-Clerks/Agents/AgentModel), [Clerks](/api/Global/Agents-and-Clerks/Clerks/OfficerModel), [Abnormalities and Minions](/api/Global/Abnormalities/CreatureModel), [Projectiles](/api/Global/Projectiles/ProjectileModel), and [Rabbits](/api/Global/Rabbits/Rabbit-Units/RabbitModel). Within each `UnitModel` unit, there is a `MovableObjectNode`, which handles all of that unit's movement.

### Nodes, Edges, and Paths

The Lobotomy Corporation [map](/api/Global/Map/MapGraph) is stored as a series of nodes connected by edges. Essentially, a **node** represents a position on the map, and an **edge** represents a connection between nodes. Units can move from one node to another when they are connected by an edge. The distance from one end of an edge to the other is called its **cost**[^2].

<img 
    style="display: block;
           margin-left: auto;
           margin-right: auto;
           margin-bottom: 0px;
           padding: 0px;
           width: 95%;"
    src="/map/example_graph.svg" 
    alt="Example Graph (nodes and edges)">
</img>

When units are on an edge between nodes, their position is interpolated between the two nodes. A position along an edge is stored as a value called `edgePosRate`, which normally ranges from `0f` to `1f`.

<img 
    style="display: block;
           margin-left: auto;
           margin-right: auto;
           margin-bottom: 0px;
           padding: 0px;
           width: 50%;"
    src="/movement/edgeposrate_diagram.svg" 
    alt="edgePosRate changing on an edge from Node1 to Node2">
</img>

Sometimes, it is desired to have `edgePosRate` go the other way, so that `0f` is at `node2` and `1f` is at `node1`. To accommodate this, the `edgePosRate` usually also has an associated `EdgeDirection`, which is either `FORWARD` (node1→node2) or `BACKWARD` (node2→node1).

When most units move, they follow a **path** made from a series of edges. The process of finding a path from one position to another is called **pathfinding**. The total distance from the start of the path to the end is also called its cost.

In addition to storing its position, each node on the map has a string ID accessible by [`MapNode::GetId()`](/api/Global/Map/MapNode#getid).

### Rooms, PassageObjectModels, and Elevators
The rooms that appear in the game are stored as [`PassageObjectModels`](/api/Global/Map/Rooms-and-Hallways/PassageObjectModel). Rooms contain multiple nodes; for example, most have at least two for the left and right doors. Hallways also have a node for each containment unit attached to them.

Each room has one of the following types ([`PassageType`](/api/Global/Map/Rooms-and-Hallways/PassageType)):

-  SEFIRA: A main room.
- DEPARTMENT: A department room, a large, but not main room. Ex: upper floors of Welfare and Disciplinary.
- VERTICAL: An elevator.
- HORIZONTAL: A hallway or elevator hub room.
- ISOLATEROOM: A containment unit.
- NONE: Anything else.

A room also has a `scaleFactor`, a float which indicates how "large" the room is inside. For example, this affects how large agents appear, and is why units in Control Department's main room appear much larger than units in Control Department's hallways.

See also: [A full color-coded map of nodes in the facility](/map/facility_mapnodes.webp) (warning: large image).

For the purposes of movement, rooms of all types behave the same, except for elevators. Note that elevators are *not* the small rooms on the map between departments; those are hub rooms (with type `HORIZONTAL`), and behave like normal rooms. Elevators (rooms with type `VERTICAL`) are nodes between certain rooms[^3] which **are never entered**. Instead, units teleport to the other side of these nodes after waiting for a certain amount of time.

<img 
    style="display: block;
           margin-left: auto;
           margin-right: auto;
           margin-bottom: 0px;
           padding: 0px;
           width: 50%;"
    src="/movement/hubroom_diagram.svg" 
    alt="Diagram showing the difference between hub rooms and elevator nodes.">
</img>

## Pathfinding and Motion
Pathfinding between [`MapNodes`](/api/Global/Map/MapNode) is done through the class [`GraphAstar`](/api/Global/Movement/Pathing/GraphAstar) using a modified[^4] version of the [A* algorithm](https://wikipedia.org/wiki/A*_search_algorithm).

[`MovableObjectNodes`](/api/Global/Movement/MovableObjectNode) are usually moved by one of the following methods.

### SetCurrentEdge, SetCurrentNode, and Assign
These methods directly set the location of the `MovableObjectNode` unit.

[`SetCurrentNode(MapNode)`](/api/Global/Movement/MovableObjectNode#setcurrentnodemapnode) moves the unit to the given [`MapNode`](/api/Global/Map/MapNode).

[`SetCurrentEdge(MapEdge, float, EdgeDirection)`](/api/Global/Movement/MovableObjectNode#setcurrentnodemapnode) moves the unit to the given [`MapEdge`](/api/Global/Map/MapNode) at the given `edgePosRate` position and direction.

[`SetCurrentEdge(MovableObjectNode)`](/api/Global/Movement/MovableObjectNode#setcurrentnodemapnode) moves the unit to the same position as another `MovableObjectNode` on an edge.

[`Assign(MovableObjectNode)`](/api/Global/Movement/MovableObjectNode#assignmovableobjectnode) does a deep copy of another `MovableObjectNode`, and essentially clones the position, pathing, and movement state of the original `MovableObjectNode`. For example, when an Agent transforms by [Laetitia](/api/Global/Abnormalities/Laetitia/LittleWitch)'s effect, the Agent's `MovableObjectNode` is copied into the spawned [Little Witch's Friend](/api/Global/Abnormalities/Laetitia/LittleWitchMonster)'s `MovableObjectNode`.

### MoveToNode, MoveToMovableNode, and ProcessMoveNode
These methods create a [`PathResult`](/api/Global/Movement/Pathing/PathResult) path for the unit to follow. This is a list of edges and edge directions from the current position to the target position[^5].

[`MoveToNode`](/api/Global/Movement/MovableObjectNode#movetonodemapnode-bool) finds a path from the current location of the `MovableObjectNode` to the given `MapNode` and starts following it.

[`MoveToMovableNode`](/api/Global/Movement/MovableObjectNode#movetomovablenodemovableobjectnode-bool) finds a path from the current location of the `MovableObjectNode` to the given other `MovableObjectNode` and starts following it.

Both of these methods use [`GraphAstar`](/api/Global/Movement/Pathing/GraphAstar) underneath (creating temporary nodes and edges on the map if needed).

The resulting path is processed by [`ProcessMoveNode`](/api/Global/Movement/MovableObjectNode), usually called each frame for each unit. This calculates the distance the unit should travel each frame as $deltaTime \cdot distanceFactor \cdot movement \cdot currentScale$, where:
- $deltaTime$ is the time since the last frame;
- $distanceFactor$ is a conversion from Unity units to in-game units, equal to `1.3333334`;
- $movement$ is the speed of the unit;
- $currentScale$ is the scale of the current room.

Then, the unit is moved that distance along the current path by [`ProcessMoveByDistance`](/api/Global/Movement/MovableObjectNode#processmovebydistancefloat).

#### ProcessMoveByDistance
[`ProcessMoveByDistance(float)`](/api/Global/Movement/MovableObjectNode#processmovebydistancefloat) moves the unit the given distance along its current path.

The code in this method is very complex. A full description can be found at its [documentation page](/api/Global/Movement/MovableObjectNode#processmovebydistancefloat), but here are some things of note:
- It processes both `PathResult` paths (see above) and `PathMoveBy` paths (see below), with priority for `PathMoveBy` paths.
- It sometimes uses loops and sometimes uses recursion, which can cause weird side-effects when patched.
- It handles elevator logic. Units will stop at elevators, wait for 0.5 seconds at minimum, then teleport to the other side of the elevator node without ever entering the elevator room (with passage type `VERTICAL`).
- It handles doors opening when approached.
- It handles teleporting units by Rabbit Protocol portals.

### MoveBy
Rarely[^6], certain units use [`MoveBy(UnitDirection, float)`](/api/Global/Movement/MovableObjectNode#movebyunitdirection-float) to move. This has separate code from `PathResult` paths and does not do all of the same checks. The existing uses in the game do not cause errors due to their specific circumstances, but **it is not advisable to use this method**.

[`MoveBy(UnitDirection, float)`](/api/Global/Movement/MovableObjectNode#movebyunitdirection-float) finds a path for the unit in the given direction (`LEFT` or `RIGHT`) that travels a certain distance (`value`).

[^1]: Not all entities that move have a [`MovableObjectNode`](/api/Global/Movement/MovableObjectNode) attached to them. For example, the [dragon that spawns as part of Yin and Yang's union](/api/Global/Abnormalities/Yin-and-Yang/YinAndYangUnion) controls its position directly through its Unity Transform. However, these are a rare exception.
[^2]: The cost of an edge is *usually* the distance between the nodes, but has a minimum value of `0.01f`. It can also, technically, be specified in the [`MapGraph`](/api/Global/Map/MapGraph) XML file, though the one used in the game (`MapGraph_final2.txt`) does not ever use this.
[^3]:  For some reason, when elevators are loaded into the map, five additional elevator nodes are added in the same area but never connected to anything.
[^4]: The algorithm is modified to block passages with Rabbit Protocol portals when relevant. The function that calculates path distance, [`GraphAstar::Distance`](/api/Global/Movement/Pathing/GraphAstar#distancemapnode-mapnode-float), is modified to only track the *cost* of the shortest path, up to a provided maximum distance.
[^5]: If the target position is partially along an edge, the value for `edgePosRateGoal` will be set to the target position on the final edge.
[^6]: The only examples in the code that actually run are [Amber Dawn](/api/Global/Abnormalities/Ordeals/Amber-Ordeals/Amber-Dawn/BugDawn)'s attack and [Green Dusk](/api/Global/Abnormalities/Ordeals/Green-Ordeals/Green-Dusk/MachineDusk)'s spawns.