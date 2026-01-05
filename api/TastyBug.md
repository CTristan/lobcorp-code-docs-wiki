# Class TastyBug

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TastyBug : StandingItemScriptBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/StandingItemScriptBase) → TastyBug

## Inherited Members
[soundDistDobule](/api/StandingItemScriptBase#sounddistdobule), [model](/api/StandingItemScriptBase#model), [_animScript](/api/StandingItemScriptBase#animscript), [_state](/api/StandingItemScriptBase#state), [name](/api/StandingItemScriptBase#name), [_maxHp](/api/StandingItemScriptBase#maxhp), [_defense](/api/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/StandingItemScriptBase#isinrange-unitmodel-float), [OnIgnoreDamage(UnitModel)](/api/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/StandingItemScriptBase#getname), [SetName(string)](/api/StandingItemScriptBase#setname-string), [HasName()](/api/StandingItemScriptBase#hasname), [Prob(float)](/api/StandingItemScriptBase#prob-float), [Prob(int)](/api/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/StandingItemScriptBase#checkcamerarange-float), [Model](/api/StandingItemScriptBase#model), [Movable](/api/StandingItemScriptBase#movable), [Passage](/api/StandingItemScriptBase#passage), [State](/api/StandingItemScriptBase#state), [MaxHp](/api/StandingItemScriptBase#maxhp), [Defense](/api/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### TastyBug()

```csharp
public TastyBug()
```

## Fields

### animScript

```csharp
public TastyBugAnim animScript
```

#### Field Value

**Type:** Global.TastyBugAnim

### creatureHeal

```csharp
public const int creatureHeal = 18
```

#### Field Value

**Type:** System.Int32

### defaultMoveFreq

```csharp
public const float defaultMoveFreq = 0
```

#### Field Value

**Type:** System.Single

### defaultSound

```csharp
public SoundEffectPlayer defaultSound
```

#### Field Value

**Type:** Global.SoundEffectPlayer

### eatRange

```csharp
public const float eatRange = 0.4
```

#### Field Value

**Type:** System.Single

### enableDelay

```csharp
public Timer enableDelay
```

#### Field Value

**Type:** Global.Timer

### healRange

```csharp
public const float healRange = 0.5
```

#### Field Value

**Type:** System.Single

### itemHeal

```csharp
public const int itemHeal = 18
```

#### Field Value

**Type:** System.Int32

### mentalDamage

```csharp
public const int mentalDamage = 6
```

#### Field Value

**Type:** System.Int32

### moveTimer

```csharp
public Timer moveTimer
```

#### Field Value

**Type:** Global.Timer

### nodeList

```csharp
public List<MapNode> nodeList
```

#### Field Value

**Type:** System.Collections.Generic.List{MapNode}

### randomEvent

```csharp
public BugsForFoodEvent randomEvent
```

#### Field Value

**Type:** Global.BugsForFoodEvent

### sound_default

```csharp
public const string sound_default = "RandomEvent/TastyBugs/TastyBug_Default"
```

#### Field Value

**Type:** System.String

### speed

```csharp
public const float speed = 0.2
```

#### Field Value

**Type:** System.Single

### textUI

```csharp
public Text textUI
```

#### Field Value

**Type:** UnityEngine.UI.Text

### volume

```csharp
public const float volume = 0.5
```

#### Field Value

**Type:** System.Single

### workerHeal

```csharp
public const int workerHeal = 12
```

#### Field Value

**Type:** System.Int32

## Methods

### CanRangeInCamera()

```csharp
public bool CanRangeInCamera()
```

#### Returns

**Type:** System.Boolean

### CanTakePhsyicalDamage(UnitModel)

```csharp
public override bool CanTakePhsyicalDamage(UnitModel target)
```

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

#### Returns

**Type:** System.Boolean

### DelayedEnable(float)

```csharp
public void DelayedEnable(float delay)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `delay` | `System.Single` |  |

### HealInRange()

```csharp
public void HealInRange()
```

### Init()

```csharp
public override void Init()
```

### IsActive()

```csharp
public bool IsActive()
```

#### Returns

**Type:** System.Boolean

### IsAttackable()

```csharp
public override bool IsAttackable()
```

#### Returns

**Type:** System.Boolean

### MoveAround()

```csharp
public void MoveAround()
```

### OnBreakDown()

```csharp
public override void OnBreakDown()
```

### OnEnable()

```csharp
public void OnEnable()
```

### OnFixedUpdate(StandingItemModel)

```csharp
public override void OnFixedUpdate(StandingItemModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.StandingItemModel` |  |

### ReadyToMove()

```csharp
public void ReadyToMove()
```

### SetActive(bool)

```csharp
public void SetActive(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetEvent(BugsForFoodEvent)

```csharp
public void SetEvent(BugsForFoodEvent bff)
```

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
