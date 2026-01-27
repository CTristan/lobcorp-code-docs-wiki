---
uid: Global.IDraggableObject
canonical_path: /api/Global/Object/IDraggableObject
---

# Interface IDraggableObject

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IDraggableObject
```
Interface for draggable objects.

Used by [DeployAgentSlot](/api/Global/Misc/DeployAgentSlot), [DeploySefiraAgentSlot](/api/Global/Misc/DeploySefiraAgentSlot), and [ResearchPanel](/api/Global/Misc/ResearchPanel).

#### Methods
GameObject GenDraggedObject(string name)
OnEndDrag
OnCanceled
OnDragStart
DraggedObject GetDraggingObject
OnDropEnd(Drop drop, bool state)


## Methods

### GenDraggedObject(string)

```csharp
GameObject GenDraggedObject(string name)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject

### GetDraggingObject()

```csharp
DraggedObject GetDraggingObject()
```
#INC


#### Returns

**Type:** Global.DraggedObject

### OnCanceled()

```csharp
void OnCanceled()
```
#INC


### OnDragStart()

```csharp
void OnDragStart()
```
#INC


### OnDropEnd(Drop, bool)

```csharp
void OnDropEnd(Drop drop, bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `drop` | `Global.Drop` |  |
| `state` | `System.Boolean` |  |

### OnEndDrag()

```csharp
void OnEndDrag()
```
#INC

