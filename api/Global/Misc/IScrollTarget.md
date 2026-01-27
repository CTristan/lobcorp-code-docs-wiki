---
uid: Global.IScrollTarget
canonical_path: /api/Global/Misc/IScrollTarget
---

# Interface IScrollTarget

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IScrollTarget
```
Interface for things that can be scrolled in.

Example: [CommandWindow](/api/CommandWindow) registers itself to listen to mouse scroll while the cursor is over an [agent](/api/CommandWindow/AgentSlot), and unregisters itself when the cursor exits.

 (used for the work log) does the same.
#INC 

#### Methods
	void Regist()
	void DeRegist()
	void AddTrigger()


## Methods

### AddTrigger()

```csharp
void AddTrigger()
```
#INC


### DeRegist()

```csharp
void DeRegist()
```
#INC


### Regist()

```csharp
void Regist()
```
#INC
#code-generated

