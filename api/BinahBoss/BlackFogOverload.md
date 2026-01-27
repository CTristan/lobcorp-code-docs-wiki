---
uid: BinahBoss.BlackFogOverload
canonical_path: /api/BinahBoss/BlackFogOverload
---

# Class BlackFogOverload

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BlackFogOverload : BinahOverload, IObserver
```
Class for the Meltdown of Dark Fog Qliphoth meltdowns (silver). Success makes [An Arbiter](/api/Global/Script/BinahCoreScript) vulnerable to all damage.

Starts in [Phase 1](/api/BinahBoss/FirstPhase).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [BinahOverload](/api/BinahBoss/BinahOverload) → BlackFogOverload

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[ProbReductionValue](/api/BinahBoss/BinahOverload#probreductionvalue), [TimeLimit](/api/BinahBoss/BinahOverload#timelimit), [BinahAttachedEffect](/api/BinahBoss/BinahOverload#binahattachedeffect), [IsolatePercent](/api/BinahBoss/BinahOverload#isolatepercent), [SuccessAction](/api/BinahBoss/BinahOverload#successaction), [FailureAction](/api/BinahBoss/BinahOverload#failureaction), [overloadType](/api/BinahBoss/BinahOverload#overloadtype), [overloadedCreatures](/api/BinahBoss/BinahOverload#overloadedcreatures), [binah](/api/BinahBoss/BinahOverload#binah), [_defenseInfo](/api/BinahBoss/BinahOverload#defenseinfo), [GetOverloadTargetCount(BinahOverload)](/api/BinahBoss/BinahOverload#getoverloadtargetcount-binahoverload), [LoadBinahAttachedEffect(string)](/api/BinahBoss/BinahOverload#loadbinahattachedeffect-string), [OnDestroy()](/api/BinahBoss/BinahOverload#ondestroy), [GetCreatureCount()](/api/BinahBoss/BinahOverload#getcreaturecount), [Interrupt()](/api/BinahBoss/BinahOverload#interrupt), [OnReducedCreature(CreatureModel)](/api/BinahBoss/BinahOverload#onreducedcreature-creaturemodel), [OnNotice(string, params object[])](/api/BinahBoss/BinahOverload#onnotice-string-params-object), [OnParticleArrived(CreatureModel)](/api/BinahBoss/BinahOverload#onparticlearrived-creaturemodel), [OnExecute()](/api/BinahBoss/BinahOverload#onexecute), [Movable](/api/BinahBoss/BinahOverload#movable), [Model](/api/BinahBoss/BinahOverload#model), [AnimScript](/api/BinahBoss/BinahOverload#animscript), [Animator](/api/BinahBoss/BinahOverload#animator), [DefenseInfo](/api/BinahBoss/BinahOverload#defenseinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BlackFogOverload(BinahCoreScript)

```csharp
public BlackFogOverload(BinahCoreScript binah)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |

## Fields

### blackFogBuf

```csharp
private BinahBlackFogBuf blackFogBuf
```
#INC


#### Field Value

**Type:** BinahBoss.BinahBlackFogBuf

## Methods

### CastOverload()

```csharp
public override void CastOverload()
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

