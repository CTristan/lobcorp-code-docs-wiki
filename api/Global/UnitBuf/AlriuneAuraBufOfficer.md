---
uid: Global.AlriuneAuraBufOfficer
canonical_path: /api/Global/UnitBuf/AlriuneAuraBufOfficer
---

# Class AlriuneAuraBufOfficer

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AlriuneAuraBufOfficer : UnitBuf
```

Effect that handles clerk death by [Alriune](/api/Global/Misc/Alriune)'s attacks.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → AlriuneAuraBufOfficer

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [FixedUpdate()](/api/Global/Misc/UnitBuf#fixedupdate), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AlriuneAuraBufOfficer()

```csharp
public AlriuneAuraBufOfficer()
```
Sets the [UnitBufType](/api/Global/Type/UnitBufType) to ALRIUNE_AURA.


## Fields

### curtainAnimator

```csharp
private Animator curtainAnimator
```
Animator for the curtain effect on this clerk.


#### Field Value

**Type:** UnityEngine.Animator

### delay

```csharp
private const float delay = 3
```
#INC


#### Field Value

**Type:** System.Single

### specialDeadScene

```csharp
private bool specialDeadScene
```
#INC


#### Field Value

**Type:** System.Boolean

### worker

```csharp
private WorkerModel worker
```
Stores the clerk affected by this buff.


#### Field Value

**Type:** Global.WorkerModel

## Methods

### Init(UnitModel)

```csharp
public override void Init(UnitModel model)
```
Sets the clerk's special death animation.


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

### OnDestroy()

```csharp
public override void OnDestroy()
```
If the worker is alive, resets the special death animation to not happen; otherwise, tells the curtainAnimator that this unit is dead and sets the special death animation randomly to one of four animations.
#code-generated


### OnUnitDie()

```csharp
public override void OnUnitDie()
```
Loads a curtain effect prefab on the clerk. Starts a 3 second timer to destroy this buff.

