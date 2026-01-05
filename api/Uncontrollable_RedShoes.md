# Class Uncontrollable_RedShoes

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_RedShoes : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/HierarchicalData) → [UncontrollableAction](/api/UncontrollableAction) → Uncontrollable_RedShoes

## Inherited Members
[OnDestroy()](/api/UncontrollableAction#ondestroy), [OnPrevDie()](/api/UncontrollableAction#onprevdie), [UnderAttack()](/api/UncontrollableAction#underattack), [OnTakePhysicalDamage(int)](/api/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/UncontrollableAction#ontakementaldamage-int), [ShowUnconSpeech(string)](/api/UncontrollableAction#showunconspeech-string), [OnKillTarget()](/api/UncontrollableAction#onkilltarget), [HasUniqueHostility()](/api/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/UncontrollableAction#ishostile), [HasAttackAnim()](/api/UncontrollableAction#hasattackanim), [SetAttackAnim()](/api/UncontrollableAction#setattackanim), [IsNextAttackWillKillTarget()](/api/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/UncontrollableAction#castingslider-slider), [IsPreferredTouch()](/api/UncontrollableAction#ispreferredtouch), [IsAttackTargetable()](/api/UncontrollableAction#isattacktargetable), [_H_index](/api/HierarchicalData#h-index), [InitialSetting()](/api/HierarchicalData#initialsetting), [GetHierachicalName()](/api/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Uncontrollable_RedShoes(WorkerModel, RedShoesSkill, int)

```csharp
public Uncontrollable_RedShoes(WorkerModel model, RedShoesSkill redShoesSkill, int startType)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `redShoesSkill` | `Global.RedShoesSkill` |  |
| `startType` | `System.Int32` |  |

## Fields

### isPursing

```csharp
public bool isPursing
```

#### Field Value

**Type:** System.Boolean

### timer

```csharp
public CreatureBase.CreatureTimer timer
```

#### Field Value

**Type:** Global.CreatureBase.CreatureTimer

## Methods

### Execute()

```csharp
public override void Execute()
```

### Init()

```csharp
public override void Init()
```

### OnAnimCalled(int)

```csharp
public void OnAnimCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnClick()

```csharp
public override void OnClick()
```

### OnDie()

```csharp
public override void OnDie()
```

### OnKill(WorkerModel)

```csharp
public void OnKill(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### OnStageEnd()

```csharp
public override void OnStageEnd()
```

### StartSettingPos()

```csharp
public void StartSettingPos()
```
