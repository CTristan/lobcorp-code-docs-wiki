---
uid: Global.DefaultSlowBuf
canonical_path: /api/Global/UnitBuf/DefaultSlowBuf
---

# Class DefaultSlowBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DefaultSlowBuf : UnitBuf
```

Slows down a unit by a given amount.

... But this is only ever used by [Singing Machine](/api/Global/Machine/SingingMachine).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → DefaultSlowBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [FixedUpdate()](/api/Global/Misc/UnitBuf#fixedupdate), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [OnUnitDie()](/api/Global/Misc/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DefaultSlowBuf(float, float)

```csharp
public DefaultSlowBuf(float movementScale, float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `movementScale` | `System.Single` |  |
| `time` | `System.Single` |  |

### DefaultSlowBuf(float, float, UnitBufType)

```csharp
public DefaultSlowBuf(float movementScale, float time, UnitBufType t)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `movementScale` | `System.Single` |  |
| `time` | `System.Single` |  |
| `t` | `Global.UnitBufType` |  |

## Fields

### _movemnetScale

```csharp
private float _movemnetScale
```
#INC


#### Field Value

**Type:** System.Single

### _time

```csharp
private float _time
```
#INC


#### Field Value

**Type:** System.Single

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

### MovementScale()

```csharp
public override float MovementScale()
```
#INC


#### Returns

**Type:** System.Single
