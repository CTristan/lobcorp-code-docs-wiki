---
uid: Global.MapNode
canonical_path: /api/Global/Misc/MapNode
---

# Class MapNode

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MapNode
```
A place in a [room](/api/Global/Model/PassageObjectModel).

May also represent an [elevator](/api/Global/Model/ElevatorPassageModel) or a [door](/api/Global/Model/DoorObjectModel).
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MapNode

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MapNode(string, Vector3, string)

```csharp
public MapNode(string id, Vector3 pos, string areaName)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |
| `areaName` | `System.String` |  |

### MapNode(string, Vector3, string, PassageObjectModel)

```csharp
public MapNode(string id, Vector3 pos, string areaName, PassageObjectModel attachedPassage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |
| `areaName` | `System.String` |  |
| `attachedPassage` | `Global.PassageObjectModel` |  |

## Fields

### _activate

```csharp
private bool _activate
```
#INC


#### Field Value

**Type:** System.Boolean

### _teleportDirectionCondition

```csharp
private UnitDirection _teleportDirectionCondition
```
#INC


#### Field Value

**Type:** Global.UnitDirection

### _teleportTo

```csharp
private List<MapNode> _teleportTo
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MapNode}

### areaName

```csharp
private string areaName
```
#INC


#### Field Value

**Type:** System.String

### attachedElevator

```csharp
private ElevatorPassageModel attachedElevator
```
#INC


#### Field Value

**Type:** Global.ElevatorPassageModel

### attachedPassage

```csharp
private PassageObjectModel attachedPassage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### closed

```csharp
public bool closed
```
#INC


#### Field Value

**Type:** System.Boolean

### connectedCreature

```csharp
public CreatureModel connectedCreature
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### door

```csharp
private DoorObjectModel door
```
#INC


#### Field Value

**Type:** Global.DoorObjectModel

### edges

```csharp
private List<MapEdge> edges
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MapEdge}

### id

```csharp
private string id
```
#INC


#### Field Value

**Type:** System.String

### isTemporary

```csharp
public bool isTemporary
```
#INC


#### Field Value

**Type:** System.Boolean

### pos

```csharp
private Vector3 pos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### rabbitUnpassable

```csharp
public bool rabbitUnpassable
```
#INC


#### Field Value

**Type:** System.Boolean

### zNodes

```csharp
private List<MapNode> zNodes
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MapNode}

## Properties

### activate

```csharp
public bool activate { get; set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### AddEdge(MapEdge)

```csharp
public void AddEdge(MapEdge edge)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `edge` | `Global.MapEdge` |  |

### AddZNode(MapNode)

```csharp
public void AddZNode(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### AttachElevator(ElevatorPassageModel)

```csharp
public void AttachElevator(ElevatorPassageModel elevator)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `elevator` | `Global.ElevatorPassageModel` |  |

### ClearTeleportNode()

```csharp
public void ClearTeleportNode()
```
#INC


### CompareByX(MapNode, MapNode)

```csharp
public static int CompareByX(MapNode a, MapNode b)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Global.MapNode` |  |
| `b` | `Global.MapNode` |  |

#### Returns

**Type:** System.Int32

### GetAreaName()

```csharp
public string GetAreaName()
```
#INC


#### Returns

**Type:** System.String

### GetAttachedPassage()

```csharp
public PassageObjectModel GetAttachedPassage()
```
#INC


#### Returns

**Type:** Global.PassageObjectModel

### GetDoor()

```csharp
public DoorObjectModel GetDoor()
```
#INC


#### Returns

**Type:** Global.DoorObjectModel

### GetEdgeByNode(MapNode)

```csharp
public MapEdge GetEdgeByNode(MapNode node)
```
#INC


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
#INC


#### Returns

**Type:** Global.MapEdge[]

### GetElevator()

```csharp
public ElevatorPassageModel GetElevator()
```
#INC


#### Returns

**Type:** Global.ElevatorPassageModel

### GetId()

```csharp
public string GetId()
```
#INC


#### Returns

**Type:** System.String

### GetPosition()

```csharp
public Vector3 GetPosition()
```
#INC


#### Returns

**Type:** UnityEngine.Vector3

### GetTeleportNode(MapNode, bool)

```csharp
public MapNode GetTeleportNode(MapNode next, bool elevatorEnter = false)
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mv` | `Global.MovableObjectNode` |  |
| `elevatorEnter` | `System.Boolean` |  |

#### Returns

**Type:** Global.MapNode

### GetTeleportNodes()

```csharp
public MapNode[] GetTeleportNodes()
```
#INC


#### Returns

**Type:** Global.MapNode[]

### GetZNodes()

```csharp
public MapNode[] GetZNodes()
```
#INC


#### Returns

**Type:** Global.MapNode[]

### RemoveEdge(MapEdge)

```csharp
public void RemoveEdge(MapEdge edge)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `edge` | `Global.MapEdge` |  |

### SetDoor(DoorObjectModel)

```csharp
public void SetDoor(DoorObjectModel door)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `door` | `Global.DoorObjectModel` |  |

### SetPosition(Vector3)

```csharp
public void SetPosition(Vector3 pos)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |

### SetTeleport(List<MapNode>, UnitDirection)

```csharp
public void SetTeleport(List<MapNode> teleportTo, UnitDirection dir)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `teleportTo` | `System.Collections.Generic.List{MapNode}` |  |
| `dir` | `Global.UnitDirection` |  |
