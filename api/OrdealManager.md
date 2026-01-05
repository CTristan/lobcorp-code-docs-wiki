# Class OrdealManager

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OrdealManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OrdealManager

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### OrdealManager()

```csharp
public OrdealManager()
```

## Fields

### availableFixers

```csharp
public List<RwbpType> availableFixers
```

#### Field Value

**Type:** System.Collections.Generic.List{RwbpType}

## Properties

### instance

```csharp
public static OrdealManager instance { get; }
```

#### Property Value

**Type:** Global.OrdealManager

## Methods

### ActivateOrdeal(OrdealBase, bool)

```csharp
public bool ActivateOrdeal(OrdealBase ordeal, bool remove = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordeal` | `Global.OrdealBase` |  |
| `remove` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean

### AddCreature(long, MapNode, OrdealBase)

```csharp
public OrdealCreatureModel AddCreature(long metadataId, MapNode pos, OrdealBase ordealBase)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `metadataId` | `System.Int64` |  |
| `pos` | `Global.MapNode` |  |
| `ordealBase` | `Global.OrdealBase` |  |

#### Returns

**Type:** Global.OrdealCreatureModel

### CheckOrdealContains(OrdealLevel, out OrdealBase)

```csharp
public bool CheckOrdealContains(OrdealLevel level, out OrdealBase ordeal)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |
| `ordeal` | `Global.OrdealBase` |  |

#### Returns

**Type:** System.Boolean

### ClearCreatures()

```csharp
public void ClearCreatures()
```

### GetActivatedOrdeals()

```csharp
public List<OrdealBase> GetActivatedOrdeals()
```

#### Returns

**Type:** System.Collections.Generic.List{OrdealBase}

### GetMaxOrdealLevel()

```csharp
public OrdealLevel GetMaxOrdealLevel()
```

#### Returns

**Type:** Global.OrdealLevel

### GetOrdealCreatureList()

```csharp
public OrdealCreatureModel[] GetOrdealCreatureList()
```

#### Returns

**Type:** Global.OrdealCreatureModel[]

### InitAvailableFixers()

```csharp
public void InitAvailableFixers()
```

### OnAddCreatureWorkCount()

```csharp
public void OnAddCreatureWorkCount()
```

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```

### OnGameInit()

```csharp
public void OnGameInit()
```

### OnOrdealEnd(OrdealBase, bool)

```csharp
public void OnOrdealEnd(OrdealBase ordeal, bool b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ordeal` | `Global.OrdealBase` |  |
| `b` | `System.Boolean` |  |

### OnStageRelease()

```csharp
public void OnStageRelease()
```

### OnStageStart()

```csharp
public void OnStageStart()
```
