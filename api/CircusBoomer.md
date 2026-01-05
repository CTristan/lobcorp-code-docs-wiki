# Class CircusBoomer

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CircusBoomer : BoomerCircusScript
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/StandingItemScriptBase) → [BoomerCircusScript](/api/BoomerCircusScript) → CircusBoomer

## Inherited Members
[randomEvent](/api/BoomerCircusScript#randomevent), [soundDistDobule](/api/StandingItemScriptBase#sounddistdobule), [model](/api/StandingItemScriptBase#model), [_animScript](/api/StandingItemScriptBase#animscript), [_state](/api/StandingItemScriptBase#state), [name](/api/StandingItemScriptBase#name), [_maxHp](/api/StandingItemScriptBase#maxhp), [_defense](/api/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/StandingItemScriptBase#isinrange-unitmodel-float), [IsAttackable()](/api/StandingItemScriptBase#isattackable), [OnIgnoreDamage(UnitModel)](/api/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/StandingItemScriptBase#ondestroystandingitem), [GetName()](/api/StandingItemScriptBase#getname), [SetName(string)](/api/StandingItemScriptBase#setname-string), [HasName()](/api/StandingItemScriptBase#hasname), [Prob(float)](/api/StandingItemScriptBase#prob-float), [Prob(int)](/api/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/StandingItemScriptBase#checkcamerarange-float), [Model](/api/StandingItemScriptBase#model), [Movable](/api/StandingItemScriptBase#movable), [Passage](/api/StandingItemScriptBase#passage), [State](/api/StandingItemScriptBase#state), [MaxHp](/api/StandingItemScriptBase#maxhp), [Defense](/api/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### CircusBoomer()

```csharp
public CircusBoomer()
```

## Fields

### animScript

```csharp
public CircusBoomerAnim animScript
```

#### Field Value

**Type:** Global.CircusBoomerAnim

### boomFreq

```csharp
public const float boomFreq = 2
```

#### Field Value

**Type:** System.Single

### boomRange

```csharp
public const float boomRange = 7
```

#### Field Value

**Type:** System.Single

### boomTimer

```csharp
public Timer boomTimer
```

#### Field Value

**Type:** Global.Timer

### canTakeDmg

```csharp
public bool canTakeDmg
```

#### Field Value

**Type:** System.Boolean

### defaultSound

```csharp
public SoundEffectPlayer defaultSound
```

#### Field Value

**Type:** Global.SoundEffectPlayer

### detectRange

```csharp
public const float detectRange = 3.25
```

#### Field Value

**Type:** System.Single

### dmgPerClick

```csharp
public const float dmgPerClick = 30
```

#### Field Value

**Type:** System.Single

### enableDelay

```csharp
public Timer enableDelay
```

#### Field Value

**Type:** Global.Timer

### index

```csharp
public int index
```

#### Field Value

**Type:** System.Int32

### indexZ

```csharp
public float indexZ
```

#### Field Value

**Type:** System.Single

### moveSpeed

```csharp
public const float moveSpeed = 3
```

#### Field Value

**Type:** System.Single

### readyToBomb

```csharp
public bool readyToBomb
```

#### Field Value

**Type:** System.Boolean

### textUI

```csharp
public Text textUI
```

#### Field Value

**Type:** UnityEngine.UI.Text

### yValueFix

```csharp
public const float yValueFix = -18
```

#### Field Value

**Type:** System.Single

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |

### Init()

```csharp
public override void Init()
```

### IsActive()

```csharp
public override bool IsActive()
```

#### Returns

**Type:** System.Boolean

### MakeExplodeEffect(UnitDirection, WorkerModel, float)

```csharp
public void MakeExplodeEffect(UnitDirection dir, WorkerModel target, float size)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `size` | `System.Single` |  |

### Move()

```csharp
public void Move()
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

### OnTakePhyisclaDamage(float)

```csharp
public override void OnTakePhyisclaDamage(float damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Single` |  |

### SetActive(bool)

```csharp
public override void SetActive(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetEvent(BoomerCircusEvent)

```csharp
public override void SetEvent(BoomerCircusEvent bce)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |

#### Returns

**Type:** System.Boolean
