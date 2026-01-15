---
uid: Global.ChopLeg
canonical_path: /api/Global/Misc/ChopLeg
---

# Class ChopLeg

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChopLeg : StandingItemScriptBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Standing/StandingItemScriptBase) → ChopLeg

## Inherited Members
[soundDistDobule](/api/Global/Standing/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Standing/StandingItemScriptBase#model), [_animScript](/api/Global/Standing/StandingItemScriptBase#animscript), [_state](/api/Global/Standing/StandingItemScriptBase#state), [name](/api/Global/Standing/StandingItemScriptBase#name), [_maxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [_defense](/api/Global/Standing/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Standing/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Standing/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [Init()](/api/Global/Standing/StandingItemScriptBase#init), [SetAnimScript(StandingItemAnim)](/api/Global/Standing/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Standing/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Standing/StandingItemScriptBase#isinrange-unitmodel-float), [CanTakePhsyicalDamage(UnitModel)](/api/Global/Standing/StandingItemScriptBase#cantakephsyicaldamage-unitmodel), [IsAttackable()](/api/Global/Standing/StandingItemScriptBase#isattackable), [OnBreakDown()](/api/Global/Standing/StandingItemScriptBase#onbreakdown), [OnIgnoreDamage(UnitModel)](/api/Global/Standing/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/Global/Standing/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/Global/Standing/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/Global/Standing/StandingItemScriptBase#getname), [SetName(string)](/api/Global/Standing/StandingItemScriptBase#setname-string), [HasName()](/api/Global/Standing/StandingItemScriptBase#hasname), [Prob(float)](/api/Global/Standing/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Standing/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Standing/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Standing/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Standing/StandingItemScriptBase#model), [Movable](/api/Global/Standing/StandingItemScriptBase#movable), [Passage](/api/Global/Standing/StandingItemScriptBase#passage), [State](/api/Global/Standing/StandingItemScriptBase#state), [MaxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [Defense](/api/Global/Standing/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ChopLeg()

```csharp
public ChopLeg()
```

## Fields

### _phase

```csharp
private ChopLeg.LegPhase _phase
```

#### Field Value

**Type:** Global.ChopLeg.LegPhase

### _type

```csharp
private ChopLeg.LegType _type
```

#### Field Value

**Type:** Global.ChopLeg.LegType

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

### attackRange

```csharp
private float attackRange
```

#### Field Value

**Type:** System.Single

### canCancel

```csharp
public bool canCancel
```

#### Field Value

**Type:** System.Boolean

### clickMax

```csharp
private const int clickMax = 3
```

#### Field Value

**Type:** System.Int32

### clickTimer

```csharp
private Timer clickTimer
```

#### Field Value

**Type:** Global.Timer

### currentClickCount

```csharp
private int currentClickCount
```

#### Field Value

**Type:** System.Int32

### currentGateOpenSpeed

```csharp
public float currentGateOpenSpeed
```

#### Field Value

**Type:** System.Single

### currentPassage

```csharp
private PassageObjectModel currentPassage
```

#### Field Value

**Type:** Global.PassageObjectModel

### Damage

```csharp
public const float Damage = 50
```

#### Field Value

**Type:** System.Single

### delayMax

```csharp
private float delayMax
```

#### Field Value

**Type:** System.Single

### delayMin

```csharp
private float delayMin
```

#### Field Value

**Type:** System.Single

### deleteRange

```csharp
private float deleteRange
```

#### Field Value

**Type:** System.Single

### movNodes

```csharp
private List<MapNode> movNodes
```

#### Field Value

**Type:** System.Collections.Generic.List{MapNode}

### randomEvent

```csharp
public FallingLegEvent randomEvent
```

#### Field Value

**Type:** Global.FallingLegEvent

## Properties

### attackDelayTime

```csharp
private float attackDelayTime { get; }
```

#### Property Value

**Type:** System.Single

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

### MakeWorkerEffect(UnitModel)

```csharp
private void MakeWorkerEffect(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

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
