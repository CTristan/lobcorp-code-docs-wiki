---
uid: Global.RedHoodBleedBuf
canonical_path: /api/Global/UnitBuf/RedHoodBleedBuf
---

# Class RedHoodBleedBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RedHoodBleedBuf : UnitBuf
```

Bleeding debuff from [Little Red](/api/Global/IOBserver/RedHood)'s attacks.

Stacks up to three times, doing 5 red damage per stack every half second. Goes away when Red is suppressed.

Also creates a bleeding prefab effect/particle system which gets more intense with more stacks of bleed.
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → RedHoodBleedBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RedHoodBleedBuf(RedHood)

```csharp
public RedHoodBleedBuf(RedHood redHood)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `redHood` | `Global.RedHood` |  |

## Fields

### _additionalSrc

```csharp
public const string _additionalSrc = "Effect/Creature/RedHood/Redhood_AdditionalDamage"
```
#INC


#### Field Value

**Type:** System.String

### _DamageDelay

```csharp
private const float _DamageDelay = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### _delayTimer

```csharp
private Timer _delayTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _effectSrc

```csharp
public const string _effectSrc = "Effect/Creature/RedHood/Redhood_Bleed"
```
#INC


#### Field Value

**Type:** System.String

### _particle

```csharp
private ParticleSystem _particle
```
#INC


#### Field Value

**Type:** UnityEngine.ParticleSystem

### CurrentStackCount

```csharp
public int CurrentStackCount
```
#INC


#### Field Value

**Type:** System.Int32

### DamageFactor

```csharp
private float DamageFactor
```
#INC


#### Field Value

**Type:** System.Single

### effect

```csharp
public GameObject effect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### MaxStackCount

```csharp
public const int MaxStackCount = 3
```
#INC


#### Field Value

**Type:** System.Int32

### RedHood

```csharp
public RedHood RedHood
```
#INC


#### Field Value

**Type:** Global.RedHood

## Properties

### movable

```csharp
private MovableObjectNode movable { get; }
```

#### Property Value

**Type:** Global.MovableObjectNode

## Methods

### EffectUpdate()

```csharp
private void EffectUpdate()
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

### OnDestroy()

```csharp
public override void OnDestroy()
```
#INC


### OnRedHoodAttacked(bool, int)

```csharp
public void OnRedHoodAttacked(bool isRanged, int stackCount = 1)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isRanged` | `System.Boolean` |  |
| `stackCount` | `System.Int32` |  |

### OnSetCount()

```csharp
public void OnSetCount()
```
#INC


### OnUnitDie()

```csharp
public override void OnUnitDie()
```
#INC


### TakeAdditionalDamage()

```csharp
public void TakeAdditionalDamage()
```
#INC

