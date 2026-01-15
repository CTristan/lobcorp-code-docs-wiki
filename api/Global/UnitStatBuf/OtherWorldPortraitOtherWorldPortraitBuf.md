---
uid: Global.OtherWorldPortrait.OtherWorldPortraitBuf
canonical_path: /api/Global/UnitStatBuf/OtherWorldPortraitOtherWorldPortraitBuf
---

# Class OtherWorldPortrait.OtherWorldPortraitBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OtherWorldPortrait.OtherWorldPortraitBuf : UnitStatBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → [UnitStatBuf](/api/Global/UnitBuf/UnitStatBuf) → OtherWorldPortrait.OtherWorldPortraitBuf

## Inherited Members
[primaryStat](/api/Global/UnitBuf/UnitStatBuf#primarystat), [maxHp](/api/Global/UnitBuf/UnitStatBuf#maxhp), [maxMental](/api/Global/UnitBuf/UnitStatBuf#maxmental), [cubeSpeed](/api/Global/UnitBuf/UnitStatBuf#cubespeed), [workProb](/api/Global/UnitBuf/UnitStatBuf#workprob), [movementSpeed](/api/Global/UnitBuf/UnitStatBuf#movementspeed), [attackSpeed](/api/Global/UnitBuf/UnitStatBuf#attackspeed), [type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### OtherWorldPortraitBuf(AgentModel, OtherWorldPortrait)

```csharp
public OtherWorldPortraitBuf(AgentModel am, OtherWorldPortrait c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `am` | `Global.AgentModel` |  |
| `c` | `Global.OtherWorldPortrait` |  |

## Fields

### _creature

```csharp
public OtherWorldPortrait _creature
```

#### Field Value

**Type:** Global.OtherWorldPortrait

### _victim

```csharp
public AgentModel _victim
```

#### Field Value

**Type:** Global.AgentModel

### _victimBufData

```csharp
public BufStateUI.BufData _victimBufData
```

#### Field Value

**Type:** Global.BufStateUI.BufData

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

### OnTakeDamage(UnitModel, DamageInfo)

```csharp
public override float OnTakeDamage(UnitModel attacker, DamageInfo damageInfo)
```

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

### SetAnotherVictim(AgentModel)

```csharp
public void SetAnotherVictim(AgentModel am)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `am` | `Global.AgentModel` |  |
