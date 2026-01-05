# Class AgentTitleTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentTitleTypeList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentTitleTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AgentTitleTypeList()

```csharp
public AgentTitleTypeList()
```

## Properties

### instance

```csharp
public static AgentTitleTypeList instance { get; }
```

#### Property Value

**Type:** Global.AgentTitleTypeList

## Methods

### GetData(int)

```csharp
public AgentTitleTypeInfo GetData(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.AgentTitleTypeInfo

### GetDataPrefix(AgentModel, int, bool)

```csharp
public AgentTitleTypeInfo GetDataPrefix(AgentModel agent, int level, bool randomly = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |
| `level` | `System.Int32` |  |
| `randomly` | `System.Boolean` |  |

#### Returns

**Type:** Global.AgentTitleTypeInfo

### GetDataSuffix(AgentModel, int, bool)

```csharp
public AgentTitleTypeInfo GetDataSuffix(AgentModel agent, int level, bool randomly = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |
| `level` | `System.Int32` |  |
| `randomly` | `System.Boolean` |  |

#### Returns

**Type:** Global.AgentTitleTypeInfo

### Init(List<AgentTitleTypeInfo>)

```csharp
public void Init(List<AgentTitleTypeInfo> list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.Generic.List{AgentTitleTypeInfo}` |  |
