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

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → LittleWitchBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitDie()](/api/Global/Misc/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### LittleWitchBuf(LittleWitch)

```csharp
public LittleWitchBuf(LittleWitch witch)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `witch` | `Global.LittleWitch` |  |

## Fields

### _activateTimer

```csharp
private Timer _activateTimer
```

#### Field Value

**Type:** Global.Timer

### _max

```csharp
private const float _max = 10
```

#### Field Value

**Type:** System.Single

### _min

```csharp
private const float _min = 5
```

#### Field Value

**Type:** System.Single

### _witch

```csharp
private LittleWitch _witch
```

#### Field Value

**Type:** Global.LittleWitch

### animParam

```csharp
private const string animParam = "Speed"
```

#### Field Value

**Type:** System.String

### bodyPosFix

```csharp
private static Vector2 bodyPosFix
```

#### Field Value

**Type:** UnityEngine.Vector2

### brokenSprite

```csharp
private Sprite brokenSprite
```

#### Field Value

**Type:** UnityEngine.Sprite

### BrokenSrc

```csharp
private const string BrokenSrc = "Sprites/CreatureSprite/LittleWitch/HeartBroken"
```

#### Field Value

**Type:** System.String

### Effect

```csharp
private GameObject Effect
```

#### Field Value

**Type:** UnityEngine.GameObject

### EffectAnimator

```csharp
private Animator EffectAnimator
```

#### Field Value

**Type:** UnityEngine.Animator

### EffectSrc

```csharp
private const string EffectSrc = "Effect/Creature/LittleWitch/LittleWitch_BufEffect"
```

#### Field Value

**Type:** System.String

### multiplier

```csharp
private const float multiplier = 2
```

#### Field Value

**Type:** System.Single

### NormalSrc

```csharp
private const string NormalSrc = "Sprites/CreatureSprite/LittleWitch/HeartNormal"
```

#### Field Value

**Type:** System.String

### originalSprite

```csharp
private Sprite originalSprite
```

#### Field Value

**Type:** UnityEngine.Sprite

### startFreq

```csharp
private const float startFreq = 0.5
```

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

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### Init(UnitModel)

```csharp
public override void Init(UnitModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

### OnDestroy()

```csharp
public override void OnDestroy()
```

### ResetHeart()

```csharp
private void ResetHeart()
```
