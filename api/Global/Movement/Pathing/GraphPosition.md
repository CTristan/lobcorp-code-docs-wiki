---
title: GraphPosition
description: 
published: true
date: 2026-07-28T19:20:25.092Z
tags: 
editor: markdown
dateCreated: 2026-07-08T04:40:14.012Z
---

# Class GraphPosition
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GraphPosition
```
> This class is not used.
{.is-info}

Unused. Represents a position and edge on the [map](/api/Global/Map/MapGraph).

See [Movement](/Movement) for an overview of the movement systems.

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GraphPosition

## Constructors
### GraphPosition(MapEdge, int, float)
```csharp
public GraphPosition(MapEdge currentEdge, int direction, float rate)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `currentEdge` | `Global.MapEdge` |  |
| `direction` | `System.Int32` |  |
| `rate` | `System.Single` |  |

### GraphPosition(MapNode)
```csharp
public GraphPosition(MapNode currentNode)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `currentNode` | `Global.MapNode` |  |

## Fields
### currentEdge
```csharp
public MapEdge currentEdge
```


#### Field Value
**Type:** Global.MapEdge

### currentNode
```csharp
public MapNode currentNode
```


#### Field Value
**Type:** Global.MapNode

### edgeDirection
```csharp
public int edgeDirection
```


#### Field Value
**Type:** System.Int32

### edgePosRate
```csharp
public float edgePosRate
```


#### Field Value
**Type:** System.Single

## Methods
### GetCurrentViewPosition(out Vector2)
```csharp
public bool GetCurrentViewPosition(out Vector2 output)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `output` | `UnityEngine.Vector2` |  |

#### Returns
**Type:** System.Boolean

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







