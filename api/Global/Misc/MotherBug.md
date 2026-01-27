---
uid: Global.MotherBug
canonical_path: /api/Global/Misc/MotherBug
---

# Class MotherBug

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MotherBug : HordeOfBugsScript
```

#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Standing/StandingItemScriptBase) → [HordeOfBugsScript](/api/Global/Script/HordeOfBugsScript) → MotherBug

## Inherited Members
[randomEvent](/api/Global/Script/HordeOfBugsScript#randomevent), [soundDistDobule](/api/Global/Standing/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Standing/StandingItemScriptBase#model), [_animScript](/api/Global/Standing/StandingItemScriptBase#animscript), [_state](/api/Global/Standing/StandingItemScriptBase#state), [name](/api/Global/Standing/StandingItemScriptBase#name), [_maxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [_defense](/api/Global/Standing/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Standing/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Standing/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/Global/Standing/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Standing/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Standing/StandingItemScriptBase#isinrange-unitmodel-float), [IsAttackable()](/api/Global/Standing/StandingItemScriptBase#isattackable), [OnBreakDown()](/api/Global/Standing/StandingItemScriptBase#onbreakdown), [OnDestroyStandingItem()](/api/Global/Standing/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/Global/Standing/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/Global/Standing/StandingItemScriptBase#getname), [SetName(string)](/api/Global/Standing/StandingItemScriptBase#setname-string), [HasName()](/api/Global/Standing/StandingItemScriptBase#hasname), [Prob(float)](/api/Global/Standing/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Standing/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Standing/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Standing/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Standing/StandingItemScriptBase#model), [Movable](/api/Global/Standing/StandingItemScriptBase#movable), [Passage](/api/Global/Standing/StandingItemScriptBase#passage), [State](/api/Global/Standing/StandingItemScriptBase#state), [MaxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [Defense](/api/Global/Standing/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MotherBug()

```csharp
public MotherBug()
```

## Fields

### _mState

```csharp
private MotherBug.MotherState _mState
```

#### Field Value

**Type:** Global.MotherBug.MotherState

### _phase

```csharp
private MotherBug.MotherPhase _phase
```

#### Field Value

**Type:** Global.MotherBug.MotherPhase

### _type

```csharp
private HordeOfBugsScript.BugType _type
```

#### Field Value

**Type:** Global.HordeOfBugsScript.BugType

### animScript

```csharp
public MotherBugAnim animScript
```
#INC


#### Field Value

**Type:** Global.MotherBugAnim

### appearEffectMake

```csharp
private bool appearEffectMake
```
#INC


#### Field Value

**Type:** System.Boolean

### canMakeChild

```csharp
private bool canMakeChild
```
#INC


#### Field Value

**Type:** System.Boolean

### damageInfo

```csharp
private DamageInfo damageInfo
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### daughterSrc

```csharp
public const string daughterSrc = "StandingItem/HordeOfBugs/DaughterBug"
```
#INC


#### Field Value

**Type:** System.String

### defaultMoveSpeed

```csharp
public const float defaultMoveSpeed = 2
```
#INC


#### Field Value

**Type:** System.Single

### defaultSound

```csharp
public SoundEffectPlayer defaultSound
```
#INC


#### Field Value

**Type:** Global.SoundEffectPlayer

### dmg

```csharp
private const int dmg = 100
```
#INC


#### Field Value

**Type:** System.Int32

### enableDelay

```csharp
public Timer enableDelay
```
#INC


#### Field Value

**Type:** Global.Timer

### entranceNode

```csharp
public MapNode entranceNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### exitNode

```csharp
public MapNode exitNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### makeChildFreq

```csharp
public const float makeChildFreq = 20
```
#INC


#### Field Value

**Type:** System.Single

### makeChildTimer

```csharp
public Timer makeChildTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### rangeMax

```csharp
public const float rangeMax = 3.7
```
#INC


#### Field Value

**Type:** System.Single

### rangeMin

```csharp
public const float rangeMin = 1.8
```
#INC


#### Field Value

**Type:** System.Single

### slowDownFreq

```csharp
public const float slowDownFreq = 1
```
#INC


#### Field Value

**Type:** System.Single

### slowMoveSpeed

```csharp
public const float slowMoveSpeed = 0.6
```
#INC


#### Field Value

**Type:** System.Single

### slowTimer

```csharp
public Timer slowTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### teleportingFreq

```csharp
public const float teleportingFreq = 1
```
#INC


#### Field Value

**Type:** System.Single

### teleportingTimer

```csharp
public Timer teleportingTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### teleportSpace

```csharp
public const float teleportSpace = 2.9
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

### CreateDaughter(int)

```csharp
public void CreateDaughter(int count)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `count` | `System.Int32` |  |

### DelayedEnable(float)

```csharp
public void DelayedEnable(float delay)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `delay` | `System.Single` |  |

### Enable()

```csharp
public void Enable()
```
#INC


### GiveDamageInRange(float, float)

```csharp
public void GiveDamageInRange(float rangeMax, float rangeMin)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rangeMax` | `System.Single` |  |
| `rangeMin` | `System.Single` |  |

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

### NodeSelection()

```csharp
public void NodeSelection()
```
#INC


### OnDisappear()

```csharp
public void OnDisappear()
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

### OnIgnoreDamage(UnitModel)

```csharp
public override bool OnIgnoreDamage(UnitModel attacker)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### ReadyToTeleport()

```csharp
public void ReadyToTeleport()
```
#INC


### RecoverSpeed()

```csharp
public void RecoverSpeed()
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

### SetPhase(MotherPhase)

```csharp
public void SetPhase(MotherBug.MotherPhase phase)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `phase` | `Global.MotherBug.MotherPhase` |  |

### SlowDown()

```csharp
public void SlowDown()
```
#INC


### TargetInRage(float, float)

```csharp
public bool TargetInRage(float rangeMax, float rangeMin)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rangeMax` | `System.Single` |  |
| `rangeMin` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### Teleport()

```csharp
public void Teleport()
```
#INC

