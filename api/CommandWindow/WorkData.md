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

#### Field Value

**Type:** Global.SkillTypeInfo

### _currentAgent

```csharp
private AgentModel _currentAgent
```

#### Field Value

**Type:** Global.AgentModel

### _currentCreature

```csharp
private CreatureModel _currentCreature
```

#### Field Value

**Type:** Global.CreatureModel

### BLevel

```csharp
public Image BLevel
```

#### Field Value

**Type:** UnityEngine.UI.Image

### PLevel

```csharp
public Image PLevel
```

#### Field Value

**Type:** UnityEngine.UI.Image

### prefix

```csharp
private static string prefix
```

#### Field Value

**Type:** System.String

### region

```csharp
private static string[] region
```

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

#### Field Value

**Type:** UnityEngine.UI.Image

### WorkIcon

```csharp
public Image WorkIcon
```

#### Field Value

**Type:** UnityEngine.UI.Image

### WorkLevel

```csharp
public Text WorkLevel
```

#### Field Value

**Type:** UnityEngine.UI.Text

### WorkSpeed

```csharp
public Text WorkSpeed
```

#### Field Value

**Type:** UnityEngine.UI.Text

### WorkSuccess

```csharp
public Text WorkSuccess
```

#### Field Value

**Type:** UnityEngine.UI.Text

## Methods

### CheckCurrentSkill()

```csharp
public void CheckCurrentSkill()
```

### SetCreature(CreatureModel)

```csharp
public void SetCreature(CreatureModel creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### SetCurrentWork(SkillTypeInfo)

```csharp
public void SetCurrentWork(SkillTypeInfo current)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `current` | `Global.SkillTypeInfo` |  |

### SetData(AgentModel)

```csharp
public void SetData(AgentModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.AgentModel` |  |
