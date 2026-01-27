---
uid: Global.MapEdge
canonical_path: /api/Global/Misc/MapEdge
---

# Class MapEdge

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MapEdge
```
A connection between [MapNode](/api/Global/Misc/MapNode)s on the map.

Represents a connection between rooms.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MapEdge

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MapEdge(MapNode, MapNode, string)

```csharp
public MapEdge(MapNode node1, MapNode node2, string type)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node1` | `Global.MapNode` |  |
| `node2` | `Global.MapNode` |  |
| `type` | `System.String` |  |

### MapEdge(MapNode, MapNode, string, float)

```csharp
public MapEdge(MapNode node1, MapNode node2, string type, float cost)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node1` | `Global.MapNode` |  |
| `node2` | `Global.MapNode` |  |
| `type` | `System.String` |  |
| `cost` | `System.Single` |  |

## Fields

### activated

```csharp
public bool activated
```
#INC


#### Field Value

**Type:** System.Boolean

### cost

```csharp
public float cost
```
#INC


#### Field Value

**Type:** System.Single

### name

```csharp
public string name
```
#INC


#### Field Value

**Type:** System.String

### node1

```csharp
public MapNode node1
```
#INC


#### Field Value

**Type:** Global.MapNode

### node2

```csharp
public MapNode node2
```
#INC


#### Field Value

**Type:** Global.MapNode

### type

```csharp
public string type
```
#INC


#### Field Value

**Type:** System.String

## Methods

### AddEdgeInNode()

```csharp
public void AddEdgeInNode()
```
#INC


### ConnectedNode(MapNode)

```csharp
public MapNode ConnectedNode(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** Global.MapNode

### ConnectedNodeIgoreActivate(MapNode)

```csharp
public MapNode ConnectedNodeIgoreActivate(MapNode node)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

#### Returns

**Type:** Global.MapNode

### GetGoalNode(EdgeDirection)

```csharp
public MapNode GetGoalNode(EdgeDirection direction)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `direction` | `Global.EdgeDirection` |  |

#### Returns

**Type:** Global.MapNode
