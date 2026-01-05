# Class WorkerSpriteData

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerSpriteData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerSpriteData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `System.String` |  |

#### Returns

**Type:** WorkerSprite.SpriteRegion
