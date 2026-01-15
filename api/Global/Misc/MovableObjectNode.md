---
uid: Global.MovableObjectNode
canonical_path: /api/Global/Misc/MovableObjectNode
---

# Class MovableObjectNode

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MovableObjectNode
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MovableObjectNode

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MovableObjectNode(bool)

```csharp
public MovableObjectNode(bool active)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `active` | `System.Boolean` |  |

### MovableObjectNode(UnitModel)

```csharp
public MovableObjectNode(UnitModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

## Fields

### _currentEdge

```csharp
private MapEdge _currentEdge
```

#### Field Value

**Type:** Global.MapEdge

### _currentNode

```csharp
private MapNode _currentNode
```

#### Field Value

**Type:** Global.MapNode

### _currentPassage

```csharp
private PassageObjectModel _currentPassage
```

#### Field Value

**Type:** Global.PassageObjectModel

### _elevatorWaitElapsedTime

```csharp
private float _elevatorWaitElapsedTime
```

#### Field Value

**Type:** System.Single

### _elevatorWaitTime

```csharp
public const float _elevatorWaitTime = 0.5
```

#### Field Value

**Type:** System.Single

### _isActive

```csharp
private bool _isActive
```

#### Field Value

**Type:** System.Boolean

### _isNextElevator

```csharp
private bool _isNextElevator
```

#### Field Value

**Type:** System.Boolean

### _teleportable

```csharp
private bool _teleportable
```

#### Field Value

**Type:** System.Boolean

### blockedTimer

```csharp
public float blockedTimer
```

#### Field Value

**Type:** System.Single

### currentElevator

```csharp
private ElevatorPassageModel currentElevator
```

#### Field Value

**Type:** Global.ElevatorPassageModel

### currentScale

```csharp
public float currentScale
```

#### Field Value

**Type:** System.Single

### currentZValue

```csharp
public float currentZValue
```

#### Field Value

**Type:** System.Single

### destinationNode

```csharp
private MapNode destinationNode
```

#### Field Value

**Type:** Global.MapNode

### destinationNode2

```csharp
private MovableObjectNode destinationNode2
```

#### Field Value

**Type:** Global.MovableObjectNode

### edgeDirection

```csharp
public EdgeDirection edgeDirection
```

#### Field Value

**Type:** Global.EdgeDirection

### edgePosRate

```csharp
public float edgePosRate
```

#### Field Value

**Type:** System.Single

### edgePosRateGoal

```csharp
private float edgePosRateGoal
```

#### Field Value

**Type:** System.Single

### isIgnoreZValue

```csharp
public bool isIgnoreZValue
```

#### Field Value

**Type:** System.Boolean

### lastNode

```csharp
private MapNode lastNode
```

#### Field Value

**Type:** Global.MapNode

### model

```csharp
private UnitModel model
```

#### Field Value

**Type:** Global.UnitModel

### moveDistance

```csharp
private float moveDistance
```

#### Field Value

**Type:** System.Single

### notNullPassage

```csharp
private PassageObjectModel notNullPassage
```

#### Field Value

**Type:** Global.PassageObjectModel

### passageChangedParam

```csharp
private object passageChangedParam
```

#### Field Value

**Type:** System.Object

### pathIndex

```csharp
private int pathIndex
```

#### Field Value

**Type:** System.Int32

### pathInfo

```csharp
private PathResult pathInfo
```

#### Field Value

**Type:** Global.PathResult

### pathMoveBy

```csharp
private PathMoveBy pathMoveBy
```

#### Field Value

**Type:** Global.PathMoveBy

### state

```csharp
private MovableState state
```

#### Field Value

**Type:** Global.MovableState

### unitDirection

```csharp
private UnitDirection unitDirection
```

#### Field Value

**Type:** Global.UnitDirection

### unpassableList

```csharp
private List<PassType> unpassableList
```

#### Field Value

**Type:** System.Collections.Generic.List{PassType}

### viewPosition

```csharp
private Vector3 viewPosition
```

#### Field Value

**Type:** UnityEngine.Vector3

### viewPositionSet

```csharp
private bool viewPositionSet
```

#### Field Value

**Type:** System.Boolean

## Properties

### currentEdge

```csharp
public MapEdge currentEdge { get; }
```

#### Property Value

**Type:** Global.MapEdge

### currentNode

```csharp
public MapNode currentNode { get; }
```

#### Property Value

**Type:** Global.MapNode

### currentPassage

```csharp
public PassageObjectModel currentPassage { get; set; }
```

#### Property Value

**Type:** Global.PassageObjectModel

### isActive

```csharp
public bool isActive { get; }
```

#### Property Value

**Type:** System.Boolean

### isBlocked

```csharp
public bool isBlocked { get; }
```

#### Property Value

**Type:** System.Boolean

### IsNextElevator

```csharp
public bool IsNextElevator { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### AddUnpassableType(PassType)

```csharp
public void AddUnpassableType(PassType pass)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pass` | `Global.PassType` |  |

### Assign(MovableObjectNode)

```csharp
public void Assign(MovableObjectNode src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `Global.MovableObjectNode` |  |

### CanMoveBy(UnitDirection)

```csharp
public bool CanMoveBy(UnitDirection direction)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `direction` | `Global.UnitDirection` |  |

#### Returns

**Type:** System.Boolean

### CheckConnectedInPassage(MovableObjectNode, MovableObjectNode)

```csharp
public static bool CheckConnectedInPassage(MovableObjectNode n1, MovableObjectNode n2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `n1` | `Global.MovableObjectNode` |  |
| `n2` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** System.Boolean

### CheckInRange(MovableObjectNode)

```csharp
public bool CheckInRange(MovableObjectNode other)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `other` | `Global.MovableObjectNode` |  |
| `range` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### CheckPassable(MapEdge, EdgeDirection, float, float)

```csharp
private bool CheckPassable(MapEdge edge, EdgeDirection edgeDir, float oldEdgePosRate, float newEdgePosRate)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `edge` | `Global.MapEdge` |  |
| `edgeDir` | `Global.EdgeDirection` |  |
| `oldEdgePosRate` | `System.Single` |  |
| `newEdgePosRate` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### CheckPassInNode()

```csharp
private bool CheckPassInNode()
```

#### Returns

**Type:** System.Boolean

### DisablePositionSetter()

```csharp
public void DisablePositionSetter()
```

### EnablePositionSetter(Vector3)

```csharp
public void EnablePositionSetter(Vector3 position)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `position` | `UnityEngine.Vector3` |  |

### EnterElevator(MapNode, MapNode)

```csharp
public void EnterElevator(MapNode elevatorNode, MapNode nextNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `elevatorNode` | `Global.MapNode` |  |
| `nextNode` | `Global.MapNode` |  |

### Equal(MovableObjectNode)

```csharp
public bool Equal(MovableObjectNode src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** System.Boolean

### EqualPosition(MapNode)

```csharp
public bool EqualPosition(MapNode node)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### GetCurrentEdge()

```csharp
public MapEdge GetCurrentEdge()
```

#### Returns

**Type:** Global.MapEdge

### GetCurrentNode()

```csharp
public MapNode GetCurrentNode()
```

#### Returns

**Type:** Global.MapNode

### GetCurrentStandingSefira()

```csharp
public Sefira GetCurrentStandingSefira()
```

#### Returns

**Type:** Global.Sefira

### GetCurrentViewPosition()

```csharp
public Vector3 GetCurrentViewPosition()
```

#### Returns

**Type:** UnityEngine.Vector3

### GetDirection()

```csharp
public UnitDirection GetDirection()
```

#### Returns

**Type:** Global.UnitDirection

### GetDistance(MapNode, float)

```csharp
public float GetDistance(MapNode other, float limit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `other` | `Global.MapNode` |  |
| `limit` | `System.Single` |  |

#### Returns

**Type:** System.Single

### GetDistance(MovableObjectNode, float)

```csharp
public float GetDistance(MovableObjectNode other, float limit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `other` | `Global.MovableObjectNode` |  |
| `limit` | `System.Single` |  |

#### Returns

**Type:** System.Single

### GetDistance(MovableObjectNode, MovableObjectNode)

```csharp
public static float GetDistance(MovableObjectNode node1, MovableObjectNode node2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node1` | `Global.MovableObjectNode` |  |
| `node2` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** System.Single

### GetDistanceDouble(MovableObjectNode)

```csharp
public float GetDistanceDouble(MovableObjectNode mov)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** System.Single

### GetEdgeDirection()

```csharp
public EdgeDirection GetEdgeDirection()
```

#### Returns

**Type:** Global.EdgeDirection

### GetPassage()

```csharp
public PassageObjectModel GetPassage()
```

#### Returns

**Type:** Global.PassageObjectModel

### GetPassageCheckPrev()

```csharp
public PassageObjectModel GetPassageCheckPrev()
```

#### Returns

**Type:** Global.PassageObjectModel

### GetSideMovableNode(UnitDirection, float)

```csharp
public MovableObjectNode GetSideMovableNode(UnitDirection direction, float distance)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `direction` | `Global.UnitDirection` |  |
| `distance` | `System.Single` |  |

#### Returns

**Type:** Global.MovableObjectNode

### GetState()

```csharp
public MovableState GetState()
```

#### Returns

**Type:** Global.MovableState

### GetUnit()

```csharp
public UnitModel GetUnit()
```

#### Returns

**Type:** Global.UnitModel

### GetViewPositionInEdge(MapEdge, EdgeDirection, float)

```csharp
public static Vector3 GetViewPositionInEdge(MapEdge edge, EdgeDirection edgeDirection, float edgePosRate)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `edge` | `Global.MapEdge` |  |
| `edgeDirection` | `Global.EdgeDirection` |  |
| `edgePosRate` | `System.Single` |  |

#### Returns

**Type:** UnityEngine.Vector3

### InElevator()

```csharp
public bool InElevator()
```

#### Returns

**Type:** System.Boolean

### InteractWithDoor(DoorObjectModel)

```csharp
private void InteractWithDoor(DoorObjectModel door)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `door` | `Global.DoorObjectModel` |  |

### IsMoving()

```csharp
public bool IsMoving()
```

#### Returns

**Type:** System.Boolean

### MoveBy(UnitDirection, float)

```csharp
public void MoveBy(UnitDirection direction, float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `direction` | `Global.UnitDirection` |  |
| `value` | `System.Single` |  |

### MoveBy_GetNextEdge(MapNode, UnitDirection)

```csharp
private static MapEdge MoveBy_GetNextEdge(MapNode node, UnitDirection direction)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |
| `direction` | `Global.UnitDirection` |  |

#### Returns

**Type:** Global.MapEdge

### MoveToMovableNode(MovableObjectNode, bool)

```csharp
public void MoveToMovableNode(MovableObjectNode targetNode, bool checkRabbit = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MovableObjectNode` |  |
| `checkRabbit` | `System.Boolean` |  |

### MoveToNode(MapNode, bool)

```csharp
public void MoveToNode(MapNode targetNode, bool checkRabbit = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |
| `checkRabbit` | `System.Boolean` |  |

### ProcessMoveByDistance(float)

```csharp
private void ProcessMoveByDistance(float distance)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `distance` | `System.Single` |  |

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
