---
uid: Global.BigTreeSapBuf
canonical_path: /api/Global/UnitBuf/BigTreeSapBuf
---

# Class BigTreeSapBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BigTreeSapBuf : UnitBuf
```

Buff which makes agents explode after drinking from [Giant Tree Sap](/api/Global/Misc/BigTreeSap), sometimes.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → BigTreeSapBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitDie()](/api/Global/Misc/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BigTreeSapBuf()

```csharp
public BigTreeSapBuf()
```

## Fields

### _explodeDamage

```csharp
private const float _explodeDamage = 30
```
#INC


#### Field Value

**Type:** System.Single

### _explosionTimer

```csharp
private Timer _explosionTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _range

```csharp
private float _range
```
#INC


#### Field Value

**Type:** System.Single

### _remainExplodeTime

```csharp
private float _remainExplodeTime
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### Explode()

```csharp
private void Explode()
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

### MakeExplodeEffect(WorkerModel, float)

```csharp
public void MakeExplodeEffect(WorkerModel target, float size)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `size` | `System.Single` |  |

### OnDestroy()

```csharp
public override void OnDestroy()
```
#INC


### OnStageRelease()

```csharp
public override void OnStageRelease()
```
#INC


### PrepareExplode()

```csharp
private void PrepareExplode()
```
#INC

