---
uid: Global.AgentLyrics
canonical_path: /api/Global/Misc/AgentLyrics
---

# Class AgentLyrics

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentLyrics
```
Class for [agent](/api/Global/Worker/AgentUnit) yapping messages (and encounter/reaction text)

See [AgentSpeech](/api/Global/Misc/AgentSpeech)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentLyrics

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AgentLyrics()

```csharp
public AgentLyrics()
```

## Fields

### _instance

```csharp
private static AgentLyrics _instance
```
#INC


#### Field Value

**Type:** Global.AgentLyrics

### creatureRecation

```csharp
public Dictionary<long, AgentLyrics.CreatureReactionList> creatureRecation
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int64,AgentLyrics.CreatureReactionList}

### creditLyric

```csharp
public AgentLyrics.CreditLyric creditLyric
```

#### Field Value

**Type:** Global.AgentLyrics.CreditLyric

### horrorLyrics

```csharp
public AgentLyrics.LyricCategory horrorLyrics
```

#### Field Value

**Type:** Global.AgentLyrics.LyricCategory

### isLoaded

```csharp
private bool isLoaded
```
#INC


#### Field Value

**Type:** System.Boolean

### list

```csharp
public List<AgentLyrics.LyricList_old> list
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentLyrics.LyricList_old}

### normalLyrics

```csharp
public AgentLyrics.LyricCategory normalLyrics
```

#### Field Value

**Type:** Global.AgentLyrics.LyricCategory

### otherdeadLyrics

```csharp
public AgentLyrics.LyricCategory otherdeadLyrics
```

#### Field Value

**Type:** Global.AgentLyrics.LyricCategory

### otherpanicLyrics

```csharp
public AgentLyrics.LyricCategory otherpanicLyrics
```

#### Field Value

**Type:** Global.AgentLyrics.LyricCategory

### panicLyrics

```csharp
public AgentLyrics.LyricCategory panicLyrics
```

#### Field Value

**Type:** Global.AgentLyrics.LyricCategory

## Properties

### instance

```csharp
public static AgentLyrics instance { get; }
```

#### Property Value

**Type:** Global.AgentLyrics

## Methods

### GetCreatureReaction(long)

```csharp
public AgentLyrics.CreatureReactionList GetCreatureReaction(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.AgentLyrics.CreatureReactionList

### GetIdleLyricByDay(int)

```csharp
public AgentLyrics.LyricList_old GetIdleLyricByDay(int day)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `day` | `System.Int32` |  |

#### Returns

**Type:** Global.AgentLyrics.LyricList_old

### GetLyricByType(LyricType)

```csharp
public AgentLyrics.LyricList_old GetLyricByType(LyricType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.LyricType` |  |

#### Returns

**Type:** Global.AgentLyrics.LyricList_old

### GetLyricText(LyricTypeNew, int, RwbpType, int)

```csharp
public string GetLyricText(LyricTypeNew type, int level, RwbpType rwbp, int uniqueLyricIndex)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.LyricTypeNew` |  |
| `level` | `System.Int32` |  |
| `rwbp` | `Global.RwbpType` |  |
| `uniqueLyricIndex` | `System.Int32` |  |

#### Returns

**Type:** System.String

### Init(List<LyricList_old>, Dictionary<long, CreatureReactionList>, List<CreatureLyricList>)

```csharp
public void Init(List<AgentLyrics.LyricList_old> inputList, Dictionary<long, AgentLyrics.CreatureReactionList> dic, List<CreatureLyrics.CreatureLyricList> creature)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `inputList` | `System.Collections.Generic.List{AgentLyrics.LyricList_old}` |  |
| `dic` | `System.Collections.Generic.Dictionary{System.Int64,AgentLyrics.CreatureReactionList}` |  |
| `creature` | `System.Collections.Generic.List{CreatureLyrics.CreatureLyricList}` |  |

### InitLyrics(LyricCategory, LyricCategory, LyricCategory, LyricCategory, LyricCategory)

```csharp
public void InitLyrics(AgentLyrics.LyricCategory normal, AgentLyrics.LyricCategory panic, AgentLyrics.LyricCategory horror, AgentLyrics.LyricCategory otherdead, AgentLyrics.LyricCategory otherpanic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `normal` | `Global.AgentLyrics.LyricCategory` |  |
| `panic` | `Global.AgentLyrics.LyricCategory` |  |
| `horror` | `Global.AgentLyrics.LyricCategory` |  |
| `otherdead` | `Global.AgentLyrics.LyricCategory` |  |
| `otherpanic` | `Global.AgentLyrics.LyricCategory` |  |

### IsLoaded()

```csharp
public bool IsLoaded()
```
#INC


#### Returns

**Type:** System.Boolean
