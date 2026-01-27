---
uid: Global.BirdEggObject
canonical_path: /api/Global/Object/BirdEggObject
---

# Class BirdEggObject

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BirdEggObject : StandingItemScriptBase
```

Unused version of the eggs for [Apocalypse Bird](/api/Global/Misc/BossBird)'s fight.

See [BossEggBase](/api/Global/Misc/BossEggBase) for the used version

#unused


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Standing/StandingItemScriptBase) → BirdEggObject

## Inherited Members
[soundDistDobule](/api/Global/Standing/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Standing/StandingItemScriptBase#model), [_animScript](/api/Global/Standing/StandingItemScriptBase#animscript), [_state](/api/Global/Standing/StandingItemScriptBase#state), [name](/api/Global/Standing/StandingItemScriptBase#name), [_maxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [_defense](/api/Global/Standing/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Standing/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Standing/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [Init()](/api/Global/Standing/StandingItemScriptBase#init), [SetAnimScript(StandingItemAnim)](/api/Global/Standing/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Standing/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Standing/StandingItemScriptBase#isinrange-unitmodel-float), [CanTakePhsyicalDamage(UnitModel)](/api/Global/Standing/StandingItemScriptBase#cantakephsyicaldamage-unitmodel), [IsAttackable()](/api/Global/Standing/StandingItemScriptBase#isattackable), [OnFixedUpdate(StandingItemModel)](/api/Global/Standing/StandingItemScriptBase#onfixedupdate-standingitemmodel), [OnIgnoreDamage(UnitModel)](/api/Global/Standing/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/Global/Standing/StandingItemScriptBase#ondestroystandingitem), [SetName(string)](/api/Global/Standing/StandingItemScriptBase#setname-string), [Prob(float)](/api/Global/Standing/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Standing/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Standing/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Standing/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Standing/StandingItemScriptBase#model), [Movable](/api/Global/Standing/StandingItemScriptBase#movable), [Passage](/api/Global/Standing/StandingItemScriptBase#passage), [State](/api/Global/Standing/StandingItemScriptBase#state), [MaxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [Defense](/api/Global/Standing/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BirdEggObject()

```csharp
public BirdEggObject()
```

## Fields

### breakDown

```csharp
private bool breakDown
```
#INC


#### Field Value

**Type:** System.Boolean

### halfActivated

```csharp
private bool halfActivated
```
#INC


#### Field Value

**Type:** System.Boolean

### sep

```csharp
private SoundEffectPlayer sep
```
#INC


#### Field Value

**Type:** Global.SoundEffectPlayer

## Properties

### animScript

```csharp
private BirdEggAnim animScript { get; }
```

#### Property Value

**Type:** Global.BirdEggAnim

## Methods

### ActivateAnimHalf()

```csharp
public void ActivateAnimHalf()
```
#INC


### ActivateScript()

```csharp
public void ActivateScript()
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

### IsEnabled()

```csharp
public bool IsEnabled()
```
#INC


#### Returns

**Type:** System.Boolean

### OnBreakDown()

```csharp
public override void OnBreakDown()
```
#INC


### OnTakePhyisclaDamage(float)

```csharp
public override void OnTakePhyisclaDamage(float damage)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Single` |  |

### SetSound(SoundEffectPlayer)

```csharp
public void SetSound(SoundEffectPlayer sep)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sep` | `Global.SoundEffectPlayer` |  |
