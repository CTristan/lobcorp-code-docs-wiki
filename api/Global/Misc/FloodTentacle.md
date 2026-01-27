---
uid: Global.FloodTentacle
canonical_path: /api/Global/Misc/FloodTentacle
---

# Class FloodTentacle

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FloodTentacle : StandingItemScriptBase
```

#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Standing/StandingItemScriptBase) → FloodTentacle

## Inherited Members
[soundDistDobule](/api/Global/Standing/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Standing/StandingItemScriptBase#model), [_animScript](/api/Global/Standing/StandingItemScriptBase#animscript), [_state](/api/Global/Standing/StandingItemScriptBase#state), [name](/api/Global/Standing/StandingItemScriptBase#name), [_maxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [_defense](/api/Global/Standing/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Standing/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Standing/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/Global/Standing/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Standing/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Standing/StandingItemScriptBase#isinrange-unitmodel-float), [CanTakePhsyicalDamage(UnitModel)](/api/Global/Standing/StandingItemScriptBase#cantakephsyicaldamage-unitmodel), [IsAttackable()](/api/Global/Standing/StandingItemScriptBase#isattackable), [OnIgnoreDamage(UnitModel)](/api/Global/Standing/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/Global/Standing/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/Global/Standing/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/Global/Standing/StandingItemScriptBase#getname), [SetName(string)](/api/Global/Standing/StandingItemScriptBase#setname-string), [HasName()](/api/Global/Standing/StandingItemScriptBase#hasname), [Prob(float)](/api/Global/Standing/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Standing/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Standing/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Standing/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Standing/StandingItemScriptBase#model), [Movable](/api/Global/Standing/StandingItemScriptBase#movable), [Passage](/api/Global/Standing/StandingItemScriptBase#passage), [State](/api/Global/Standing/StandingItemScriptBase#state), [MaxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [Defense](/api/Global/Standing/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FloodTentacle()

```csharp
public FloodTentacle()
```

## Fields

### _phase

```csharp
private FloodTentacle.TentaclePhase _phase
```

#### Field Value

**Type:** Global.FloodTentacle.TentaclePhase

### _tentacleState

```csharp
private FloodTentacle.TentacleState _tentacleState
```

#### Field Value

**Type:** Global.FloodTentacle.TentacleState

### _type

```csharp
private FloodTentacle.TentacleType _type
```

#### Field Value

**Type:** Global.FloodTentacle.TentacleType

### allocatedSefira

```csharp
public string allocatedSefira
```
#INC


#### Field Value

**Type:** System.String

### animScript

```csharp
public FloodRestTentacleAnim animScript
```
#INC


#### Field Value

**Type:** Global.FloodRestTentacleAnim

### appearEffect

```csharp
public const string appearEffect = "Effect/RandomEvent/TentacleAppear"
```
#INC


#### Field Value

**Type:** System.String

### appearEffectMake

```csharp
private bool appearEffectMake
```
#INC


#### Field Value

**Type:** System.Boolean

### attackDelay

```csharp
public Timer attackDelay
```
#INC


#### Field Value

**Type:** Global.Timer

### attackDelayTime

```csharp
public float attackDelayTime
```
#INC


#### Field Value

**Type:** System.Single

### attackRange

```csharp
public float attackRange
```
#INC


#### Field Value

**Type:** System.Single

### AtypeHit

```csharp
public const string AtypeHit = "Effect/RandomEvent/ATypeHit"
```
#INC


#### Field Value

**Type:** System.String

### BtypeHit

```csharp
public const string BtypeHit = "Effect/RandomEvent/BTypeHit"
```
#INC


#### Field Value

**Type:** System.String

### CtypeHit

```csharp
public const string CtypeHit = "Effect/RandomEvent/CTypeHit"
```
#INC


#### Field Value

**Type:** System.String

### damage

```csharp
public float damage
```
#INC


#### Field Value

**Type:** System.Single

### enableDelay

```csharp
public Timer enableDelay
```
#INC


#### Field Value

**Type:** Global.Timer

### initialRange

```csharp
public const float initialRange = 2.5
```
#INC


#### Field Value

**Type:** System.Single

### initialScale

```csharp
public const float initialScale = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### randomEvent

```csharp
public FloodRestArmEvent randomEvent
```
#INC


