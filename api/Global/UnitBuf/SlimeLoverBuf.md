---
uid: Global.SlimeLoverBuf
canonical_path: /api/Global/UnitBuf/SlimeLoverBuf
---

# Class SlimeLoverBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SlimeLoverBuf : UnitBuf
```

Buff marking an employee as [Melting Love](/api/Global/Misc/SlimeGirl)'s favorite.

Infects other employees in the same room every 10 seconds at a 25% chance each, unless paused due to successful work with Melting Love. Infecting gives them the [SlimePawnBuf](/api/Global/UnitBuf/SlimePawnBuf).

Restores 30 SP every 15 seconds #verify .

If this employee dies, depletes Melting Love's Qliphoth counter #verify .


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → SlimeLoverBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Init(UnitModel)](/api/Global/Misc/UnitBuf#init-unitmodel), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SlimeLoverBuf(WorkerModel, SlimeGirl)

```csharp
public SlimeLoverBuf(WorkerModel worker, SlimeGirl script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |
| `script` | `Global.SlimeGirl` |  |

## Fields

### _mentalHealMax

```csharp
private const float _mentalHealMax = 30
```
#INC


#### Field Value

**Type:** System.Single

### _mentalHealMin

```csharp
private const float _mentalHealMin = 30
```
#INC


#### Field Value

**Type:** System.Single

### INFEST_PAUSE_TIME

```csharp
private const float INFEST_PAUSE_TIME = 30
```
#INC


#### Field Value

**Type:** System.Single

### INFEST_PROB

```csharp
private const float INFEST_PROB = 0.25
```
#INC


#### Field Value

**Type:** System.Single

### INFEST_TIME

```csharp
private const float INFEST_TIME = 10
```
#INC


#### Field Value

**Type:** System.Single

### infestPauseTimer

```csharp
private Timer infestPauseTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### infestTimer

```csharp
private Timer infestTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### MENTAL_HEAL_TIME

```csharp
private const float MENTAL_HEAL_TIME = 15
```
#INC


#### Field Value

**Type:** System.Single

### mentalHealTimer

```csharp
private Timer mentalHealTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### script

```csharp
private SlimeGirl script
```
#INC


#### Field Value

**Type:** Global.SlimeGirl

### worker

```csharp
private WorkerModel worker
```
#INC


#### Field Value

**Type:** Global.WorkerModel

## Properties

### MentalHealValue

```csharp
private static float MentalHealValue { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC


### Infest()

```csharp
private void Infest()
```
#INC


### Infest(WorkerModel)

```csharp
private void Infest(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### MentalHeal()

```csharp
private void MentalHeal()
```
#INC


### OnDestroy()

```csharp
public override void OnDestroy()
```
#INC


### OnSuccessWork()

```csharp
public void OnSuccessWork()
```
#INC


### OnUnitDie()

```csharp
public override void OnUnitDie()
```
#INC
#code-generated

