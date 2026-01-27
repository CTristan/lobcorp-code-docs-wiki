---
uid: Global.DaughterBug
canonical_path: /api/Global/Misc/DaughterBug
---

# Class DaughterBug

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DaughterBug : HordeOfBugsScript
```
#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Standing/StandingItemScriptBase) → [HordeOfBugsScript](/api/Global/Script/HordeOfBugsScript) → DaughterBug

## Inherited Members
[randomEvent](/api/Global/Script/HordeOfBugsScript#randomevent), [soundDistDobule](/api/Global/Standing/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Standing/StandingItemScriptBase#model), [_animScript](/api/Global/Standing/StandingItemScriptBase#animscript), [_state](/api/Global/Standing/StandingItemScriptBase#state), [name](/api/Global/Standing/StandingItemScriptBase#name), [_maxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [_defense](/api/Global/Standing/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Standing/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Standing/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/Global/Standing/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Standing/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Standing/StandingItemScriptBase#isinrange-unitmodel-float), [IsAttackable()](/api/Global/Standing/StandingItemScriptBase#isattackable), [OnIgnoreDamage(UnitModel)](/api/Global/Standing/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/Global/Standing/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/Global/Standing/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/Global/Standing/StandingItemScriptBase#getname), [SetName(string)](/api/Global/Standing/StandingItemScriptBase#setname-string), [HasName()](/api/Global/Standing/StandingItemScriptBase#hasname), [Prob(float)](/api/Global/Standing/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Standing/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Standing/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Standing/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Standing/StandingItemScriptBase#model), [Movable](/api/Global/Standing/StandingItemScriptBase#movable), [Passage](/api/Global/Standing/StandingItemScriptBase#passage), [State](/api/Global/Standing/StandingItemScriptBase#state), [MaxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [Defense](/api/Global/Standing/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DaughterBug()

```csharp
public DaughterBug()
```

## Fields

### _attackCount

```csharp
private int _attackCount
```
#INC


#### Field Value

**Type:** System.Int32

### _currentTarget

```csharp
private UnitModel _currentTarget
```
#INC


#### Field Value

**Type:** Global.UnitModel

### _dState

```csharp
private DaughterBug.DaughterState _dState
```

#### Field Value

**Type:** Global.DaughterBug.DaughterState

### _phase

```csharp
private DaughterBug.DaughterPhase _phase
```

#### Field Value

**Type:** Global.DaughterBug.DaughterPhase

### animScript

```csharp
public DaughterBugAnim animScript
```
#INC


#### Field Value

**Type:** Global.DaughterBugAnim

### appearEffectMake

```csharp
private bool appearEffectMake
```
#INC


#### Field Value

**Type:** System.Boolean

### attackDelay

```csharp
public const float attackDelay = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### attackDelayTimer

```csharp
public Timer attackDelayTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### attackDirection

```csharp
private UnitDirection attackDirection
```
#INC


#### Field Value

**Type:** Global.UnitDirection

### attackRange

```csharp
public const float attackRange = 5
```
#INC


#### Field Value

**Type:** System.Single

### damagedUnits

```csharp
private List<UnitModel> damagedUnits
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

### defaultRange

```csharp
public const float defaultRange = 2
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

### makeChildFreq

```csharp
public const float makeChildFreq = 10
```
#INC


#### Field Value

**Type:** System.Single

### oldPosX

```csharp
private float oldPosX
```
#INC


#### Field Value

**Type:** System.Single

### sound_default

```csharp
public const string sound_default = "RandomEvent/Default"
```
#INC


#### Field Value

**Type:** System.String

### teleportDelay

```csharp
public const float teleportDelay = 2
```
#INC


#### Field Value

**Type:** System.Single

### teleportDelayTimer

```csharp
public Timer teleportDelayTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### teleportFreq

```csharp
public const float teleportFreq = 2
```
#INC


#### Field Value

**Type:** System.Single

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

### DelayedEnable(float)

```csharp
public void DelayedEnable(float delay)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `delay` | `System.Single` |  |

### Enable(UnitDirection)

```csharp
public void Enable(UnitDirection direction)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `direction` | `Global.UnitDirection` |  |

### EncounterWorker()

```csharp
private void EncounterWorker()
```
#INC


### FindTarget()

```csharp
private void FindTarget()
```
#INC


### GiveDamageInRange(float, float)

```csharp
public void GiveDamageInRange(float range, float dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `dmg` | `System.Single` |  |

### Init()

```csharp
public override void Init()
```
#INC


### IsActive()

```csharp
public bool IsActive()
```
#INC


#### Returns

**Type:** System.Boolean

### IsHostile(UnitModel)

```csharp
private bool IsHostile(UnitModel u)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `u` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### OnBreakDown()

```csharp
public override void OnBreakDown()
```
#INC


### OnClick()

```csharp
public void OnClick()
```
#INC


### OnEnable()

```csharp
public void OnEnable()
```
#INC


### OnEndAttack()

```csharp
public void OnEndAttack()
```
#INC


### OnEndDigIn()

```csharp
public void OnEndDigIn()
```
#INC


### OnEndDigOut()

```csharp
public void OnEndDigOut()
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

### ProccessAttack(float)

```csharp
private void ProccessAttack(float baseRange)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `baseRange` | `System.Single` |  |

### ProccessMoving()

```csharp
private void ProccessMoving()
```
#INC


### ReadyToTeleport()

```csharp
public void ReadyToTeleport()
```
#INC


### SetActive(bool)

```csharp
public void SetActive(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetEvent(HordeOfBugs)

```csharp
public override void SetEvent(HordeOfBugs hob)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `hob` | `Global.HordeOfBugs` |  |

### SetSpawnPosition(GrandmaBug)

```csharp
public void SetSpawnPosition(GrandmaBug grand)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `grand` | `Global.GrandmaBug` |  |

### StartAttack()

```csharp
private void StartAttack()
```
#INC


### StartTeleport()

```csharp
private void StartTeleport()
```
#INC

