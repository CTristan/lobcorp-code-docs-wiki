---
uid: Legacy.Uncontrollable_DeathApostle
canonical_path: /api/Legacy/Uncontrollable_DeathApostle
---

# Class Uncontrollable_DeathApostle

**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_DeathApostle : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Misc/HierarchicalData) → [UncontrollableAction](/api/Global/Action/UncontrollableAction) → Uncontrollable_DeathApostle

## Derived
[Uncontrollable_DeathApostleCharge](/api/Legacy/Uncontrollable_DeathApostleCharge), [Uncontrollable_DeathApostleMelee](/api/Legacy/Uncontrollable_DeathApostleMelee), [Uncontrollable_DeathApostleRanged](/api/Legacy/Uncontrollable_DeathApostleRanged)

## Inherited Members
[Execute()](/api/Global/Action/UncontrollableAction#execute), [OnDestroy()](/api/Global/Action/UncontrollableAction#ondestroy), [UnderAttack()](/api/Global/Action/UncontrollableAction#underattack), [OnTakePhysicalDamage(int)](/api/Global/Action/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/Global/Action/UncontrollableAction#ontakementaldamage-int), [ShowUnconSpeech(string)](/api/Global/Action/UncontrollableAction#showunconspeech-string), [OnKillTarget()](/api/Global/Action/UncontrollableAction#onkilltarget), [HasUniqueHostility()](/api/Global/Action/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/Global/Action/UncontrollableAction#ishostile), [IsNextAttackWillKillTarget()](/api/Global/Action/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/Global/Action/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/Global/Action/UncontrollableAction#castingslider-slider), [IsAttackTargetable()](/api/Global/Action/UncontrollableAction#isattacktargetable), [_H_index](/api/Global/Misc/HierarchicalData#h-index), [InitialSetting()](/api/Global/Misc/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Misc/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Misc/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Misc/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Misc/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Uncontrollable_DeathApostle()

```csharp
public Uncontrollable_DeathApostle()
```

## Fields

### _currentAttackTarget

```csharp
protected UnitModel _currentAttackTarget
```

#### Field Value

**Type:** Global.UnitModel

### agentAttachScale

```csharp
private Vector3 agentAttachScale
```

#### Field Value

**Type:** UnityEngine.Vector3

### angel

```csharp
protected DeathAngel angel
```

#### Field Value

**Type:** Legacy.DeathAngel

### animScript

```csharp
protected DeathAngelApostleAnim animScript
```

#### Field Value

**Type:** Legacy.DeathAngelApostleAnim

### AnimSrc

```csharp
public const string AnimSrc = "Unit/CreatureAnimator/Apostle/DeathAngelApostle"
```

#### Field Value

**Type:** System.String

### animTrans

```csharp
public bool animTrans
```

#### Field Value

**Type:** System.Boolean

### apostleNumber

```csharp
public int apostleNumber
```

#### Field Value

**Type:** System.Int32

### encounteredWorker

```csharp
protected List<WorkerModel> encounteredWorker
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerModel}

### forcelyDie

```csharp
protected bool forcelyDie
```

#### Field Value

**Type:** System.Boolean

### guardAngel

```csharp
protected bool guardAngel
```

#### Field Value

**Type:** System.Boolean

### hairSprite

```csharp
public Sprite hairSprite
```

#### Field Value

**Type:** UnityEngine.Sprite

### isAttackAnimPlaying

```csharp
public bool isAttackAnimPlaying
```

#### Field Value

**Type:** System.Boolean

### isSuppressed

```csharp
protected bool isSuppressed
```

#### Field Value

**Type:** System.Boolean

### isTranforming

```csharp
protected bool isTranforming
```

#### Field Value

**Type:** System.Boolean

### model

```csharp
protected WorkerModel model
```

#### Field Value

**Type:** Global.WorkerModel

### NameUISrc

```csharp
public const string NameUISrc = "UIComponent/ApostleName"
```

#### Field Value

**Type:** System.String

## Properties

### currentAttackTarget

```csharp
protected UnitModel currentAttackTarget { get; set; }
```

#### Property Value

**Type:** Global.UnitModel

### Model

```csharp
public WorkerModel Model { get; }
```

#### Property Value

**Type:** Global.WorkerModel

### movable

```csharp
protected MovableObjectNode movable { get; }
```

#### Property Value

**Type:** Global.MovableObjectNode

## Methods

### CheckNearUnit(ref List<UnitModel>)

```csharp
protected virtual bool CheckNearUnit(ref List<UnitModel> near)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |

#### Returns

**Type:** System.Boolean

### ForcelyDie()

```csharp
public virtual void ForcelyDie()
```

### GetCurrentCommand()

```csharp
public virtual WorkerCommand GetCurrentCommand()
```

#### Returns

**Type:** Global.WorkerCommand

### GetModel()

```csharp
public WorkerModel GetModel()
```

#### Returns

**Type:** Global.WorkerModel

### GetRandomNearTarget(List<UnitModel>)

```csharp
protected virtual UnitModel GetRandomNearTarget(List<UnitModel> near)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |

#### Returns

**Type:** Global.UnitModel

### HasAttackAnim()

```csharp
public override bool HasAttackAnim()
```

#### Returns

**Type:** System.Boolean

### Init()

```csharp
public override void Init()
```

### IsGuard()

```csharp
public bool IsGuard()
```

#### Returns

**Type:** System.Boolean

### IsPreferredTouch()

```csharp
public override bool IsPreferredTouch()
```

#### Returns

**Type:** System.Boolean

### MakeMovement()

```csharp
public virtual void MakeMovement()
```

### OnClick()

```csharp
public override void OnClick()
```

### OnDie()

```csharp
public override void OnDie()
```

### OnKillAgent(AgentModel)

```csharp
public virtual void OnKillAgent(AgentModel agent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### OnPrevDie()

```csharp
public override void OnPrevDie()
```

### OnResurrect()

```csharp
public virtual void OnResurrect()
```

### OnStageEnd()

```csharp
public override void OnStageEnd()
```

### OnTransformAnimEnd()

```csharp
public virtual void OnTransformAnimEnd()
```

### SetAttackAnim()

```csharp
public override void SetAttackAnim()
```

### SetGuardAngel(bool)

```csharp
public void SetGuardAngel(bool guard)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `guard` | `System.Boolean` |  |

### StopMovement()

```csharp
public virtual void StopMovement()
```

### TeleportToAngel()

```csharp
public virtual void TeleportToAngel()
```

### TransformCall()

```csharp
public virtual void TransformCall()
```
