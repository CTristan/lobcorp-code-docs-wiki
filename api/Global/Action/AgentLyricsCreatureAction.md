---
uid: Global.AgentLyrics.CreatureAction
canonical_path: /api/Global/Action/AgentLyricsCreatureAction
---

# Class AgentLyrics.CreatureAction

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentLyrics.CreatureAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentLyrics.CreatureAction

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureAction()

```csharp
public CreatureAction()
```

## Fields

### creatureId

```csharp
public long creatureId
```

#### Field Value

**Type:** System.Int64

### lib

```csharp
public Dictionary<string, AgentLyrics.CreatureNormal> lib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,AgentLyrics.CreatureNormal}

## Methods

### GetActionDesc(string)

```csharp
public AgentLyrics.CreatureNormal GetActionDesc(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** Global.AgentLyrics.CreatureNormal
