---
uid: Global.AgentName
canonical_path: /api/Global/Misc/AgentName
---

# Class AgentName

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentName : ISerializablePlayData
```

Represents an [agent](/api/Global/Worker/AgentModel)'s name

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentName

## Implements
[ISerializablePlayData](/api/Global/Misc/ISerializablePlayData)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentName(AgentNameTypeInfo, int)

```csharp
public AgentName(AgentNameTypeInfo meta, int instId)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `meta` | `Global.AgentNameTypeInfo` |  |
| `instId` | `System.Int32` |  |

### AgentName(int)

```csharp
public AgentName(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

## Fields

### canUse

```csharp
public bool canUse
```
#INC


#### Field Value

**Type:** System.Boolean

### id

```csharp
public int id
```
#INC


#### Field Value

**Type:** System.Int32

### instanceId

```csharp
public int instanceId
```
#INC


#### Field Value

**Type:** System.Int32

### isCredit

```csharp
public bool isCredit
```
#INC


#### Field Value

**Type:** System.Boolean

### isCustom

```csharp
public bool isCustom
```
#INC


#### Field Value

**Type:** System.Boolean

### isUsed

```csharp
public bool isUsed
```
#INC


#### Field Value

**Type:** System.Boolean

### metaInfo

```csharp
public AgentNameTypeInfo metaInfo
```
#INC


#### Field Value

**Type:** Global.AgentNameTypeInfo

### nameDic

```csharp
public Dictionary<string, string> nameDic
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

## Methods

### GetName()

```csharp
public string GetName()
```
#INC


#### Returns

**Type:** System.String

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### SetUseState(bool)

```csharp
public void SetUseState(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### ToString()

```csharp
public override string ToString()
```
#INC
#code-generated


#### Returns

**Type:** System.String
