---
uid: Global.BossBirdGateway
canonical_path: /api/Global/Misc/BossBirdGateway
---

# Class BossBirdGateway

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BossBirdGateway : StandingItemScriptBase
```

Unused version of Entrance to the Black Forest, as seen in [Apocalypse Bird](/api/Global/Misc/BossBird)'s fight.

See [BossGateWay](/api/Global/Misc/BossGateWay) for the used version of this.
#unused


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Standing/StandingItemScriptBase) → BossBirdGateway

## Inherited Members
[soundDistDobule](/api/Global/Standing/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Standing/StandingItemScriptBase#model), [_animScript](/api/Global/Standing/StandingItemScriptBase#animscript), [_state](/api/Global/Standing/StandingItemScriptBase#state), [name](/api/Global/Standing/StandingItemScriptBase#name), [_maxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [_defense](/api/Global/Standing/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Standing/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Standing/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/Global/Standing/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Standing/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Standing/StandingItemScriptBase#isinrange-unitmodel-float), [CanTakePhsyicalDamage(UnitModel)](/api/Global/Standing/StandingItemScriptBase#cantakephsyicaldamage-unitmodel), [IsAttackable()](/api/Global/Standing/StandingItemScriptBase#isattackable), [OnBreakDown()](/api/Global/Standing/StandingItemScriptBase#onbreakdown), [OnIgnoreDamage(UnitModel)](/api/Global/Standing/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/Global/Standing/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/Global/Standing/StandingItemScriptBase#ontakephyiscladamage-float), [Prob(float)](/api/Global/Standing/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Standing/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Standing/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Standing/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Standing/StandingItemScriptBase#model), [Movable](/api/Global/Standing/StandingItemScriptBase#movable), [Passage](/api/Global/Standing/StandingItemScriptBase#passage), [State](/api/Global/Standing/StandingItemScriptBase#state), [MaxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [Defense](/api/Global/Standing/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BossBirdGateway()

```csharp
public BossBirdGateway()
```

## Fields

### __GatewayState

```csharp
private BossBirdGateway.GateWayState __GatewayState
```

#### Field Value

**Type:** Global.BossBirdGateway.GateWayState

### bigBird

```csharp
private BigBird bigBird
```
#INC


#### Field Value

**Type:** Global.BigBird

### longBird

```csharp
private LongBird longBird
```
#INC


#### Field Value

**Type:** Global.LongBird

### mentalDamage

```csharp
private const float mentalDamage = 2
```
#INC


#### Field Value

**Type:** System.Single

### mentalDamageFreq

```csharp
private const float mentalDamageFreq = 1
```
#INC


#### Field Value

**Type:** System.Single

### mentalDamageTimer

```csharp
private Timer mentalDamageTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### smallBird

```csharp
private SmallBird smallBird
```
#INC


#### Field Value

**Type:** Global.SmallBird

### stateChecker

```csharp
private Timer stateChecker
```
#INC


#### Field Value

**Type:** Global.Timer

### stateCheckFreq

```csharp
private const float stateCheckFreq = 5
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### animScript

```csharp
public BossBirdGatewayAnim animScript { get; }
```

#### Property Value

**Type:** Global.BossBirdGatewayAnim

### gateWayState

```csharp
public BossBirdGateway.GateWayState gateWayState { get; }
```

#### Property Value

**Type:** Global.BossBirdGateway.GateWayState

## Methods

### BirdsCheck()

```csharp
private void BirdsCheck()
```
#INC


### GetName()

```csharp
public override string GetName()
```
#INC


#### Returns

**Type:** System.String

### HasName()

```csharp
public override bool HasName()
```
#INC


#### Returns

**Type:** System.Boolean

### Init()

```csharp
public override void Init()
```
#INC
#code-generated


### OnEnterBird()

```csharp
public void OnEnterBird()
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

### OnSetState()

```csharp
private void OnSetState()
```
#INC


### SetBirds(BigBird, SmallBird, LongBird)

```csharp
public void SetBirds(BigBird big, SmallBird small, LongBird @long)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `big` | `Global.BigBird` |  |
| `small` | `Global.SmallBird` |  |
| `long` | `Global.LongBird` |  |

### SetName(string)

```csharp
public override void SetName(string str)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |

### TakeNearMentalDamage()

```csharp
private void TakeNearMentalDamage()
```
#INC

