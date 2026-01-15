---
uid: Global.AgentLyrics.CreditLyric
canonical_path: /api/Global/Misc/AgentLyricsCreditLyric
---

# Class AgentLyrics.CreditLyric

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AgentLyrics.CreditLyric
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AgentLyrics.CreditLyric

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreditLyric()

```csharp
public CreditLyric()
```

## Fields

### horror

```csharp
public Dictionary<int, List<string>> horror
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.List{System.String}}

### normal

```csharp
public Dictionary<int, List<string>> normal
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.List{System.String}}

### otherdead

```csharp
public Dictionary<int, List<string>> otherdead
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.List{System.String}}

### otherpanic

```csharp
public Dictionary<int, List<string>> otherpanic
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.List{System.String}}

### panic

```csharp
public Dictionary<int, List<string>> panic
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.List{System.String}}

## Methods

### GetRandomLyric(LyricTypeNew, int)

```csharp
public string GetRandomLyric(LyricTypeNew type, int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.LyricTypeNew` |  |
| `id` | `System.Int32` |  |

#### Returns

**Type:** System.String
