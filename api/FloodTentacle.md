# Class FloodTentacle

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FloodTentacle : StandingItemScriptBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/StandingItemScriptBase) → FloodTentacle

## Inherited Members
[soundDistDobule](/api/StandingItemScriptBase#sounddistdobule), [model](/api/StandingItemScriptBase#model), [_animScript](/api/StandingItemScriptBase#animscript), [_state](/api/StandingItemScriptBase#state), [name](/api/StandingItemScriptBase#name), [_maxHp](/api/StandingItemScriptBase#maxhp), [_defense](/api/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/StandingItemScriptBase#isinrange-unitmodel-float), [CanTakePhsyicalDamage(UnitModel)](/api/StandingItemScriptBase#cantakephsyicaldamage-unitmodel), [IsAttackable()](/api/StandingItemScriptBase#isattackable), [OnIgnoreDamage(UnitModel)](/api/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/StandingItemScriptBase#getname), [SetName(string)](/api/StandingItemScriptBase#setname-string), [HasName()](/api/StandingItemScriptBase#hasname), [Prob(float)](/api/StandingItemScriptBase#prob-float), [Prob(int)](/api/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/StandingItemScriptBase#checkcamerarange-float), [Model](/api/StandingItemScriptBase#model), [Movable](/api/StandingItemScriptBase#movable), [Passage](/api/StandingItemScriptBase#passage), [State](/api/StandingItemScriptBase#state), [MaxHp](/api/StandingItemScriptBase#maxhp), [Defense](/api/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### FloodTentacle()

```csharp
public FloodTentacle()
```

## Fields

### allocatedSefira

```csharp
public string allocatedSefira
```

#### Field Value

**Type:** System.String

### animScript

```csharp
public FloodRestTentacleAnim animScript
```

#### Field Value

**Type:** Global.FloodRestTentacleAnim

### appearEffect

```csharp
public const string appearEffect = "Effect/RandomEvent/TentacleAppear"
```

#### Field Value

**Type:** System.String

### attackDelay

```csharp
public Timer attackDelay
```

#### Field Value

**Type:** Global.Timer

### attackDelayTime

```csharp
public float attackDelayTime
```

#### Field Value

**Type:** System.Single

### attackRange

```csharp
public float attackRange
```

#### Field Value

**Type:** System.Single

### AtypeHit

```csharp
public const string AtypeHit = "Effect/RandomEvent/ATypeHit"
```

#### Field Value

**Type:** System.String

### BtypeHit

```csharp
public const string BtypeHit = "Effect/RandomEvent/BTypeHit"
```

#### Field Value

**Type:** System.String

### CtypeHit

```csharp
public const string CtypeHit = "Effect/RandomEvent/CTypeHit"
```

#### Field Value

**Type:** System.String

### damage

```csharp
public float damage
```

#### Field Value

**Type:** System.Single

### enableDelay

```csharp
public Timer enableDelay
```

#### Field Value

**Type:** Global.Timer

### initialRange

```csharp
public const float initialRange = 2.5
```

#### Field Value

**Type:** System.Single

### initialScale

```csharp
public const float initialScale = 0.5
```

#### Field Value

**Type:** System.Single

### randomEvent

```csharp
public FloodRestArmEvent randomEvent
```

#### Field Value

**Type:** Global.FloodRestArmEvent

### rootEffect

```csharp
public const string rootEffect = "Effect/RandomEvent/RootNear"
```

#### Field Value

**Type:** System.String

### ScaleFactor

```csharp
public float ScaleFactor
```

#### Field Value

**Type:** System.Single

### textUI

```csharp
public Text textUI
```

#### Field Value

**Type:** UnityEngine.UI.Text

## Methods

### CheckInRange(UnitModel, float)

```csharp
public bool CheckInRange(UnitModel target, float range)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `delay` | `System.Single` |  |

### GetNearUnitInRange()

```csharp
public List<UnitModel> GetNearUnitInRange()
```

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

### Init()

```csharp
public override void Init()
```

### IsActive()

```csharp
public bool IsActive()
```

#### Returns

**Type:** System.Boolean

### MakeEffect(string)

```csharp
public GameObject MakeEffect(string src)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `positionSet` | `UnityEngine.Vector2` |  |
| `targetPos` | `UnityEngine.Vector3` |  |
| `rotEuler` | `UnityEngine.Vector3` |  |

### OnAttackEnd()

```csharp
public void OnAttackEnd()
```

### OnBreakDown()

```csharp
public override void OnBreakDown()
```

### OnEnable()

```csharp
public void OnEnable()
```

### OnFixedUpdate(StandingItemModel)

```csharp
public override void OnFixedUpdate(StandingItemModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.StandingItemModel` |  |

### OnStartAttack(UnitModel)

```csharp
public void OnStartAttack(UnitModel mainTarget)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `mainTarget` | `Global.UnitModel` |  |

### SetActive(bool)

```csharp
public void SetActive(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetEvent(FloodRestArmEvent)

```csharp
public void SetEvent(FloodRestArmEvent fra)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fra` | `Global.FloodRestArmEvent` |  |

### SetScaleFactor(float)

```csharp
public void SetScaleFactor(float factor)
```

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
