---
uid: CommandWindow.WorkData
canonical_path: /api/CommandWindow/WorkData
---

# Class WorkData

**Namespace:** [CommandWindow](/api/CommandWindow)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkData
```
Stores the information for an employee's work (e.g., work type, speed, success rate).

See also [ManagementSlot](/api/CommandWindow/ManagementSlot)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkData()

```csharp
public WorkData()
```

## Fields

### _current

```csharp
private SkillTypeInfo _current
```
#INC


#### Field Value

**Type:** Global.SkillTypeInfo

### _currentAgent

```csharp
private AgentModel _currentAgent
```
#INC


#### Field Value

**Type:** Global.AgentModel

### _currentCreature

```csharp
private CreatureModel _currentCreature
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### BLevel

```csharp
public Image BLevel
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### PLevel

```csharp
public Image PLevel
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### prefix

```csharp
private static string prefix
```
#INC


#### Field Value

**Type:** System.String

### region

```csharp
private static string[] region
```
#INC


#### Field Value

**Type:** System.String[]

### RLevel

```csharp
[Header("Stat Level")]
public Image RLevel
```

#### Field Value

**Type:** UnityEngine.UI.Image

### WLevel

```csharp
public Image WLevel
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### WorkIcon

```csharp
public Image WorkIcon
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### WorkLevel

```csharp
public Text WorkLevel
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### WorkSpeed

```csharp
public Text WorkSpeed
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### WorkSuccess

```csharp
public Text WorkSuccess
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

## Methods

### CheckCurrentSkill()

```csharp
public void CheckCurrentSkill()
```
#INC


### SetCreature(CreatureModel)

```csharp
public void SetCreature(CreatureModel creature)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### SetCurrentWork(SkillTypeInfo)

```csharp
public void SetCurrentWork(SkillTypeInfo current)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `current` | `Global.SkillTypeInfo` |  |

### SetData(AgentModel)

```csharp
public void SetData(AgentModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.AgentModel` |  |
