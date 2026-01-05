# Class SkillTriggerCheck

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkillTriggerCheck
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkillTriggerCheck

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SkillTriggerCheck()

```csharp
public SkillTriggerCheck()
```

## Fields

### onEnterRoom

```csharp
public List<SkillTrigger> onEnterRoom
```

#### Field Value

**Type:** System.Collections.Generic.List{SkillTrigger}

### onExitRoom

```csharp
public List<SkillTrigger> onExitRoom
```

#### Field Value

**Type:** System.Collections.Generic.List{SkillTrigger}

### total

```csharp
public List<SkillTrigger> total
```

#### Field Value

**Type:** System.Collections.Generic.List{SkillTrigger}

## Methods

### OnActivated()

```csharp
public void OnActivated()
```

### roomEnterCheck(UseSkill)

```csharp
public void roomEnterCheck(UseSkill skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### SetScript(CreatureBase)

```csharp
public void SetScript(CreatureBase script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.CreatureBase` |  |
