---
uid: Global.IAnimatorEventCalled
canonical_path: /api/Global/Misc/IAnimatorEventCalled
---

# Interface IAnimatorEventCalled

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IAnimatorEventCalled
```
Interface representing something which should be animated when certain events are called.

Used *mainly* by abnormality animation handlers, but also by [agents](/api/Global/Misc/AgentAnim) and (frustratingly) some UI elements.

#### Methods
	OnCalled
	OnCalled(int i)
	AgentReset
	SimpleReset
	AnimatorEventInit
	CreatureAnimCall(int i, CreatureBase script)
	AttackCalled(int i)
	AttackDamageTimeCalled
	SoundMake(string src)

#INC (Say what each of these do. AttackCalled is when this thing attacks. (??))


## Methods

### AgentReset()

```csharp
void AgentReset()
```
#INC


### AnimatorEventInit()

```csharp
void AnimatorEventInit()
```
#INC


### AttackCalled(int)

```csharp
void AttackCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### AttackDamageTimeCalled()

```csharp
void AttackDamageTimeCalled()
```
#INC


### CreatureAnimCall(int, CreatureBase)

```csharp
void CreatureAnimCall(int i, CreatureBase script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `script` | `Global.CreatureBase` |  |

### OnCalled()

```csharp
void OnCalled()
```
#INC
#code-generated


### OnCalled(int)

```csharp
void OnCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### SimpleReset()

```csharp
void SimpleReset()
```
#INC


### SoundMake(string)

```csharp
void SoundMake(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
