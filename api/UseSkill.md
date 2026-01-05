# Class UseSkill

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UseSkill
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → UseSkill

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### UseSkill()

```csharp
public UseSkill()
```

## Fields

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

### failCount

```csharp
public int failCount
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

### CancelWork()

```csharp
public void CancelWork()
```

### CheckLive()

```csharp
public void CheckLive()
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

### ResumeWorking()

```csharp
public void ResumeWorking()
```

### SetForceSuccess()

```csharp
public void SetForceSuccess()
```
