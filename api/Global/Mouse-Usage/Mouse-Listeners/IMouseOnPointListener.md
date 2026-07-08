---
uid: Global.IMouseOnPointListener
canonical_path: /api/Global/Misc/IMouseOnPointListener
---
# Interface IMouseOnPointListener
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IMouseOnPointListener
```
> This section may have incomplete or incorrect information.
{.is-warning}

Interface for things which react to being hovered over by the cursor.

Implemented by [AgentUnit](/api/Global/Worker/AgentUnit) and [PassageObject](/api/Global/Object/PassageObject).

Used by [UnitMouseEventManager](/api/Global/Unit/UnitMouseEventManager).


#### Methods
	bool HasPointListener()
	void OnPointEnter()
	void OnPointExit()


## Methods
### HasPointListener()
```csharp
bool HasPointListener()
```


#### Returns
**Type:** System.Boolean

### OnPointEnter()
```csharp
void OnPointEnter()
```


### OnPointExit()
```csharp
void OnPointExit()
```





