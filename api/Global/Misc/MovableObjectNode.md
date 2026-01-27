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
Represents an object which can move, for example:
- [Units](/api/Global/Model/UnitModel) (abnormalities, workers, rabbits, projectiles, sephirah bosses, ordeal creatures...)
- Possibly other things, too


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MovableObjectNode

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MovableObjectNode(bool)

```csharp
public MovableObjectNode(bool active)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `active` | `System.Boolean` |  |

### MovableObjectNode(UnitModel)

```csharp
public MovableObjectNode(UnitModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

## Fields

### _currentEdge

```csharp
private MapEdge _currentEdge
```
#INC


#### Field Value

**Type:** Global.MapEdge

### _currentNode

```csharp
private MapNode _currentNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### _currentPassage

```csharp
private PassageObjectModel _currentPassage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### _elevatorWaitElapsedTime

```csharp
private float _elevatorWaitElapsedTime
```
#INC


#### Field Value

**Type:** System.Single

### _elevatorWaitTime

```csharp
public const float _elevatorWaitTime = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### _isActive

```csharp
private bool _isActive
```
#INC


#### Field Value

**Type:** System.Boolean

### _isNextElevator

```csharp
private bool _isNextElevator
```
#INC


#### Field Value

**Type:** System.Boolean

### _teleportable

```csharp
private bool _teleportable
```
#INC


#### Field Value

**Type:** System.Boolean

### blockedTimer

```csharp
public float blockedTimer
```
#INC


#### Field Value

**Type:** System.Single

### currentElevator

```csharp
private ElevatorPassageModel currentElevator
```
#INC


#### Field Value

**Type:** Global.ElevatorPassageModel

### currentScale

```csharp
public float currentScale
```
#INC


#### Field Value

**Type:** System.Single

### currentZValue

```csharp
public float currentZValue
```
#INC


#### Field Value

**Type:** System.Single

### destinationNode

```csharp
private MapNode destinationNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### destinationNode2

```csharp
private MovableObjectNode destinationNode2
```
#INC


#### Field Value

**Type:** Global.MovableObjectNode

### edgeDirection

```csharp
public EdgeDirection edgeDirection
```
#INC


#### Field Value

**Type:** Global.EdgeDirection

### edgePosRate

```csharp
public float edgePosRate
```
#INC


#### Field Value

**Type:** System.Single

### edgePosRateGoal

```csharp
private float edgePosRateGoal
```
#INC


#### Field Value

**Type:** System.Single

### isIgnoreZValue

```csharp
public bool isIgnoreZValue
```
#INC


#### Field Value

**Type:** System.Boolean

### lastNode

```csharp
private MapNode lastNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### model

```csharp
private UnitModel model
```
#INC


#### Field Value

**Type:** Global.UnitModel

### moveDistance

```csharp
private float moveDistance
```
#INC


#### Field Value

**Type:** System.Single

### notNullPassage

```csharp
private PassageObjectModel notNullPassage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### passageChangedParam

```csharp
private object passageChangedParam
```
#INC


#### Field Value

**Type:** System.Object

### pathIndex

```csharp
private int pathIndex
```
#INC


#### Field Value

**Type:** System.Int32

### pathInfo

```csharp
private PathResult pathInfo
```
#INC


#### Field Value

**Type:** Global.PathResult

### pathMoveBy

```csharp
private PathMoveBy pathMoveBy
```
#INC


#### Field Value

**Type:** Global.PathMoveBy

### state

```csharp
private MovableState state
```
#INC


#### Field Value

**Type:** Global.MovableState

### unitDirection

```csharp
private UnitDirection unitDirection
```
#INC


#### Field Value

**Type:** Global.UnitDirection

### unpassableList

```csharp
private List<PassType> unpassableList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{PassType}

### viewPosition

```csharp
private Vector3 viewPosition
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### viewPositionSet

```csharp
private bool viewPositionSet
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pass` | `Global.PassType` |  |

### Assign(MovableObjectNode)

```csharp
public void Assign(MovableObjectNode src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `Global.MovableObjectNode` |  |

### CanMoveBy(UnitDirection)

```csharp
public bool CanMoveBy(UnitDirection direction)
```
#INC


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
#INC


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
#INC


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
#INC


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
#INC


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
#INC


#### Returns

**Type:** System.Boolean

### DisablePositionSetter()

```csharp
public void DisablePositionSetter()
```
#INC


### EnablePositionSetter(Vector3)

```csharp
public void EnablePositionSetter(Vector3 position)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `position` | `UnityEngine.Vector3` |  |

### EnterElevator(MapNode, MapNode)

```csharp
public void EnterElevator(MapNode elevatorNode, MapNode nextNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `elevatorNode` | `Global.MapNode` |  |
| `nextNode` | `Global.MapNode` |  |

### Equal(MovableObjectNode)

```csharp
public bool Equal(MovableObjectNode src)
```
#INC


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
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### GetCurrentEdge()

```csharp
public MapEdge GetCurrentEdge()
```
#INC


#### Returns

**Type:** Global.MapEdge

### GetCurrentNode()

```csharp
public MapNode GetCurrentNode()
```
#INC


#### Returns

**Type:** Global.MapNode

### GetCurrentStandingSefira()

```csharp
public Sefira GetCurrentStandingSefira()
```
#INC


#### Returns

**Type:** Global.Sefira

### GetCurrentViewPosition()

```csharp
public Vector3 GetCurrentViewPosition()
```
#INC


#### Returns

**Type:** UnityEngine.Vector3

### GetDirection()

```csharp
public UnitDirection GetDirection()
```
#INC


#### Returns

**Type:** Global.UnitDirection

### GetDistance(MapNode, float)

```csharp
public float GetDistance(MapNode other, float limit)
```
#INC


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
#INC


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
#INC


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
#INC


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
#INC


#### Returns

**Type:** Global.EdgeDirection

### GetPassage()

```csharp
public PassageObjectModel GetPassage()
```
#INC


#### Returns

**Type:** Global.PassageObjectModel

### GetPassageCheckPrev()

```csharp
public PassageObjectModel GetPassageCheckPrev()
```
#INC


#### Returns

**Type:** Global.PassageObjectModel

### GetSideMovableNode(UnitDirection, float)

```csharp
public MovableObjectNode GetSideMovableNode(UnitDirection direction, float distance)
```
#INC


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
#INC


#### Returns

**Type:** Global.MovableState

### GetUnit()

```csharp
public UnitModel GetUnit()
```
#INC


#### Returns

**Type:** Global.UnitModel

### GetViewPositionInEdge(MapEdge, EdgeDirection, float)

```csharp
public static Vector3 GetViewPositionInEdge(MapEdge edge, EdgeDirection edgeDirection, float edgePosRate)
```
#INC


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
#INC


#### Returns

**Type:** System.Boolean

### InteractWithDoor(DoorObjectModel)

```csharp
private void InteractWithDoor(DoorObjectModel door)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `door` | `Global.DoorObjectModel` |  |

### IsMoving()

```csharp
public bool IsMoving()
```
#INC


#### Returns

**Type:** System.Boolean

### MoveBy(UnitDirection, float)

```csharp
public void MoveBy(UnitDirection direction, float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `direction` | `Global.UnitDirection` |  |
| `value` | `System.Single` |  |

### MoveBy_GetNextEdge(MapNode, UnitDirection)

```csharp
private static MapEdge MoveBy_GetNextEdge(MapNode node, UnitDirection direction)
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MovableObjectNode` |  |
| `checkRabbit` | `System.Boolean` |  |

### MoveToNode(MapNode, bool)

```csharp
public void MoveToNode(MapNode targetNode, bool checkRabbit = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |
| `checkRabbit` | `System.Boolean` |  |

### ProcessMoveByDistance(float)

```csharp
private void ProcessMoveByDistance(float distance)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `distance` | `System.Single` |  |

### ProcessMoveNode(float)

```csharp
public void ProcessMoveNode(float movement)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `movement` | `System.Single` |  |

### RemoveUnpassableType(PassType)

```csharp
public void RemoveUnpassableType(PassType pass)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pass` | `Global.PassType` |  |

### ReportUnitName()

```csharp
public void ReportUnitName()
```
#INC


### SetActive(bool)

```csharp
public void SetActive(bool active)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `active` | `System.Boolean` |  |

### SetCurrentEdge(MapEdge, float, EdgeDirection)

```csharp
public void SetCurrentEdge(MapEdge srcEdge, float srcEdgePosRate, EdgeDirection srcDirection)
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

### SetCurrentNode(MapNode)

```csharp
public void SetCurrentNode(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### SetDirection(UnitDirection)

```csharp
public void SetDirection(UnitDirection direction)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `direction` | `Global.UnitDirection` |  |

### SetPassageChangedParam(object)

```csharp
public void SetPassageChangedParam(object target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `System.Object` |  |

### SetTeleportable(bool)

```csharp
public void SetTeleportable(bool b)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `b` | `System.Boolean` |  |

### StopMoving()

```csharp
public void StopMoving()
```
#INC


### TrySetCurrentNode(MapNode)

```csharp
private void TrySetCurrentNode(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### UpdateCurrentPassage()

```csharp
private void UpdateCurrentPassage()
```
#INC


### UpdateNodeEdge(MapNode, MapEdge)

```csharp
private void UpdateNodeEdge(MapNode node, MapEdge edge)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |
| `edge` | `Global.MapEdge` |  |

### Wait()

```csharp
public void Wait()
```
#INC

