# Class TextConverter

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TextConverter
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TextConverter

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### TextConverter()

```csharp
public TextConverter()
```

## Methods

### GetTextFromFormatAlter(string)

```csharp
public static string GetTextFromFormatAlter(string text)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

#### Returns

**Type:** System.String

### GetTextFromFormatProcessText(string)

```csharp
public static string[] GetTextFromFormatProcessText(string format_text)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `format_text` | `System.String` |  |

#### Returns

**Type:** System.String[]

### GetTextFromFormatProcessText(string, CreatureModel, params string[])

```csharp
public static string[] GetTextFromFormatProcessText(string format_text, CreatureModel model, params string[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `format_text` | `System.String` |  |
| `model` | `Global.CreatureModel` |  |
| `param` | `System.String[]` |  |

#### Returns

**Type:** System.String[]

### GetTextFromFormatProcessText(string, params string[])

```csharp
public static string[] GetTextFromFormatProcessText(string format_text, params string[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `format_text` | `System.String` |  |
| `param` | `System.String[]` |  |

#### Returns

**Type:** System.String[]

### GetTextFromFormatText(string, CreatureModel, params string[])

```csharp
public static string GetTextFromFormatText(string format_text, CreatureModel model, params string[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `format_text` | `System.String` |  |
| `model` | `Global.CreatureModel` |  |
| `param` | `System.String[]` |  |

#### Returns

**Type:** System.String

### GetTextFromFormatText(string, params string[])

```csharp
public static string GetTextFromFormatText(string format_text, params string[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `format_text` | `System.String` |  |
| `param` | `System.String[]` |  |

#### Returns

**Type:** System.String

### TranslateDescData(string)

```csharp
public static string TranslateDescData(string descData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `descData` | `System.String` |  |

#### Returns

**Type:** System.String
