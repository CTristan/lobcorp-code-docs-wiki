---
uid: Global.FactionTypeList
canonical_path: /api/Global/List/FactionTypeList
---

# Class FactionTypeList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FactionTypeList
```
Maintains a list of [factions](/api/Global/Info/FactionTypeInfo).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → FactionTypeList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FactionTypeList()

```csharp
public FactionTypeList()
```

## Fields

### _instance

```csharp
private static FactionTypeList _instance
```
#INC


#### Field Value

**Type:** Global.FactionTypeList

### factions

```csharp
private Dictionary<string, FactionTypeInfo> factions
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,FactionTypeInfo}

### isLoaded

```csharp
private bool isLoaded
```
#INC


#### Field Value

**Type:** System.Boolean

## Properties

### instance

```csharp
public static FactionTypeList instance { get; }
```

#### Property Value

**Type:** Global.FactionTypeList

### IsLoaded

```csharp
public bool IsLoaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetFaction(string)

```csharp
public FactionTypeInfo GetFaction(string code)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `code` | `System.String` |  |

#### Returns

**Type:** Global.FactionTypeInfo

### GetFactionByName(string)

```csharp
public FactionTypeInfo GetFactionByName(string factionName)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factionName` | `System.String` |  |

#### Returns

**Type:** Global.FactionTypeInfo

### Init(ReadOnlyCollection<FactionTypeInfo>)

```csharp
public void Init(ReadOnlyCollection<FactionTypeInfo> factions)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factions` | `System.Collections.ObjectModel.ReadOnlyCollection{FactionTypeInfo}` |  |
