# Class StageRewardTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StageRewardTypeInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StageRewardTypeInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### StageRewardTypeInfo()

```csharp
public StageRewardTypeInfo()
```

## Fields

### agentList

```csharp
public List<StageRewardTypeInfo.AgentRewardInfo> agentList
```

#### Field Value

**Type:** System.Collections.Generic.List{StageRewardTypeInfo.AgentRewardInfo}

### day

```csharp
public int day
```

#### Field Value

**Type:** System.Int32

### money

```csharp
public int money
```

#### Field Value

**Type:** System.Int32

### rankLimit

```csharp
public int rankLimit
```

#### Field Value

**Type:** System.Int32

## Methods

### GenerateRankLimit()

```csharp
public void GenerateRankLimit()
```

### GetLimitTime(StageRank)

```csharp
public float GetLimitTime(StageRank rank)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rank` | `Global.StageRank` |  |

#### Returns

**Type:** System.Single

### GetRewardMoney(float)

```csharp
public int GetRewardMoney(float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

#### Returns

**Type:** System.Int32

### GetStageRank(float)

```csharp
public StageRank GetStageRank(float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

#### Returns

**Type:** Global.StageRank

### MakeChallengeModeReward()

```csharp
public static StageRewardTypeInfo MakeChallengeModeReward()
```

#### Returns

**Type:** Global.StageRewardTypeInfo
