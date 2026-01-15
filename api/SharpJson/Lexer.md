---
uid: SharpJson.Lexer
canonical_path: /api/SharpJson/Lexer
---

# Class Lexer

**Namespace:** [SharpJson](/api/SharpJson)
**Assembly:** Assembly-CSharp.dll

```csharp
internal class Lexer
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Lexer

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Lexer(string)

```csharp
public Lexer(string text)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

## Fields

### index

```csharp
private int index
```

#### Field Value

**Type:** System.Int32

### json

```csharp
private char[] json
```

#### Field Value

**Type:** System.Char[]

### stringBuffer

```csharp
private char[] stringBuffer
```

#### Field Value

**Type:** System.Char[]

### success

```csharp
private bool success
```

#### Field Value

**Type:** System.Boolean

## Properties

### hasError

```csharp
public bool hasError { get; }
```

#### Property Value

**Type:** System.Boolean

### lineNumber

```csharp
public int lineNumber { get; private set; }
```

#### Property Value

**Type:** System.Int32

### parseNumbersAsFloat

```csharp
public bool parseNumbersAsFloat { get; set; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetLastIndexOfNumber(int)

```csharp
private int GetLastIndexOfNumber(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### GetNumberString()

```csharp
private string GetNumberString()
```

#### Returns

**Type:** System.String

### LookAhead()

```csharp
public Lexer.Token LookAhead()
```

#### Returns

**Type:** SharpJson.Lexer.Token

### NextToken()

```csharp
public Lexer.Token NextToken()
```

#### Returns

**Type:** SharpJson.Lexer.Token

### NextToken(char[], ref int)

```csharp
private static Lexer.Token NextToken(char[] json, ref int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `json` | `System.Char[]` |  |
| `index` | `System.Int32` |  |

#### Returns

**Type:** SharpJson.Lexer.Token

### ParseDoubleNumber()

```csharp
public double ParseDoubleNumber()
```

#### Returns

**Type:** System.Double

### ParseFloatNumber()

```csharp
public float ParseFloatNumber()
```

#### Returns

**Type:** System.Single

### ParseString()

```csharp
public string ParseString()
```

#### Returns

**Type:** System.String

### Reset()

```csharp
public void Reset()
```

### SkipWhiteSpaces()

```csharp
private void SkipWhiteSpaces()
```
