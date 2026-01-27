---
uid: Global.DistanceUnitUtil
canonical_path: /api/Global/Misc/DistanceUnitUtil
---

# Class DistanceUnitUtil

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DistanceUnitUtil
```
Seems to be a utility for converting between the game's internal units and unity's units.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DistanceUnitUtil

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DistanceUnitUtil()

```csharp
public DistanceUnitUtil()
```

## Fields

### distanceScale

```csharp
public const float distanceScale = 1.3333334
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### GameToUnity(float)

```csharp
public static float GameToUnity(float v)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `v` | `System.Single` |  |

#### Returns

**Type:** System.Single

### SelectNearestUnit(UnitModel, List<UnitModel>)

```csharp
public static UnitModel SelectNearestUnit(UnitModel model, List<UnitModel> list)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |
| `list` | `System.Collections.Generic.List{UnitModel}` |  |

#### Returns

**Type:** Global.UnitModel

### UnityToGame(float)

```csharp
public static float UnityToGame(float v)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `v` | `System.Single` |  |

#### Returns

**Type:** System.Single
