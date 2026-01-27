---
uid: Global.CreatureLyrics
canonical_path: /api/Global/Misc/CreatureLyrics
---

# Class CreatureLyrics

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureLyrics
```
Text for abnormalities which yap. Like Queen of Hatred.

See [CreatureSpeech](/api/Global/Misc/CreatureSpeech)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureLyrics

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureLyrics()

```csharp
public CreatureLyrics()
```

## Fields

### _instance

```csharp
private static CreatureLyrics _instance
```
#INC


#### Field Value

**Type:** Global.CreatureLyrics

### lib

```csharp
private Dictionary<long, CreatureLyrics.CreatureLyricList> lib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int64,CreatureLyrics.CreatureLyricList}

## Properties

### instnace

```csharp
public static CreatureLyrics instnace { get; }
```

#### Property Value

**Type:** Global.CreatureLyrics

### isLoaded

```csharp
public bool isLoaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### AddCreatureLyricList(CreatureLyricList)

```csharp
public void AddCreatureLyricList(CreatureLyrics.CreatureLyricList list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `Global.CreatureLyrics.CreatureLyricList` |  |

### GetCreatureLyricList(long)

```csharp
public CreatureLyrics.CreatureLyricList GetCreatureLyricList(long id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** Global.CreatureLyrics.CreatureLyricList

### GetRandomLyricByKey(long, string)

```csharp
public string GetRandomLyricByKey(long creatureId, string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creatureId` | `System.Int64` |  |
| `key` | `System.String` |  |

#### Returns

**Type:** System.String

### Init(CreatureLyricList[])

```csharp
public void Init(CreatureLyrics.CreatureLyricList[] ary)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ary` | `Global.CreatureLyrics.CreatureLyricList[]` |  |
