---
uid: Global.DeathAngelBetrayerBuf
canonical_path: /api/Global/UnitBuf/DeathAngelBetrayerBuf
---

# Class DeathAngelBetrayerBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeathAngelBetrayerBuf : UnitBuf
```

Effect for the special twelth apostle, The Heretic.
Gives immunity to all damage and allows a special work type with One Sin.
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → DeathAngelBetrayerBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitDie()](/api/Global/Misc/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DeathAngelBetrayerBuf(DeathAngel, ApostleData)

```csharp
public DeathAngelBetrayerBuf(DeathAngel angel, ApostleData data)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `angel` | `WhiteNightSpace.DeathAngel` |  |
| `data` | `WhiteNightSpace.ApostleData` |  |

## Fields

### agent

```csharp
private AgentModel agent
```
#INC


#### Field Value

**Type:** Global.AgentModel

### angel

```csharp
private DeathAngel angel
```
#INC


#### Field Value

**Type:** WhiteNightSpace.DeathAngel

### data

```csharp
private ApostleData data
```
#INC


#### Field Value

**Type:** WhiteNightSpace.ApostleData

### oneBadManyGood

```csharp
private CreatureModel oneBadManyGood
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### position

```csharp
private static Vector3 position
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### rotation

```csharp
private static Vector3 rotation
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### scale

```csharp
private static Vector3 scale
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

## Methods

### Confess()

```csharp
public void Confess()
```
#INC


### Destroy()

```csharp
public override void Destroy()
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

### OnDeathAngelSuppressed()

```csharp
public void OnDeathAngelSuppressed()
```
#INC


### OnStageRelease()

```csharp
public override void OnStageRelease()
```
#INC


### OnSuppress()

```csharp
public bool OnSuppress()
```
#INC


#### Returns

**Type:** System.Boolean

### OnWork()

```csharp
public bool OnWork()
```
#INC


#### Returns

**Type:** System.Boolean
