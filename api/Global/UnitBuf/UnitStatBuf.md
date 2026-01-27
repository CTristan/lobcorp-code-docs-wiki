---
uid: Global.UnitStatBuf
canonical_path: /api/Global/UnitBuf/UnitStatBuf
---

# Class UnitStatBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnitStatBuf : UnitBuf
```

Buff which increases stats.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → UnitStatBuf

## Derived
[BinahJusticeDebuf](/api/BinahBoss/BinahJusticeDebuf), [DesireHeart.DesireHeartEquipBuf](/api/Global/UnitStatBuf/DesireHeartDesireHeartEquipBuf), [FireBirdDebuf](/api/Global/UnitStatBuf/FireBirdDebuf), [HealthBracelet.HealthBraceletEquipBuf](/api/Global/UnitStatBuf/HealthBraceletHealthBraceletEquipBuf), [HodBossBuf](/api/Global/UnitStatBuf/HodBossBuf), [JusticeReceiver.JusticeReceiverEquipBuf](/api/Global/UnitStatBuf/JusticeReceiverJusticeReceiverEquipBuf), [OtherWorldPortrait.OtherWorldPortraitBuf](/api/Global/UnitStatBuf/OtherWorldPortraitOtherWorldPortraitBuf), [PianoBuf](/api/Global/UnitStatBuf/PianoBuf), [ProphecyOfSkin.ProphecyOfSkinBuf](/api/Global/UnitStatBuf/ProphecyOfSkinProphecyOfSkinBuf), [ResearcherNote.ResearcherNoteEquipBuf](/api/Global/UnitStatBuf/ResearcherNoteResearcherNoteEquipBuf), [SingingMachineGiftBuf](/api/Global/UnitStatBuf/SingingMachineGiftBuf), [YangEquipBuf](/api/Global/UnitStatBuf/YangEquipBuf), [YouMustHappy.YouMustHappyBuf](/api/Global/UnitStatBuf/YouMustHappyYouMustHappyBuf)

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Init(UnitModel)](/api/Global/Misc/UnitBuf#init-unitmodel), [FixedUpdate()](/api/Global/Misc/UnitBuf#fixedupdate), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitDie()](/api/Global/Misc/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UnitStatBuf(float)

```csharp
public UnitStatBuf(float time)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

### UnitStatBuf(float, UnitBufType)

```csharp
public UnitStatBuf(float time, UnitBufType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |
| `type` | `Global.UnitBufType` |  |

## Fields

### attackSpeed

```csharp
public float attackSpeed
```
#INC


#### Field Value

**Type:** System.Single

### cubeSpeed

```csharp
public int cubeSpeed
```
#INC


#### Field Value

**Type:** System.Int32

### maxHp

```csharp
public int maxHp
```
#INC


#### Field Value

**Type:** System.Int32

### maxMental

```csharp
public int maxMental
```
#INC


#### Field Value

**Type:** System.Int32

### movementSpeed

```csharp
public float movementSpeed
```
#INC


#### Field Value

**Type:** System.Single

### primaryStat

```csharp
public WorkerPrimaryStatBonus primaryStat
```
#INC


#### Field Value

**Type:** Global.WorkerPrimaryStatBonus

### workProb

```csharp
public int workProb
```
#INC


#### Field Value

**Type:** System.Int32
