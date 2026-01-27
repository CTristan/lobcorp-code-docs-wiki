---
uid: Global.SlimePawnBuf
canonical_path: /api/Global/UnitBuf/SlimePawnBuf
---

# Class SlimePawnBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SlimePawnBuf : UnitBuf
```

Buff given to [Melting Love](/api/Global/Misc/SlimeGirl)'s infected employees (for her favorite, see [SlimeLoverBuf](/api/Global/UnitBuf/SlimeLoverBuf)).

Applies an effect to the worker's face #verify which changes after 80% of the transform timer (see below).

Recovers 10 SP every 5 seconds #verify .

After some time randomly between 100 and 120 seconds, applies the [SlimeTransformBuf](/api/Global/UnitBuf/SlimeTransformBuf) to this worker.

If another worker is within 1 unit, randomly infects them at a 25% chance with this buff and plays an effect.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → SlimePawnBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SlimePawnBuf(WorkerModel, SlimeGirl)

```csharp
public SlimePawnBuf(WorkerModel worker, SlimeGirl script)
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
private const float _mentalHealMax = 10
```
#INC


#### Field Value

**Type:** System.Single

### _mentalHealMin

```csharp
private const float _mentalHealMin = 10
```
#INC


#### Field Value

**Type:** System.Single

### _transformTimeMax

```csharp
private const float _transformTimeMax = 120
```
#INC


#### Field Value

**Type:** System.Single

### _transformTimeMin

```csharp
private const float _transformTimeMin = 100
```
#INC


#### Field Value

**Type:** System.Single

### CHANGE_FACE_RATE

```csharp
private const float CHANGE_FACE_RATE = 0.8
```
#INC


#### Field Value

**Type:** System.Single

### checkDic

```csharp
private Dictionary<WorkerModel, SlimePawnBuf.InfestCheckInfo> checkDic
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{WorkerModel,SlimePawnBuf.InfestCheckInfo}

### effect

```csharp
private GameObject effect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### EFFECT_POS_AGENT

```csharp
private static Vector3 EFFECT_POS_AGENT
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### EFFECT_POS_OFFICER

```csharp
private static Vector3 EFFECT_POS_OFFICER
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### EFFECT_SPRITE_SRC

```csharp
private const string EFFECT_SPRITE_SRC = "Sprites/CreatureSprite/SlimeGirl/SlimePawnBuf"
```
#INC


#### Field Value

**Type:** System.String

### FACE_COLOR

```csharp
private const string FACE_COLOR = "#CE6767FF"
```
#INC


#### Field Value

**Type:** System.String

### faceChanged

```csharp
private bool faceChanged
```
#INC


#### Field Value

**Type:** System.Boolean

### INFEST_DIST

```csharp
private const float INFEST_DIST = 1
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

### MENTAL_HEAL_TIME

```csharp
private const float MENTAL_HEAL_TIME = 5
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

### transformTimer

```csharp
private Timer transformTimer
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

### MentalHealValue

```csharp
private static float MentalHealValue { get; }
```

#### Property Value

**Type:** System.Single

### TransformTime

```csharp
private static float TransformTime { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### ChangeFace()

```csharp
private void ChangeFace()
```
#INC


### CheckInfest(WorkerModel)

```csharp
private bool CheckInfest(WorkerModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### CheckNearWorker()

```csharp
public void CheckNearWorker()
```
#INC


### FixedUpdate()

```csharp
public override void FixedUpdate()
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

### MentalHeal()

```csharp
private void MentalHeal()
```
#INC


### OnUnitDie()

```csharp
public override void OnUnitDie()
```
#INC


### Transform()

```csharp
public void Transform()
```
#INC

