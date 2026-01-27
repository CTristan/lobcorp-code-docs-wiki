---
uid: Global.PinkCorpsBuf
canonical_path: /api/Global/UnitBuf/PinkCorpsBuf
---

# Class PinkCorpsBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PinkCorpsBuf : UnitBuf
```

Parent class for buffs of employees affected by [Army in Black](/api/Global/IOBserver/PinkCorps)'s special work type.

See:
- [PinkCorpsProtectBuf](/api/Global/Misc/PinkCorpsProtectBuf) (defense up also?) #Inc
- [PinkCorpsLoveBuf](/api/Global/Misc/PinkCorpsLoveBuf) (defense up) #inc


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → PinkCorpsBuf

## Derived
[PinkCorpsLoveBuf](/api/Global/Misc/PinkCorpsLoveBuf), [PinkCorpsProtectBuf](/api/Global/Misc/PinkCorpsProtectBuf)

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Init(UnitModel)](/api/Global/Misc/UnitBuf#init-unitmodel), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PinkCorpsBuf(UnitModel, PinkCorps)

```csharp
public PinkCorpsBuf(UnitModel target, PinkCorps pink)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `pink` | `Global.PinkCorps` |  |

## Fields

### DamageFactor

```csharp
public float DamageFactor
```
#INC


#### Field Value

**Type:** System.Single

### pink

```csharp
public PinkCorps pink
```
#INC


#### Field Value

**Type:** Global.PinkCorps

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC
#code-generated


### OnUnitDie()

```csharp
public override void OnUnitDie()
```
#INC

