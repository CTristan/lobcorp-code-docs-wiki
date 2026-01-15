---
uid: Global.Uncontrollable_LightsHammer
canonical_path: /api/Global/UncontrollableAction/UncontrollableLightsHammer
---

# Class Uncontrollable_LightsHammer

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_LightsHammer : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Misc/HierarchicalData) → [UncontrollableAction](/api/Global/Action/UncontrollableAction) → Uncontrollable_LightsHammer

## Inherited Members
[OnPrevDie()](/api/Global/Action/UncontrollableAction#onprevdie), [OnClick()](/api/Global/Action/UncontrollableAction#onclick), [UnderAttack()](/api/Global/Action/UncontrollableAction#underattack), [OnTakePhysicalDamage(int)](/api/Global/Action/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/Global/Action/UncontrollableAction#ontakementaldamage-int), [ShowUnconSpeech(string)](/api/Global/Action/UncontrollableAction#showunconspeech-string), [OnKillTarget()](/api/Global/Action/UncontrollableAction#onkilltarget), [HasUniqueHostility()](/api/Global/Action/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/Global/Action/UncontrollableAction#ishostile), [HasAttackAnim()](/api/Global/Action/UncontrollableAction#hasattackanim), [SetAttackAnim()](/api/Global/Action/UncontrollableAction#setattackanim), [IsNextAttackWillKillTarget()](/api/Global/Action/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/Global/Action/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/Global/Action/UncontrollableAction#castingslider-slider), [IsPreferredTouch()](/api/Global/Action/UncontrollableAction#ispreferredtouch), [IsAttackTargetable()](/api/Global/Action/UncontrollableAction#isattacktargetable), [_H_index](/api/Global/Misc/HierarchicalData#h-index), [InitialSetting()](/api/Global/Misc/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Misc/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Misc/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Misc/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Misc/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Uncontrollable_LightsHammer(WorkerModel, LightsHammer, UnitModel)

```csharp
public Uncontrollable_LightsHammer(WorkerModel model, LightsHammer hammer, UnitModel firstTarget)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `hammer` | `Global.LightsHammer` |  |
| `firstTarget` | `Global.UnitModel` |  |

## Fields

### allDeathTime

```csharp
private float allDeathTime
```

#### Field Value

**Type:** System.Single

### allDeathTimer

```csharp
private Timer allDeathTimer
```

#### Field Value

**Type:** Global.Timer

### animSrc

```csharp
public const string animSrc = "Unit/CreatureAnimator/LightsHammerWorker"
```

#### Field Value

**Type:** System.String

### castingTeleport

```csharp
private bool castingTeleport
```

#### Field Value

**Type:** System.Boolean

### effectCreated

```csharp
private bool effectCreated
```

#### Field Value

**Type:** System.Boolean

### effectCreateTime

```csharp
private float effectCreateTime
```

#### Field Value

**Type:** System.Single

### effectCreateTimer

```csharp
private Timer effectCreateTimer
```

#### Field Value

**Type:** Global.Timer

### effectObject

```csharp
private GameObject effectObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### hammer

```csharp
public LightsHammer hammer
```

#### Field Value

**Type:** Global.LightsHammer

### model

```csharp
private WorkerModel model
```

#### Field Value

**Type:** Global.WorkerModel

### started

```csharp
private bool started
```

#### Field Value

**Type:** System.Boolean

### startWaitTimer

```csharp
private float startWaitTimer
```

#### Field Value

**Type:** System.Single

### target

```csharp
private UnitModel target
```

#### Field Value

**Type:** Global.UnitModel

### teleportCastRemainTime

```csharp
private float teleportCastRemainTime
```

#### Field Value

**Type:** System.Single

## Methods

### ChangeAnim()

```csharp
private void ChangeAnim()
```

### ChangeTarget()

```csharp
private void ChangeTarget()
```

### Execute()

```csharp
public override void Execute()
```

### Init()

```csharp
public override void Init()
```

### MakeTeleportEffect(Vector3)

```csharp
private void MakeTeleportEffect(Vector3 pos)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |

### OnDestroy()

```csharp
public override void OnDestroy()
```

### OnDie()

```csharp
public override void OnDie()
```

### OnStageEnd()

```csharp
public override void OnStageEnd()
```

### TeleportToCreature()

```csharp
private void TeleportToCreature()
```
