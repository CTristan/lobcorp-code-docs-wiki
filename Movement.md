---
title: Movement
description: How units calculate paths and motion
published: true
date: 2026-07-27T23:20:59.203Z
tags: 
editor: markdown
dateCreated: 2026-07-27T21:28:26.739Z
---

# Movement

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

When most units move, they follow a **path** made from a series of edges. The process of finding a path from one position to another is called **pathfinding**.

### Rooms, PassageObjectModels, and Elevators
The rooms that appear in the game are stored as [`PassageObjectModels`](/api/Global/Map/Rooms-and-Hallways/PassageObjectModel). Each node on the map belongs to some room.

Each room has a type ([`PassageType`](/api/Global/Map/Rooms-and-Hallways/PassageType)):

-  SEFIRA: A main room.
- DEPARTMENT: A department room, a large, but not main room. Ex: upper floors of Welfare and Disciplinary.
- VERTICAL: An elevator.
- HORIZONTAL: A hallway.
- ISOLATEROOM: A containment unit.
- NONE: Anything else.

See also: [A full color-coded map of all nodes in the facility](/map/facility_mapnodes.webp).

For the purposes of movement, these behave the same, except for elevators. Note that elevators are *not* the small rooms on the map between departments; those are hub rooms (with type `HORIZONTAL`), and behave like normal rooms. Elevators are invisible nodes between certain rooms which **are never entered**. Instead, units teleport to the other side of elevator nodes after waiting for a certain amount of time.

### Pathfinding



[^1]: Not all entities that move have a [`MovableObjectNode`](/api/Global/Movement/MovableObjectNode) attached to them. For example, the [dragon that spawns as part of Yin and Yang's union](/api/Global/Abnormalities/Yin-and-Yang/YinAndYangUnion) controls its position directly through its Unity Transform. However, these are a rare exception.
[^2]: The cost of an edge is *usually* the distance between the nodes, but has a minimum value of `0.01f`. It can also, technically, be specified in the [`MapGraph`](/api/Global/Map/MapGraph) XML file, though the one used in the game (`MapGraph_final2.txt`) does not ever use this.
