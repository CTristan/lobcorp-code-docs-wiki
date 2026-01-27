---
uid: WorkerSprite.WorkerBasicSpriteController
canonical_path: /api/WorkerSprite/WorkerBasicSpriteController
---

# Class WorkerBasicSpriteController

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerBasicSpriteController : WorkerSpriteData
```

Stores a sprite for each region, and provides a getter


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [WorkerSpriteData](/api/WorkerSprite/WorkerSpriteData) → WorkerBasicSpriteController

## Inherited Members
[<>f__switch$map0](WorkerSprite.WorkerSpriteData.html#WorkerSprite_WorkerSpriteData___f__switch_map0), [GetSpriteRegion(string)](/api/WorkerSprite/WorkerSpriteData#getspriteregion-string), [GetBasicSpriteRegion(string)](/api/WorkerSprite/WorkerSpriteData#getbasicspriteregion-string), [GetEquipmentSpriteRegion(string)](/api/WorkerSprite/WorkerSpriteData#getequipmentspriteregion-string), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerBasicSpriteController()

```csharp
public WorkerBasicSpriteController()
```

## Fields

### _regionType

```csharp
private SpriteRegionType _regionType
```
#INC


#### Field Value

**Type:** WorkerSprite.SpriteRegionType

### lib

```csharp
public Dictionary<BasicSpriteRegion, WorkerBasicSprite> lib
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{WorkerSprite.BasicSpriteRegion,WorkerSprite.WorkerBasicSprite}

### list

```csharp
public List<WorkerBasicSprite> list
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{WorkerSprite.WorkerBasicSprite}

## Properties

### RegionType

```csharp
public override SpriteRegionType RegionType { get; }
```

#### Property Value

**Type:** WorkerSprite.SpriteRegionType

## Methods

### GetData(BasicSpriteRegion, out WorkerBasicSprite)

```csharp
public bool GetData(BasicSpriteRegion region, out WorkerBasicSprite output)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `WorkerSprite.BasicSpriteRegion` |  |
| `output` | `WorkerSprite.WorkerBasicSprite` |  |

#### Returns

**Type:** System.Boolean
