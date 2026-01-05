# Class Uncontrollable_SingingMachine_attacker

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_SingingMachine_attacker : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/HierarchicalData) → [UncontrollableAction](/api/UncontrollableAction) → Uncontrollable_SingingMachine_attacker

## Inherited Members
[OnDestroy()](/api/UncontrollableAction#ondestroy), [OnPrevDie()](/api/UncontrollableAction#onprevdie), [UnderAttack()](/api/UncontrollableAction#underattack), [OnTakePhysicalDamage(int)](/api/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/UncontrollableAction#ontakementaldamage-int), [ShowUnconSpeech(string)](/api/UncontrollableAction#showunconspeech-string), [OnKillTarget()](/api/UncontrollableAction#onkilltarget), [HasUniqueHostility()](/api/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/UncontrollableAction#ishostile), [HasAttackAnim()](/api/UncontrollableAction#hasattackanim), [SetAttackAnim()](/api/UncontrollableAction#setattackanim), [IsNextAttackWillKillTarget()](/api/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/UncontrollableAction#castingslider-slider), [IsPreferredTouch()](/api/UncontrollableAction#ispreferredtouch), [IsAttackTargetable()](/api/UncontrollableAction#isattacktargetable), [_H_index](/api/HierarchicalData#h-index), [InitialSetting()](/api/HierarchicalData#initialsetting), [GetHierachicalName()](/api/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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
