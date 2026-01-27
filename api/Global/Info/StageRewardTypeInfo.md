---
uid: Global.StageRewardTypeInfo
canonical_path: /api/Global/Info/StageRewardTypeInfo
---

# Class StageRewardTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StageRewardTypeInfo
```
Stores the LOB reward for the day and which agents were promoted #verify .


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StageRewardTypeInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StageRewardTypeInfo()

```csharp
public StageRewardTypeInfo()
```
#INC
#code-generated


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
#INC


#### Field Value

**Type:** System.Int32

### money

```csharp
public int money
```
#INC


#### Field Value

**Type:** System.Int32

### rankLimit

```csharp
public int rankLimit
```
#INC


#### Field Value

**Type:** System.Int32

## Methods

### GenerateRankLimit()

```csharp
public void GenerateRankLimit()
```
#INC


### GetLimitTime(StageRank)

```csharp
public float GetLimitTime(StageRank rank)
```
#INC


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
#INC


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
#INC


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
#INC


#### Returns

**Type:** Global.StageRewardTypeInfo
