---
uid: Global.RandomEventInfo
canonical_path: /api/Global/Info/RandomEventInfo
---

# Class RandomEventInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RandomEventInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RandomEventInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RandomEventInfo()

```csharp
public RandomEventInfo()
```

## Fields

### clearLib

```csharp
public Dictionary<string, string> clearLib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

### color

```csharp
public string color
```

#### Field Value

**Type:** System.String

### conditions

```csharp
public List<RandomEventInfo.ConditionInfo> conditions
```

#### Field Value

**Type:** System.Collections.Generic.List{RandomEventInfo.ConditionInfo}

### descLib

```csharp
public Dictionary<string, string> descLib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

### endTitleLib

```csharp
public Dictionary<string, string> endTitleLib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

### id

```csharp
public long id
```

#### Field Value

**Type:** System.Int64

### independentCondition

```csharp
public bool independentCondition
```

#### Field Value

**Type:** System.Boolean

### nameLib

```csharp
public Dictionary<string, string> nameLib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

### rank

```csharp
public string rank
```

#### Field Value

**Type:** System.String

### script

```csharp
public string script
```

#### Field Value

**Type:** System.String

### type

```csharp
public string type
```

#### Field Value

**Type:** System.String

### typeLib

```csharp
public Dictionary<string, string> typeLib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

## Properties

### currentLanguage

```csharp
public static string currentLanguage { get; }
```

#### Property Value

**Type:** System.String

## Methods

### DefaultCondition()

```csharp
public void DefaultCondition()
```

### GetClearMessage()

```csharp
public string GetClearMessage()
```

#### Returns

**Type:** System.String

### GetConditionInfo(int)

```csharp
public RandomEventInfo.ConditionInfo GetConditionInfo(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.RandomEventInfo.ConditionInfo

### GetDesc()

```csharp
public string GetDesc()
```

#### Returns

**Type:** System.String

### GetEndTitle()

```csharp
public string GetEndTitle()
```

#### Returns

**Type:** System.String

### GetName()

```csharp
public string GetName()
```

#### Returns

**Type:** System.String

### GetTypeString()

```csharp
public string GetTypeString()
```

#### Returns

**Type:** System.String
