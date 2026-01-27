---
uid: Global.GrandmaBug
canonical_path: /api/Global/Misc/GrandmaBug
---

# Class GrandmaBug

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GrandmaBug : HordeOfBugsScript
```

#unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Standing/StandingItemScriptBase) → [HordeOfBugsScript](/api/Global/Script/HordeOfBugsScript) → GrandmaBug

## Inherited Members
[randomEvent](/api/Global/Script/HordeOfBugsScript#randomevent), [soundDistDobule](/api/Global/Standing/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Standing/StandingItemScriptBase#model), [_animScript](/api/Global/Standing/StandingItemScriptBase#animscript), [_state](/api/Global/Standing/StandingItemScriptBase#state), [name](/api/Global/Standing/StandingItemScriptBase#name), [_maxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [_defense](/api/Global/Standing/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Standing/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Standing/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/Global/Standing/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Standing/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Standing/StandingItemScriptBase#isinrange-unitmodel-float), [OnBreakDown()](/api/Global/Standing/StandingItemScriptBase#onbreakdown), [OnIgnoreDamage(UnitModel)](/api/Global/Standing/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/Global/Standing/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/Global/Standing/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/Global/Standing/StandingItemScriptBase#getname), [SetName(string)](/api/Global/Standing/StandingItemScriptBase#setname-string), [HasName()](/api/Global/Standing/StandingItemScriptBase#hasname), [Prob(float)](/api/Global/Standing/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Standing/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Standing/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Standing/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Standing/StandingItemScriptBase#model), [Movable](/api/Global/Standing/StandingItemScriptBase#movable), [Passage](/api/Global/Standing/StandingItemScriptBase#passage), [State](/api/Global/Standing/StandingItemScriptBase#state), [MaxHp](/api/Global/Standing/StandingItemScriptBase#maxhp), [Defense](/api/Global/Standing/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GrandmaBug()

```csharp
public GrandmaBug()
```

## Fields

### _gState

```csharp
private GrandmaBug.GrandmaState _gState
```

#### Field Value

**Type:** Global.GrandmaBug.GrandmaState

### _phase

```csharp
private GrandmaBug.GrandmaPhase _phase
```

#### Field Value

**Type:** Global.GrandmaBug.GrandmaPhase

### animScript

```csharp
public GrandmaBugAnim animScript
```
#INC


#### Field Value

**Type:** Global.GrandmaBugAnim

### AppearDelayMax

```csharp
public const float AppearDelayMax = 4
```
#INC


#### Field Value

**Type:** System.Single

### AppearDelayMin

```csharp
public const float AppearDelayMin = 2
```
#INC


#### Field Value

**Type:** System.Single

### appearSoundMake

```csharp
private bool appearSoundMake
```
#INC


#### Field Value

**Type:** System.Boolean

### currentPassage

```csharp
private PassageObjectModel currentPassage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### damageInfo

```csharp
private DamageInfo damageInfo
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### damageRange

```csharp
public const float damageRange = 5
```
#INC


#### Field Value

**Type:** System.Single

### defaultRange

```csharp
public const float defaultRange = 2
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

### disappearMentalDamage

```csharp
public const float disappearMentalDamage = 30
```
#INC


#### Field Value

**Type:** System.Single

### dmg

```csharp
private const float dmg = 200
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

### motherBugDefualt

```csharp
public const int motherBugDefualt = 2
```
#INC


#### Field Value

**Type:** System.Int32

### motherBugMax

```csharp
public const int motherBugMax = 10
```
#INC


#### Field Value

**Type:** System.Int32

### nodes

```csharp
public List<MapNode> nodes
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{MapNode}

### RemainDelayMax

```csharp
public const float RemainDelayMax = 40
```
#INC


#### Field Value

**Type:** System.Single

### RemainDelayMin

```csharp
public const float RemainDelayMin = 20
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

### spawnChildTimer

```csharp
public Timer spawnChildTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### SpawnDelayMax

```csharp
public const float SpawnDelayMax = 15
```
#INC


#### Field Value

**Type:** System.Single

### SpawnDelayMin

```csharp
public const float SpawnDelayMin = 5
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

### teleportTimer

```csharp
public Timer teleportTimer
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

## Properties

### spawnDelay

```csharp
private float spawnDelay { get; }
```

#### Property Value

**Type:** System.Single

### teleportCoolTime

```csharp
private float teleportCoolTime { get; }
```

#### Property Value

**Type:** System.Single

### teleportDelay

```csharp
private float teleportDelay { get; }
```

#### Property Value

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

### Disappear()

```csharp
public void Disappear()
```
#INC


### Enable()

```csharp
public void Enable()
```
#INC


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


### InvokeAppearDamage()

```csharp
public void InvokeAppearDamage()
```
#INC


### InvokeSpawn()

```csharp
public void InvokeSpawn()
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

### MakeAppearEnvironmentSound()

```csharp
private void MakeAppearEnvironmentSound()
```
#INC


### MakeCloseMentalDamage()

```csharp
public void MakeCloseMentalDamage()
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

### OnWorkerDead(List<WorkerModel>)

```csharp
public void OnWorkerDead(List<WorkerModel> target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `System.Collections.Generic.List{WorkerModel}` |  |

### ReadyForTeleport()

```csharp
public void ReadyForTeleport()
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

### SetCurrent()

```csharp
public void SetCurrent()
```
#INC


### SetCurrentPassage(PassageObjectModel)

```csharp
public void SetCurrentPassage(PassageObjectModel passage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

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

### SpawnChilds()

```csharp
public void SpawnChilds()
```
#INC

