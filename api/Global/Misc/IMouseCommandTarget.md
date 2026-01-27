---
uid: Global.IMouseCommandTarget
canonical_path: /api/Global/Misc/IMouseCommandTarget
---

# Interface IMouseCommandTarget

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IMouseCommandTarget
```
Interface with one method, which gets the [IMouseCommandTargetModel](/api/Global/Model/IMouseCommandTargetModel) user.

For getting certain things which can be targeted with the mouse:
- [Agents](/api/Global/Worker/AgentUnit)
- [Clerks](/api/Global/Worker/OfficerUnit)
- [Abnormalities](/api/Global/Unit/CreatureUnit)
- [Rabbit units](/api/Global/Unit/RabbitUnit)
- [Passageways](/api/Global/Object/PassageObject)

Used by [UnitMouseEventManager](/api/Global/Unit/UnitMouseEventManager) (for selection and ordering agents to move) and for [bullet research](/api/GlobalBullet/GlobalBulletWindow).
#INC 

#### Method
	IMouseCommandTargetModel GetCommandTargetModel


## Methods

### GetCommandTargetModel()

```csharp
IMouseCommandTargetModel GetCommandTargetModel()
```
#INC
#code-generated


#### Returns

**Type:** Global.IMouseCommandTargetModel
