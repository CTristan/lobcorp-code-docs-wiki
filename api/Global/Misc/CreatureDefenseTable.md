---
uid: Global.CreatureDefenseTable
canonical_path: /api/Global/Misc/CreatureDefenseTable
---

# Class CreatureDefenseTable

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureDefenseTable
```
Stores an abnormality's defenses.

Loaded by [CreatureDataLoader](/api/Global/Loader/CreatureDataLoader).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureDefenseTable

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureDefenseTable()

```csharp
public CreatureDefenseTable()
```

## Fields

### _defenseTable

```csharp
private Dictionary<string, DefenseInfo> _defenseTable
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,DefenseInfo}

## Methods

### GetDefenseInfo()

```csharp
public DefenseInfo GetDefenseInfo()
```
#INC


#### Returns

**Type:** Global.DefenseInfo

### GetDefenseInfo(string)

```csharp
public DefenseInfo GetDefenseInfo(string id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns

**Type:** Global.DefenseInfo

### GetDefenseInfoList()

```csharp
public List<DefenseInfo> GetDefenseInfoList()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{DefenseInfo}

### Init(Dictionary<string, DefenseInfo>)

```csharp
public void Init(Dictionary<string, DefenseInfo> dic)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,DefenseInfo}` |  |
