---
uid: Global.LittleWitchBuf
canonical_path: /api/Global/UnitBuf/LittleWitchBuf
---

# Class LittleWitchBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class LittleWitchBuf : UnitBuf
```

Buff for [Laetitia](/api/Global/Misc/LittleWitch)'s gift; starts a timer when this agent is assigned to someone else, and turns them into [Little Witch's Friend](/api/Global/Misc/LittleWitchMonster) if it isn't canceled.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → LittleWitchBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitDie()](/api/Global/Misc/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### LittleWitchBuf(LittleWitch)

```csharp
public LittleWitchBuf(LittleWitch witch)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `witch` | `Global.LittleWitch` |  |

## Fields

### _activateTimer

```csharp
private Timer _activateTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _max

```csharp
private const float _max = 10
```
#INC


#### Field Value

**Type:** System.Single

### _min

```csharp
private const float _min = 5
```
#INC


#### Field Value

**Type:** System.Single

### _witch

```csharp
private LittleWitch _witch
```
#INC


#### Field Value

**Type:** Global.LittleWitch

### animParam

```csharp
private const string animParam = "Speed"
```
#INC


#### Field Value

**Type:** System.String

### bodyPosFix

```csharp
private static Vector2 bodyPosFix
```
#INC


#### Field Value

**Type:** UnityEngine.Vector2

### brokenSprite

```csharp
private Sprite brokenSprite
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### BrokenSrc

```csharp
private const string BrokenSrc = "Sprites/CreatureSprite/LittleWitch/HeartBroken"
```
#INC


#### Field Value

**Type:** System.String

### Effect

```csharp
private GameObject Effect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### EffectAnimator

```csharp
private Animator EffectAnimator
```
#INC


#### Field Value

**Type:** UnityEngine.Animator

### EffectSrc

```csharp
private const string EffectSrc = "Effect/Creature/LittleWitch/LittleWitch_BufEffect"
```
#INC


#### Field Value

**Type:** System.String

### multiplier

```csharp
private const float multiplier = 2
```
#INC


#### Field Value

**Type:** System.Single

### NormalSrc

```csharp
private const string NormalSrc = "Sprites/CreatureSprite/LittleWitch/HeartNormal"
```
#INC


#### Field Value

**Type:** System.String

### originalSprite

```csharp
private Sprite originalSprite
```
#INC


#### Field Value

**Type:** UnityEngine.Sprite

### startFreq

```csharp
private const float startFreq = 0.5
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### Agent

```csharp
private AgentModel Agent { get; }
```

#### Property Value

**Type:** Global.AgentModel

## Methods

### BreakHeart()

```csharp
private void BreakHeart()
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


### ResetHeart()

```csharp
private void ResetHeart()
```
#INC

