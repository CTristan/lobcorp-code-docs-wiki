---
uid: Global.SlimeProjectileDebuf
canonical_path: /api/Global/UnitBuf/SlimeProjectileDebuf
---

# Class SlimeProjectileDebuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SlimeProjectileDebuf : UnitBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → SlimeProjectileDebuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SlimeProjectileDebuf(WorkerModel, SlimeGirl)

```csharp
public SlimeProjectileDebuf(WorkerModel worker, SlimeGirl script)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |
| `script` | `Global.SlimeGirl` |  |

## Fields

### _dmgMax

```csharp
private const int _dmgMax = 3
```

#### Field Value

**Type:** System.Int32

### _dmgMin

```csharp
private const int _dmgMin = 2
```

#### Field Value

**Type:** System.Int32

### _dmgTickTime

```csharp
private const float _dmgTickTime = 2
```

#### Field Value

**Type:** System.Single

### _dmgType

```csharp
private const RwbpType _dmgType = B
```

#### Field Value

**Type:** Global.RwbpType

### _remainTime

```csharp
private const float _remainTime = 10
```

#### Field Value

**Type:** System.Single

### dmgTickTimer

```csharp
private Timer dmgTickTimer
```

#### Field Value

**Type:** Global.Timer

### effect

```csharp
private GameObject effect
```

#### Field Value

**Type:** UnityEngine.GameObject

### script

```csharp
private SlimeGirl script
```

#### Field Value

**Type:** Global.SlimeGirl

### worker

```csharp
private WorkerModel worker
```

#### Field Value

**Type:** Global.WorkerModel

## Properties

### Dmg

```csharp
private static DamageInfo Dmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

## Methods

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

### OnUnitDie()

```csharp
public override void OnUnitDie()
```
