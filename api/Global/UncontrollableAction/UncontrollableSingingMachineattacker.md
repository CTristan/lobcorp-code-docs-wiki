---
uid: Global.Uncontrollable_SingingMachine_attacker
canonical_path: /api/Global/UncontrollableAction/UncontrollableSingingMachineattacker
---

# Class Uncontrollable_SingingMachine_attacker

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_SingingMachine_attacker : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Misc/HierarchicalData) → [UncontrollableAction](/api/Global/Action/UncontrollableAction) → Uncontrollable_SingingMachine_attacker

## Inherited Members
[OnDestroy()](/api/Global/Action/UncontrollableAction#ondestroy), [OnPrevDie()](/api/Global/Action/UncontrollableAction#onprevdie), [UnderAttack()](/api/Global/Action/UncontrollableAction#underattack), [OnTakePhysicalDamage(int)](/api/Global/Action/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/Global/Action/UncontrollableAction#ontakementaldamage-int), [ShowUnconSpeech(string)](/api/Global/Action/UncontrollableAction#showunconspeech-string), [OnKillTarget()](/api/Global/Action/UncontrollableAction#onkilltarget), [HasUniqueHostility()](/api/Global/Action/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/Global/Action/UncontrollableAction#ishostile), [HasAttackAnim()](/api/Global/Action/UncontrollableAction#hasattackanim), [SetAttackAnim()](/api/Global/Action/UncontrollableAction#setattackanim), [IsNextAttackWillKillTarget()](/api/Global/Action/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/Global/Action/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/Global/Action/UncontrollableAction#castingslider-slider), [IsPreferredTouch()](/api/Global/Action/UncontrollableAction#ispreferredtouch), [IsAttackTargetable()](/api/Global/Action/UncontrollableAction#isattacktargetable), [_H_index](/api/Global/Misc/HierarchicalData#h-index), [InitialSetting()](/api/Global/Misc/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Misc/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Misc/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Misc/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Misc/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Uncontrollable_SingingMachine_attacker(WorkerModel, SingingMachine)

```csharp
public Uncontrollable_SingingMachine_attacker(WorkerModel model, SingingMachine singingMachine)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `singingMachine` | `Global.SingingMachine` |  |

## Fields

### _deadBackHairReRenderer

```csharp
private SpriteRenderer _deadBackHairReRenderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### _deadFrontHairReRenderer

```csharp
private SpriteRenderer _deadFrontHairReRenderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

### _killTarget

```csharp
private WorkerModel _killTarget
```

#### Field Value

**Type:** Global.WorkerModel

### _model

```csharp
private WorkerModel _model
```

#### Field Value

**Type:** Global.WorkerModel

### _singingMachine

```csharp
private SingingMachine _singingMachine
```

#### Field Value

**Type:** Global.SingingMachine

### _waitingTimer

```csharp
private Timer _waitingTimer
```

#### Field Value

**Type:** Global.Timer

### deadBackhairBoneName

```csharp
public const string deadBackhairBoneName = "bone_BACKHAIR_dead_Agent"
```

#### Field Value

**Type:** System.String

### deadFronthairBoneName

```csharp
public const string deadFronthairBoneName = "bone4bone_FRONTHAIR_dead_Agent"
```

#### Field Value

**Type:** System.String

### maxHpRatio

```csharp
private const float maxHpRatio = 1
```

#### Field Value

**Type:** System.Single

## Methods

### Execute()

```csharp
public override void Execute()
```

### GetNearWorkerEncounted()

```csharp
public List<WorkerModel> GetNearWorkerEncounted()
```

#### Returns

**Type:** System.Collections.Generic.List{WorkerModel}

### Init()

```csharp
public override void Init()
```

### MakeMovement()

```csharp
private void MakeMovement()
```

### OnClick()

```csharp
public override void OnClick()
```

### OnDie()

```csharp
public override void OnDie()
```

### OnStageEnd()

```csharp
public override void OnStageEnd()
```

### StopMovement()

```csharp
private void StopMovement()
```
