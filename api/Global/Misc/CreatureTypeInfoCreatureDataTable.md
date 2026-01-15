---
uid: Global.CreatureTypeInfo.CreatureDataTable
canonical_path: /api/Global/Misc/CreatureTypeInfoCreatureDataTable
---

# Class CreatureTypeInfo.CreatureDataTable

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureTypeInfo.CreatureDataTable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureTypeInfo.CreatureDataTable

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureDataTable()

```csharp
public CreatureDataTable()
```

## Fields

### dictionary

```csharp
public Dictionary<string, CreatureTypeInfo.CreatureDataList> dictionary
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,CreatureTypeInfo.CreatureDataList}

## Methods

### GetDataString()

```csharp
public string[] GetDataString()
```

#### Returns

**Type:** System.String[]

### GetList(string)

```csharp
public CreatureTypeInfo.CreatureDataList GetList(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns

**Type:** Global.CreatureTypeInfo.CreatureDataList

### PrintElementName()

```csharp
public void PrintElementName()
```
