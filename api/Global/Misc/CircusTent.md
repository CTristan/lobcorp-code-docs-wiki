---
uid: Global.CircusTent
canonical_path: /api/Global/Misc/CircusTent
---

# Class CircusTent

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CircusTent : BoomerCircusScript
```
old tent ordeal thing
#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Standing/StandingItemScriptBase) → [BoomerCircusScript](/api/Global/Script/BoomerCircusScript) → CircusTent

## Inherited Members
[randomEvent](/api/Global/Script/BoomerCircusScript#randomevent), [soundDistDobule](/api/Global/Standing/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Standing/StandingItemScriptBase#model), [_animScript](/api/Global/Standing/StandingItemScriptBase#animscript), [_state](/api/Global/Standing/StandingItemScriptBase#state), [name](/api/Global/Standing/StandingItemScriptBase#name), [_maxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [_defense](/api/Global/Standing/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Standing/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Standing/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/Global/Standing/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Standing/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Standing/StandingItemScriptBase#isinrange-unitmodel-float), [OnBreakDown()](/api/Global/Standing/StandingItemScriptBase#onbreakdown), [OnIgnoreDamage(UnitModel)](/api/Global/Standing/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/Global/Standing/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/Global/Standing/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/Global/Standing/StandingItemScriptBase#getname), [SetName(string)](/api/Global/Standing/StandingItemScriptBase#setname-string), [HasName()](/api/Global/Standing/StandingItemScriptBase#hasname), [Prob(float)](/api/Global/Standing/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Standing/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Standing/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Standing/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Standing/StandingItemScriptBase#model), [Movable](/api/Global/Standing/StandingItemScriptBase#movable), [Passage](/api/Global/Standing/StandingItemScriptBase#passage), [State](/api/Global/Standing/StandingItemScriptBase#state), [MaxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [Defense](/api/Global/Standing/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CircusTent()

```csharp
public CircusTent()
```

## Fields

### _tState

```csharp
private CircusTent.TentState _tState
```

#### Field Value

**Type:** Global.CircusTent.TentState

### animScript

```csharp
public CircusTentAnim animScript
```
#INC


#### Field Value

**Type:** Global.CircusTentAnim

### appearEffectMake

```csharp
private bool appearEffectMake
```
#INC


#### Field Value

**Type:** System.Boolean

### defaultSound

```csharp
public SoundEffectPlayer defaultSound
```
#INC


#### Field Value

**Type:** Global.SoundEffectPlayer

### enableDelay

```csharp
public Timer enableDelay
```
#INC


#### Field Value

**Type:** Global.Timer

### textUI

```csharp
public Text textUI
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

## Methods

### AppearEffect()

```csharp
private void AppearEffect()
```
#INC


### CanRangeInCamera()

```csharp
public bool CanRangeInCamera()
```
#INC


#### Returns

**Type:** System.Boolean

### CanTakePhsyicalDamage(UnitModel)

```csharp
public override bool CanTakePhsyicalDamage(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### CreateBoomer()

```csharp
public void CreateBoomer()
```
#INC


### DelayedEnable(float)

```csharp
public void DelayedEnable(float delay)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `delay` | `System.Single` |  |

### Init()

```csharp
public override void Init()
```
#INC


### IsActive()

```csharp
public override bool IsActive()
```
#INC


#### Returns

**Type:** System.Boolean

### IsAttackable()

```csharp
public override bool IsAttackable()
```
#INC


#### Returns

**Type:** System.Boolean

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

### SetActive(bool)

```csharp
public override void SetActive(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetEvent(BoomerCircusEvent)

```csharp
public override void SetEvent(BoomerCircusEvent bce)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bce` | `Global.BoomerCircusEvent` |  |
