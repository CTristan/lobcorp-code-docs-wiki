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
#INC
#code-generated


#### Returns

**Type:** System.Boolean

### OnSelect()

```csharp
void OnSelect()
```
#INC


### OnUnselect()

```csharp
void OnUnselect()
```
#INC

