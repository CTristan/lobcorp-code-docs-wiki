---
uid: Global.EnergyModel
canonical_path: /api/Global/IOBserver/EnergyModel
---

# Class EnergyModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EnergyModel : IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EnergyModel

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EnergyModel()

```csharp
public EnergyModel()
```

## Fields

### _fillBlock

```csharp
private bool _fillBlock
```

#### Field Value

**Type:** System.Boolean

### _instance

```csharp
private static EnergyModel _instance
```

#### Field Value

**Type:** Global.EnergyModel

### energy

```csharp
private float energy
```

#### Field Value

**Type:** System.Single

### finishCounter

```csharp
private int finishCounter
```

#### Field Value

**Type:** System.Int32

### finishTimer

```csharp
private float finishTimer
```

#### Field Value

**Type:** System.Single

### fullSay

```csharp
private bool fullSay
```

#### Field Value

**Type:** System.Boolean

### halfSay

```csharp
private bool halfSay
```

#### Field Value

**Type:** System.Boolean

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

### OnFixedUpdate()

```csharp
private void OnFixedUpdate()
```

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

### UpdateEnergy()

```csharp
private void UpdateEnergy()
```
