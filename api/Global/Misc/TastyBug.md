---
uid: Global.TastyBug
canonical_path: /api/Global/Misc/TastyBug
---

# Class TastyBug

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TastyBug : StandingItemScriptBase
```

#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Standing/StandingItemScriptBase) → TastyBug

## Inherited Members
[soundDistDobule](/api/Global/Standing/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Standing/StandingItemScriptBase#model), [_animScript](/api/Global/Standing/StandingItemScriptBase#animscript), [_state](/api/Global/Standing/StandingItemScriptBase#state), [name](/api/Global/Standing/StandingItemScriptBase#name), [_maxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [_defense](/api/Global/Standing/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Standing/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Standing/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/Global/Standing/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Standing/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Standing/StandingItemScriptBase#isinrange-unitmodel-float), [OnIgnoreDamage(UnitModel)](/api/Global/Standing/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/Global/Standing/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/Global/Standing/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/Global/Standing/StandingItemScriptBase#getname), [SetName(string)](/api/Global/Standing/StandingItemScriptBase#setname-string), [HasName()](/api/Global/Standing/StandingItemScriptBase#hasname), [Prob(float)](/api/Global/Standing/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Standing/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Standing/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Standing/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Standing/StandingItemScriptBase#model), [Movable](/api/Global/Standing/StandingItemScriptBase#movable), [Passage](/api/Global/Standing/StandingItemScriptBase#passage), [State](/api/Global/Standing/StandingItemScriptBase#state), [MaxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [Defense](/api/Global/Standing/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### TastyBug()

```csharp
public TastyBug()
```

## Fields

### _alive

```csharp
private TastyBug.BugAlive _alive
```

#### Field Value

**Type:** Global.TastyBug.BugAlive

### _bugState

```csharp
private TastyBug.BugState _bugState
```

#### Field Value

**Type:** Global.TastyBug.BugState

### _type

```csharp
private TastyBug.BugType _type
```

#### Field Value

**Type:** Global.TastyBug.BugType

### animScript

```csharp
public TastyBugAnim animScript
```
#INC


#### Field Value

**Type:** Global.TastyBugAnim

### appearEffectMake

```csharp
private bool appearEffectMake
```
#INC


#### Field Value

**Type:** System.Boolean

### creatureHeal

```csharp
public const int creatureHeal = 18
```
#INC


#### Field Value

**Type:** System.Int32

### defaultMoveFreq

```csharp
public const float defaultMoveFreq = 0
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

### eatRange

```csharp
public const float eatRange = 0.4
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

### healRange

```csharp
public const float healRange = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### itemHeal

```csharp
public const int itemHeal = 18
```
#INC


#### Field Value

**Type:** System.Int32

### mentalDamage

```csharp
public const int mentalDamage = 6
```
#INC


#### Field Value

**Type:** System.Int32

### moveTimer

```csharp
public Timer moveTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### nodeList

```csharp
public List<MapNode> nodeList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MapNode}

### randomEvent

```csharp
public BugsForFoodEvent randomEvent
```
#INC


#### Field Value

**Type:** Global.BugsForFoodEvent

### sound_default

```csharp
public const string sound_default = "RandomEvent/TastyBugs/TastyBug_Default"
```
#INC


#### Field Value

**Type:** System.String

### speed

```csharp
public const float speed = 0.2
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

### volume

```csharp
public const float volume = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### workerHeal

```csharp
public const int workerHeal = 12
```
#INC


#### Field Value

**Type:** System.Int32

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
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### CheckDistance(UnitModel)

```csharp
public float CheckDistance(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Single

### CheckInRange()

```csharp
public bool CheckInRange()
```
#INC


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

### HealInRange()

```csharp
public void HealInRange()
```
#INC


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

### IsAttackable()

```csharp
public override bool IsAttackable()
```
#INC


#### Returns

**Type:** System.Boolean

### MoveAround()

```csharp
public void MoveAround()
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

### ReadyToMove()

```csharp
public void ReadyToMove()
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

### SetEvent(BugsForFoodEvent)

```csharp
public void SetEvent(BugsForFoodEvent bff)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bff` | `Global.BugsForFoodEvent` |  |

### SetType(BugType)

```csharp
public void SetType(TastyBug.BugType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.TastyBug.BugType` |  |

### Type()

```csharp
public TastyBug.BugType Type()
```

#### Returns

**Type:** Global.TastyBug.BugType