#### Field Value

**Type:** Global.FloodRestArmEvent

### rootEffect

```csharp
public const string rootEffect = "Effect/RandomEvent/RootNear"
```
#INC


#### Field Value

**Type:** System.String

### ScaleFactor

```csharp
public float ScaleFactor
```
#INC


#### Field Value

**Type:** System.Single

### textUI

```csharp
public Text textUI
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

## Properties

### current

```csharp
private float current { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### AppearEffect()

```csharp
private void AppearEffect()
```
#INC


### CheckInRange(UnitModel, float)

```csharp
public bool CheckInRange(UnitModel target, float range)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### DelayedEnable(float)

```csharp
public void DelayedEnable(float delay)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `delay` | `System.Single` |  |

### GetDirectionTarget(List<UnitModel>)

```csharp
private List<UnitModel> GetDirectionTarget(List<UnitModel> targets)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targets` | `System.Collections.Generic.List{UnitModel}` |  |

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetNearUnitInRange()

```csharp
public List<UnitModel> GetNearUnitInRange()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetPhase()

```csharp
public FloodTentacle.TentaclePhase GetPhase()
```

#### Returns

**Type:** Global.FloodTentacle.TentaclePhase

### GiveDamage()

```csharp
public void GiveDamage()
```
#INC


### GiveDamage(UnitModel, float)

```csharp
private void GiveDamage(UnitModel target, float damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `System.Single` |  |

### Init()

```csharp
public override void Init()
```
#INC
#code-generated


### IsActive()

```csharp
public bool IsActive()
```
#INC


#### Returns

**Type:** System.Boolean

### MakeEffect(string)

```csharp
public GameObject MakeEffect(string src)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeEffect(string, Vector2)

```csharp
public GameObject MakeEffect(string src, Vector2 positionSet)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `positionSet` | `UnityEngine.Vector2` |  |

#### Returns

**Type:** UnityEngine.GameObject

### MakeEffect(string, Vector2, Vector3, Vector3)

```csharp
public void MakeEffect(string src, Vector2 positionSet, Vector3 targetPos, Vector3 rotEuler)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `positionSet` | `UnityEngine.Vector2` |  |
| `targetPos` | `UnityEngine.Vector3` |  |
| `rotEuler` | `UnityEngine.Vector3` |  |

### Multiple(List<UnitModel>, DamageEvent)

```csharp
private void Multiple(List<UnitModel> targets, FloodTentacle.DamageEvent e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targets` | `System.Collections.Generic.List{UnitModel}` |  |
| `e` | `Global.FloodTentacle.DamageEvent` |  |

### OnAttackEnd()

```csharp
public void OnAttackEnd()
```
#INC


### OnBreakDown()

```csharp
public override void OnBreakDown()
```
#INC


### OnEnable()

```csharp
public void OnEnable()
```
#INC


### OnFixedUpdate(StandingItemModel)

```csharp
public override void OnFixedUpdate(StandingItemModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.StandingItemModel` |  |

### OnlyOne(List<UnitModel>, DamageEvent)

```csharp
private void OnlyOne(List<UnitModel> targets, FloodTentacle.DamageEvent e)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targets` | `System.Collections.Generic.List{UnitModel}` |  |
| `e` | `Global.FloodTentacle.DamageEvent` |  |

### OnStartAttack(UnitModel)

```csharp
public void OnStartAttack(UnitModel mainTarget)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mainTarget` | `Global.UnitModel` |  |

### SetActive(bool)

```csharp
public void SetActive(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetEvent(FloodRestArmEvent)

```csharp
public void SetEvent(FloodRestArmEvent fra)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fra` | `Global.FloodRestArmEvent` |  |

### SetScaleFactor(float)

```csharp
public void SetScaleFactor(float factor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factor` | `System.Single` |  |

### SetType(TentacleType)

```csharp
public void SetType(FloodTentacle.TentacleType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.FloodTentacle.TentacleType` |  |

### TentalceGiveDamage(UnitModel, float)

```csharp
public bool TentalceGiveDamage(UnitModel target, float damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### Type()

```csharp
public FloodTentacle.TentacleType Type()
```

#### Returns

**Type:** Global.FloodTentacle.TentacleType
