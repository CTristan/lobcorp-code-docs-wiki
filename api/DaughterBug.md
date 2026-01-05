# Class DaughterBug

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DaughterBug : HordeOfBugsScript
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/StandingItemScriptBase) → [HordeOfBugsScript](/api/HordeOfBugsScript) → DaughterBug

## Inherited Members
[randomEvent](/api/HordeOfBugsScript#randomevent), [soundDistDobule](/api/StandingItemScriptBase#sounddistdobule), [model](/api/StandingItemScriptBase#model), [_animScript](/api/StandingItemScriptBase#animscript), [_state](/api/StandingItemScriptBase#state), [name](/api/StandingItemScriptBase#name), [_maxHp](/api/StandingItemScriptBase#maxhp), [_defense](/api/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/StandingItemScriptBase#isinrange-unitmodel-float), [IsAttackable()](/api/StandingItemScriptBase#isattackable), [OnIgnoreDamage(UnitModel)](/api/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/StandingItemScriptBase#getname), [SetName(string)](/api/StandingItemScriptBase#setname-string), [HasName()](/api/StandingItemScriptBase#hasname), [Prob(float)](/api/StandingItemScriptBase#prob-float), [Prob(int)](/api/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/StandingItemScriptBase#checkcamerarange-float), [Model](/api/StandingItemScriptBase#model), [Movable](/api/StandingItemScriptBase#movable), [Passage](/api/StandingItemScriptBase#passage), [State](/api/StandingItemScriptBase#state), [MaxHp](/api/StandingItemScriptBase#maxhp), [Defense](/api/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DaughterBug()

```csharp
public DaughterBug()
```

## Fields

### animScript

```csharp
public DaughterBugAnim animScript
```

#### Field Value

**Type:** Global.DaughterBugAnim

### attackDelay

```csharp
public const float attackDelay = 0.5
```

#### Field Value

**Type:** System.Single

### attackDelayTimer

```csharp
public Timer attackDelayTimer
```

#### Field Value

**Type:** Global.Timer

### attackRange

```csharp
public const float attackRange = 5
```

#### Field Value

**Type:** System.Single

### defaultRange

```csharp
public const float defaultRange = 2
```

#### Field Value

**Type:** System.Single

### enableDelay

```csharp
public Timer enableDelay
```

#### Field Value

**Type:** Global.Timer

### makeChildFreq

```csharp
public const float makeChildFreq = 10
```

#### Field Value

**Type:** System.Single

### sound_default

```csharp
public const string sound_default = "RandomEvent/Default"
```

#### Field Value

**Type:** System.String

### teleportDelay

```csharp
public const float teleportDelay = 2
```

#### Field Value

**Type:** System.Single

### teleportDelayTimer

```csharp
public Timer teleportDelayTimer
```

#### Field Value

**Type:** Global.Timer

### teleportFreq

```csharp
public const float teleportFreq = 2
```

#### Field Value

**Type:** System.Single

### textUI

```csharp
public Text textUI
```

#### Field Value

**Type:** UnityEngine.UI.Text

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

### DelayedEnable(float)

```csharp
public void DelayedEnable(float delay)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `delay` | `System.Single` |  |

### Enable(UnitDirection)

```csharp
public void Enable(UnitDirection direction)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `direction` | `Global.UnitDirection` |  |

### GiveDamageInRange(float, float)

```csharp
public void GiveDamageInRange(float range, float dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `dmg` | `System.Single` |  |

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

### OnBreakDown()

```csharp
public override void OnBreakDown()
```

### OnClick()

```csharp
public void OnClick()
```

### OnEnable()

```csharp
public void OnEnable()
```

### OnEndAttack()

```csharp
public void OnEndAttack()
```

### OnEndDigIn()

```csharp
public void OnEndDigIn()
```

### OnEndDigOut()

```csharp
public void OnEndDigOut()
```

### OnFixedUpdate(StandingItemModel)

```csharp
public override void OnFixedUpdate(StandingItemModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.StandingItemModel` |  |

### ReadyToTeleport()

```csharp
public void ReadyToTeleport()
```

### SetActive(bool)

```csharp
public void SetActive(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetEvent(HordeOfBugs)

```csharp
public override void SetEvent(HordeOfBugs hob)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `hob` | `Global.HordeOfBugs` |  |

### SetSpawnPosition(GrandmaBug)

```csharp
public void SetSpawnPosition(GrandmaBug grand)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `grand` | `Global.GrandmaBug` |  |
