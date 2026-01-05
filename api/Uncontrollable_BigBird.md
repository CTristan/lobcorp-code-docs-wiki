# Class Uncontrollable_BigBird

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_BigBird : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/HierarchicalData) → [UncontrollableAction](/api/UncontrollableAction) → Uncontrollable_BigBird

## Inherited Members
[Init()](/api/UncontrollableAction#init), [OnStageEnd()](/api/UncontrollableAction#onstageend), [OnPrevDie()](/api/UncontrollableAction#onprevdie), [OnClick()](/api/UncontrollableAction#onclick), [UnderAttack()](/api/UncontrollableAction#underattack), [OnTakePhysicalDamage(int)](/api/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/UncontrollableAction#ontakementaldamage-int), [ShowUnconSpeech(string)](/api/UncontrollableAction#showunconspeech-string), [OnKillTarget()](/api/UncontrollableAction#onkilltarget), [HasUniqueHostility()](/api/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/UncontrollableAction#ishostile), [HasAttackAnim()](/api/UncontrollableAction#hasattackanim), [SetAttackAnim()](/api/UncontrollableAction#setattackanim), [IsNextAttackWillKillTarget()](/api/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/UncontrollableAction#castingslider-slider), [IsPreferredTouch()](/api/UncontrollableAction#ispreferredtouch), [IsAttackTargetable()](/api/UncontrollableAction#isattacktargetable), [_H_index](/api/HierarchicalData#h-index), [InitialSetting()](/api/HierarchicalData#initialsetting), [GetHierachicalName()](/api/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Uncontrollable_BigBird(WorkerModel, BigBird)

```csharp
public Uncontrollable_BigBird(WorkerModel model, BigBird script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `script` | `Global.BigBird` |  |

### Uncontrollable_BigBird(WorkerModel, BossBird)

```csharp
public Uncontrollable_BigBird(WorkerModel model, BossBird bossScript)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `bossScript` | `Global.BossBird` |  |

## Methods

### Execute()

```csharp
public override void Execute()
```

### OnDestroy()

```csharp
public override void OnDestroy()
```

### OnDie()

```csharp
public override void OnDie()
```
