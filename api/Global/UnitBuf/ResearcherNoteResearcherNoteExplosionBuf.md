---
uid: Global.ResearcherNote.ResearcherNoteExplosionBuf
canonical_path: /api/Global/UnitBuf/ResearcherNoteResearcherNoteExplosionBuf
---

# Class ResearcherNote.ResearcherNoteExplosionBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResearcherNote.ResearcherNoteExplosionBuf : UnitBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → ResearcherNote.ResearcherNoteExplosionBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [FixedUpdate()](/api/Global/Misc/UnitBuf#fixedupdate), [Destroy()](/api/Global/Misc/UnitBuf#destroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ResearcherNoteExplosionBuf(ResearcherNote, bool)

```csharp
public ResearcherNoteExplosionBuf(ResearcherNote note, bool splash)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `note` | `Global.ResearcherNote` |  |
| `splash` | `System.Boolean` |  |

## Fields

### _explodeDamage

```csharp
private const float _explodeDamage = 30
```

#### Field Value

**Type:** System.Single

### _note

```csharp
private ResearcherNote _note
```

#### Field Value

**Type:** Global.ResearcherNote

### _range

```csharp
private const float _range = 10
```

#### Field Value

**Type:** System.Single

### _splash

```csharp
private bool _splash
```

#### Field Value

**Type:** System.Boolean

### effectLength

```csharp
private const float effectLength = 5.5
```

#### Field Value

**Type:** System.Single

### explosionBigSound

```csharp
private const string explosionBigSound = "creature/match_girl/explosion_large_01"
```

#### Field Value

**Type:** System.String

### explosionSound

```csharp
private const string explosionSound = "creature/deathangel/Lucifer_yaduafinish_poof"
```

#### Field Value

**Type:** System.String

### recoil

```csharp
private const int recoil = 3
```

#### Field Value

**Type:** System.Int32

### sefiraEffect

```csharp
private const string sefiraEffect = "Effect/Creature/MatchGirl/MatchGirl_Sefira"
```

#### Field Value

**Type:** System.String

## Methods

### Explode(AgentModel, bool)

```csharp
private void Explode(AgentModel actor, bool splash)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |
| `splash` | `System.Boolean` |  |

### Init(UnitModel)

```csharp
public override void Init(UnitModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

### MakeExplodeEffect(WorkerModel, float)

```csharp
public void MakeExplodeEffect(WorkerModel target, float size)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `size` | `System.Single` |  |

### OnDestroy()

```csharp
public override void OnDestroy()
```

### OnUnitDie()

```csharp
public override void OnUnitDie()
```
