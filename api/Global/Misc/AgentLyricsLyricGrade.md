---
uid: Global.AgentLyrics.LyricGrade
canonical_path: /api/Global/Misc/AgentLyricsLyricGrade
---

# Class AgentLyrics.LyricGrade

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentLyrics.LyricGrade
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentLyrics.LyricGrade

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### LyricGrade()

```csharp
public LyricGrade()
```

## Fields

### _lyricLists

```csharp
private List<AgentLyrics.LyricList> _lyricLists
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentLyrics.LyricList}

### level

```csharp
public int level
```

#### Field Value

**Type:** System.Int32

## Methods

### AddItem(LyricList)

```csharp
public void AddItem(AgentLyrics.LyricList lyricList)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lyricList` | `Global.AgentLyrics.LyricList` |  |

### GetRandomLyric(RwbpType)

```csharp
public string GetRandomLyric(RwbpType rwbp)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rwbp` | `Global.RwbpType` |  |

#### Returns

**Type:** System.String
