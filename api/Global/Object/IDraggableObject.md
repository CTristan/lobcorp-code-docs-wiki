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

## Methods

### GenDraggedObject(string)

```csharp
GameObject GenDraggedObject(string name)
```

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

#### Returns

**Type:** Global.DraggedObject

### OnCanceled()

```csharp
void OnCanceled()
```

### OnDragStart()

```csharp
void OnDragStart()
```

### OnDropEnd(Drop, bool)

```csharp
void OnDropEnd(Drop drop, bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `drop` | `Global.Drop` |  |
| `state` | `System.Boolean` |  |

### OnEndDrag()

```csharp
void OnEndDrag()
```
