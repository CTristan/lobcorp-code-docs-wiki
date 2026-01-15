---
uid: Global.HierarchicalDataManager
canonical_path: /api/Global/Misc/HierarchicalDataManager
---

# Class HierarchicalDataManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class HierarchicalDataManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → HierarchicalDataManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### HierarchicalDataManager()

```csharp
public HierarchicalDataManager()
```

## Fields

### _intance

```csharp
private static HierarchicalDataManager _intance
```

#### Field Value

**Type:** Global.HierarchicalDataManager

### isInitiated

```csharp
private bool isInitiated
```

#### Field Value

**Type:** System.Boolean

### lib

```csharp
public Dictionary<string, List<string>> lib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}}

### Uncon

```csharp
public static string Uncon
```

#### Field Value

**Type:** System.String

## Properties

### instance

```csharp
public static HierarchicalDataManager instance { get; }
```

#### Property Value

**Type:** Global.HierarchicalDataManager

### IsInit

```csharp
public bool IsInit { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### Init(Dictionary<string, List<string>>)

```csharp
public void Init(Dictionary<string, List<string>> lib)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `lib` | `System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}}` |  |

### InitialSetting(string, string)

```csharp
public int InitialSetting(string area, string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `area` | `System.String` |  |
| `name` | `System.String` |  |

#### Returns

**Type:** System.Int32
