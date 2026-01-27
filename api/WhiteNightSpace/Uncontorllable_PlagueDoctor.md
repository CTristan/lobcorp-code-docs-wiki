---
uid: WhiteNightSpace.Uncontorllable_PlagueDoctor
canonical_path: /api/WhiteNightSpace/Uncontorllable_PlagueDoctor
---

# Class Uncontorllable_PlagueDoctor

**Namespace:** [WhiteNightSpace](/api/WhiteNightSpace)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontorllable_PlagueDoctor : UncontrollableAction
```

Uncontrollable action for employees which are being drawn to [Plague Doctor](/api/Legacy/PlagueDoctor) when its Qliphoth counter hits 0.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Misc/HierarchicalData) → [UncontrollableAction](/api/Global/Action/UncontrollableAction) → Uncontorllable_PlagueDoctor

## Inherited Members
[OnStageEnd()](/api/Global/Action/UncontrollableAction#onstageend), [OnPrevDie()](/api/Global/Action/UncontrollableAction#onprevdie), [OnClick()](/api/Global/Action/UncontrollableAction#onclick), [UnderAttack()](/api/Global/Action/UncontrollableAction#underattack), [OnTakePhysicalDamage(int)](/api/Global/Action/UncontrollableAction#ontakephysicaldamage-int), [OnTakeMentalDamage(int)](/api/Global/Action/UncontrollableAction#ontakementaldamage-int), [ShowUnconSpeech(string)](/api/Global/Action/UncontrollableAction#showunconspeech-string), [OnKillTarget()](/api/Global/Action/UncontrollableAction#onkilltarget), [HasUniqueHostility()](/api/Global/Action/UncontrollableAction#hasuniquehostility), [IsHostile()](/api/Global/Action/UncontrollableAction#ishostile), [HasAttackAnim()](/api/Global/Action/UncontrollableAction#hasattackanim), [SetAttackAnim()](/api/Global/Action/UncontrollableAction#setattackanim), [IsNextAttackWillKillTarget()](/api/Global/Action/UncontrollableAction#isnextattackwillkilltarget), [OnNextAttakInvokeKill()](/api/Global/Action/UncontrollableAction#onnextattakinvokekill), [CastingSlider(Slider)](/api/Global/Action/UncontrollableAction#castingslider-slider), [IsPreferredTouch()](/api/Global/Action/UncontrollableAction#ispreferredtouch), [IsAttackTargetable()](/api/Global/Action/UncontrollableAction#isattacktargetable), [_H_index](/api/Global/Misc/HierarchicalData#h-index), [InitialSetting()](/api/Global/Misc/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Misc/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Misc/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Misc/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Misc/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Uncontorllable_PlagueDoctor(AgentModel, PlagueDoctor)

```csharp
public Uncontorllable_PlagueDoctor(AgentModel agent, PlagueDoctor doctor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |
| `doctor` | `WhiteNightSpace.PlagueDoctor` |  |

## Fields

### _currentDest

```csharp
private MapNode _currentDest
```
#INC


#### Field Value

**Type:** Global.MapNode

### _destNode

```csharp
private MapNode _destNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### _entryNode

```csharp
private MapNode _entryNode
```
#INC


#### Field Value

**Type:** Global.MapNode

### _model

```csharp
private AgentModel _model
```
#INC


#### Field Value

**Type:** Global.AgentModel

### _plagueDoctor

```csharp
private PlagueDoctor _plagueDoctor
```
#INC


#### Field Value

**Type:** WhiteNightSpace.PlagueDoctor

### _waitFreq

```csharp
private static float _waitFreq
```
#INC


#### Field Value

**Type:** System.Single

### waitTimer

```csharp
private float waitTimer
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### Execute()

```csharp
public override void Execute()
```
#INC


### Init()

```csharp
public override void Init()
```
#INC
#code-generated


### OnDestroy()

```csharp
public override void OnDestroy()
```
#INC


### OnDie()

```csharp
public override void OnDie()
```
#INC

