# Class Uncontrollable_SilentOrchestra

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_SilentOrchestra : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/HierarchicalData) → [UncontrollableAction](/api/UncontrollableAction) → Uncontrollable_SilentOrchestra

## Inherited Members
[OnPrevDie()](/api/UncontrollableAction#onprevdie), [OnClick()](/api/UncontrollableAction#onclick), [UnderAttack()](/api/UncontrollableAction#underattack), [OnTakePhysicalDamage(int)](/api/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/UncontrollableAction#ontakementaldamage-int), [ShowUnconSpeech(string)](/api/UncontrollableAction#showunconspeech-string), [HasUniqueHostility()](/api/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/UncontrollableAction#ishostile), [HasAttackAnim()](/api/UncontrollableAction#hasattackanim), [SetAttackAnim()](/api/UncontrollableAction#setattackanim), [IsNextAttackWillKillTarget()](/api/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/UncontrollableAction#castingslider-slider), [IsPreferredTouch()](/api/UncontrollableAction#ispreferredtouch), [IsAttackTargetable()](/api/UncontrollableAction#isattacktargetable), [_H_index](/api/HierarchicalData#h-index), [InitialSetting()](/api/HierarchicalData#initialsetting), [GetHierachicalName()](/api/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

### ExplodeAfterEffect

```csharp
public const string ExplodeAfterEffect = "Effect/Creature/SilentOrchestra/NoteEffectSilentDead"
```

#### Field Value

**Type:** System.String

## Methods

### AfterEffect()

```csharp
public void AfterEffect()
```

### CastDie()

```csharp
public void CastDie()
```

### DeadCommand()

```csharp
public void DeadCommand()
```

### Execute()

```csharp
public override void Execute()
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

### StartTargeting()

```csharp
public void StartTargeting()
```

### ViolenceCommand()

```csharp
public void ViolenceCommand()
```
