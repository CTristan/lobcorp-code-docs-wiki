---
uid: Global.BarrierBuf
canonical_path: /api/Global/UnitBuf/BarrierBuf
---

# Class BarrierBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BarrierBuf : UnitBuf
```
Buff for having a shield applied?
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → BarrierBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitDie()](/api/Global/Misc/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BarrierBuf(RwbpType, float, float)

```csharp
public BarrierBuf(RwbpType type, float barrierValue, float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |
| `barrierValue` | `System.Single` |  |
| `time` | `System.Single` |  |

## Fields

### _barrierValue

```csharp
private float _barrierValue
```
#INC


#### Field Value

**Type:** System.Single

### _barrierValueMax

```csharp
private float _barrierValueMax
```
#INC


#### Field Value

**Type:** System.Single

### _rwbpType

```csharp
private RwbpType _rwbpType
```
#INC


#### Field Value

**Type:** Global.RwbpType

### barrierEffect

```csharp
private BarrierEffect barrierEffect
```
#INC


#### Field Value

**Type:** Global.BarrierEffect

### maxTime

```csharp
private float maxTime
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### Rate

```csharp
private float Rate { get; }
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

### OnCrackBarrier()

```csharp
public void OnCrackBarrier()
```
#INC


### OnDestroy()

```csharp
public override void OnDestroy()
```
#INC


### UseBarrier(RwbpType, float)

```csharp
public float UseBarrier(RwbpType dmgRwbpType, float damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dmgRwbpType` | `Global.RwbpType` |  |
| `damage` | `System.Single` |  |

#### Returns

**Type:** System.Single
