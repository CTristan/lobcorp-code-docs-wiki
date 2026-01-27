---
uid: Global.FactionTypeInfo
canonical_path: /api/Global/Info/FactionTypeInfo
---

# Class FactionTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FactionTypeInfo
```
Contains a layer of units which are considered in the same group for targetting, e.g., workers, or idle creatures, or panicked workers.

Contains a list of factions which are considered hostile.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → FactionTypeInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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
#INC


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
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,FactionActionType}

### name

```csharp
public string name
```
#INC


#### Field Value

**Type:** System.String

### type

```csharp
public string type
```
#INC


#### Field Value

**Type:** System.String

## Methods

### Check(UnitModel)

```csharp
public FactionActionType Check(UnitModel unit)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.FactionActionType
