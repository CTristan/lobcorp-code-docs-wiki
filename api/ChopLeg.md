# Class ChopLeg

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChopLeg : StandingItemScriptBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/StandingItemScriptBase) → ChopLeg

## Inherited Members
[soundDistDobule](/api/StandingItemScriptBase#sounddistdobule), [model](/api/StandingItemScriptBase#model), [_animScript](/api/StandingItemScriptBase#animscript), [_state](/api/StandingItemScriptBase#state), [name](/api/StandingItemScriptBase#name), [_maxHp](/api/StandingItemScriptBase#maxhp), [_defense](/api/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [Init()](/api/StandingItemScriptBase#init), [SetAnimScript(StandingItemAnim)](/api/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/StandingItemScriptBase#isinrange-unitmodel-float), [CanTakePhsyicalDamage(UnitModel)](/api/StandingItemScriptBase#cantakephsyicaldamage-unitmodel), [IsAttackable()](/api/StandingItemScriptBase#isattackable), [OnBreakDown()](/api/StandingItemScriptBase#onbreakdown), [OnIgnoreDamage(UnitModel)](/api/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/StandingItemScriptBase#getname), [SetName(string)](/api/StandingItemScriptBase#setname-string), [HasName()](/api/StandingItemScriptBase#hasname), [Prob(float)](/api/StandingItemScriptBase#prob-float), [Prob(int)](/api/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/StandingItemScriptBase#checkcamerarange-float), [Model](/api/StandingItemScriptBase#model), [Movable](/api/StandingItemScriptBase#movable), [Passage](/api/StandingItemScriptBase#passage), [State](/api/StandingItemScriptBase#state), [MaxHp](/api/StandingItemScriptBase#maxhp), [Defense](/api/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ChopLeg()

```csharp
public ChopLeg()
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
public ChopLegAnim animScript
```

#### Field Value

**Type:** Global.ChopLegAnim

### attackDelay

```csharp
public Timer attackDelay
```

#### Field Value

**Type:** Global.Timer

### canCancel

```csharp
public bool canCancel
```

#### Field Value

**Type:** System.Boolean

### currentGateOpenSpeed

```csharp
public float currentGateOpenSpeed
```

#### Field Value

**Type:** System.Single

### Damage

```csharp
public const float Damage = 50
```

#### Field Value

**Type:** System.Single

### randomEvent

```csharp
public FallingLegEvent randomEvent
```

#### Field Value

**Type:** Global.FallingLegEvent

## Properties

### phase

```csharp
public ChopLeg.LegPhase phase { get; }
```

#### Property Value

**Type:** Global.ChopLeg.LegPhase

### type

```csharp
public ChopLeg.LegType type { get; }
```

#### Property Value

**Type:** Global.ChopLeg.LegType

## Methods

### DelayedEnable(float)

```csharp
public void DelayedEnable(float value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### EndAttack()

```csharp
public void EndAttack()
```

### GetNearTargets()

```csharp
public List<UnitModel> GetNearTargets()
```

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetRangeTargets()

```csharp
public List<UnitModel> GetRangeTargets()
```

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GiveDamage()

```csharp
public void GiveDamage()
```

### OnAppearEnd()

```csharp
public void OnAppearEnd()
```

### OnCancelFail()

```csharp
public void OnCancelFail()
```

### OnClick()

```csharp
public void OnClick()
```

### OnFixedUpdate(StandingItemModel)

```csharp
public override void OnFixedUpdate(StandingItemModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.StandingItemModel` |  |

### SetEvent(FallingLegEvent)

```csharp
public void SetEvent(FallingLegEvent fle)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fle` | `Global.FallingLegEvent` |  |

### SetNodes()

```csharp
public void SetNodes()
```

### SetPassage(PassageObjectModel)

```csharp
public void SetPassage(PassageObjectModel targetPassage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetPassage` | `Global.PassageObjectModel` |  |

### SetRandomPosition()

```csharp
public void SetRandomPosition()
```

### SetType(LegType)

```csharp
public void SetType(ChopLeg.LegType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.ChopLeg.LegType` |  |

### StartAttack()

```csharp
public void StartAttack()
```
