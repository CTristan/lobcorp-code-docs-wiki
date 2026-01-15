---
uid: Global.DeployAgentList.AgentSortData
canonical_path: /api/Global/Misc/DeployAgentListAgentSortData
---

# Class DeployAgentList.AgentSortData

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeployAgentList.AgentSortData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DeployAgentList.AgentSortData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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

### sort

```csharp
private DeployAgentList.AgentSortData.SortAction sort
```

#### Field Value

**Type:** Global.DeployAgentList.AgentSortData.SortAction

## Methods

### ChangeMainSort()

```csharp
private void ChangeMainSort()
```

### ChangeSortType(SortExecuteData)

```csharp
public void ChangeSortType(DeployAgentList.SortExecuteData data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Global.DeployAgentList.SortExecuteData` |  |

### GenderExecute()

```csharp
private void GenderExecute()
```

### Init()

```csharp
public void Init()
```

### LevelExecute()

```csharp
private void LevelExecute()
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

### ValueExecute()

```csharp
private void ValueExecute()
```
