---
uid: BinahBoss.BinahJusticeDebuf
canonical_path: /api/BinahBoss/BinahJusticeDebuf
---

# Class BinahJusticeDebuf

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahJusticeDebuf : UnitStatBuf
```
Binah slowing debuf


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → [UnitStatBuf](/api/Global/UnitBuf/UnitStatBuf) → BinahJusticeDebuf

## Inherited Members
[primaryStat](/api/Global/UnitBuf/UnitStatBuf#primarystat), [maxHp](/api/Global/UnitBuf/UnitStatBuf#maxhp), [maxMental](/api/Global/UnitBuf/UnitStatBuf#maxmental), [cubeSpeed](/api/Global/UnitBuf/UnitStatBuf#cubespeed), [workProb](/api/Global/UnitBuf/UnitStatBuf#workprob), [movementSpeed](/api/Global/UnitBuf/UnitStatBuf#movementspeed), [attackSpeed](/api/Global/UnitBuf/UnitStatBuf#attackspeed), [type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BinahJusticeDebuf(float)

```csharp
public BinahJusticeDebuf(float time)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

## Fields

### _reduceVal

```csharp
private float _reduceVal
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

### attach

```csharp
private GameObject attach
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### lateInit

```csharp
private bool lateInit
```
#INC


#### Field Value

**Type:** System.Boolean

### P_min

```csharp
private const float P_min = 10
```
#INC


#### Field Value

**Type:** System.Single

### unitEffectSrc

```csharp
private const string unitEffectSrc = "Effect/SefiraBoss/BinahBoss/Effect/BinahAgentSlow"
```
#INC


#### Field Value

**Type:** System.String

## Properties

### P_buf

```csharp
private float P_buf { get; }
```

#### Property Value

**Type:** System.Single

## Methods

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

### LateInit()

```csharp
private void LateInit()
```
#INC


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


### SetReduceValue(float)

```csharp
public void SetReduceValue(float val)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |
