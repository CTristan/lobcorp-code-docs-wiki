---
uid: Global.Uncontrollable_Machine
canonical_path: /api/Global/UncontrollableAction/UncontrollableMachine
---

# Class Uncontrollable_Machine

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_Machine : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Misc/HierarchicalData) → [UncontrollableAction](/api/Global/Action/UncontrollableAction) → Uncontrollable_Machine

## Inherited Members
[OnDestroy()](/api/Global/Action/UncontrollableAction#ondestroy), [OnPrevDie()](/api/Global/Action/UncontrollableAction#onprevdie), [OnTakePhysicalDamage(int)](/api/Global/Action/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/Global/Action/UncontrollableAction#ontakementaldamage-int), [OnKillTarget()](/api/Global/Action/UncontrollableAction#onkilltarget), [HasUniqueHostility()](/api/Global/Action/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/Global/Action/UncontrollableAction#ishostile), [HasAttackAnim()](/api/Global/Action/UncontrollableAction#hasattackanim), [SetAttackAnim()](/api/Global/Action/UncontrollableAction#setattackanim), [IsNextAttackWillKillTarget()](/api/Global/Action/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/Global/Action/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/Global/Action/UncontrollableAction#castingslider-slider), [IsPreferredTouch()](/api/Global/Action/UncontrollableAction#ispreferredtouch), [IsAttackTargetable()](/api/Global/Action/UncontrollableAction#isattacktargetable), [_H_index](/api/Global/Misc/HierarchicalData#h-index), [InitialSetting()](/api/Global/Misc/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Misc/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Misc/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Misc/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Misc/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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

### creatureAnim

```csharp
private Animator creatureAnim
```

#### Field Value

**Type:** UnityEngine.Animator

### drag

```csharp
private bool drag
```

#### Field Value

**Type:** System.Boolean

### encountered

```csharp
private List<UnitModel> encountered
```

#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

### listen

```csharp
private bool listen
```

#### Field Value

**Type:** System.Boolean

### listenDelay

```csharp
private float listenDelay
```

#### Field Value

**Type:** System.Single

### listenTime

```csharp
private float listenTime
```

#### Field Value

**Type:** System.Single

### machineSkill

```csharp
public SingingMachineSkill machineSkill
```

#### Field Value

**Type:** Global.SingingMachineSkill

### model

```csharp
private WorkerModel model
```

#### Field Value

**Type:** Global.WorkerModel

### moveDelayTimer

```csharp
private float moveDelayTimer
```

#### Field Value

**Type:** System.Single

### puppetAnim

```csharp
private Animator puppetAnim
```

#### Field Value

**Type:** UnityEngine.Animator

### speech_attack

```csharp
private const string speech_attack = "attack"
```

#### Field Value

**Type:** System.String

### speech_listen

```csharp
private const string speech_listen = "listen"
```

#### Field Value

**Type:** System.String

### startWaitTimer

```csharp
private float startWaitTimer
```

#### Field Value

**Type:** System.Single

### target

```csharp
public UnitModel target
```

#### Field Value

**Type:** Global.UnitModel

### underattackTimer

```csharp
private float underattackTimer
```

#### Field Value

**Type:** System.Single

### victim

```csharp
private WorkerModel victim
```

#### Field Value

**Type:** Global.WorkerModel

### victimAnim

```csharp
private Animator victimAnim
```

#### Field Value

**Type:** UnityEngine.Animator

### waitTimer

```csharp
private float waitTimer
```

#### Field Value

**Type:** System.Single

## Properties

### machineID

```csharp
private long machineID { get; }
```

#### Property Value

**Type:** System.Int64

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
