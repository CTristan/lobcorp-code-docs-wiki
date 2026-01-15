---
uid: SharpJson.JsonDecoder
canonical_path: /api/SharpJson/JsonDecoder
---

# Class JsonDecoder

**Namespace:** [SharpJson](/api/SharpJson)
**Assembly:** Assembly-CSharp.dll

```csharp
public class JsonDecoder
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → JsonDecoder

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### JsonDecoder()

```csharp
public JsonDecoder()
```

## Fields

### lexer

```csharp
private Lexer lexer
```

#### Field Value

**Type:** SharpJson.Lexer

## Properties

### errorMessage

```csharp
public string errorMessage { get; private set; }
```

#### Property Value

**Type:** System.String

### parseNumbersAsFloat

```csharp
public bool parseNumbersAsFloat { get; set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### Decode(string)

```csharp
public object Decode(string text)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

#### Returns

**Type:** System.Object

### DecodeText(string)

```csharp
public static object DecodeText(string text)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

#### Returns

**Type:** System.Object

### EvalLexer<T>(T)

```csharp
private T EvalLexer<T>(T value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `{T}` |  |

#### Returns

**Type:** {T}

### ParseArray()

```csharp
private IList<object> ParseArray()
```

#### Returns

**Type:** System.Collections.Generic.IList{System.Object}

### ParseObject()

```csharp
private IDictionary<string, object> ParseObject()
```

#### Returns

**Type:** System.Collections.Generic.IDictionary{System.String,System.Object}

### ParseValue()

```csharp
private object ParseValue()
```

#### Returns

**Type:** System.Object

### TriggerError(string)

```csharp
private void TriggerError(string message)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `message` | `System.String` |  |
