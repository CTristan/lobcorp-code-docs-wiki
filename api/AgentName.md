# Class AgentName

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentName
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentName

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AgentName(AgentNameTypeInfo, int)

```csharp
public AgentName(AgentNameTypeInfo meta, int instId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `meta` | `Global.AgentNameTypeInfo` |  |
| `instId` | `System.Int32` |  |

### AgentName(int)

```csharp
public AgentName(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

## Fields

### canUse

```csharp
public bool canUse
```

#### Field Value

**Type:** System.Boolean

### id

```csharp
public int id
```

#### Field Value

**Type:** System.Int32

### instanceId

```csharp
public int instanceId
```

#### Field Value

**Type:** System.Int32

### isCredit

```csharp
public bool isCredit
```

#### Field Value

**Type:** System.Boolean

### isCustom

```csharp
public bool isCustom
```

#### Field Value

**Type:** System.Boolean

### isUsed

```csharp
public bool isUsed
```

#### Field Value

**Type:** System.Boolean

### metaInfo

```csharp
public AgentNameTypeInfo metaInfo
```

#### Field Value

**Type:** Global.AgentNameTypeInfo

### nameDic

```csharp
public Dictionary<string, string> nameDic
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

## Methods

### GetName()

```csharp
public string GetName()
```

#### Returns

**Type:** System.String

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### SetUseState(bool)

```csharp
public void SetUseState(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
