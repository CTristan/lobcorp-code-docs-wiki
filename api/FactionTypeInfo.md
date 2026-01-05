# Class FactionTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FactionTypeInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → FactionTypeInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### FactionTypeInfo()

```csharp
public FactionTypeInfo()
```

## Fields

### code

```csharp
public string code
```

#### Field Value

**Type:** System.String

### except

```csharp
public FactionTypeInfo.ExceptType except
```

#### Field Value

**Type:** Global.FactionTypeInfo.ExceptType

### lib

```csharp
public Dictionary<string, FactionActionType> lib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,FactionActionType}

### name

```csharp
public string name
```

#### Field Value

**Type:** System.String

### type

```csharp
public string type
```

#### Field Value

**Type:** System.String

## Methods

### Check(UnitModel)

```csharp
public FactionActionType Check(UnitModel unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.FactionActionType
