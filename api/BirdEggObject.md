# Class BirdEggObject

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BirdEggObject : StandingItemScriptBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/StandingItemScriptBase) → BirdEggObject

## Inherited Members
[soundDistDobule](/api/StandingItemScriptBase#sounddistdobule), [model](/api/StandingItemScriptBase#model), [_animScript](/api/StandingItemScriptBase#animscript), [_state](/api/StandingItemScriptBase#state), [name](/api/StandingItemScriptBase#name), [_maxHp](/api/StandingItemScriptBase#maxhp), [_defense](/api/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [Init()](/api/StandingItemScriptBase#init), [SetAnimScript(StandingItemAnim)](/api/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/StandingItemScriptBase#isinrange-unitmodel-float), [CanTakePhsyicalDamage(UnitModel)](/api/StandingItemScriptBase#cantakephsyicaldamage-unitmodel), [IsAttackable()](/api/StandingItemScriptBase#isattackable), [OnFixedUpdate(StandingItemModel)](/api/StandingItemScriptBase#onfixedupdate-standingitemmodel), [OnIgnoreDamage(UnitModel)](/api/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/StandingItemScriptBase#ondestroystandingitem), [SetName(string)](/api/StandingItemScriptBase#setname-string), [Prob(float)](/api/StandingItemScriptBase#prob-float), [Prob(int)](/api/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/StandingItemScriptBase#checkcamerarange-float), [Model](/api/StandingItemScriptBase#model), [Movable](/api/StandingItemScriptBase#movable), [Passage](/api/StandingItemScriptBase#passage), [State](/api/StandingItemScriptBase#state), [MaxHp](/api/StandingItemScriptBase#maxhp), [Defense](/api/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BirdEggObject()

```csharp
public BirdEggObject()
```

## Methods

### ActivateAnimHalf()

```csharp
public void ActivateAnimHalf()
```

### ActivateScript()

```csharp
public void ActivateScript()
```

### GetName()

```csharp
public override string GetName()
```

#### Returns

**Type:** System.String

### HasName()

```csharp
public override bool HasName()
```

#### Returns

**Type:** System.Boolean

### IsEnabled()

```csharp
public bool IsEnabled()
```

#### Returns

**Type:** System.Boolean

### OnBreakDown()

```csharp
public override void OnBreakDown()
```

### OnTakePhyisclaDamage(float)

```csharp
public override void OnTakePhyisclaDamage(float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Single` |  |

### SetSound(SoundEffectPlayer)

```csharp
public void SetSound(SoundEffectPlayer sep)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sep` | `Global.SoundEffectPlayer` |  |
