---
uid: Global.PassageObjectModel
canonical_path: /api/Global/Model/PassageObjectModel
---

# Class PassageObjectModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PassageObjectModel : ObjectModelBase, IMouseCommandTargetModel
```

Represents a room, hallway, [containment unit](/api/Global/IOBserver/IsolateRoom), or elevator.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [ObjectModelBase](/api/Global/Object/ObjectModelBase) → PassageObjectModel

## Implements
[IMouseCommandTargetModel](/api/Global/Model/IMouseCommandTargetModel)

## Inherited Members
[position](/api/Global/Object/ObjectModelBase#position), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PassageObjectModel(string, string)

```csharp
public PassageObjectModel(string id, string sefiraName)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |
| `sefiraName` | `System.String` |  |

### PassageObjectModel(string, string, string)

```csharp
public PassageObjectModel(string id, string sefiraName, string prefabSrc)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |
| `sefiraName` | `System.String` |  |
| `prefabSrc` | `System.String` |  |

## Fields

### _sortedList

```csharp
private List<MapNode> _sortedList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MapNode}

### centerNode

```csharp
public MapNode centerNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### connectedSefira

```csharp
private List<string> connectedSefira
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{System.String}

### deletedUnitList

```csharp
private List<MovableObjectNode> deletedUnitList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MovableObjectNode}

### doorObjectList

```csharp
private List<DoorObjectModel> doorObjectList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{DoorObjectModel}

### elevatorList

```csharp
private List<ElevatorPassageModel> elevatorList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{ElevatorPassageModel}

### enteredUnitList

```csharp
private List<MovableObjectNode> enteredUnitList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MovableObjectNode}

### groundInfo

```csharp
public PassageGroundInfo groundInfo
```
#INC


#### Field Value

**Type:** Global.PassageGroundInfo

### height

```csharp
public float height
```
#INC


#### Field Value

**Type:** System.Single

### id

```csharp
private string id
```
#INC


#### Field Value

**Type:** System.String

### isActivate

```csharp
public bool isActivate
```
#INC


#### Field Value

**Type:** System.Boolean

### isDynamic

```csharp
public bool isDynamic
```
#INC


#### Field Value

**Type:** System.Boolean

### isIsolate

```csharp
private bool isIsolate
```
#INC


#### Field Value

**Type:** System.Boolean

### mapNodeList

