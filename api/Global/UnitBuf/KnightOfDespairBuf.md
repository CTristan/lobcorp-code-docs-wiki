---
uid: Global.KnightOfDespairBuf
canonical_path: /api/Global/UnitBuf/KnightOfDespairBuf
---

# Class KnightOfDespairBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KnightOfDespairBuf : UnitBuf
```

Buff for [The Knight of Despair](/api/Global/Misc/KnightOfDespair)'s blessed agent.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → KnightOfDespairBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### KnightOfDespairBuf(KnightOfDespair)

```csharp
public KnightOfDespairBuf(KnightOfDespair knight)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `knight` | `Global.KnightOfDespair` |  |

## Fields

### knight

```csharp
public KnightOfDespair knight
```
#INC


#### Field Value

**Type:** Global.KnightOfDespair

## Methods

### Check()

```csharp
private bool Check()
```
#INC


#### Returns

**Type:** System.Boolean

### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC


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

### OnStageRelease()

```csharp
public override void OnStageRelease()
```
#INC


### OnTakeDamage(UnitModel, DamageInfo)

```csharp
public override float OnTakeDamage(UnitModel attacker, DamageInfo damageInfo)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `damageInfo` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Single

### OnUnitDie()

```csharp
public override void OnUnitDie()
```
#INC


### OnUnitPanic()

```csharp
public override void OnUnitPanic()
```
#INC

