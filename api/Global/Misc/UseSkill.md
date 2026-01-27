---
uid: Global.UseSkill
canonical_path: /api/Global/Misc/UseSkill
---

# Class UseSkill

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UseSkill
```
Represents an active work cycle.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → UseSkill

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UseSkill()

```csharp
public UseSkill()
```

## Fields

### _elapsedTime

```csharp
private float _elapsedTime
```
#INC


#### Field Value

**Type:** System.Single

### _faceCreature

```csharp
private bool _faceCreature
```
#INC


#### Field Value

**Type:** System.Boolean

### _isOverloadedCreature

```csharp
private bool _isOverloadedCreature
```
#INC


#### Field Value

**Type:** System.Boolean

### _readyToFinish

```csharp
private bool _readyToFinish
```
#INC


#### Field Value

**Type:** System.Boolean

### agent

```csharp
public AgentModel agent
```
#INC


#### Field Value

**Type:** Global.AgentModel

### agentView

```csharp
public AgentUnit agentView
```
#INC


#### Field Value

**Type:** Global.AgentUnit

### animRemoveOnDestroy

```csharp
public bool animRemoveOnDestroy
```
#INC


#### Field Value

**Type:** System.Boolean

### closed

```csharp
private bool closed
```
#INC


#### Field Value

**Type:** System.Boolean

### CONFESS_ID

```csharp
private const int CONFESS_ID = 6
```
#INC


#### Field Value

**Type:** System.Int32

### failCount

```csharp
public int failCount
```
#INC


#### Field Value

**Type:** System.Int32

### forceSuccess

```csharp
private bool forceSuccess
```
#INC


#### Field Value

**Type:** System.Boolean

### IMPROVISE_ID

```csharp
private const int IMPROVISE_ID = 7
```
#INC


#### Field Value

**Type:** System.Int32

### KIT_WORK_ID

```csharp
private const int KIT_WORK_ID = 5
```
#INC


#### Field Value

**Type:** System.Int32

### maxCubeCount

```csharp
public int maxCubeCount
```
#INC


#### Field Value

**Type:** System.Int32

### narrationPart1

```csharp
public bool narrationPart1
```
#INC


#### Field Value

**Type:** System.Boolean

### narrationPart2

```csharp
public bool narrationPart2
```
#INC


#### Field Value

**Type:** System.Boolean

### narrationPart3

```csharp
public bool narrationPart3
```
#INC


#### Field Value

**Type:** System.Boolean

### narrationPart4

```csharp
public bool narrationPart4
```
#INC


#### Field Value

**Type:** System.Boolean

### room

```csharp
public IsolateRoom room
```
#INC


#### Field Value

**Type:** Global.IsolateRoom

### skillTypeInfo

```csharp
public SkillTypeInfo skillTypeInfo
```
#INC


#### Field Value

**Type:** Global.SkillTypeInfo

### startAgentHp

```csharp
public float startAgentHp
```
#INC


#### Field Value

**Type:** System.Single

### startAgentMental

```csharp
public float startAgentMental
```
#INC


#### Field Value

**Type:** System.Single

### successCount

```csharp
public int successCount
```
#INC


#### Field Value

**Type:** System.Int32

### targetCreature

```csharp
public CreatureModel targetCreature
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### targetCreatureView

```csharp
public CreatureUnit targetCreatureView
```
#INC


#### Field Value

**Type:** Global.CreatureUnit

### tickInterval

```csharp
public float tickInterval
```
#INC


#### Field Value

**Type:** System.Single

### workCount

```csharp
public int workCount
```
#INC


#### Field Value

**Type:** System.Int32

### workPlaying

```csharp
private bool workPlaying
```
#INC


#### Field Value

**Type:** System.Boolean

### workProgress

```csharp
public float workProgress
```
#INC


#### Field Value

**Type:** System.Single

### workSpeed

```csharp
public float workSpeed
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### creatureFaced

```csharp
public bool creatureFaced { get; }
```

#### Property Value

**Type:** System.Boolean

### elapsedTime

```csharp
public float elapsedTime { get; }
```

#### Property Value

**Type:** System.Single

### IsWorkPlaying

```csharp
public bool IsWorkPlaying { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### CalculateDmgExp(float)

```csharp
private float CalculateDmgExp(float rate)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rate` | `System.Single` |  |

#### Returns

**Type:** System.Single

### CalculateLevelExp(RwbpType)

```csharp
private float CalculateLevelExp(RwbpType rwbpType)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rwbpType` | `Global.RwbpType` |  |

#### Returns

**Type:** System.Single

### CancelWork()

```csharp
public void CancelWork()
```
#INC


### CheckLive()

```csharp
public void CheckLive()
```
#INC


### CloseWork(bool)

```csharp
private void CloseWork(bool success)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `success` | `System.Boolean` |  |

### FinishWorkSuccessfully()

```csharp
private void FinishWorkSuccessfully()
```
#INC


### GetCurrentFeelingState()

```csharp
public CreatureFeelingState GetCurrentFeelingState()
```
#INC


#### Returns

**Type:** Global.CreatureFeelingState

### GetFailCubeCount()

```csharp
public int GetFailCubeCount()
```
#INC


#### Returns

**Type:** System.Int32

### GetFeelingState(int)

```csharp
public CreatureFeelingState GetFeelingState(int successCount)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `successCount` | `System.Int32` |  |

#### Returns

**Type:** Global.CreatureFeelingState

### GetMaxCubCount()

```csharp
public int GetMaxCubCount()
```
#INC


#### Returns

**Type:** System.Int32

### GetSuccessCubeCount()

```csharp
public int GetSuccessCubeCount()
```
#INC


#### Returns

**Type:** System.Int32

### HorrorDamage()

```csharp
private void HorrorDamage()
```
#INC


### InitUseSkillAction(SkillTypeInfo, AgentModel, CreatureModel)

```csharp
public static UseSkill InitUseSkillAction(SkillTypeInfo skillInfo, AgentModel agent, CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skillInfo` | `Global.SkillTypeInfo` |  |
| `agent` | `Global.AgentModel` |  |
| `creature` | `Global.CreatureModel` |  |

#### Returns

**Type:** Global.UseSkill

### InvokeEffect(UnitModel, DamageInfo)

```csharp
private void InvokeEffect(UnitModel target, DamageInfo damageInfo)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damageInfo` | `Global.DamageInfo` |  |

### IsFinished()

```csharp
public bool IsFinished()
```
#INC


#### Returns

**Type:** System.Boolean

### IsWorking()

```csharp
public bool IsWorking()
```
#INC


#### Returns

**Type:** System.Boolean

### OnEnterRoom()

```csharp
private void OnEnterRoom()
```
#INC


### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```
#INC
#code-generated


### OnWorkEndAnimPlayed()

```csharp
public void OnWorkEndAnimPlayed()
```
#INC


### PauseWorking()

```csharp
public void PauseWorking()
```
#INC


### ProcessKitCreatureWork()

```csharp
private void ProcessKitCreatureWork()
```
#INC


### ProcessWorkNarration()

```csharp
private void ProcessWorkNarration()
```
#INC


### ProcessWorkTick(out bool)

```csharp
private void ProcessWorkTick(out bool isSuccess)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isSuccess` | `System.Boolean` |  |

### ProgressWork()

```csharp
private void ProgressWork()
```
#INC


### ResumeWorking()

```csharp
public void ResumeWorking()
```
#INC


### SetForceSuccess()

```csharp
public void SetForceSuccess()
```
#INC

