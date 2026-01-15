---
uid: Global.AgentLyrics.CreatureReactionList
canonical_path: /api/Global/List/AgentLyricsCreatureReactionList
---

# Class AgentLyrics.CreatureReactionList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentLyrics.CreatureReactionList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentLyrics.CreatureReactionList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureReactionList()

```csharp
public CreatureReactionList()
```

## Fields

### action

```csharp
public AgentLyrics.CreatureAction action
```

#### Field Value

**Type:** Global.AgentLyrics.CreatureAction

### creatureId

```csharp
public long creatureId
```

#### Field Value

**Type:** System.Int64

### lib

```csharp
public List<AgentLyrics.CreatureReaction> lib
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentLyrics.CreatureReaction}

## Methods

### GetDesc(int)

```csharp
public string GetDesc(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.String

### GetReaction(int)

```csharp
public AgentLyrics.CreatureReaction GetReaction(int level)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** Global.AgentLyrics.CreatureReaction
