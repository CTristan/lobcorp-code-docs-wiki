---
uid: Global.CreatureLyrics.CreatureLyricList
canonical_path: /api/Global/List/CreatureLyricsCreatureLyricList
---

# Class CreatureLyrics.CreatureLyricList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureLyrics.CreatureLyricList
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureLyrics.CreatureLyricList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureLyricList(long, CreatureLyric[])

```csharp
public CreatureLyricList(long id, CreatureLyrics.CreatureLyric[] ary)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
| `ary` | `Global.CreatureLyrics.CreatureLyric[]` |  |

## Fields

### creatureId

```csharp
public long creatureId
```

#### Field Value

**Type:** System.Int64

### lib

```csharp
public Dictionary<string, CreatureLyrics.CreatureLyric> lib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,CreatureLyrics.CreatureLyric}

## Methods

### GetCreatureLyric(string)

```csharp
public CreatureLyrics.CreatureLyric GetCreatureLyric(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** Global.CreatureLyrics.CreatureLyric

### GetRandomDescByKey(string)

```csharp
public string GetRandomDescByKey(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String
