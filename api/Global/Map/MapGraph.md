---
title: MapGraph
description: 
published: true
date: 2026-07-28T19:27:45.480Z
tags: 
editor: markdown
dateCreated: 2026-07-08T04:19:39.872Z
---

# Class MapGraph
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MapGraph : IObserver
```
> This section may have incomplete or incorrect information.
{.is-warning}


The map, stored as a series of [`MapNodes`](/api/Global/Map/MapNode) and the [`MapEdges`](/api/Global/Map/MapEdge) between them.

See here for [a full color-coded map of nodes in the facility](/map/facility_mapnodes.webp) (warning: very large image).

See also [Movement](/Movement) for an overview of the movement systems.

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MapGraph

## Implements
[IObserver](/api/Global/Notices/IObserver)

## Constructors
### MapGraph()
```csharp
public MapGraph()
```

## Fields
### _instance
```csharp
private static MapGraph _instance
```


#### Field Value
**Type:** Global.MapGraph

### additionalSefiraTable
```csharp
private Dictionary<string, List<MapNode>> additionalSefiraTable
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{MapNode}}

### deptNodeTable
```csharp
private Dictionary<string, List<List<MapNode>>> deptNodeTable
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.Collections.Generic.List{MapNode}}}

### edges
```csharp
private List<MapEdge> edges
```


#### Field Value
**Type:** System.Collections.Generic.List{MapEdge}

### elevatorList
```csharp
private List<ElevatorPassageModel> elevatorList
```


#### Field Value
**Type:** System.Collections.Generic.List{ElevatorPassageModel}

### graphNodes
```csharp
private Dictionary<string, MapNode> graphNodes
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.String,MapNode}

### mapAreaTable
```csharp
private Dictionary<string, MapSefiraArea> mapAreaTable
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.String,MapSefiraArea}

### passageTable
```csharp
private Dictionary<string, PassageObjectModel> passageTable
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.String,PassageObjectModel}

### rabbitTeamGroupTable
```csharp
private Dictionary<string, List<PassageObjectModel>> rabbitTeamGroupTable
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{PassageObjectModel}}

### sefiraContainsTable
```csharp
private Dictionary<string, List<MapNode>> sefiraContainsTable
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{MapNode}}

### sefiraCoreNodesTable
```csharp
private Dictionary<string, List<MapNode>> sefiraCoreNodesTable
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{MapNode}}

### sefiraPassageTable
```csharp
private Dictionary<string, List<MapNode>> sefiraPassageTable
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{MapNode}}

### sefiraRoamingNodesTable
```csharp
private Dictionary<string, List<MapNode>> sefiraRoamingNodesTable
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{MapNode}}

## Properties
### instance
```csharp
public static MapGraph instance { get; }
```

#### Property Value
**Type:** Global.MapGraph

### loaded
```csharp
public bool loaded { get; private set; }
```


#### Property Value
**Type:** System.Boolean

## Methods
### ActivateArea(string)
```csharp
public void ActivateArea(string name)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

### ActivateArea(string, string)
```csharp
public void ActivateArea(string name, string passageGroupName)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `passageGroupName` | `System.String` |  |

### DeactivateAll()
```csharp
public void DeactivateAll()
```


### DeactivateArea(string)
```csharp
public void DeactivateArea(string name)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

### FixedUpdate()
```csharp
private void FixedUpdate()
```


### GetActivatedAreaList()
```csharp
public Dictionary<string, List<string>> GetActivatedAreaList()
```


#### Returns
**Type:** System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}}

### GetAdditionalSefira(Sefira)
```csharp
public MapNode[] GetAdditionalSefira(Sefira sefira)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns
**Type:** Global.MapNode[]

### GetAdditionalSefira(string)
```csharp
public MapNode[] GetAdditionalSefira(string area)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns
**Type:** Global.MapNode[]

### GetCreatureRoamingPoint()
```csharp
public MapNode GetCreatureRoamingPoint()
```


#### Returns
**Type:** Global.MapNode

### GetElevatorPassageList()
```csharp
public ElevatorPassageModel[] GetElevatorPassageList()
```


#### Returns
**Type:** Global.ElevatorPassageModel[]

### GetGraphEdges()
```csharp
public MapEdge[] GetGraphEdges()
```


#### Returns
**Type:** Global.MapEdge[]

### GetGraphNodes()
```csharp
public MapNode[] GetGraphNodes()
```


#### Returns
**Type:** Global.MapNode[]

### GetNodeById(string)
```csharp
public MapNode GetNodeById(string id)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns
**Type:** Global.MapNode

### GetPassageListByRabbitGroup(string)
```csharp
public List<PassageObjectModel> GetPassageListByRabbitGroup(string id)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns
**Type:** System.Collections.Generic.List{PassageObjectModel}

### GetPassageObjectList()
```csharp
public PassageObjectModel[] GetPassageObjectList()
```


#### Returns
**Type:** Global.PassageObjectModel[]

### GetRoamingNodeByRandom()
```csharp
public MapNode GetRoamingNodeByRandom()
```


#### Returns
**Type:** Global.MapNode

### GetRoamingNodeByRandom(string)
```csharp
public MapNode GetRoamingNodeByRandom(string area)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns
**Type:** Global.MapNode

### GetSefiraAllNodes(string)
```csharp
public MapNode[] GetSefiraAllNodes(string area)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns
**Type:** Global.MapNode[]

