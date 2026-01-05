# Class WorkerBasicSpriteController

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerBasicSpriteController : WorkerSpriteData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [WorkerSpriteData](/api/WorkerSprite-WorkerSpriteData) → WorkerBasicSpriteController

## Inherited Members
[GetSpriteRegion(string)](/api/WorkerSprite-WorkerSpriteData#getspriteregion-string), [GetBasicSpriteRegion(string)](/api/WorkerSprite-WorkerSpriteData#getbasicspriteregion-string), [GetEquipmentSpriteRegion(string)](/api/WorkerSprite-WorkerSpriteData#getequipmentspriteregion-string), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### WorkerBasicSpriteController()

```csharp
public WorkerBasicSpriteController()
```

## Fields

### lib

```csharp
public Dictionary<BasicSpriteRegion, WorkerBasicSprite> lib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{WorkerSprite.BasicSpriteRegion,WorkerSprite.WorkerBasicSprite}

### list

```csharp
public List<WorkerBasicSprite> list
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `WorkerSprite.BasicSpriteRegion` |  |
| `output` | `WorkerSprite.WorkerBasicSprite` |  |

#### Returns

**Type:** System.Boolean
