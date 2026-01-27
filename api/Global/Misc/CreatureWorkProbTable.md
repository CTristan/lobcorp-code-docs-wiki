---
uid: Global.CreatureWorkProbTable
canonical_path: /api/Global/Misc/CreatureWorkProbTable
---

# Class CreatureWorkProbTable

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureWorkProbTable
```
Stores the probabilities for each work type at each level for an abnormality.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureWorkProbTable

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureWorkProbTable()

```csharp
public CreatureWorkProbTable()
```
Initializes `_prob` to have five levels for each work type.


## Fields

### _prob

```csharp
private Dictionary<RwbpType, float[]> _prob
```
Stores the probabilities of each work type at each level.


#### Field Value

**Type:** System.Collections.Generic.Dictionary{RwbpType,System.Single[]}

## Methods

### GetWorkProb(RwbpType, int)

```csharp
public float GetWorkProb(RwbpType type, int level)
```
Gets the probability of `type` work at the level `level`.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `level` | `System.Int32` |  |

#### Returns

**Type:** System.Single

### SetWorkProb(RwbpType, int, float)

```csharp
public void SetWorkProb(RwbpType type, int level, float prob)
```
Sets the probability of `type` work at the level `level` to `prob`. Used by [CreatureDataLoader](/api/Global/Loader/CreatureDataLoader).


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `level` | `System.Int32` |  |
| `prob` | `System.Single` |  |
