---
uid: Global.LocalizeTextDataModel
canonical_path: /api/Global/Model/LocalizeTextDataModel
---

# Class LocalizeTextDataModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class LocalizeTextDataModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → LocalizeTextDataModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### LocalizeTextDataModel()

```csharp
public LocalizeTextDataModel()
```

## Fields

### _instance

```csharp
private static LocalizeTextDataModel _instance
```

#### Field Value

**Type:** Global.LocalizeTextDataModel

### _list

```csharp
private Dictionary<string, string> _list
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

### _loaded

```csharp
private bool _loaded
```

#### Field Value

**Type:** System.Boolean

### Failed

```csharp
public const string Failed = "UNKNOWN"
```

#### Field Value

**Type:** System.String

## Properties

### instance

```csharp
public static LocalizeTextDataModel instance { get; }
```

#### Property Value

**Type:** Global.LocalizeTextDataModel

### loaded

```csharp
public bool loaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetText(string)

```csharp
public string GetText(string id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns

**Type:** System.String

### GetTextAppend(params string[])

```csharp
public string GetTextAppend(params string[] ids)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.String[]` |  |

#### Returns

**Type:** System.String

### GetTextAppendFailEmpty(params string[])

```csharp
public string GetTextAppendFailEmpty(params string[] ids)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ids` | `System.String[]` |  |

#### Returns

**Type:** System.String

### Init(Dictionary<string, string>)

```csharp
public void Init(Dictionary<string, string> data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.Dictionary{System.String,System.String}` |  |
