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

#### Field Value

**Type:** System.Single

### _faceCreature

```csharp
private bool _faceCreature
```

#### Field Value

**Type:** System.Boolean

### _isOverloadedCreature

```csharp
private bool _isOverloadedCreature
```

#### Field Value

**Type:** System.Boolean

### _readyToFinish

```csharp
private bool _readyToFinish
```

#### Field Value

**Type:** System.Boolean

### agent

```csharp
public AgentModel agent
```

#### Field Value

**Type:** Global.AgentModel

### agentView

```csharp
public AgentUnit agentView
```

#### Field Value

**Type:** Global.AgentUnit

### animRemoveOnDestroy

```csharp
public bool animRemoveOnDestroy
```

#### Field Value

**Type:** System.Boolean

### closed

```csharp
private bool closed
```

#### Field Value

**Type:** System.Boolean

### CONFESS_ID

```csharp
private const int CONFESS_ID = 6
```

#### Field Value

**Type:** System.Int32

### failCount

```csharp
public int failCount
```

#### Field Value

**Type:** System.Int32

### forceSuccess

```csharp
private bool forceSuccess
```

#### Field Value

**Type:** System.Boolean

### IMPROVISE_ID

```csharp
private const int IMPROVISE_ID = 7
```

#### Field Value

**Type:** System.Int32

### KIT_WORK_ID

```csharp
private const int KIT_WORK_ID = 5
```

#### Field Value

**Type:** System.Int32

### maxCubeCount

```csharp
public int maxCubeCount
```

#### Field Value

**Type:** System.Int32

### narrationPart1

```csharp
public bool narrationPart1
```

#### Field Value

**Type:** System.Boolean

### narrationPart2

```csharp
public bool narrationPart2
```

#### Field Value

**Type:** System.Boolean

### narrationPart3

```csharp
public bool narrationPart3
```

#### Field Value

**Type:** System.Boolean

### narrationPart4

```csharp
public bool narrationPart4
```

#### Field Value

**Type:** System.Boolean

### room

```csharp
public IsolateRoom room
```

#### Field Value

**Type:** Global.IsolateRoom

### skillTypeInfo

```csharp
public SkillTypeInfo skillTypeInfo
```

#### Field Value

**Type:** Global.SkillTypeInfo

### startAgentHp

```csharp
public float startAgentHp
```

#### Field Value

**Type:** System.Single

### startAgentMental

```csharp
public float startAgentMental
```

#### Field Value

**Type:** System.Single

### successCount

```csharp
public int successCount
```

#### Field Value

**Type:** System.Int32

### targetCreature

```csharp
public CreatureModel targetCreature
```

#### Field Value

**Type:** Global.CreatureModel

### targetCreatureView

```csharp
public CreatureUnit targetCreatureView
```

#### Field Value

**Type:** Global.CreatureUnit

### tickInterval

```csharp
public float tickInterval
```

#### Field Value

**Type:** System.Single

### workCount

```csharp
public int workCount
```

#### Field Value

**Type:** System.Int32

### workPlaying

```csharp
private bool workPlaying
```

#### Field Value

**Type:** System.Boolean

### workProgress

```csharp
public float workProgress
```

#### Field Value

**Type:** System.Single

### workSpeed

```csharp
public float workSpeed
```

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

### CheckLive()

```csharp
public void CheckLive()
```

### CloseWork(bool)

```csharp
private void CloseWork(bool success)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `success` | `System.Boolean` |  |

### FinishWorkSuccessfully()

```csharp
private void FinishWorkSuccessfully()
```

### GetCurrentFeelingState()

```csharp
public CreatureFeelingState GetCurrentFeelingState()
```

#### Returns

**Type:** Global.CreatureFeelingState

### GetFailCubeCount()

```csharp
public int GetFailCubeCount()
```

#### Returns

**Type:** System.Int32

### GetFeelingState(int)

```csharp
public CreatureFeelingState GetFeelingState(int successCount)
```

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

#### Returns

**Type:** System.Int32

### GetSuccessCubeCount()

```csharp
public int GetSuccessCubeCount()
```

#### Returns

**Type:** System.Int32

### HorrorDamage()

```csharp
private void HorrorDamage()
```

### InitUseSkillAction(SkillTypeInfo, AgentModel, CreatureModel)

```csharp
public static UseSkill InitUseSkillAction(SkillTypeInfo skillInfo, AgentModel agent, CreatureModel creature)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damageInfo` | `Global.DamageInfo` |  |

### IsFinished()

```csharp
public bool IsFinished()
```

#### Returns

**Type:** System.Boolean

### IsWorking()

```csharp
public bool IsWorking()
```

#### Returns

**Type:** System.Boolean

### OnEnterRoom()

```csharp
private void OnEnterRoom()
```

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```

### OnWorkEndAnimPlayed()

```csharp
public void OnWorkEndAnimPlayed()
```

### PauseWorking()

```csharp
public void PauseWorking()
```

### ProcessKitCreatureWork()

```csharp
private void ProcessKitCreatureWork()
```

### ProcessWorkNarration()

```csharp
private void ProcessWorkNarration()
```

### ProcessWorkTick(out bool)

```csharp
private void ProcessWorkTick(out bool isSuccess)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isSuccess` | `System.Boolean` |  |

### ProgressWork()

```csharp
private void ProgressWork()
```

### ResumeWorking()

```csharp
public void ResumeWorking()
```

### SetForceSuccess()

```csharp
public void SetForceSuccess()
```
