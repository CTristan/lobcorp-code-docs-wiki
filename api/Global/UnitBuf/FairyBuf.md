---
uid: Global.FairyBuf
canonical_path: /api/Global/UnitBuf/FairyBuf
---

# Class FairyBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FairyBuf : UnitBuf
```

Effect given by [Fairy Festival](/api/Global/Misc/Fairy) which heals over time, and kills instantly if assigned to work another abnormality.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → FairyBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FairyBuf(Fairy)

```csharp
public FairyBuf(Fairy script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.Fairy` |  |

## Fields

### _bufRemainTime

```csharp
private const float _bufRemainTime = 8
```
#INC


#### Field Value

**Type:** System.Single

### _healRatio

```csharp
private const float _healRatio = 0.1
```
#INC


#### Field Value

**Type:** System.Single

### _healTickTime

```csharp
private const float _healTickTime = 1
```
#INC


#### Field Value

**Type:** System.Single

### _sound_dead

```csharp
private const string _sound_dead = "creature/Fairy/Fairy_Dead"
```
#INC


#### Field Value

**Type:** System.String

### agent

```csharp
private AgentModel agent
```
#INC


#### Field Value

**Type:** Global.AgentModel

### effect

```csharp
private GameObject effect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### healTickTimer

```csharp
private Timer healTickTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### script

```csharp
private Fairy script
```
#INC


#### Field Value

**Type:** Global.Fairy

## Methods

### Destroy()

```csharp
public override void Destroy()
```
#INC


### DestroyEffect()

```csharp
private void DestroyEffect()
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

### OnAnimCalled(int)

```csharp
private void OnAnimCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnUnitDie()

```csharp
public override void OnUnitDie()
```
#INC

