---
uid: Global.AgentTitleTypeList
canonical_path: /api/Global/List/AgentTitleTypeList
---

# Class AgentTitleTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentTitleTypeList
```
Maintains titles for [agents](/api/Global/Worker/AgentModel).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentTitleTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentTitleTypeList()

```csharp
public AgentTitleTypeList()
```

## Fields

### _instance

```csharp
private static AgentTitleTypeList _instance
```
#INC


#### Field Value

**Type:** Global.AgentTitleTypeList

### _list

```csharp
private List<AgentTitleTypeInfo> _list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{AgentTitleTypeInfo}

## Properties

### instance

```csharp
public static AgentTitleTypeList instance { get; }
```

#### Property Value

**Type:** Global.AgentTitleTypeList

## Methods

### GetData(AgentModel, int, string, bool)

```csharp
private AgentTitleTypeInfo GetData(AgentModel agent, int level, string pos, bool randomly = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |
| `level` | `System.Int32` |  |
| `pos` | `System.String` |  |
| `randomly` | `System.Boolean` |  |

#### Returns

**Type:** Global.AgentTitleTypeInfo

### GetData(int)

```csharp
public AgentTitleTypeInfo GetData(int id)
```
#INC


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
#INC


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
#INC


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
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.Generic.List{AgentTitleTypeInfo}` |  |
