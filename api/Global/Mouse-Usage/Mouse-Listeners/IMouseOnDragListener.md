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
> This section may have incomplete or incorrect information.
{.is-warning}

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


#### Returns
**Type:** System.Boolean

### OnEnterDragArea()
```csharp
void OnEnterDragArea()
```


### OnExitDragArea()
```csharp
void OnExitDragArea()
```





