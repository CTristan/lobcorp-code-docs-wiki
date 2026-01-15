---
uid: Global.Uncontrollable_YoungPrince
canonical_path: /api/Global/UncontrollableAction/UncontrollableYoungPrince
---

# Class Uncontrollable_YoungPrince

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_YoungPrince : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Misc/HierarchicalData) → [UncontrollableAction](/api/Global/Action/UncontrollableAction) → Uncontrollable_YoungPrince

## Inherited Members
[OnStageEnd()](/api/Global/Action/UncontrollableAction#onstageend), [OnPrevDie()](/api/Global/Action/UncontrollableAction#onprevdie), [UnderAttack()](/api/Global/Action/UncontrollableAction#underattack), [OnTakePhysicalDamage(int)](/api/Global/Action/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/Global/Action/UncontrollableAction#ontakementaldamage-int), [ShowUnconSpeech(string)](/api/Global/Action/UncontrollableAction#showunconspeech-string), [OnKillTarget()](/api/Global/Action/UncontrollableAction#onkilltarget), [HasUniqueHostility()](/api/Global/Action/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/Global/Action/UncontrollableAction#ishostile), [HasAttackAnim()](/api/Global/Action/UncontrollableAction#hasattackanim), [SetAttackAnim()](/api/Global/Action/UncontrollableAction#setattackanim), [IsNextAttackWillKillTarget()](/api/Global/Action/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/Global/Action/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/Global/Action/UncontrollableAction#castingslider-slider), [IsPreferredTouch()](/api/Global/Action/UncontrollableAction#ispreferredtouch), [IsAttackTargetable()](/api/Global/Action/UncontrollableAction#isattacktargetable), [_H_index](/api/Global/Misc/HierarchicalData#h-index), [InitialSetting()](/api/Global/Misc/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Misc/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Misc/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Misc/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Misc/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Uncontrollable_YoungPrince(WorkerModel, YoungPrince)

```csharp
public Uncontrollable_YoungPrince(WorkerModel model, YoungPrince prince)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `prince` | `Global.YoungPrince` |  |

## Fields

### model

```csharp
private WorkerModel model
```

#### Field Value

**Type:** Global.WorkerModel

### prince

```csharp
private YoungPrince prince
```

#### Field Value

**Type:** Global.YoungPrince

### remainClicked

```csharp
private int remainClicked
```

#### Field Value

**Type:** System.Int32

### slowTimer

```csharp
private float slowTimer
```

#### Field Value

**Type:** System.Single

### waitTimer

```csharp
private float waitTimer
```

#### Field Value

**Type:** System.Single

### wakeUp

```csharp
private bool wakeUp
```

#### Field Value

**Type:** System.Boolean

### wakeUpTimer

```csharp
private float wakeUpTimer
```

#### Field Value

**Type:** System.Single

## Methods

### Execute()

```csharp
public override void Execute()
```

### Init()

```csharp
public override void Init()
```

### OnClick()

```csharp
public override void OnClick()
```

### OnDestroy()

```csharp
public override void OnDestroy()
```

### OnDie()

```csharp
public override void OnDie()
```

### WakeUp()

```csharp
private void WakeUp()
```
