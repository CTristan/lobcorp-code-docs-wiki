# Class ElevatorPassageModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ElevatorPassageModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ElevatorPassageModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ElevatorPassageModel(MapNode, PassageObjectModel, string)

```csharp
public ElevatorPassageModel(MapNode elevatorNode, PassageObjectModel basePassage, string elevatorPrefabPath)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `elevatorNode` | `Global.MapNode` |  |
| `basePassage` | `Global.PassageObjectModel` |  |
| `elevatorPrefabPath` | `System.String` |  |

## Methods

### AddFloorInfo(MapNode[], Vector3)

```csharp
public void AddFloorInfo(MapNode[] node, Vector3 position)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode[]` |  |
| `position` | `UnityEngine.Vector3` |  |

### AddNode(MapNode)

```csharp
public void AddNode(MapNode node)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### ClickButton(MapNode)

```csharp
public void ClickButton(MapNode callNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `callNode` | `Global.MapNode` |  |

### FinishMove(int)

```csharp
public void FinishMove(int floor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `floor` | `System.Int32` |  |

### GetCurrentFloorNodes()

```csharp
public MapNode[] GetCurrentFloorNodes()
```

#### Returns

**Type:** Global.MapNode[]

### GetCurrentPos()

```csharp
public float GetCurrentPos()
```

#### Returns

**Type:** System.Single

### GetElevatorPosition()

```csharp
public Vector3 GetElevatorPosition()
```

#### Returns

**Type:** UnityEngine.Vector3

### GetElevatorPrefab()

```csharp
public GameObject GetElevatorPrefab()
```

#### Returns

**Type:** UnityEngine.GameObject

### GetElevatorType()

```csharp
public ElevatorType GetElevatorType()
```

#### Returns

**Type:** Global.ElevatorType

### GetNode()

```csharp
public MapNode GetNode()
```

#### Returns

**Type:** Global.MapNode

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```

### OnUnitEnter(MovableObjectNode, MapNode)

```csharp
public void OnUnitEnter(MovableObjectNode unit, MapNode destination)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.MovableObjectNode` |  |
| `destination` | `Global.MapNode` |  |

### OnUnitExit(MovableObjectNode)

```csharp
public void OnUnitExit(MovableObjectNode unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.MovableObjectNode` |  |

### StartMove()

```csharp
public void StartMove()
```
