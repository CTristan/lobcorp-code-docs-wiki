# Class BlackFogOverload

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BlackFogOverload : BinahOverload, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [BinahOverload](/api/BinahBoss-BinahOverload) → BlackFogOverload

## Inherited Members
[ProbReductionValue](/api/BinahBoss-BinahOverload#probreductionvalue), [TimeLimit](/api/BinahBoss-BinahOverload#timelimit), [BinahAttachedEffect](/api/BinahBoss-BinahOverload#binahattachedeffect), [IsolatePercent](/api/BinahBoss-BinahOverload#isolatepercent), [SuccessAction](/api/BinahBoss-BinahOverload#successaction), [FailureAction](/api/BinahBoss-BinahOverload#failureaction), [overloadType](/api/BinahBoss-BinahOverload#overloadtype), [overloadedCreatures](/api/BinahBoss-BinahOverload#overloadedcreatures), [binah](/api/BinahBoss-BinahOverload#binah), [GetOverloadTargetCount(BinahOverload)](/api/BinahBoss-BinahOverload#getoverloadtargetcount-binahoverload), [LoadBinahAttachedEffect(string)](/api/BinahBoss-BinahOverload#loadbinahattachedeffect-string), [OnDestroy()](/api/BinahBoss-BinahOverload#ondestroy), [GetCreatureCount()](/api/BinahBoss-BinahOverload#getcreaturecount), [Interrupt()](/api/BinahBoss-BinahOverload#interrupt), [OnReducedCreature(CreatureModel)](/api/BinahBoss-BinahOverload#onreducedcreature-creaturemodel), [OnNotice(string, params object[])](/api/BinahBoss-BinahOverload#onnotice-string-params-object), [OnParticleArrived(CreatureModel)](/api/BinahBoss-BinahOverload#onparticlearrived-creaturemodel), [OnExecute()](/api/BinahBoss-BinahOverload#onexecute), [Movable](/api/BinahBoss-BinahOverload#movable), [Model](/api/BinahBoss-BinahOverload#model), [AnimScript](/api/BinahBoss-BinahOverload#animscript), [Animator](/api/BinahBoss-BinahOverload#animator), [DefenseInfo](/api/BinahBoss-BinahOverload#defenseinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BlackFogOverload(BinahCoreScript)

```csharp
public BlackFogOverload(BinahCoreScript binah)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |

## Methods

### CastOverload()

```csharp
public override void CastOverload()
```

### OnFail()

```csharp
public override void OnFail()
```

### OnSuccess()

```csharp
public override void OnSuccess()
```
