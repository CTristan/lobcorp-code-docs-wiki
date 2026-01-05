# Class StoryMemoryManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StoryMemoryManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StoryMemoryManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### StoryMemoryManager()

```csharp
public StoryMemoryManager()
```

## Properties

### instance

```csharp
public static StoryMemoryManager instance { get; }
```

#### Property Value

**Type:** Global.StoryMemoryManager

## Methods

### GetUnlockedDayStoryList()

```csharp
public List<string> GetUnlockedDayStoryList()
```

#### Returns

**Type:** System.Collections.Generic.List{System.String}

### GetUnlockedSeedStoryList()

```csharp
public List<string> GetUnlockedSeedStoryList()
```

#### Returns

**Type:** System.Collections.Generic.List{System.String}

### GetUnlockedSefiraStoryList(SefiraEnum)

```csharp
public List<string> GetUnlockedSefiraStoryList(SefiraEnum sefira)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.SefiraEnum` |  |

#### Returns

**Type:** System.Collections.Generic.List{System.String}
