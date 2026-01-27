---
uid: Global.PinkCorpsProtectBuf
canonical_path: /api/Global/Misc/PinkCorpsProtectBuf
---

# Class PinkCorpsProtectBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PinkCorpsProtectBuf : PinkCorpsBuf
```

Reduces damage by a factor of 0.8x.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → [PinkCorpsBuf](/api/Global/UnitBuf/PinkCorpsBuf) → PinkCorpsProtectBuf

## Inherited Members
[DamageFactor](/api/Global/UnitBuf/PinkCorpsBuf#damagefactor), [pink](/api/Global/UnitBuf/PinkCorpsBuf#pink), [FixedUpdate()](/api/Global/UnitBuf/PinkCorpsBuf#fixedupdate), [OnUnitDie()](/api/Global/UnitBuf/PinkCorpsBuf#onunitdie), [type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Init(UnitModel)](/api/Global/Misc/UnitBuf#init-unitmodel), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PinkCorpsProtectBuf(UnitModel, PinkCorps)

```csharp
public PinkCorpsProtectBuf(UnitModel owner, PinkCorps pink)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.UnitModel` |  |
| `pink` | `Global.PinkCorps` |  |

## Methods

### OnTakeDamage(UnitModel, DamageInfo)

```csharp
public override float OnTakeDamage(UnitModel attacker, DamageInfo damageInfo)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `damageInfo` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Single
