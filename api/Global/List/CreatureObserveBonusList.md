---
uid: Global.CreatureObserveBonusList
canonical_path: /api/Global/List/CreatureObserveBonusList
---

# Class CreatureObserveBonusList

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureObserveBonusList
```
A list of the [observation bonuses](/api/Global/Creature/CreatureObserveBonusData). Provides methods for getting the sum of the bonuses.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureObserveBonusList

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureObserveBonusList()

```csharp
public CreatureObserveBonusList()
```

## Fields

### bonusList

```csharp
public List<CreatureObserveBonusData> bonusList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{CreatureObserveBonusData}

## Methods

### GetProbBonus(int)

```csharp
public int GetProbBonus(int level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### GetSpeedBonus(int)

```csharp
public int GetSpeedBonus(int level)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### Init(List<CreatureObserveBonusData>)

```csharp
public void Init(List<CreatureObserveBonusData> list)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `list` | `System.Collections.Generic.List{CreatureObserveBonusData}` |  |
