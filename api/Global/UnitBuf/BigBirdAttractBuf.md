---
uid: Global.BigBirdAttractBuf
canonical_path: /api/Global/UnitBuf/BigBirdAttractBuf
---

# Class BigBirdAttractBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BigBirdAttractBuf : UnitBuf
```

Attract effect for [Big Bird](/api/Global/Misc/BigBird) during breach. Three phases, take half damage in first and none in the second and third. Marks for instakill when Big Bird is reached.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → BigBirdAttractBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BigBirdAttractBuf(BigBird)

```csharp
public BigBirdAttractBuf(BigBird script)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.BigBird` |  |

## Fields

### _dmgRatio_First

```csharp
private const float _dmgRatio_First = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### _dmgRatio_Second

```csharp
private const float _dmgRatio_Second = 0
```
#INC


#### Field Value

**Type:** System.Single

### _dmgRatio_Third

```csharp
private const float _dmgRatio_Third = 0
```
#INC


#### Field Value

**Type:** System.Single

### _elapsedCondition2nd

```csharp
private const float _elapsedCondition2nd = 15
```
#INC


#### Field Value

**Type:** System.Single

### _elapsedCondition3rd

```csharp
private const float _elapsedCondition3rd = 40
```
#INC


#### Field Value

**Type:** System.Single

### _phase

```csharp
private BigBirdAttractBuf.Phase _phase
```

#### Field Value

**Type:** Global.BigBirdAttractBuf.Phase

### _remainTime

```csharp
private const float _remainTime = Infinity
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

### elapsedTime

```csharp
private float elapsedTime
```
#INC


#### Field Value

**Type:** System.Single

### script

```csharp
private BigBird script
```
#INC


#### Field Value

**Type:** Global.BigBird

### src

```csharp
private const string src = "Effect/Creature/BigBird/BigBirdAttractEffect_"
```
#INC


#### Field Value

**Type:** System.String

### worker

```csharp
private WorkerModel worker
```
#INC


#### Field Value

**Type:** Global.WorkerModel

## Properties

### phase

```csharp
public BigBirdAttractBuf.Phase phase { get; }
```

#### Property Value

**Type:** Global.BigBirdAttractBuf.Phase

## Methods

### AttachEffect(Phase)

```csharp
private GameObject AttachEffect(BigBirdAttractBuf.Phase p)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `Global.BigBirdAttractBuf.Phase` |  |

#### Returns

**Type:** UnityEngine.GameObject

### CheckAvailable()

```csharp
private bool CheckAvailable()
```
#INC


#### Returns

**Type:** System.Boolean

### FixedUpdate()

```csharp
public override void FixedUpdate()
```
#INC


### FixedUpdate_First()

```csharp
private void FixedUpdate_First()
```
#INC


### FixedUpdate_Second()

```csharp
private void FixedUpdate_Second()
```
#INC


### FixedUpdate_Third()

```csharp
private void FixedUpdate_Third()
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


### OnTakeDamage(UnitModel, DamageInfo)

```csharp
public override float OnTakeDamage(UnitModel attacker, DamageInfo damageInfo)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `damageInfo` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Single

### OnUnitDie()

```csharp
public override void OnUnitDie()
```
#INC


### RemoveEffect()

```csharp
private void RemoveEffect()
```
#INC

