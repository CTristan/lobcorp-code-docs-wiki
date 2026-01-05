# Class WorkerEquipmentSpriteController

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerEquipmentSpriteController : WorkerSpriteData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [WorkerSpriteData](/api/WorkerSprite-WorkerSpriteData) → WorkerEquipmentSpriteController

## Inherited Members
[GetSpriteRegion(string)](/api/WorkerSprite-WorkerSpriteData#getspriteregion-string), [GetBasicSpriteRegion(string)](/api/WorkerSprite-WorkerSpriteData#getbasicspriteregion-string), [GetEquipmentSpriteRegion(string)](/api/WorkerSprite-WorkerSpriteData#getequipmentspriteregion-string), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### WorkerEquipmentSpriteController()

```csharp
public WorkerEquipmentSpriteController()
```

## Fields

### lib

```csharp
public Dictionary<EquipmentSpriteRegion, WorkerEquipmentSprite> lib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{WorkerSprite.EquipmentSpriteRegion,WorkerSprite.WorkerEquipmentSprite}

### list

```csharp
public List<WorkerEquipmentSprite> list
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerSprite.WorkerEquipmentSprite}

## Properties

### RegionType

```csharp
public override SpriteRegionType RegionType { get; }
```

#### Property Value

**Type:** WorkerSprite.SpriteRegionType

## Methods

### GetData(EquipmentSpriteRegion, out WorkerEquipmentSprite)

```csharp
public bool GetData(EquipmentSpriteRegion region, out WorkerEquipmentSprite output)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `WorkerSprite.EquipmentSpriteRegion` |  |
| `output` | `WorkerSprite.WorkerEquipmentSprite` |  |

#### Returns

**Type:** System.Boolean
