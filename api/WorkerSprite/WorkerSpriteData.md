---
uid: WorkerSprite.WorkerSpriteData
canonical_path: /api/WorkerSprite/WorkerSpriteData
---

# Class WorkerSpriteData

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerSpriteData
```
Holds the region for a sprite and provides helper functions for switching between strings and enum values for regions


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerSpriteData

## Derived
[WorkerBasicSpriteController](/api/WorkerSprite/WorkerBasicSpriteController), [WorkerEquipmentSpriteController](/api/WorkerSprite/WorkerEquipmentSpriteController)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerSpriteData()

```csharp
public WorkerSpriteData()
```

## Properties

### RegionType

```csharp
public virtual SpriteRegionType RegionType { get; }
```

#### Property Value

**Type:** WorkerSprite.SpriteRegionType

## Methods

### GetBasicSpriteRegion(string)

```csharp
public static BasicSpriteRegion GetBasicSpriteRegion(string region)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `System.String` |  |

#### Returns

**Type:** WorkerSprite.BasicSpriteRegion

### GetEquipmentSpriteRegion(string)

```csharp
public static EquipmentSpriteRegion GetEquipmentSpriteRegion(string region)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `System.String` |  |

#### Returns

**Type:** WorkerSprite.EquipmentSpriteRegion

### GetSpriteRegion(string)

```csharp
public static SpriteRegion GetSpriteRegion(string region)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `System.String` |  |

#### Returns

**Type:** WorkerSprite.SpriteRegion