```csharp
private List<MapNode> mapNodeList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MapNode}

### passageGroup

```csharp
public string passageGroup
```
#INC


#### Field Value

**Type:** System.String

### rabbitTeamGroup

```csharp
public string rabbitTeamGroup
```
#INC


#### Field Value

**Type:** System.String

### scaleFactor

```csharp
public float scaleFactor
```
#INC


#### Field Value

**Type:** System.Single

### sefiraDisabled

```csharp
public bool sefiraDisabled
```
#INC


#### Field Value

**Type:** System.Boolean

### sefiraEnum

```csharp
private SefiraEnum sefiraEnum
```
#INC


#### Field Value

**Type:** Global.SefiraEnum

### sefiraName

```csharp
private string sefiraName
```
#INC


#### Field Value

**Type:** System.String

### src

```csharp
private string src
```
#INC


#### Field Value

**Type:** System.String

### type

```csharp
public PassageType type
```
#INC


#### Field Value

**Type:** Global.PassageType

### wallInfo

```csharp
public PassageWallInfo wallInfo
```
#INC


#### Field Value

**Type:** Global.PassageWallInfo

## Methods

### Activate()

```csharp
public void Activate()
```
#INC


### AddAttachedSefira(string)

```csharp
public void AddAttachedSefira(string sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

### AddBloodMapObject(BloodMapObjectModel)

```csharp
private void AddBloodMapObject(BloodMapObjectModel mapObject)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mapObject` | `Global.BloodMapObjectModel` |  |

### AddDeletedUnit(MovableObjectNode)

```csharp
public void AddDeletedUnit(MovableObjectNode unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.MovableObjectNode` |  |

### AddDoor(DoorObjectModel)

```csharp
public void AddDoor(DoorObjectModel door)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `door` | `Global.DoorObjectModel` |  |

### AddElevator(ElevatorPassageModel)

```csharp
public void AddElevator(ElevatorPassageModel elevator)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `elevator` | `Global.ElevatorPassageModel` |  |

### AddNode(MapNode)

```csharp
public void AddNode(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### AttachBloodObject(float)

```csharp
public void AttachBloodObject(float posx)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `posx` | `System.Single` |  |

### AttachBloodObjectAlter(float)

```csharp
public void AttachBloodObjectAlter(float posx)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `posx` | `System.Single` |  |

### AttachToConnetedSefira()

```csharp
public void AttachToConnetedSefira()
```
#INC


### CheckCenter()

```csharp
public void CheckCenter()
```
#INC


### DisableSefira()

```csharp
public void DisableSefira()
```
#INC


### EnterUnit(MovableObjectNode)

```csharp
public void EnterUnit(MovableObjectNode unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.MovableObjectNode` |  |

### ExitUnit(MovableObjectNode)

```csharp
public void ExitUnit(MovableObjectNode unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.MovableObjectNode` |  |

### FixedUpdate()

```csharp
public virtual void FixedUpdate()
```
#INC


### GetDeletedUnits()

```csharp
public MovableObjectNode[] GetDeletedUnits()
```
#INC


#### Returns

**Type:** Global.MovableObjectNode[]

### GetDoorList()

```csharp
public DoorObjectModel[] GetDoorList()
```
#INC


#### Returns

**Type:** Global.DoorObjectModel[]

### GetElevatorList()

```csharp
public ElevatorPassageModel[] GetElevatorList()
```
#INC


#### Returns

**Type:** Global.ElevatorPassageModel[]

### GetEnteredTargets()

```csharp
public ReadOnlyCollection<MovableObjectNode> GetEnteredTargets()
```
#INC


#### Returns

**Type:** System.Collections.ObjectModel.ReadOnlyCollection{MovableObjectNode}

### GetEnteredTargets(MovableObjectNode)

```csharp
public MovableObjectNode[] GetEnteredTargets(MovableObjectNode exclude)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `exclude` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** Global.MovableObjectNode[]

### GetEnteredTargetsAsArray()

```csharp
public MovableObjectNode[] GetEnteredTargetsAsArray()
```
#INC


#### Returns

**Type:** Global.MovableObjectNode[]

### GetId()

```csharp
public string GetId()
```
#INC


#### Returns

**Type:** System.String

### GetLeft()

```csharp
public MapNode GetLeft()
```
#INC


#### Returns

**Type:** Global.MapNode

### GetNodeList()

```csharp
public MapNode[] GetNodeList()
```
#INC


#### Returns

**Type:** Global.MapNode[]

### GetNodeListAsReadOnly()

```csharp
public IList<MapNode> GetNodeListAsReadOnly()
```
#INC


#### Returns

**Type:** System.Collections.Generic.IList{MapNode}

### GetPassageType()

```csharp
public PassageType GetPassageType()
```
#INC


#### Returns

**Type:** Global.PassageType

### GetPassageTypeByString(string)

```csharp
public static PassageType GetPassageTypeByString(string str)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |

#### Returns

**Type:** Global.PassageType

### GetRandomMovableNode()

```csharp
public MovableObjectNode GetRandomMovableNode()
```
#INC


#### Returns

**Type:** Global.MovableObjectNode

### GetRight()

```csharp
public MapNode GetRight()
```
#INC


#### Returns

**Type:** Global.MapNode

### GetScaleFactor()

```csharp
public float GetScaleFactor()
```
#INC


#### Returns

**Type:** System.Single

### GetSefira()

```csharp
public Sefira GetSefira()
```
#INC


#### Returns

**Type:** Global.Sefira

### GetSefiraEnum()

```csharp
public SefiraEnum GetSefiraEnum()
```
#INC


#### Returns

**Type:** Global.SefiraEnum

### GetSefiraName()

```csharp
public string GetSefiraName()
```
#INC


#### Returns

**Type:** System.String

### GetSortedList()

```csharp
private List<MapNode> GetSortedList()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{MapNode}

### GetSortedListAsAry()

```csharp
public MapNode[] GetSortedListAsAry()
```
#INC


#### Returns

**Type:** Global.MapNode[]

### GetSrc()

```csharp
public string GetSrc()
```
#INC


#### Returns

**Type:** System.String

### GetVerticalRange(ref float, ref float)

```csharp
public void GetVerticalRange(ref float left, ref float right)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `left` | `System.Single` |  |
| `right` | `System.Single` |  |

### GetWidth()

```csharp
public float GetWidth()
```
#INC


#### Returns

**Type:** System.Single

### isAreaHasOtherMov(MovableObjectNode)

```csharp
public bool isAreaHasOtherMov(MovableObjectNode mov)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

#### Returns

**Type:** System.Boolean

### IsIsolate()

```csharp
public bool IsIsolate()
```
#INC


#### Returns

**Type:** System.Boolean

### isPassageEnteredAnyUnit()

```csharp
public bool isPassageEnteredAnyUnit()
```
#INC


#### Returns

**Type:** System.Boolean

### OnStageEnd()

```csharp
public void OnStageEnd()
```
#INC


### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### RemoveDeletedUnit(MovableObjectNode)

```csharp
public void RemoveDeletedUnit(MovableObjectNode unit)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.MovableObjectNode` |  |

### SetPassageType(PassageType)

```csharp
public void SetPassageType(PassageType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.PassageType` |  |

### SetToIsolate()

```csharp
public void SetToIsolate()
```
#INC

