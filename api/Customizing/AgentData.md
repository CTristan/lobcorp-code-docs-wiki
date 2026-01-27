---
uid: Customizing.AgentData
canonical_path: /api/Customizing/AgentData
---

# Class AgentData

**Namespace:** [Customizing](/api/Customizing)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentData
```
Stores a (potential?) agent's name, stats, and appearance (possibly customized).

Has a section for copying appearance? o_o

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentData()

```csharp
public AgentData()
```
#INC
#code-generated


## Fields

### agentName

```csharp
public AgentName agentName
```
#INC


#### Field Value

**Type:** Global.AgentName

### appearance

```csharp
public Appearance appearance
```
#INC


#### Field Value

**Type:** Customizing.Appearance

### CustomName

```csharp
public string CustomName
```
#INC


#### Field Value

**Type:** System.String

### isCustomAppearance

```csharp
public bool isCustomAppearance
```
#INC


#### Field Value

**Type:** System.Boolean

### isCustomName

```csharp
public bool isCustomName
```
#INC


#### Field Value

**Type:** System.Boolean

### isStatBonusAdded

```csharp
public bool isStatBonusAdded
```
#INC


#### Field Value

**Type:** System.Boolean

### isUniqueCredit

```csharp
public bool isUniqueCredit
```
#INC


#### Field Value

**Type:** System.Boolean

### originalModel

```csharp
public AgentModel originalModel
```
#INC


#### Field Value

**Type:** Global.AgentModel

### stat

```csharp
public WorkerPrimaryStat stat
```
#INC


#### Field Value

**Type:** Global.WorkerPrimaryStat

### statBonus

```csharp
public StatBonus statBonus
```
#INC


#### Field Value

**Type:** Customizing.StatBonus

### uniqueScriptIndex

```csharp
public int uniqueScriptIndex
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `copied` | `Customizing.AgentData` |  |

### GetVanliaLevel()

```csharp
public int GetVanliaLevel()
```
#INC


#### Returns

**Type:** System.Int32
