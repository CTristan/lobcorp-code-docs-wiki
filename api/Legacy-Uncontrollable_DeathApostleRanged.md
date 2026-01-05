# Class Uncontrollable_DeathApostleRanged

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_DeathApostleRanged : Uncontrollable_DeathApostle
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/HierarchicalData) → [UncontrollableAction](/api/UncontrollableAction) → [Uncontrollable_DeathApostle](/api/Legacy-Uncontrollable_DeathApostle) → Uncontrollable_DeathApostleRanged

## Inherited Members
[NameUISrc](/api/Legacy-Uncontrollable_DeathApostle#nameuisrc), [AnimSrc](/api/Legacy-Uncontrollable_DeathApostle#animsrc), [isAttackAnimPlaying](/api/Legacy-Uncontrollable_DeathApostle#isattackanimplaying), [model](/api/Legacy-Uncontrollable_DeathApostle#model), [_currentAttackTarget](/api/Legacy-Uncontrollable_DeathApostle#currentattacktarget), [apostleNumber](/api/Legacy-Uncontrollable_DeathApostle#apostlenumber), [encounteredWorker](/api/Legacy-Uncontrollable_DeathApostle#encounteredworker), [animScript](/api/Legacy-Uncontrollable_DeathApostle#animscript), [hairSprite](/api/Legacy-Uncontrollable_DeathApostle#hairsprite), [animTrans](/api/Legacy-Uncontrollable_DeathApostle#animtrans), [angel](/api/Legacy-Uncontrollable_DeathApostle#angel), [isTranforming](/api/Legacy-Uncontrollable_DeathApostle#istranforming), [isSuppressed](/api/Legacy-Uncontrollable_DeathApostle#issuppressed), [forcelyDie](/api/Legacy-Uncontrollable_DeathApostle#forcelydie), [guardAngel](/api/Legacy-Uncontrollable_DeathApostle#guardangel), [CheckNearUnit(ref List<UnitModel>)](/api/Legacy-Uncontrollable_DeathApostle#checknearunit-ref-list-unitmodel), [GetModel()](/api/Legacy-Uncontrollable_DeathApostle#getmodel), [TransformCall()](/api/Legacy-Uncontrollable_DeathApostle#transformcall), [SetGuardAngel(bool)](/api/Legacy-Uncontrollable_DeathApostle#setguardangel-bool), [IsGuard()](/api/Legacy-Uncontrollable_DeathApostle#isguard), [OnStageEnd()](/api/Legacy-Uncontrollable_DeathApostle#onstageend), [OnResurrect()](/api/Legacy-Uncontrollable_DeathApostle#onresurrect), [OnClick()](/api/Legacy-Uncontrollable_DeathApostle#onclick), [GetRandomNearTarget(List<UnitModel>)](/api/Legacy-Uncontrollable_DeathApostle#getrandomneartarget-list-unitmodel), [GetCurrentCommand()](/api/Legacy-Uncontrollable_DeathApostle#getcurrentcommand), [MakeMovement()](/api/Legacy-Uncontrollable_DeathApostle#makemovement), [StopMovement()](/api/Legacy-Uncontrollable_DeathApostle#stopmovement), [TeleportToAngel()](/api/Legacy-Uncontrollable_DeathApostle#teleporttoangel), [ForcelyDie()](/api/Legacy-Uncontrollable_DeathApostle#forcelydie), [OnDie()](/api/Legacy-Uncontrollable_DeathApostle#ondie), [OnKillAgent(AgentModel)](/api/Legacy-Uncontrollable_DeathApostle#onkillagent-agentmodel), [OnTransformAnimEnd()](/api/Legacy-Uncontrollable_DeathApostle#ontransformanimend), [HasAttackAnim()](/api/Legacy-Uncontrollable_DeathApostle#hasattackanim), [SetAttackAnim()](/api/Legacy-Uncontrollable_DeathApostle#setattackanim), [IsPreferredTouch()](/api/Legacy-Uncontrollable_DeathApostle#ispreferredtouch), [Model](/api/Legacy-Uncontrollable_DeathApostle#model), [currentAttackTarget](/api/Legacy-Uncontrollable_DeathApostle#currentattacktarget), [movable](/api/Legacy-Uncontrollable_DeathApostle#movable), [OnDestroy()](/api/UncontrollableAction#ondestroy), [UnderAttack()](/api/UncontrollableAction#underattack), [OnTakePhysicalDamage(int)](/api/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/UncontrollableAction#ontakementaldamage-int), [ShowUnconSpeech(string)](/api/UncontrollableAction#showunconspeech-string), [HasUniqueHostility()](/api/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/UncontrollableAction#ishostile), [IsNextAttackWillKillTarget()](/api/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/UncontrollableAction#castingslider-slider), [IsAttackTargetable()](/api/UncontrollableAction#isattacktargetable), [_H_index](/api/HierarchicalData#h-index), [InitialSetting()](/api/HierarchicalData#initialsetting), [GetHierachicalName()](/api/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Uncontrollable_DeathApostleRanged(WorkerModel, DeathAngel, int, Sprite)

```csharp
public Uncontrollable_DeathApostleRanged(WorkerModel model, DeathAngel angel, int apostleNumber, Sprite hair)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `angel` | `Legacy.DeathAngel` |  |
| `apostleNumber` | `System.Int32` |  |
| `hair` | `UnityEngine.Sprite` |  |

## Methods

### AttackEnd()

```csharp
public void AttackEnd()
```

### AttackStart(List<UnitModel>)

```csharp
public void AttackStart(List<UnitModel> near)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |

### CallAttack()

```csharp
public void CallAttack()
```

### Execute()

```csharp
public override void Execute()
```

### Init()

```csharp
public override void Init()
```

### OnKill(UnitModel)

```csharp
public void OnKill(UnitModel unit)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

### OnKillTarget()

```csharp
public override void OnKillTarget()
```

### OnPrevDie()

```csharp
public override void OnPrevDie()
```

### ReadyAttack()

```csharp
public void ReadyAttack()
```
