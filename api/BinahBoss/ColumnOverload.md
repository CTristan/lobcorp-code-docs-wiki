---
uid: BinahBoss.ColumnOverload
canonical_path: /api/BinahBoss/ColumnOverload
---

# Class ColumnOverload

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ColumnOverload : BinahOverload, IObserver
```
Class for the Meltdown of Pillars Qliphoth meltdown (light blue). Success cancels the [Eight Column](/api/BinahBoss/EightColumn) attack; failure fires it.
Starts in [Phase 3](/api/BinahBoss/ThirdPhase).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [BinahOverload](/api/BinahBoss/BinahOverload) → ColumnOverload

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[ProbReductionValue](/api/BinahBoss/BinahOverload#probreductionvalue), [TimeLimit](/api/BinahBoss/BinahOverload#timelimit), [BinahAttachedEffect](/api/BinahBoss/BinahOverload#binahattachedeffect), [IsolatePercent](/api/BinahBoss/BinahOverload#isolatepercent), [SuccessAction](/api/BinahBoss/BinahOverload#successaction), [FailureAction](/api/BinahBoss/BinahOverload#failureaction), [overloadType](/api/BinahBoss/BinahOverload#overloadtype), [overloadedCreatures](/api/BinahBoss/BinahOverload#overloadedcreatures), [binah](/api/BinahBoss/BinahOverload#binah), [_defenseInfo](/api/BinahBoss/BinahOverload#defenseinfo), [GetOverloadTargetCount(BinahOverload)](/api/BinahBoss/BinahOverload#getoverloadtargetcount-binahoverload), [LoadBinahAttachedEffect(string)](/api/BinahBoss/BinahOverload#loadbinahattachedeffect-string), [OnDestroy()](/api/BinahBoss/BinahOverload#ondestroy), [CastOverload()](/api/BinahBoss/BinahOverload#castoverload), [GetCreatureCount()](/api/BinahBoss/BinahOverload#getcreaturecount), [Interrupt()](/api/BinahBoss/BinahOverload#interrupt), [OnReducedCreature(CreatureModel)](/api/BinahBoss/BinahOverload#onreducedcreature-creaturemodel), [OnNotice(string, params object[])](/api/BinahBoss/BinahOverload#onnotice-string-params-object), [OnParticleArrived(CreatureModel)](/api/BinahBoss/BinahOverload#onparticlearrived-creaturemodel), [Movable](/api/BinahBoss/BinahOverload#movable), [Model](/api/BinahBoss/BinahOverload#model), [AnimScript](/api/BinahBoss/BinahOverload#animscript), [Animator](/api/BinahBoss/BinahOverload#animator), [DefenseInfo](/api/BinahBoss/BinahOverload#defenseinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ColumnOverload(BinahCoreScript, EightColumn)

```csharp
public ColumnOverload(BinahCoreScript binah, EightColumn column)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |
| `column` | `BinahBoss.EightColumn` |  |

## Fields

### action

```csharp
private EightColumn action
```
#INC


#### Field Value

**Type:** BinahBoss.EightColumn

## Methods

### OnExecute()

```csharp
public override void OnExecute()
```
#INC
#code-generated


### OnFail()

```csharp
public override void OnFail()
```
#INC


### OnSuccess()

```csharp
public override void OnSuccess()
```
#INC

