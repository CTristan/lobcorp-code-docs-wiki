---
uid: Global.StoryMemoryManager
canonical_path: /api/Global/Story/StoryMemoryManager
---

# Class StoryMemoryManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StoryMemoryManager
```
Keeps track of which stories should be unlocked on this save file, for the story viewer.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StoryMemoryManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StoryMemoryManager()

```csharp
public StoryMemoryManager()
```

## Fields

### _filename

```csharp
private const string _filename = "saveStory.dat"
```
#INC


#### Field Value

**Type:** System.String

### _instance

```csharp
private static StoryMemoryManager _instance
```
#INC


#### Field Value

**Type:** Global.StoryMemoryManager

### _saveVer

```csharp
private const string _saveVer = "story1"
```
#INC


#### Field Value

**Type:** System.String

### _unlockedStorySet

```csharp
private HashSet<string> _unlockedStorySet
```
#INC


#### Field Value

**Type:** System.Collections.Generic.HashSet{System.String}

## Properties

### instance

```csharp
public static StoryMemoryManager instance { get; }
```

#### Property Value

**Type:** Global.StoryMemoryManager

### saveFileName

```csharp
private string saveFileName { get; }
```

#### Property Value

**Type:** System.String

## Methods

### GetUnlockedDayStoryList()

```csharp
public List<string> GetUnlockedDayStoryList()
```
#INC
#code-generated


#### Returns

**Type:** System.Collections.Generic.List{System.String}

### GetUnlockedSeedStoryList()

```csharp
public List<string> GetUnlockedSeedStoryList()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{System.String}

### GetUnlockedSefiraStoryList(SefiraEnum)

```csharp
public List<string> GetUnlockedSefiraStoryList(SefiraEnum sefira)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Collections.Generic.List{System.String}
