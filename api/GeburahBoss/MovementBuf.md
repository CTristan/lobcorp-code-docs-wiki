---
uid: GeburahBoss.MovementBuf
canonical_path: /api/GeburahBoss/MovementBuf
---

# Class MovementBuf

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MovementBuf : UnitBuf
```

Buff that scales a unit's speed.

Used on [The Red Mist](/api/Global/Script/GeburahCoreScript) for her [chase attack](/api/GeburahBoss/ChaseAction) and [Gold Rush attack](/api/GeburahBoss/GreedyTelepeort) (including the [phase 4 version](/api/GeburahBoss/GreedyThrow)).

Also used to apply a slowing debuff to agents hit by projectile of the Phase 4 Gold Rush attack.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → MovementBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Init(UnitModel)](/api/Global/Misc/UnitBuf#init-unitmodel), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [OnUnitDie()](/api/Global/Misc/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MovementBuf(float)

```csharp
public MovementBuf(float factor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factor` | `System.Single` |  |

### MovementBuf(float, float)

```csharp
public MovementBuf(float factor, float lifeTime)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factor` | `System.Single` |  |
| `lifeTime` | `System.Single` |  |

## Fields

### _timer

```csharp
private Timer _timer
```
#INC


#### Field Value

**Type:** Global.Timer

### factor

```csharp
private float factor
```
#INC


#### Field Value

**Type:** System.Single

### lifeTime

```csharp
private float lifeTime
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC


### MovementScale()

```csharp
public override float MovementScale()
```
#INC
#code-generated


#### Returns

**Type:** System.Single
