# Class Mission

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Mission
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Mission

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Mission()

```csharp
public Mission()
```

### Mission(MissionTypeInfo)

```csharp
public Mission(MissionTypeInfo metadata)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metadata` | `Global.MissionTypeInfo` |  |

## Fields

### baseConditions

```csharp
public List<Condition> baseConditions
```

#### Field Value

**Type:** System.Collections.Generic.List{Condition}

### checkedObjects

```csharp
public List<object> checkedObjects
```

#### Field Value

**Type:** System.Collections.Generic.List{System.Object}

### conditions

```csharp
public List<Condition> conditions
```

#### Field Value

**Type:** System.Collections.Generic.List{Condition}

### doneConditions

```csharp
public List<bool> doneConditions
```

#### Field Value

**Type:** System.Collections.Generic.List{System.Boolean}

### failConditions

```csharp
public List<Condition> failConditions
```

#### Field Value

**Type:** System.Collections.Generic.List{Condition}

### isCleared

```csharp
public bool isCleared
```

#### Field Value

**Type:** System.Boolean

### isInProcess

```csharp
public bool isInProcess
```

#### Field Value

**Type:** System.Boolean

### metaInfo

```csharp
public MissionTypeInfo metaInfo
```

#### Field Value

**Type:** Global.MissionTypeInfo

### successCondition

```csharp
public Condition successCondition
```

#### Field Value

**Type:** Global.Condition

## Properties

### isGlobal

```csharp
public bool isGlobal { get; }
```

#### Property Value

**Type:** System.Boolean

### sefira_Name

```csharp
public string sefira_Name { get; }
```

#### Property Value

**Type:** System.String

## Methods

### CheckConditions(string, params object[])

```csharp
public void CheckConditions(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### Init(MissionTypeInfo)

```csharp
public void Init(MissionTypeInfo metadata)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metadata` | `Global.MissionTypeInfo` |  |

### LoadData(Dictionary<string, object>)

```csharp
public void LoadData(Dictionary<string, object> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### OnDisabled()

```csharp
public void OnDisabled()
```

### OnEnabled()

```csharp
public void OnEnabled()
```
