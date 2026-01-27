---
uid: Global.StandingItemScriptBase
canonical_path: /api/Global/Standing/StandingItemScriptBase
---

# Class StandingItemScriptBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StandingItemScriptBase
```
#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StandingItemScriptBase

## Derived
[BirdEggObject](/api/Global/Object/BirdEggObject), [BoomerCircusScript](/api/Global/Script/BoomerCircusScript), [BossBirdGateway](/api/Global/Misc/BossBirdGateway), [ChopLeg](/api/Global/Misc/ChopLeg), [FloodTentacle](/api/Global/Misc/FloodTentacle), [HordeOfBugsScript](/api/Global/Script/HordeOfBugsScript), [RandomEventRoot](/api/Global/Misc/RandomEventRoot), [TastyBug](/api/Global/Misc/TastyBug)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StandingItemScriptBase()

```csharp
public StandingItemScriptBase()
```

## Fields

### _animScript

```csharp
protected StandingItemAnim _animScript
```
#INC


#### Field Value

**Type:** Global.StandingItemAnim

### _defense

```csharp
protected float _defense
```
#INC


#### Field Value

**Type:** System.Single

### _maxHp

```csharp
public int _maxHp
```
#INC


#### Field Value

**Type:** System.Int32

### _state

```csharp
protected StandingItemScriptBase.StandingItemState _state
```

#### Field Value

**Type:** Global.StandingItemScriptBase.StandingItemState

### model

```csharp
protected StandingItemModel model
```
#INC


#### Field Value

**Type:** Global.StandingItemModel

### name

```csharp
public string name
```
#INC


#### Field Value

**Type:** System.String

### soundDistDobule

```csharp
public const float soundDistDobule = 30
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### Defense

```csharp
public float Defense { get; }
```

#### Property Value

**Type:** System.Single

### MaxHp

```csharp
public int MaxHp { get; }
```

#### Property Value

**Type:** System.Int32

### Model

```csharp
public virtual StandingItemModel Model { get; }
```

#### Property Value

**Type:** Global.StandingItemModel

### Movable

```csharp
public virtual MovableObjectNode Movable { get; }
```

#### Property Value

**Type:** Global.MovableObjectNode

### Passage

```csharp
public virtual PassageObjectModel Passage { get; }
```

#### Property Value

**Type:** Global.PassageObjectModel

### State

```csharp
public StandingItemScriptBase.StandingItemState State { get; }
```

#### Property Value

**Type:** Global.StandingItemScriptBase.StandingItemState

## Methods

### CanTakePhsyicalDamage(UnitModel)

```csharp
public virtual bool CanTakePhsyicalDamage(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### CheckCameraRange()

```csharp
public bool CheckCameraRange()
```
#INC


#### Returns

**Type:** System.Boolean

### CheckCameraRange(float)

```csharp
public bool CheckCameraRange(float range)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### GetName()

```csharp
public virtual string GetName()
```
#INC


#### Returns

**Type:** System.String

### GetNearUnit()

```csharp
public virtual List<UnitModel> GetNearUnit()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### HasName()

```csharp
public virtual bool HasName()
```
#INC


#### Returns

**Type:** System.Boolean

### Init()

```csharp
public virtual void Init()
```
#INC


### IsAttackable()

```csharp
public virtual bool IsAttackable()
```
#INC


#### Returns

**Type:** System.Boolean

### IsInRange(UnitModel, float)

```csharp
public virtual bool IsInRange(UnitModel target, float range)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### OnBreakDown()

```csharp
public virtual void OnBreakDown()
```
#INC


### OnDestroyStandingItem()

```csharp
public virtual void OnDestroyStandingItem()
```
#INC


### OnFixedUpdate(StandingItemModel)

```csharp
public virtual void OnFixedUpdate(StandingItemModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.StandingItemModel` |  |

### OnIgnoreDamage(UnitModel)

```csharp
public virtual bool OnIgnoreDamage(UnitModel attacker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### OnNearUnitArrived(List<UnitModel>)

```csharp
public virtual void OnNearUnitArrived(List<UnitModel> near)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |

### OnTakePhyisclaDamage(float)

```csharp
public virtual void OnTakePhyisclaDamage(float damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Single` |  |

### Prob(float)

```csharp
public bool Prob(float value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### Prob(int)

```csharp
public bool Prob(int value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### SetAnimScript(StandingItemAnim)

```csharp
public virtual void SetAnimScript(StandingItemAnim anim)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `anim` | `Global.StandingItemAnim` |  |

### SetModel(StandingItemModel)

```csharp
public void SetModel(StandingItemModel model)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.StandingItemModel` |  |

### SetName(string)

```csharp
public virtual void SetName(string str)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |
