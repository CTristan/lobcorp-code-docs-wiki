# Class Uncontrollable_Machine

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_Machine : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/HierarchicalData) → [UncontrollableAction](/api/UncontrollableAction) → Uncontrollable_Machine

## Inherited Members
[OnDestroy()](/api/UncontrollableAction#ondestroy), [OnPrevDie()](/api/UncontrollableAction#onprevdie), [OnTakePhysicalDamage(int)](/api/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/UncontrollableAction#ontakementaldamage-int), [OnKillTarget()](/api/UncontrollableAction#onkilltarget), [HasUniqueHostility()](/api/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/UncontrollableAction#ishostile), [HasAttackAnim()](/api/UncontrollableAction#hasattackanim), [SetAttackAnim()](/api/UncontrollableAction#setattackanim), [IsNextAttackWillKillTarget()](/api/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/UncontrollableAction#castingslider-slider), [IsPreferredTouch()](/api/UncontrollableAction#ispreferredtouch), [IsAttackTargetable()](/api/UncontrollableAction#isattacktargetable), [_H_index](/api/HierarchicalData#h-index), [InitialSetting()](/api/HierarchicalData#initialsetting), [GetHierachicalName()](/api/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Uncontrollable_Machine(WorkerModel, SingingMachineSkill)

```csharp
public Uncontrollable_Machine(WorkerModel model, SingingMachineSkill machineSkill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `machineSkill` | `Global.SingingMachineSkill` |  |

## Fields

### machineSkill

```csharp
public SingingMachineSkill machineSkill
```

#### Field Value

**Type:** Global.SingingMachineSkill

### target

```csharp
public UnitModel target
```

#### Field Value

**Type:** Global.UnitModel

## Methods

### Drag()

```csharp
public void Drag()
```

### Drop()

```csharp
public void Drop()
```

### Execute()

```csharp
public override void Execute()
```

### FailDrag()

```csharp
public void FailDrag()
```

### GetMachineSkill()

```csharp
public SingingMachineSkill GetMachineSkill()
```

#### Returns

**Type:** Global.SingingMachineSkill

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

### ShowUnconSpeech(string)

```csharp
public override void ShowUnconSpeech(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

### StartDrag(WorkerModel)

```csharp
public void StartDrag(WorkerModel victim)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `victim` | `Global.WorkerModel` |  |

### UnderAttack()

```csharp
public override void UnderAttack()
```
