---
uid: Global.SnowQueenBuf
canonical_path: /api/Global/UnitBuf/SnowQueenBuf
---

# Class SnowQueenBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SnowQueenBuf : UnitBuf
```

Old version of [The Snow Queen](/api/Global/Misc/SnowQueen)'s first kiss effect.

Does nothing, but when destroyed sets the agent's maximum HP and SP to what it was when this was originally given. #verify 

#unused #maybe_unused 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → SnowQueenBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitDie()](/api/Global/Misc/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SnowQueenBuf(SnowQueen)

```csharp
public SnowQueenBuf(SnowQueen sq)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sq` | `Global.SnowQueen` |  |

## Fields

### _agentModel

```csharp
private AgentModel _agentModel
```
#INC


#### Field Value

**Type:** Global.AgentModel

### _snowQueen

```csharp
private SnowQueen _snowQueen
```
#INC


#### Field Value

**Type:** Global.SnowQueen

### BUF_CONSTANT

```csharp
private readonly int BUF_CONSTANT
```
#INC


#### Field Value

**Type:** System.Int32

### defaultMaxHp

```csharp
private int defaultMaxHp
```
#INC


#### Field Value

**Type:** System.Int32

### defaultMaxMental

```csharp
private int defaultMaxMental
```
#INC


#### Field Value

**Type:** System.Int32

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC
#code-generated


### Init(UnitModel)

```csharp
public override void Init(UnitModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

### OnDestroy()

```csharp
public override void OnDestroy()
```
#INC

