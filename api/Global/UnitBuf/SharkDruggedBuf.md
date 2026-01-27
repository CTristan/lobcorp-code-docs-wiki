---
uid: Global.SharkDruggedBuf
canonical_path: /api/Global/UnitBuf/SharkDruggedBuf
---

# Class SharkDruggedBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SharkDruggedBuf : UnitBuf
```

Debuff given by [The Dreaming Current](/api/Global/Misc/Shark)'s hallways.

Slows by 0.4x.
Damages for 2-4 red and heals for 2-4 white every 2 seconds... but only lasts 1 second, so this never happens. #verify 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → SharkDruggedBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SharkDruggedBuf()

```csharp
public SharkDruggedBuf()
```
#INC


## Fields

### debufMovement

```csharp
private const float debufMovement = 0.4
```
#INC


#### Field Value

**Type:** System.Single

### dmgMax

```csharp
private const int dmgMax = 3
```
#INC


#### Field Value

**Type:** System.Int32

### dmgMin

```csharp
private const int dmgMin = 2
```
#INC


#### Field Value

**Type:** System.Int32

### mpHealMax

```csharp
private const int mpHealMax = 3
```
#INC


#### Field Value

**Type:** System.Int32

### mpHealMin

```csharp
private const int mpHealMin = 2
```
#INC


#### Field Value

**Type:** System.Int32

### tickTime

```csharp
private const float tickTime = 2
```
#INC


#### Field Value

**Type:** System.Single

### tickTimer

```csharp
private Timer tickTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### worker

```csharp
private WorkerModel worker
```
#INC


#### Field Value

**Type:** Global.WorkerModel

## Properties

### dmg

```csharp
private static int dmg { get; }
```

#### Property Value

**Type:** System.Int32

### mpHeal

```csharp
private static int mpHeal { get; }
```

#### Property Value

**Type:** System.Int32

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

### MovementScale()

```csharp
public override float MovementScale()
```
#INC


#### Returns

**Type:** System.Single

### OnUnitDie()

```csharp
public override void OnUnitDie()
```
#INC

