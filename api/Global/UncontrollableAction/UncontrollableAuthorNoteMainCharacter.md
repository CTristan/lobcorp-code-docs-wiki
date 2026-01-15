---
uid: Global.Uncontrollable_AuthorNoteMainCharacter
canonical_path: /api/Global/UncontrollableAction/UncontrollableAuthorNoteMainCharacter
---

# Class Uncontrollable_AuthorNoteMainCharacter

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_AuthorNoteMainCharacter : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Misc/HierarchicalData) → [UncontrollableAction](/api/Global/Action/UncontrollableAction) → Uncontrollable_AuthorNoteMainCharacter

## Inherited Members
[OnStageEnd()](/api/Global/Action/UncontrollableAction#onstageend), [OnPrevDie()](/api/Global/Action/UncontrollableAction#onprevdie), [OnClick()](/api/Global/Action/UncontrollableAction#onclick), [UnderAttack()](/api/Global/Action/UncontrollableAction#underattack), [OnTakePhysicalDamage(int)](/api/Global/Action/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/Global/Action/UncontrollableAction#ontakementaldamage-int), [ShowUnconSpeech(string)](/api/Global/Action/UncontrollableAction#showunconspeech-string), [HasUniqueHostility()](/api/Global/Action/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/Global/Action/UncontrollableAction#ishostile), [HasAttackAnim()](/api/Global/Action/UncontrollableAction#hasattackanim), [SetAttackAnim()](/api/Global/Action/UncontrollableAction#setattackanim), [IsNextAttackWillKillTarget()](/api/Global/Action/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/Global/Action/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/Global/Action/UncontrollableAction#castingslider-slider), [IsPreferredTouch()](/api/Global/Action/UncontrollableAction#ispreferredtouch), [IsAttackTargetable()](/api/Global/Action/UncontrollableAction#isattacktargetable), [_H_index](/api/Global/Misc/HierarchicalData#h-index), [InitialSetting()](/api/Global/Misc/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Misc/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Misc/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Misc/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Misc/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Uncontrollable_AuthorNoteMainCharacter(AgentModel, AuthorNote)

```csharp
public Uncontrollable_AuthorNoteMainCharacter(AgentModel model, AuthorNote note)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.AgentModel` |  |
| `note` | `Global.AuthorNote` |  |

## Fields

### actionStartTimer

```csharp
private Timer actionStartTimer
```

#### Field Value

**Type:** Global.Timer

### balloon

```csharp
private AuthorNoteWorkerBalloon balloon
```

#### Field Value

**Type:** Global.AuthorNoteWorkerBalloon

### currentTarget

```csharp
public WorkerModel currentTarget
```

#### Field Value

**Type:** Global.WorkerModel

### effectObject

```csharp
private GameObject effectObject
```

#### Field Value

**Type:** UnityEngine.GameObject

### model

```csharp
private AgentModel model
```

#### Field Value

**Type:** Global.AgentModel

### note

```csharp
private AuthorNote note
```

#### Field Value

**Type:** Global.AuthorNote

## Methods

### ChangeTarget(WorkerModel)

```csharp
public void ChangeTarget(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### Execute()

```csharp
public override void Execute()
```

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

### RemoveBalloon()

```csharp
private void RemoveBalloon()
```
