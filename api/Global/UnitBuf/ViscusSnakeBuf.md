---
uid: Global.ViscusSnakeBuf
canonical_path: /api/Global/UnitBuf/ViscusSnakeBuf
---

# Class ViscusSnakeBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ViscusSnakeBuf : UnitBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → ViscusSnakeBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ViscusSnakeBuf(ViscusSnake)

```csharp
public ViscusSnakeBuf(ViscusSnake script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.ViscusSnake` |  |

## Fields

### _currentLevel

```csharp
private ViscusSnakeBuf.Level _currentLevel
```

#### Field Value

**Type:** Global.ViscusSnakeBuf.Level

### _effectSpriteSrc

```csharp
private const string _effectSpriteSrc = "Sprites/CreatureSprite/ViscusSnake/Viscusinfested"
```

#### Field Value

**Type:** System.String

### _first_max

```csharp
private const float _first_max = 40
```

#### Field Value

**Type:** System.Single

### _first_min

```csharp
private const float _first_min = 30
```

#### Field Value

**Type:** System.Single

### _gasEffectSrc

```csharp
private const string _gasEffectSrc = "Effect/Creature/ViscusSnake/ViscusGas"
```

#### Field Value

**Type:** System.String

### _increaseTimer

```csharp
private Timer _increaseTimer
```

#### Field Value

**Type:** Global.Timer

### _infectionEffectSrc

```csharp
private const string _infectionEffectSrc = "Effect/Creature/ViscusSnake/ViscusInfectionEffect"
```

#### Field Value

**Type:** System.String

### _infestedEffectTime

```csharp
private const float _infestedEffectTime = 5
```

#### Field Value

**Type:** System.Single

### _infestedEffectTimer

```csharp
private Timer _infestedEffectTimer
```

#### Field Value

**Type:** Global.Timer

### _movementDebufRate

```csharp
private const float _movementDebufRate = 0.5
```

#### Field Value

**Type:** System.Single

### _snake

```csharp
private ViscusSnake _snake
```

#### Field Value

**Type:** Global.ViscusSnake

### _zero_max

```csharp
private const float _zero_max = 10
```

#### Field Value

**Type:** System.Single

### _zero_min

```csharp
private const float _zero_min = 5
```

#### Field Value

**Type:** System.Single

### checkDic

```csharp
private Dictionary<WorkerModel, ViscusSnakeBuf.InfectionCheckInfo> checkDic
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{WorkerModel,ViscusSnakeBuf.InfectionCheckInfo}

### effectPositionFix

```csharp
private static Vector3 effectPositionFix
```

#### Field Value

**Type:** UnityEngine.Vector3

### gasEffect

```csharp
private GameObject gasEffect
```

#### Field Value

**Type:** UnityEngine.GameObject

### infectionDist

```csharp
private const float infectionDist = 1
```

#### Field Value

**Type:** System.Single

### renderer

```csharp
private SpriteRenderer renderer
```

#### Field Value

**Type:** UnityEngine.SpriteRenderer

## Properties

### DurationTIme

```csharp
private float DurationTIme { get; }
```

#### Property Value

**Type:** System.Single

### gasSystem

```csharp
private ParticleSystem gasSystem { get; }
```

#### Property Value

**Type:** UnityEngine.ParticleSystem

## Methods

### CheckGas()

```csharp
private void CheckGas()
```

### CheckInfection(WorkerModel)

```csharp
public bool CheckInfection(WorkerModel worker)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### CheckNearWorker()

```csharp
public void CheckNearWorker()
```

### EnableEffect(float)

```csharp
public void EnableEffect(float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### IncreaseLevel()

```csharp
private void IncreaseLevel()
```

### Init(UnitModel)

```csharp
public override void Init(UnitModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

### MakeInfectionEffect(WorkerModel)

```csharp
private void MakeInfectionEffect(WorkerModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### MakeViscusGasEffect()

```csharp
private void MakeViscusGasEffect()
```

### MovementScale()

```csharp
public override float MovementScale()
```

#### Returns

**Type:** System.Single

### OnUnitDie()

```csharp
public override void OnUnitDie()
```

### SetInfestedSpriteAlpha(float)

```csharp
public void SetInfestedSpriteAlpha(float a)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `System.Single` |  |

### Transition()

```csharp
private void Transition()
```
