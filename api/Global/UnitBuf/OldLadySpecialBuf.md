---
uid: Global.OldLadySpecialBuf
canonical_path: /api/Global/UnitBuf/OldLadySpecialBuf
---

# Class OldLadySpecialBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OldLadySpecialBuf : UnitBuf
```

Effect given to 'solitude' employees after working with an upset [Old Lady](/api/Global/IOBserver/OldLady).

Lasts 30 seconds.
Removes control of the agent, moves them to the entrance to Old Lady's containment unit, and damages them for between 4 and 6 white damage every 6 seconds for 30 seconds.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → OldLadySpecialBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitDie()](/api/Global/Misc/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OldLadySpecialBuf(OldLady)

```csharp
public OldLadySpecialBuf(OldLady oldLady)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `oldLady` | `Global.OldLady` |  |

## Fields

### defaultRemainTime

```csharp
private const float defaultRemainTime = 30
```
#INC


#### Field Value

**Type:** System.Single

### defaultTickTime

```csharp
private const float defaultTickTime = 6
```
#INC


#### Field Value

**Type:** System.Single

### effect

```csharp
private GameObject effect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### oldLady

```csharp
private OldLady oldLady
```
#INC


#### Field Value

**Type:** Global.OldLady

### tickTime

```csharp
private float tickTime
```
#INC


#### Field Value

**Type:** System.Single

### whiteDmgMax

```csharp
private const float whiteDmgMax = 6
```
#INC


#### Field Value

**Type:** System.Single

### whiteDmgMin

```csharp
private const float whiteDmgMin = 4
```
#INC


#### Field Value

**Type:** System.Single

### worker

```csharp
private WorkerModel worker
```
#INC


#### Field Value

**Type:** Global.WorkerModel

## Properties

### whiteDmg

```csharp
private static float whiteDmg { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### Destroy()

```csharp
public override void Destroy()
```
#INC


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
