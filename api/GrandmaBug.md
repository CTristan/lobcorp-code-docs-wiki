# Class GrandmaBug

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GrandmaBug : HordeOfBugsScript
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/StandingItemScriptBase) → [HordeOfBugsScript](/api/HordeOfBugsScript) → GrandmaBug

## Inherited Members
[randomEvent](/api/HordeOfBugsScript#randomevent), [soundDistDobule](/api/StandingItemScriptBase#sounddistdobule), [model](/api/StandingItemScriptBase#model), [_animScript](/api/StandingItemScriptBase#animscript), [_state](/api/StandingItemScriptBase#state), [name](/api/StandingItemScriptBase#name), [_maxHp](/api/StandingItemScriptBase#maxhp), [_defense](/api/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/StandingItemScriptBase#isinrange-unitmodel-float), [OnBreakDown()](/api/StandingItemScriptBase#onbreakdown), [OnIgnoreDamage(UnitModel)](/api/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/StandingItemScriptBase#getname), [SetName(string)](/api/StandingItemScriptBase#setname-string), [HasName()](/api/StandingItemScriptBase#hasname), [Prob(float)](/api/StandingItemScriptBase#prob-float), [Prob(int)](/api/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/StandingItemScriptBase#checkcamerarange-float), [Model](/api/StandingItemScriptBase#model), [Movable](/api/StandingItemScriptBase#movable), [Passage](/api/StandingItemScriptBase#passage), [State](/api/StandingItemScriptBase#state), [MaxHp](/api/StandingItemScriptBase#maxhp), [Defense](/api/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### GrandmaBug()

```csharp
public GrandmaBug()
```

## Fields

### animScript

```csharp
public GrandmaBugAnim animScript
```

#### Field Value

**Type:** Global.GrandmaBugAnim

### AppearDelayMax

```csharp
public const float AppearDelayMax = 4
```

#### Field Value

**Type:** System.Single

### AppearDelayMin

```csharp
public const float AppearDelayMin = 2
```

#### Field Value

**Type:** System.Single

### damageRange

```csharp
public const float damageRange = 5
```

#### Field Value

**Type:** System.Single

### defaultRange

```csharp
public const float defaultRange = 2
```

#### Field Value

**Type:** System.Single

### defaultSound

```csharp
public SoundEffectPlayer defaultSound
```

#### Field Value

**Type:** Global.SoundEffectPlayer

### disappearMentalDamage

```csharp
public const float disappearMentalDamage = 30
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

### motherBugDefualt

```csharp
public const int motherBugDefualt = 2
```

#### Field Value

**Type:** System.Int32

### motherBugMax

```csharp
public const int motherBugMax = 10
```

#### Field Value

**Type:** System.Int32

### nodes

```csharp
public List<MapNode> nodes
```

#### Field Value

**Type:** System.Collections.Generic.List{MapNode}

### RemainDelayMax

```csharp
public const float RemainDelayMax = 40
```

#### Field Value

**Type:** System.Single

### RemainDelayMin

```csharp
public const float RemainDelayMin = 20
```

#### Field Value

**Type:** System.Single

### sound_default

```csharp
public const string sound_default = "RandomEvent/Default"
```

#### Field Value

**Type:** System.String

### spawnChildTimer

```csharp
public Timer spawnChildTimer
```

#### Field Value

**Type:** Global.Timer

### SpawnDelayMax

```csharp
public const float SpawnDelayMax = 15
```

#### Field Value

**Type:** System.Single

### SpawnDelayMin

```csharp
public const float SpawnDelayMin = 5
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

### teleportTimer

```csharp
public Timer teleportTimer
```

#### Field Value

**Type:** Global.Timer

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

### Disappear()

```csharp
public void Disappear()
```

### Enable()

```csharp
public void Enable()
```

### GiveDamageInRange(float)

```csharp
public void GiveDamageInRange(float range)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |

### Init()

```csharp
public override void Init()
```

### InvokeAppearDamage()

```csharp
public void InvokeAppearDamage()
```

### InvokeSpawn()

```csharp
public void InvokeSpawn()
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

### MakeCloseMentalDamage()

```csharp
public void MakeCloseMentalDamage()
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

### OnWorkerDead(List<WorkerModel>)

```csharp
public void OnWorkerDead(List<WorkerModel> target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `System.Collections.Generic.List{WorkerModel}` |  |

### ReadyForTeleport()

```csharp
public void ReadyForTeleport()
```

### SetActive(bool)

```csharp
public void SetActive(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetCurrent()

```csharp
public void SetCurrent()
```

### SetCurrentPassage(PassageObjectModel)

```csharp
public void SetCurrentPassage(PassageObjectModel passage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### SetEvent(HordeOfBugs)

```csharp
public override void SetEvent(HordeOfBugs hob)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `hob` | `Global.HordeOfBugs` |  |

### SpawnChilds()

```csharp
public void SpawnChilds()
```
