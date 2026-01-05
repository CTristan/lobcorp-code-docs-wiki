# Class MapNode

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MapNode
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MapNode

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### MapNode(string, Vector3, string)

```csharp
public MapNode(string id, Vector3 pos, string areaName)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |
| `areaName` | `System.String` |  |
| `attachedPassage` | `Global.PassageObjectModel` |  |

## Fields

### closed

```csharp
public bool closed
```

#### Field Value

**Type:** System.Boolean

### connectedCreature

```csharp
public CreatureModel connectedCreature
```

#### Field Value

**Type:** Global.CreatureModel

### isTemporary

```csharp
public bool isTemporary
```

#### Field Value

**Type:** System.Boolean

### rabbitUnpassable

```csharp
public bool rabbitUnpassable
```

#### Field Value

**Type:** System.Boolean

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `edge` | `Global.MapEdge` |  |

### AddZNode(MapNode)

```csharp
public void AddZNode(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### AttachElevator(ElevatorPassageModel)

```csharp
public void AttachElevator(ElevatorPassageModel elevator)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `elevator` | `Global.ElevatorPassageModel` |  |

### ClearTeleportNode()

```csharp
public void ClearTeleportNode()
```

### CompareByX(MapNode, MapNode)

```csharp
public static int CompareByX(MapNode a, MapNode b)
```

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

#### Returns

**Type:** System.String

### GetAttachedPassage()

```csharp
public PassageObjectModel GetAttachedPassage()
```

#### Returns

**Type:** Global.PassageObjectModel

### GetDoor()

```csharp
public DoorObjectModel GetDoor()
```

#### Returns

**Type:** Global.DoorObjectModel

### GetEdgeByNode(MapNode)

```csharp
public MapEdge GetEdgeByNode(MapNode node)
```

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

#### Returns

**Type:** Global.MapEdge[]

### GetElevator()

```csharp
public ElevatorPassageModel GetElevator()
```

#### Returns

**Type:** Global.ElevatorPassageModel

### GetId()

```csharp
public string GetId()
```

#### Returns

**Type:** System.String

### GetPosition()

```csharp
public Vector3 GetPosition()
```

#### Returns

**Type:** UnityEngine.Vector3

### GetTeleportNode(MapNode, bool)

```csharp
public MapNode GetTeleportNode(MapNode next, bool elevatorEnter = false)
```

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

#### Returns

**Type:** Global.MapNode[]

### GetZNodes()

```csharp
public MapNode[] GetZNodes()
```

#### Returns

**Type:** Global.MapNode[]

### RemoveEdge(MapEdge)

```csharp
public void RemoveEdge(MapEdge edge)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `edge` | `Global.MapEdge` |  |

### SetDoor(DoorObjectModel)

```csharp
public void SetDoor(DoorObjectModel door)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `door` | `Global.DoorObjectModel` |  |

### SetPosition(Vector3)

```csharp
public void SetPosition(Vector3 pos)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |

### SetTeleport(List<MapNode>, UnitDirection)

```csharp
public void SetTeleport(List<MapNode> teleportTo, UnitDirection dir)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `teleportTo` | `System.Collections.Generic.List{MapNode}` |  |
| `dir` | `Global.UnitDirection` |  |
