---
title: Movement
description: How units calculate paths and motion
published: true
date: 2026-07-27T22:15:56.815Z
tags: 
editor: markdown
dateCreated: 2026-07-27T21:28:26.739Z
---

# Movement

## Basics
### MovableObjectNodes and UnitModels
A [`MovableObjectNode`](/api/Global/Movement/MovableObjectNode) represents an entity that can move. This class handles the position and movement of entities across the map.

Most of Lobotomy Corporation's moving entities are [`UnitModels`](/api/Global/Units/UnitModel). This includes [Agents](/api/Global/Agents-and-Clerks/Agents/AgentModel), [Clerks](/api/Global/Agents-and-Clerks/Clerks/OfficerModel), [Abnormalities and Minions](/api/Global/Abnormalities/CreatureModel), [Projectiles](/api/Global/Projectiles/ProjectileModel), and [Rabbits](/api/Global/Rabbits/Rabbit-Units/RabbitModel). Within each `UnitModel` unit, there is a `MovableObjectNode`, which handles all of that unit's movement.

### Nodes and Edges

The Lobotomy Corporation [map](/api/Global/Map/MapGraph) is stored as a series of nodes connected by edges. Essentially, a node represents a **position** on the map, and an edge repesents a **connection** between nodes. Units can move from one node to another when they are connected by an edge.

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

When units are on an edge between nodes, their position is interpolated between the two nodes. The distance traveled is stored as a value called `edgePosRate`, which normally ranges from `0f` to `1f`.

<img 
    style="display: block;
           margin-left: auto;
           margin-right: auto;
           margin-bottom: 0px;
           padding: 0px;
           width: 95%;"
    src="/movement/edgeposrate_diagram.svg" 
    alt="edgePosRate changing on an edge from Node1 to Node2">
</img>

