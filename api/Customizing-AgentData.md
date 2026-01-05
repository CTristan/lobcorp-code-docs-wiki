# Class AgentData

**Namespace:** [Customizing](/api/Customizing)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AgentData()

```csharp
public AgentData()
```

## Fields

### agentName

```csharp
public AgentName agentName
```

#### Field Value

**Type:** Global.AgentName

### appearance

```csharp
public Appearance appearance
```

#### Field Value

**Type:** Customizing.Appearance

### CustomName

```csharp
public string CustomName
```

#### Field Value

**Type:** System.String

### isCustomAppearance

```csharp
public bool isCustomAppearance
```

#### Field Value

**Type:** System.Boolean

### isCustomName

```csharp
public bool isCustomName
```

#### Field Value

**Type:** System.Boolean

### isStatBonusAdded

```csharp
public bool isStatBonusAdded
```

#### Field Value

**Type:** System.Boolean

### isUniqueCredit

```csharp
public bool isUniqueCredit
```

#### Field Value

**Type:** System.Boolean

### originalModel

```csharp
public AgentModel originalModel
```

#### Field Value

**Type:** Global.AgentModel

### stat

```csharp
public WorkerPrimaryStat stat
```

#### Field Value

**Type:** Global.WorkerPrimaryStat

### statBonus

```csharp
public StatBonus statBonus
```

#### Field Value

**Type:** Customizing.StatBonus

### uniqueScriptIndex

```csharp
public int uniqueScriptIndex
```

#### Field Value

**Type:** System.Int32

## Properties

### BLevel

```csharp
public int BLevel { get; }
```

#### Property Value

**Type:** System.Int32

### PLevel

```csharp
public int PLevel { get; }
```

#### Property Value

**Type:** System.Int32

### RLevel

```csharp
public int RLevel { get; }
```

#### Property Value

**Type:** System.Int32

### WLevel

```csharp
public int WLevel { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### AppearCopy(AgentData)

```csharp
public void AppearCopy(AgentData copied)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `copied` | `Customizing.AgentData` |  |

### GetVanliaLevel()

```csharp
public int GetVanliaLevel()
```

#### Returns

**Type:** System.Int32
