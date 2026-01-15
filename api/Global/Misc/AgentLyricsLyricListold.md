---
uid: Global.AgentLyrics.LyricList_old
canonical_path: /api/Global/Misc/AgentLyricsLyricListold
---

# Class AgentLyrics.LyricList_old

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentLyrics.LyricList_old
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentLyrics.LyricList_old

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### LyricList_old(LyricType, AgentLyric[], int, int)

```csharp
public LyricList_old(LyricType type, AgentLyrics.AgentLyric[] ary, int danger, int inner)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.LyricType` |  |
| `ary` | `Global.AgentLyrics.AgentLyric[]` |  |
| `danger` | `System.Int32` |  |
| `inner` | `System.Int32` |  |

### LyricList_old(LyricType, List<AgentLyric>)

```csharp
public LyricList_old(LyricType type, List<AgentLyrics.AgentLyric> list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.LyricType` |  |
| `list` | `System.Collections.Generic.List{AgentLyrics.AgentLyric}` |  |

## Fields

### dangerLevel

```csharp
public int dangerLevel
```

#### Field Value

**Type:** System.Int32

### innerLevel

```csharp
public int innerLevel
```

#### Field Value

**Type:** System.Int32

### list

```csharp
public List<AgentLyrics.AgentLyric> list
```

#### Field Value

**Type:** System.Collections.Generic.List{AgentLyrics.AgentLyric}

### type

```csharp
public LyricType type
```

#### Field Value

**Type:** Global.LyricType

## Methods

### GetAllLyrics()

```csharp
public List<AgentLyrics.AgentLyric> GetAllLyrics()
```

#### Returns

**Type:** System.Collections.Generic.List{AgentLyrics.AgentLyric}

### GetRandomLyric()

```csharp
public AgentLyrics.AgentLyric GetRandomLyric()
```

#### Returns

**Type:** Global.AgentLyrics.AgentLyric

### GetUniqueLyricById(int)

```csharp
public AgentLyrics.AgentLyric GetUniqueLyricById(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** Global.AgentLyrics.AgentLyric

### GetUniqueLyricByIndex(int)

```csharp
public AgentLyrics.AgentLyric GetUniqueLyricByIndex(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.AgentLyrics.AgentLyric
