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

Manager for energy collection during the day.

#INC 


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
#INC
#code-generated


## Fields

### _fillBlock

```csharp
private bool _fillBlock
```
#INC


#### Field Value

**Type:** System.Boolean

### _instance

```csharp
private static EnergyModel _instance
```
#INC


#### Field Value

**Type:** Global.EnergyModel

### energy

```csharp
private float energy
```
#INC


#### Field Value

**Type:** System.Single

### finishCounter

```csharp
private int finishCounter
```
#INC


#### Field Value

**Type:** System.Int32

### finishTimer

```csharp
private float finishTimer
```
#INC


#### Field Value

**Type:** System.Single

### fullSay

```csharp
private bool fullSay
```
#INC


#### Field Value

**Type:** System.Boolean

### halfSay

```csharp
private bool halfSay
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `added` | `System.Single` |  |

### GetEnergy()

```csharp
public float GetEnergy()
```
#INC


#### Returns

**Type:** System.Single

### GetFinishCounter()

```csharp
public int GetFinishCounter()
```
#INC


#### Returns

**Type:** System.Int32

### ManualAdd(CreatureModel, float)

```csharp
public void ManualAdd(CreatureModel creature, float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `value` | `System.Single` |  |

### OnFixedUpdate()

```csharp
private void OnFixedUpdate()
```
#INC


### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageStart()

```csharp
public void OnStageStart()
```
#INC


### SubEnergy(float)

```csharp
public void SubEnergy(float sub)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sub` | `System.Single` |  |

### UpdateEnergy()

```csharp
private void UpdateEnergy()
```
#INC

