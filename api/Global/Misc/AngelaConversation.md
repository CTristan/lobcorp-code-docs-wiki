---
uid: Global.AngelaConversation
canonical_path: /api/Global/Misc/AngelaConversation
---

# Class AngelaConversation

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AngelaConversation
```
Angela's yapping handler

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AngelaConversation

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AngelaConversation()

```csharp
private AngelaConversation()
```
#INC
#code-generated


## Fields

### _instance

```csharp
private static AngelaConversation _instance
```
#INC


#### Field Value

**Type:** Global.AngelaConversation

### agentDeadTimer

```csharp
public Timer agentDeadTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### isLoaded

```csharp
private bool isLoaded
```
#INC


#### Field Value

**Type:** System.Boolean

### messageLib

```csharp
public AngelaMessageLib messageLib
```
#INC


#### Field Value

**Type:** Global.AngelaMessageLib

## Properties

### instance

```csharp
public static AngelaConversation instance { get; }
```

#### Property Value

**Type:** Global.AngelaConversation

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### DeplayedGreeting()

```csharp
public void DeplayedGreeting()
```
#INC


### DeplayedMessage()

```csharp
public void DeplayedMessage()
```
#INC


### GetAngelaMessageState(int)

```csharp
public static AngelaMessageState GetAngelaMessageState(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.AngelaMessageState

### Init(AngelaMessage[])

```csharp
public void Init(AngelaMessage[] ary)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ary` | `Global.AngelaMessage[]` |  |

### MakeDefaultFormatMessage(AngelaMessageState, params object[])

```csharp
public string MakeDefaultFormatMessage(AngelaMessageState state, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.AngelaMessageState` |  |
| `param` | `System.Object[]` |  |

#### Returns

**Type:** System.String

### MakeDefaultMessage(AngelaMessageState, bool, bool, params object[])

```csharp
public string MakeDefaultMessage(AngelaMessageState state, bool writeLog, bool angelaNarrate, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.AngelaMessageState` |  |
| `writeLog` | `System.Boolean` |  |
| `angelaNarrate` | `System.Boolean` |  |
| `param` | `System.Object[]` |  |

#### Returns

**Type:** System.String

### MakeDetailMessage(AngelaMessageState, bool, bool, params object[])

```csharp
public string MakeDetailMessage(AngelaMessageState state, bool writeLog, bool angelaNarrate, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.AngelaMessageState` |  |
| `writeLog` | `System.Boolean` |  |
| `angelaNarrate` | `System.Boolean` |  |
| `param` | `System.Object[]` |  |

#### Returns

**Type:** System.String

### MakeMessage(AngelaMessageState, params object[])

```csharp
public string MakeMessage(AngelaMessageState state, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.AngelaMessageState` |  |
| `param` | `System.Object[]` |  |

#### Returns

**Type:** System.String

### RefineAgentName(string, AgentModel)

```csharp
public string RefineAgentName(string origin, AgentModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `target` | `Global.AgentModel` |  |

#### Returns

**Type:** System.String

### RefineAgentName(string, List<AgentModel>)

```csharp
public string RefineAgentName(string origin, List<AgentModel> list)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `list` | `System.Collections.Generic.List{AgentModel}` |  |

#### Returns

**Type:** System.String

### RefineCreatureName(string, CreatureModel)

```csharp
public string RefineCreatureName(string origin, CreatureModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `target` | `Global.CreatureModel` |  |

#### Returns

**Type:** System.String

### RefineCreatureName(string, List<CreatureModel>)

```csharp
public string RefineCreatureName(string origin, List<CreatureModel> list)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `list` | `System.Collections.Generic.List{CreatureModel}` |  |

#### Returns

**Type:** System.String

### RefineMessage(string, out CreatureModel, params object[])

```csharp
public string RefineMessage(string origin, out CreatureModel model, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `model` | `Global.CreatureModel` |  |
| `param` | `System.Object[]` |  |

#### Returns

**Type:** System.String

### RefineNarrationText(string, UseSkill)

```csharp
public string RefineNarrationText(string origin, UseSkill skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `skill` | `Global.UseSkill` |  |

#### Returns

**Type:** System.String

### RefineOfficerName(string, List<OfficerModel>)

```csharp
public string RefineOfficerName(string origin, List<OfficerModel> list)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `list` | `System.Collections.Generic.List{OfficerModel}` |  |

#### Returns

**Type:** System.String

### RefineSefiraName(string, List<Sefira>)

```csharp
public string RefineSefiraName(string origin, List<Sefira> target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `target` | `System.Collections.Generic.List{Sefira}` |  |

#### Returns

**Type:** System.String

### RefineSefiraName(string, Sefira)

```csharp
public string RefineSefiraName(string origin, Sefira target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `target` | `Global.Sefira` |  |

#### Returns

**Type:** System.String

### RefineSkillName(string, List<SkillTypeInfo>)

```csharp
public string RefineSkillName(string origin, List<SkillTypeInfo> list)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `list` | `System.Collections.Generic.List{SkillTypeInfo}` |  |

#### Returns

**Type:** System.String

### RefineSkillName(string, SkillTypeInfo)

```csharp
public string RefineSkillName(string origin, SkillTypeInfo target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `target` | `Global.SkillTypeInfo` |  |

#### Returns

**Type:** System.String

### RefineSkillOriginName(string, List<SkillTypeInfo>)

```csharp
public string RefineSkillOriginName(string origin, List<SkillTypeInfo> list)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `list` | `System.Collections.Generic.List{SkillTypeInfo}` |  |

#### Returns

**Type:** System.String

### RefineSkillOriginName(string, SkillTypeInfo)

```csharp
public string RefineSkillOriginName(string origin, SkillTypeInfo target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `origin` | `System.String` |  |
| `target` | `Global.SkillTypeInfo` |  |

#### Returns

**Type:** System.String

### SendNarrationLogMessage(CreatureModel, string)

```csharp
public void SendNarrationLogMessage(CreatureModel model, string desc)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |
| `desc` | `System.String` |  |

### SendSystemLogMessage(CreatureModel, string)

```csharp
public void SendSystemLogMessage(CreatureModel cm, string desc)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cm` | `Global.CreatureModel` |  |
| `desc` | `System.String` |  |
