---
uid: Global.IMouseOnSelectListener
canonical_path: /api/Global/Misc/IMouseOnSelectListener
---
# Interface IMouseOnSelectListener
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IMouseOnSelectListener
```
> This section may have incomplete or incorrect information.
{.is-warning}

Interface for listeners of being selected by the mouse (presumably, by clicking).

Implemented by:
- [Agents](/api/Global/Worker/AgentUnit)
- [Abnormalities](/api/Global/Unit/CreatureUnit)
- [Clerks](/api/Global/Worker/OfficerUnit)
- [Rabbit units](/api/Global/Unit/RabbitUnit)

Used by [UnitMouseEventManager](/api/Global/Unit/UnitMouseEventManager).


#### Methods
	bool IsSelectable()
	void OnSelect()
	void OnUnselect()


## Methods
### IsSelectable()
```csharp
bool IsSelectable()
```


#### Returns
**Type:** System.Boolean

### OnSelect()
```csharp
void OnSelect()
```


### OnUnselect()
```csharp
void OnUnselect()
```





