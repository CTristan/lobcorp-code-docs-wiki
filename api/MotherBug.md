# Class MotherBug

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MotherBug : HordeOfBugsScript
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/StandingItemScriptBase) → [HordeOfBugsScript](/api/HordeOfBugsScript) → MotherBug

## Inherited Members
[randomEvent](/api/HordeOfBugsScript#randomevent), [soundDistDobule](/api/StandingItemScriptBase#sounddistdobule), [model](/api/StandingItemScriptBase#model), [_animScript](/api/StandingItemScriptBase#animscript), [_state](/api/StandingItemScriptBase#state), [name](/api/StandingItemScriptBase#name), [_maxHp](/api/StandingItemScriptBase#maxhp), [_defense](/api/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/StandingItemScriptBase#isinrange-unitmodel-float), [IsAttackable()](/api/StandingItemScriptBase#isattackable), [OnBreakDown()](/api/StandingItemScriptBase#onbreakdown), [OnDestroyStandingItem()](/api/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/StandingItemScriptBase#getname), [SetName(string)](/api/StandingItemScriptBase#setname-string), [HasName()](/api/StandingItemScriptBase#hasname), [Prob(float)](/api/StandingItemScriptBase#prob-float), [Prob(int)](/api/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/StandingItemScriptBase#checkcamerarange-float), [Model](/api/StandingItemScriptBase#model), [Movable](/api/StandingItemScriptBase#movable), [Passage](/api/StandingItemScriptBase#passage), [State](/api/StandingItemScriptBase#state), [MaxHp](/api/StandingItemScriptBase#maxhp), [Defense](/api/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### MotherBug()

```csharp
public MotherBug()
```

## Fields

### animScript

```csharp
public MotherBugAnim animScript
```

#### Field Value

**Type:** Global.MotherBugAnim

### daughterSrc

```csharp
public const string daughterSrc = "StandingItem/HordeOfBugs/DaughterBug"
```

#### Field Value

**Type:** System.String

### defaultMoveSpeed

```csharp
public const float defaultMoveSpeed = 2
```

#### Field Value

**Type:** System.Single

### defaultSound

```csharp
public SoundEffectPlayer defaultSound
```

#### Field Value

**Type:** Global.SoundEffectPlayer

### enableDelay

```csharp
public Timer enableDelay
```

#### Field Value

**Type:** Global.Timer

### entranceNode

```csharp
public MapNode entranceNode
```

#### Field Value

**Type:** Global.MapNode

### exitNode

```csharp
public MapNode exitNode
```

#### Field Value

**Type:** Global.MapNode

### makeChildFreq

```csharp
public const float makeChildFreq = 20
```

#### Field Value

**Type:** System.Single

### makeChildTimer

```csharp
public Timer makeChildTimer
```

#### Field Value

**Type:** Global.Timer

### rangeMax

```csharp
public const float rangeMax = 3.7
```

#### Field Value

**Type:** System.Single

### rangeMin

```csharp
public const float rangeMin = 1.8
```

#### Field Value

**Type:** System.Single

### slowDownFreq

```csharp
public const float slowDownFreq = 1
```

#### Field Value

**Type:** System.Single

### slowMoveSpeed

```csharp
public const float slowMoveSpeed = 0.6
```

#### Field Value

**Type:** System.Single

### slowTimer

```csharp
public Timer slowTimer
```

#### Field Value

**Type:** Global.Timer

### teleportingFreq

```csharp
public const float teleportingFreq = 1
```

#### Field Value

**Type:** System.Single

### teleportingTimer

```csharp
public Timer teleportingTimer
```

#### Field Value

**Type:** Global.Timer

### teleportSpace

```csharp
public const float teleportSpace = 2.9
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

### CreateDaughter(int)

```csharp
public void CreateDaughter(int count)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `count` | `System.Int32` |  |

### DelayedEnable(float)

```csharp
public void DelayedEnable(float delay)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `delay` | `System.Single` |  |

### Enable()

```csharp
public void Enable()
```

### GiveDamageInRange(float, float)

```csharp
public void GiveDamageInRange(float rangeMax, float rangeMin)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `rangeMax` | `System.Single` |  |
| `rangeMin` | `System.Single` |  |

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

### NodeSelection()

```csharp
public void NodeSelection()
```

### OnDisappear()

```csharp
public void OnDisappear()
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

### OnIgnoreDamage(UnitModel)

```csharp
public override bool OnIgnoreDamage(UnitModel attacker)
```

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

### RecoverSpeed()

```csharp
public void RecoverSpeed()
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

### TargetInRage(float, float)

```csharp
public bool TargetInRage(float rangeMax, float rangeMin)
```

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
