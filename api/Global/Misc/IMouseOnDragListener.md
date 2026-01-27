---
uid: Global.IMouseOnDragListener
canonical_path: /api/Global/Misc/IMouseOnDragListener
---

# Interface IMouseOnDragListener

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IMouseOnDragListener
```
Interface for listeners to drag area selections.

Only implemented by [AgentUnit](/api/Global/Worker/AgentUnit).

Used by [UnitMouseEventManager](/api/Global/Unit/UnitMouseEventManager).


#### Methods
	bool IsDragSelectable
	void OnEnterDragArea
	void OnExitDragArea


## Methods

### IsDragSelectable()

```csharp
bool IsDragSelectable()
```
#INC
#code-generated


#### Returns

**Type:** System.Boolean

### OnEnterDragArea()

```csharp
void OnEnterDragArea()
```
#INC


### OnExitDragArea()

```csharp
void OnExitDragArea()
```
#INC

