---
uid: Global.PianoBuf
canonical_path: /api/Global/UnitStatBuf/PianoBuf
---

# Class PianoBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PianoBuf : UnitStatBuf
```

Buff applied to agents while an agent is playing [Il Pianto della Luna](/api/Global/Misc/Piano)'s piano.

Adds 5 to justice and temperance.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → [UnitStatBuf](/api/Global/UnitBuf/UnitStatBuf) → PianoBuf

## Inherited Members
[primaryStat](/api/Global/UnitBuf/UnitStatBuf#primarystat), [maxHp](/api/Global/UnitBuf/UnitStatBuf#maxhp), [maxMental](/api/Global/UnitBuf/UnitStatBuf#maxmental), [cubeSpeed](/api/Global/UnitBuf/UnitStatBuf#cubespeed), [workProb](/api/Global/UnitBuf/UnitStatBuf#workprob), [movementSpeed](/api/Global/UnitBuf/UnitStatBuf#movementspeed), [attackSpeed](/api/Global/UnitBuf/UnitStatBuf#attackspeed), [type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [FixedUpdate()](/api/Global/Misc/UnitBuf#fixedupdate), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PianoBuf()

```csharp
public PianoBuf()
```
#INC


## Fields

### agent

```csharp
private AgentModel agent
```
#INC


#### Field Value

**Type:** Global.AgentModel

### JUSTICE_BUF

```csharp
private const int JUSTICE_BUF = 5
```
#INC


#### Field Value

**Type:** System.Int32

### TEMPERANCE_BUF

```csharp
private const int TEMPERANCE_BUF = 5
```
#INC


#### Field Value

**Type:** System.Int32

## Methods

### Init(UnitModel)

```csharp
public override void Init(UnitModel model)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

### OnUnitDie()

```csharp
public override void OnUnitDie()
```
#INC

