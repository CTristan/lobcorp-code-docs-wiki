---
title: Movement
description: How units calculate paths and motion
published: true
date: 2026-07-27T21:28:26.739Z
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

The Lobotomy Corporation [map](/api/Global/Map/MapGraph) is stored as a series of nodes connected by edges. Essentially, a node represents a **position** on the map, and an edge repesents a **connection** between nodes. Units can move from one node to another only when they are connected by an edge.

<img 
    style="display: block;
           margin-left: auto;
           margin-right: auto;
           margin-bottom: 0px;
           padding: 0px;
           width: 80%;"
    src="/map/example_graph.svg" 
    alt="CreatureSelectUI Diagram 2">
</img>

