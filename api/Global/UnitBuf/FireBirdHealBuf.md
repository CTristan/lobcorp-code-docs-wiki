---
uid: Global.FireBirdHealBuf
canonical_path: /api/Global/UnitBuf/FireBirdHealBuf
---

# Class FireBirdHealBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FireBirdHealBuf : UnitBuf
```

[The Firebird](/api/Global/IOBserver/FireBird)'s heal buff (for when its Qliphoth Counter is 1, or an agent has <20% of max HP at the end of work).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → FireBirdHealBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FireBirdHealBuf(FireBird)

```csharp
public FireBirdHealBuf(FireBird script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.FireBird` |  |

## Fields

### _healValueHpMax

```csharp
private const float _healValueHpMax = 5
```
#INC


#### Field Value

**Type:** System.Single

### _healValueHpMin

```csharp
private const float _healValueHpMin = 5
```
#INC


#### Field Value

**Type:** System.Single

### _healValueMpMax

```csharp
private const float _healValueMpMax = 5
```
#INC


#### Field Value

**Type:** System.Single

### _healValueMpMin

```csharp
private const float _healValueMpMin = 5
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

### defaultRemain

```csharp
private const float defaultRemain = 60
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

### healTickTime

```csharp
private const float healTickTime = 5
```
#INC


#### Field Value

**Type:** System.Single

### healTickTimer

```csharp
private Timer healTickTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### script

```csharp
private FireBird script
```
#INC


#### Field Value

**Type:** Global.FireBird

## Properties

### HealValueHp

```csharp
private static float HealValueHp { get; }
```

#### Property Value

**Type:** System.Single

### HealValueMp

```csharp
private static float HealValueMp { get; }
```

#### Property Value

**Type:** System.Single

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


### Heal()

```csharp
private void Heal()
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

### OnDestroy()

```csharp
public override void OnDestroy()
```
#INC


### OnUnitDie()

```csharp
public override void OnUnitDie()
```
#INC

