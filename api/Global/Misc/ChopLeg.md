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

Part of [BugsForFoodEvent](/api/Global/Event/BugsForFoodEvent), maybe? And some [FallingLegEvent](/api/Global/Event/FallingLegEvent) thing...
#unused 


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
#INC


#### Field Value

**Type:** System.String

### animScript

```csharp
public ChopLegAnim animScript
```
#INC


#### Field Value

**Type:** Global.ChopLegAnim

### attackDelay

```csharp
public Timer attackDelay
```
#INC


#### Field Value

**Type:** Global.Timer

### attackRange

```csharp
private float attackRange
```
#INC


#### Field Value

**Type:** System.Single

### canCancel

```csharp
public bool canCancel
```
#INC


#### Field Value

**Type:** System.Boolean

### clickMax

```csharp
private const int clickMax = 3
```
#INC


#### Field Value

**Type:** System.Int32

### clickTimer

```csharp
private Timer clickTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### currentClickCount

```csharp
private int currentClickCount
```
#INC


#### Field Value

**Type:** System.Int32

### currentGateOpenSpeed

```csharp
public float currentGateOpenSpeed
```
#INC


#### Field Value

**Type:** System.Single

### currentPassage

```csharp
private PassageObjectModel currentPassage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### Damage

```csharp
public const float Damage = 50
```
#INC


#### Field Value

**Type:** System.Single

### delayMax

```csharp
private float delayMax
```
#INC


#### Field Value

**Type:** System.Single

### delayMin

```csharp
private float delayMin
```
#INC


#### Field Value

**Type:** System.Single

### deleteRange

```csharp
private float deleteRange
```
#INC


#### Field Value

**Type:** System.Single

### movNodes

```csharp
private List<MapNode> movNodes
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MapNode}

### randomEvent

```csharp
public FallingLegEvent randomEvent
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### EndAttack()

```csharp
public void EndAttack()
```
#INC


### GetNearTargets()

```csharp
public List<UnitModel> GetNearTargets()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GetRangeTargets()

```csharp
public List<UnitModel> GetRangeTargets()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GiveDamage()

```csharp
public void GiveDamage()
```
#INC


### MakeWorkerEffect(UnitModel)

```csharp
private void MakeWorkerEffect(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### OnAppearEnd()

```csharp
public void OnAppearEnd()
```
#INC


### OnCancelFail()

```csharp
public void OnCancelFail()
```
#INC


### OnClick()

```csharp
public void OnClick()
```
#INC


### OnFixedUpdate(StandingItemModel)

```csharp
public override void OnFixedUpdate(StandingItemModel model)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.StandingItemModel` |  |

### SetEvent(FallingLegEvent)

```csharp
public void SetEvent(FallingLegEvent fle)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fle` | `Global.FallingLegEvent` |  |

### SetNodes()

```csharp
public void SetNodes()
```
#INC


### SetPassage(PassageObjectModel)

```csharp
public void SetPassage(PassageObjectModel targetPassage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targetPassage` | `Global.PassageObjectModel` |  |

### SetRandomPosition()

```csharp
public void SetRandomPosition()
```
#INC


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
#INC