### GetSefiraAndDeptByRandom(string)
```csharp
public MapNode GetSefiraAndDeptByRandom(string area)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns
**Type:** Global.MapNode

### GetSefiraMovableNodeByRandom(string)
```csharp
public MovableObjectNode GetSefiraMovableNodeByRandom(string area)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns
**Type:** Global.MovableObjectNode

### GetSefiraNodes(Sefira)
```csharp
public MapNode[] GetSefiraNodes(Sefira sefira)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns
**Type:** Global.MapNode[]

### GetSefiraNodes(string)
```csharp
public MapNode[] GetSefiraNodes(string area)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns
**Type:** Global.MapNode[]

### GetSefiraPassage(string)
```csharp
public PassageObjectModel GetSefiraPassage(string area)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns
**Type:** Global.PassageObjectModel

### GetSefiraPassagePointNode(string)
```csharp
public MapNode[] GetSefiraPassagePointNode(string area)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns
**Type:** Global.MapNode[]

### GetSepiraNodeByRandom(string)
```csharp
public MapNode GetSepiraNodeByRandom(string area)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |

#### Returns
**Type:** Global.MapNode

### LoadMap()
```csharp
public void LoadMap()
```
Reads the map information from `Assets/Resources/xml/MapGraph_final2.txt`.

Uses [`LoadMap(XmlNode, XmlNode)`](/api/Global/Map/MapGraph#loadmapxmlnode-xmlnode).

### LoadMap(XmlNode, XmlNode)
```csharp
public void LoadMap(XmlNode nodeRoot, XmlNode edgeRoot)
```
> This section is incomplete.
{.is-warning}

Reads in [`MapNode`](/api/Global/Map/MapNode) information from `nodeRoot` and [`MapEdge`](/api/Global/Map/MapEdge) information from `edgeRoot`.

node_list
	Children:
		areas (see below)

area (department)
- Attributes:
	- name -- department number
	- sub -- unused
- Children:
	- passage (below)
	- (child with name \#comment is ignored)
		- (otherwise prints debug with the name)

passage (rooms)
- Attributes:
	- src -- prefab location
	- x, y -- position
	- passageGroup -- passage group
	- rabbitTeamGroup -- department, as used by Rabbits
	- scale -- amount to scale things in the room by
	- passageType:
		- sefira -- main room
		- horizontal -- hallway
		- vertical -- elevator
		- dept -- room
		- isolateroom -- containment unit
- Children:
	- connected -- if this connects to another department? 	- ground -- see [PassageGroundInfo](/api/Global/Map/Rooms-and-Hallways/PassageGroundInfo)
		- height -- how high the ground is
	- wall -- see [PassageWallInfo](/api/Global/Map/Rooms-and-Hallways/PassageWallInfo)
		- height -- how high the wall is
	- height -- how tall this room is (except 0 becomes 2.5)
	- node (below)

node (place in a room)
- Attributes:
	- id -- this node's name
	- x, y -- position
	- rabbitUnpassable -- unused
	- type -- 
	- elevator -- prefab path for this elevator (see [ElevatorPassageModel](/api/Global/Map/Elevators/ElevatorPassageModel))
		- NOTE: makes 5 more nodes in weird places! 
	- pos:
		- center -- marks a node as the center of its room
			- (this is otherwise automatically calculated by [PassageObjectModel](/api/Global/Map/Rooms-and-Hallways/PassageObjectModel))
- Children:
	- option -- unused
	- door -- a [door](/api/Global/Map/Rooms-and-Hallways/DoorObjectModel)



edge_list
- Children:
	- edge (see below)

edge
- Attributes:
	- node1 -- the starting node
	- node2 -- the ending node
	- cost -- manual distance for this edge
	- type:
		- door -- elevator connection
		- road -- normal connection

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `nodeRoot` | `System.Xml.XmlNode` |  |
| `edgeRoot` | `System.Xml.XmlNode` |  |

### LoadModMap(Dictionary<string, XmlNode>, XmlNode)
```csharp
public void LoadModMap(Dictionary<string, XmlNode> nodeRoot, XmlNode edgeRoot)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `nodeRoot` | `System.Collections.Generic.Dictionary{System.String,System.Xml.XmlNode}` |  |
| `edgeRoot` | `System.Xml.XmlNode` |  |

### LoadModMap_Add(Dictionary<string, XmlNode>, XmlNode, XmlDocument)
```csharp
public void LoadModMap_Add(Dictionary<string, XmlNode> nodeRoot, XmlNode edgeRoot, XmlDocument mxml)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `nodeRoot` | `System.Collections.Generic.Dictionary{System.String,System.Xml.XmlNode}` |  |
| `edgeRoot` | `System.Xml.XmlNode` |  |
| `mxml` | `System.Xml.XmlDocument` |  |

### LoadModMap_Replace(Dictionary<string, XmlNode>, XmlNode, XmlDocument)
```csharp
public void LoadModMap_Replace(Dictionary<string, XmlNode> nodeRoot, XmlNode edgeRoot, XmlDocument mxml)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `nodeRoot` | `System.Collections.Generic.Dictionary{System.String,System.Xml.XmlNode}` |  |
| `edgeRoot` | `System.Xml.XmlNode` |  |
| `mxml` | `System.Xml.XmlDocument` |  |

### OnNotice(string, params object[])
```csharp
public void OnNotice(string name, params object[] param)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `param` | `System.Object[]` |  |

### RegisterPassage(PassageObjectModel)
```csharp
public void RegisterPassage(PassageObjectModel passage)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### Reset()
```csharp
public void Reset()
```


### StageEnd()
```csharp
private void StageEnd()
```


## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








