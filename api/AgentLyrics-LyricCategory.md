# Class AgentLyrics.LyricCategory

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentLyrics.LyricCategory
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentLyrics.LyricCategory

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### LyricCategory()

```csharp
public LyricCategory()
```

## Fields

### type

```csharp
public string type
```

#### Field Value

**Type:** System.String

## Methods

### AddItem(LyricGrade)

```csharp
public void AddItem(AgentLyrics.LyricGrade grade)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `grade` | `Global.AgentLyrics.LyricGrade` |  |

### GetRandomLyric(int, RwbpType)

```csharp
public string GetRandomLyric(int level, RwbpType rwbp)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |
| `rwbp` | `Global.RwbpType` |  |

#### Returns

**Type:** System.String
