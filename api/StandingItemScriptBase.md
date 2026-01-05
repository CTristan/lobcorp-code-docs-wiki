# Class StandingItemScriptBase

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StandingItemScriptBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StandingItemScriptBase

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** Global.StandingItemAnim

### _defense

```csharp
protected float _defense
```

#### Field Value

**Type:** System.Single

### _maxHp

```csharp
public int _maxHp
```

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

#### Field Value

**Type:** Global.StandingItemModel

### name

```csharp
public string name
```

#### Field Value

**Type:** System.String

### soundDistDobule

```csharp
public const float soundDistDobule = 30
```

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

#### Returns

**Type:** System.Boolean

### CheckCameraRange(float)

```csharp
public bool CheckCameraRange(float range)
```

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

#### Returns

**Type:** System.String

### GetNearUnit()

```csharp
public virtual List<UnitModel> GetNearUnit()
```

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### HasName()

```csharp
public virtual bool HasName()
```

#### Returns

**Type:** System.Boolean

### Init()

```csharp
public virtual void Init()
```

### IsAttackable()

```csharp
public virtual bool IsAttackable()
```

#### Returns

**Type:** System.Boolean

### IsInRange(UnitModel, float)

```csharp
public virtual bool IsInRange(UnitModel target, float range)
```

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

### OnDestroyStandingItem()

```csharp
public virtual void OnDestroyStandingItem()
```

### OnFixedUpdate(StandingItemModel)

```csharp
public virtual void OnFixedUpdate(StandingItemModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.StandingItemModel` |  |

### OnIgnoreDamage(UnitModel)

```csharp
public virtual bool OnIgnoreDamage(UnitModel attacker)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |

### OnTakePhyisclaDamage(float)

```csharp
public virtual void OnTakePhyisclaDamage(float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Single` |  |

### Prob(float)

```csharp
public bool Prob(float value)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `anim` | `Global.StandingItemAnim` |  |

### SetModel(StandingItemModel)

```csharp
public void SetModel(StandingItemModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.StandingItemModel` |  |

### SetName(string)

```csharp
public virtual void SetName(string str)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |
