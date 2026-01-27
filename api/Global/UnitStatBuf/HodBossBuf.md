---
uid: Global.HodBossBuf
canonical_path: /api/Global/UnitStatBuf/HodBossBuf
---

# Class HodBossBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class HodBossBuf : UnitStatBuf
```

Buff which reduces reduces all stats by a certain amount.

Used by Hod in [her core suppression](/api/Global/Misc/HodBossBase).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → [UnitStatBuf](/api/Global/UnitBuf/UnitStatBuf) → HodBossBuf

## Inherited Members
[primaryStat](/api/Global/UnitBuf/UnitStatBuf#primarystat), [maxHp](/api/Global/UnitBuf/UnitStatBuf#maxhp), [maxMental](/api/Global/UnitBuf/UnitStatBuf#maxmental), [cubeSpeed](/api/Global/UnitBuf/UnitStatBuf#cubespeed), [workProb](/api/Global/UnitBuf/UnitStatBuf#workprob), [movementSpeed](/api/Global/UnitBuf/UnitStatBuf#movementspeed), [attackSpeed](/api/Global/UnitBuf/UnitStatBuf#attackspeed), [type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitDie()](/api/Global/Misc/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### HodBossBuf()

```csharp
public HodBossBuf()
```
#INC


## Fields

### _reduceVal

```csharp
private float _reduceVal
```
#INC


#### Field Value

**Type:** System.Single

### agent

```csharp
private AgentModel agent
```
#INC


#### Field Value

**Type:** Global.AgentModel

### B_min

```csharp
private const float B_min = 10
```
#INC


#### Field Value

**Type:** System.Single

### lateInit

```csharp
private bool lateInit
```
#INC


#### Field Value

**Type:** System.Boolean

### P_min

```csharp
private const float P_min = 10
```
#INC


#### Field Value

**Type:** System.Single

### R_min

```csharp
private const float R_min = 10
```
#INC


#### Field Value

**Type:** System.Single

### W_min

```csharp
private const float W_min = 10
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### B_buf

```csharp
private float B_buf { get; }
```

#### Property Value

**Type:** System.Single

### P_buf

```csharp
private float P_buf { get; }
```

#### Property Value

**Type:** System.Single

### R_buf

```csharp
private float R_buf { get; }
```

#### Property Value

**Type:** System.Single

### W_buf

```csharp
private float W_buf { get; }
```

#### Property Value

**Type:** System.Single

## Methods

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

### LateInit()

```csharp
private void LateInit()
```
#INC


### SetReduceValue(float)

```csharp
public void SetReduceValue(float val)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |
