# Class DeployAgentList.AgentSortData

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeployAgentList.AgentSortData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DeployAgentList.AgentSortData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AgentSortData()

```csharp
public AgentSortData()
```

## Fields

### currentGender

```csharp
public DeployAgentList.AgentSortData.GenderType currentGender
```

#### Field Value

**Type:** Global.DeployAgentList.AgentSortData.GenderType

### currentLevelOrder

```csharp
public DeployAgentList.AgentSortData.LevelType currentLevelOrder
```

#### Field Value

**Type:** Global.DeployAgentList.AgentSortData.LevelType

### currentMainSort

```csharp
public DeployAgentList.AgentSortData.MainSortType currentMainSort
```

#### Field Value

**Type:** Global.DeployAgentList.AgentSortData.MainSortType

### currentPersonality

```csharp
public PersonalityType currentPersonality
```

#### Field Value

**Type:** Global.PersonalityType

## Methods

### ChangeSortType(SortExecuteData)

```csharp
public void ChangeSortType(DeployAgentList.SortExecuteData data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Global.DeployAgentList.SortExecuteData` |  |

### Init()

```csharp
public void Init()
```

### SetSortEvent(SortAction)

```csharp
public void SetSortEvent(DeployAgentList.AgentSortData.SortAction sort)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sort` | `Global.DeployAgentList.AgentSortData.SortAction` |  |

### SetSortSetting()

```csharp
public void SetSortSetting()
```
