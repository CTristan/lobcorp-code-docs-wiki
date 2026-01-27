---
uid: Global.CircusBoomer
canonical_path: /api/Global/Misc/CircusBoomer
---

# Class CircusBoomer

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CircusBoomer : BoomerCircusScript
```

old red dawn, I guess

#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Standing/StandingItemScriptBase) → [BoomerCircusScript](/api/Global/Script/BoomerCircusScript) → CircusBoomer

## Inherited Members
[randomEvent](/api/Global/Script/BoomerCircusScript#randomevent), [soundDistDobule](/api/Global/Standing/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Standing/StandingItemScriptBase#model), [_animScript](/api/Global/Standing/StandingItemScriptBase#animscript), [_state](/api/Global/Standing/StandingItemScriptBase#state), [name](/api/Global/Standing/StandingItemScriptBase#name), [_maxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [_defense](/api/Global/Standing/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Standing/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Standing/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/Global/Standing/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Standing/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Standing/StandingItemScriptBase#isinrange-unitmodel-float), [IsAttackable()](/api/Global/Standing/StandingItemScriptBase#isattackable), [OnIgnoreDamage(UnitModel)](/api/Global/Standing/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/Global/Standing/StandingItemScriptBase#ondestroystandingitem), [GetName()](/api/Global/Standing/StandingItemScriptBase#getname), [SetName(string)](/api/Global/Standing/StandingItemScriptBase#setname-string), [HasName()](/api/Global/Standing/StandingItemScriptBase#hasname), [Prob(float)](/api/Global/Standing/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Standing/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Standing/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Standing/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Standing/StandingItemScriptBase#model), [Movable](/api/Global/Standing/StandingItemScriptBase#movable), [Passage](/api/Global/Standing/StandingItemScriptBase#passage), [State](/api/Global/Standing/StandingItemScriptBase#state), [MaxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [Defense](/api/Global/Standing/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CircusBoomer()

```csharp
public CircusBoomer()
```

## Fields

### _bState

```csharp
private CircusBoomer.BoomerState _bState
```

#### Field Value

**Type:** Global.CircusBoomer.BoomerState

### _phase

```csharp
private CircusBoomer.BoomerPhase _phase
```

#### Field Value

**Type:** Global.CircusBoomer.BoomerPhase

### animScript

```csharp
public CircusBoomerAnim animScript
```
#INC


#### Field Value

**Type:** Global.CircusBoomerAnim

### appearEffectMake

```csharp
private bool appearEffectMake
```
#INC


#### Field Value

**Type:** System.Boolean

### boomFreq

```csharp
public const float boomFreq = 2
```
#INC


#### Field Value

**Type:** System.Single

### boomRange

```csharp
public const float boomRange = 7
```
#INC


#### Field Value

**Type:** System.Single

### boomTimer

```csharp
public Timer boomTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### canTakeDmg

```csharp
public bool canTakeDmg
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

### detectRange

```csharp
public const float detectRange = 3.25
```
#INC


#### Field Value

**Type:** System.Single

### dmg

```csharp
private const int dmg = 50
```
#INC


#### Field Value

**Type:** System.Int32

### dmgPerClick

```csharp
public const float dmgPerClick = 30
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

### explosionDmg

```csharp
private DamageInfo explosionDmg
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### index

```csharp
public int index
```
#INC


#### Field Value

**Type:** System.Int32

### indexZ

```csharp
public float indexZ
```
#INC


#### Field Value

**Type:** System.Single

### moveSpeed

```csharp
public const float moveSpeed = 3
```
#INC


#### Field Value

**Type:** System.Single

### readyToBomb

```csharp
public bool readyToBomb
```
#INC


#### Field Value

**Type:** System.Boolean

### textUI

```csharp
public Text textUI
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### yValueFix

```csharp
public const float yValueFix = -18
```
#INC


#### Field Value

**Type:** System.Single

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

### DelayedEnable(float)

```csharp
public void DelayedEnable(float delay)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `delay` | `System.Single` |  |

### GetPhase()

```csharp
public CircusBoomer.BoomerPhase GetPhase()
```

#### Returns

**Type:** Global.CircusBoomer.BoomerPhase

### GiveDamageInRange(float)

```csharp
public void GiveDamageInRange(float range)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |

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

### MakeExplodeEffect(UnitDirection, WorkerModel, float)

```csharp
public void MakeExplodeEffect(UnitDirection dir, WorkerModel target, float size)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dir` | `Global.UnitDirection` |  |
| `target` | `Global.WorkerModel` |  |
| `size` | `System.Single` |  |

### MakeExplodeEffect(Vector3, float)

```csharp
public void MakeExplodeEffect(Vector3 pos, float size)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `size` | `System.Single` |  |

### Move()

```csharp
public void Move()
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

### OnTakePhyisclaDamage(float)

```csharp
public override void OnTakePhyisclaDamage(float damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Single` |  |

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

### SetPhase(BoomerPhase)

```csharp
public void SetPhase(CircusBoomer.BoomerPhase phase)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `phase` | `Global.CircusBoomer.BoomerPhase` |  |

### TargetInRage(float)

```csharp
public bool TargetInRage(float range)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |

#### Returns

**Type:** System.Boolean
