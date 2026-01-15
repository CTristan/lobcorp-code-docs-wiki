---
uid: Global.Uncontrollable_SilentOrchestra
canonical_path: /api/Global/UncontrollableAction/UncontrollableSilentOrchestra
---

# Class Uncontrollable_SilentOrchestra

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_SilentOrchestra : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Misc/HierarchicalData) → [UncontrollableAction](/api/Global/Action/UncontrollableAction) → Uncontrollable_SilentOrchestra

## Inherited Members
[OnPrevDie()](/api/Global/Action/UncontrollableAction#onprevdie), [OnClick()](/api/Global/Action/UncontrollableAction#onclick), [UnderAttack()](/api/Global/Action/UncontrollableAction#underattack), [OnTakePhysicalDamage(int)](/api/Global/Action/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/Global/Action/UncontrollableAction#ontakementaldamage-int), [ShowUnconSpeech(string)](/api/Global/Action/UncontrollableAction#showunconspeech-string), [HasUniqueHostility()](/api/Global/Action/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/Global/Action/UncontrollableAction#ishostile), [HasAttackAnim()](/api/Global/Action/UncontrollableAction#hasattackanim), [SetAttackAnim()](/api/Global/Action/UncontrollableAction#setattackanim), [IsNextAttackWillKillTarget()](/api/Global/Action/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/Global/Action/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/Global/Action/UncontrollableAction#castingslider-slider), [IsPreferredTouch()](/api/Global/Action/UncontrollableAction#ispreferredtouch), [IsAttackTargetable()](/api/Global/Action/UncontrollableAction#isattacktargetable), [_H_index](/api/Global/Misc/HierarchicalData#h-index), [InitialSetting()](/api/Global/Misc/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Misc/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Misc/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Misc/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Misc/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Uncontrollable_SilentOrchestra(WorkerModel, SilentOrchestra)

```csharp
public Uncontrollable_SilentOrchestra(WorkerModel model, SilentOrchestra orchestra)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `orchestra` | `Global.SilentOrchestra` |  |

## Fields

### afterTimer

```csharp
private AutoTimer afterTimer
```

#### Field Value

**Type:** Global.AutoTimer

### animInit

```csharp
private bool animInit
```

#### Field Value

**Type:** System.Boolean

### battleCmd

```csharp
private UnconPursueInSilentOrchestra battleCmd
```

#### Field Value

**Type:** Global.UnconPursueInSilentOrchestra

### ChangeTargetTimer

```csharp
private Timer ChangeTargetTimer
```

#### Field Value

**Type:** Global.Timer

### currentAttackTarget

```csharp
private UnitModel currentAttackTarget
```

#### Field Value

**Type:** Global.UnitModel

### currentCmd

```csharp
private Uncontrollable_SilentOrchestra.UnitCmd currentCmd
```

#### Field Value

**Type:** Global.Uncontrollable_SilentOrchestra.UnitCmd

### currentExe

```csharp
private Uncontrollable_SilentOrchestra.CommandExecution currentExe
```

#### Field Value

**Type:** Global.Uncontrollable_SilentOrchestra.CommandExecution

### dead

```csharp
private bool dead
```

#### Field Value

**Type:** System.Boolean

### DeadCastTimer

```csharp
private AutoTimer DeadCastTimer
```

#### Field Value

**Type:** Global.AutoTimer

### defMaxHp

```csharp
private float defMaxHp
```

#### Field Value

**Type:** System.Single

### dieInit

```csharp
private bool dieInit
```

#### Field Value

**Type:** System.Boolean

### ExplodeAfterEffect

```csharp
public const string ExplodeAfterEffect = "Effect/Creature/SilentOrchestra/NoteEffectSilentDead"
```

#### Field Value

**Type:** System.String

### fightInit

```csharp
private bool fightInit
```

#### Field Value

**Type:** System.Boolean

### isMovingToPassage

```csharp
private bool isMovingToPassage
```

#### Field Value

**Type:** System.Boolean

### model

```csharp
private WorkerModel model
```

#### Field Value

**Type:** Global.WorkerModel

### orchestra

```csharp
private SilentOrchestra orchestra
```

#### Field Value

**Type:** Global.SilentOrchestra

### ReadyForFight

```csharp
private bool ReadyForFight
```

#### Field Value

**Type:** System.Boolean

### targetNode

```csharp
private MapNode targetNode
```

#### Field Value

**Type:** Global.MapNode

## Properties

### currentMovement

```csharp
private SilentOrchestra.Movement currentMovement { get; }
```

#### Property Value

**Type:** Global.SilentOrchestra.Movement

## Methods

### AfterEffect()

```csharp
public void AfterEffect()
```

### AnimInit()

```csharp
private void AnimInit()
```

### CastDie()

```csharp
public void CastDie()
```

### CheckNearTarget(out List<UnitModel>)

```csharp
private bool CheckNearTarget(out List<UnitModel> targets)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `targets` | `System.Collections.Generic.List{UnitModel}` |  |

#### Returns

**Type:** System.Boolean

### DeadAnimInit()

```csharp
private void DeadAnimInit()
```

### DeadCommand()

```csharp
public void DeadCommand()
```

### Execute()

```csharp
public override void Execute()
```

### ExecuteDead()

```csharp
private void ExecuteDead()
```

### FightAnimInit()

```csharp
private void FightAnimInit()
```

### FightingDie()

```csharp
public void FightingDie()
```

### GetWorker()

```csharp
public WorkerModel GetWorker()
```

#### Returns

**Type:** Global.WorkerModel

### Init()

```csharp
public override void Init()
```

### Invincivle()

```csharp
private void Invincivle()
```

### IsInOrchestraPassage()

```csharp
private bool IsInOrchestraPassage()
```

#### Returns

**Type:** System.Boolean

### ListenCommand()

```csharp
private void ListenCommand()
```

### MakeUnconPursue(UnitModel)

```csharp
private UnconPursueInSilentOrchestra MakeUnconPursue(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.UnconPursueInSilentOrchestra

### MoveCommand()

```csharp
private void MoveCommand()
```

### OnDestroy()

```csharp
public override void OnDestroy()
```

### OnDie()

```csharp
public override void OnDie()
```

### OnKillTarget()

```csharp
public override void OnKillTarget()
```

### OnOrchestraSuppressed()

```csharp
public void OnOrchestraSuppressed()
```

### OnStageEnd()

```csharp
public override void OnStageEnd()
```

### StandCommand()

```csharp
private void StandCommand()
```

### StartTargeting()

```csharp
public void StartTargeting()
```

### ViolenceCommand()

```csharp
public void ViolenceCommand()
```

### ViolencExecute()

```csharp
private void ViolencExecute()
```
