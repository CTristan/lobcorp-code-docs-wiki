# Class RandomEventRoot

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RandomEventRoot : StandingItemScriptBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/StandingItemScriptBase) → RandomEventRoot

## Inherited Members
[soundDistDobule](/api/StandingItemScriptBase#sounddistdobule), [model](/api/StandingItemScriptBase#model), [_animScript](/api/StandingItemScriptBase#animscript), [_state](/api/StandingItemScriptBase#state), [name](/api/StandingItemScriptBase#name), [_maxHp](/api/StandingItemScriptBase#maxhp), [_defense](/api/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [Init()](/api/StandingItemScriptBase#init), [SetAnimScript(StandingItemAnim)](/api/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/StandingItemScriptBase#isinrange-unitmodel-float), [CanTakePhsyicalDamage(UnitModel)](/api/StandingItemScriptBase#cantakephsyicaldamage-unitmodel), [IsAttackable()](/api/StandingItemScriptBase#isattackable), [OnFixedUpdate(StandingItemModel)](/api/StandingItemScriptBase#onfixedupdate-standingitemmodel), [OnBreakDown()](/api/StandingItemScriptBase#onbreakdown), [OnIgnoreDamage(UnitModel)](/api/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/StandingItemScriptBase#getname), [SetName(string)](/api/StandingItemScriptBase#setname-string), [HasName()](/api/StandingItemScriptBase#hasname), [Prob(float)](/api/StandingItemScriptBase#prob-float), [Prob(int)](/api/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/StandingItemScriptBase#checkcamerarange-float), [Model](/api/StandingItemScriptBase#model), [Movable](/api/StandingItemScriptBase#movable), [Passage](/api/StandingItemScriptBase#passage), [State](/api/StandingItemScriptBase#state), [MaxHp](/api/StandingItemScriptBase#maxhp), [Defense](/api/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### RandomEventRoot()

```csharp
public RandomEventRoot()
```

## Fields

### script

```csharp
public RandomEventBase script
```

#### Field Value

**Type:** Global.RandomEventBase

## Properties

### AudioSrc

```csharp
public AudioSource AudioSrc { get; }
```

#### Property Value

**Type:** UnityEngine.AudioSource

## Methods

### PlayBgm(string)

```csharp
public void PlayBgm(string src)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### ReturnBgm()

```csharp
public bool ReturnBgm()
```

#### Returns

**Type:** System.Boolean
