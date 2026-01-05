# Class EnergyModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EnergyModel : IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EnergyModel

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### EnergyModel()

```csharp
public EnergyModel()
```

## Properties

### fillBlock

```csharp
public bool fillBlock { get; set; }
```

#### Property Value

**Type:** System.Boolean

### instance

```csharp
public static EnergyModel instance { get; }
```

#### Property Value

**Type:** Global.EnergyModel

## Methods

### AddEnergy(float)

```csharp
public void AddEnergy(float added)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `added` | `System.Single` |  |

### GetEnergy()

```csharp
public float GetEnergy()
```

#### Returns

**Type:** System.Single

### GetFinishCounter()

```csharp
public int GetFinishCounter()
```

#### Returns

**Type:** System.Int32

### ManualAdd(CreatureModel, float)

```csharp
public void ManualAdd(CreatureModel creature, float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `value` | `System.Single` |  |

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageStart()

```csharp
public void OnStageStart()
```

### SubEnergy(float)

```csharp
public void SubEnergy(float sub)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sub` | `System.Single` |  |
