# Class JsonDecoder

**Namespace:** [SharpJson](/api/SharpJson)
**Assembly:** Assembly-CSharp.dll

```csharp
public class JsonDecoder
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → JsonDecoder

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### JsonDecoder()

```csharp
public JsonDecoder()
```

## Properties

### errorMessage

```csharp
public string errorMessage { get; }
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
