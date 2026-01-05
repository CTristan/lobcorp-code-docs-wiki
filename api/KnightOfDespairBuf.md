# Class KnightOfDespairBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KnightOfDespairBuf : UnitBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/UnitBuf) → KnightOfDespairBuf

## Inherited Members
[type](/api/UnitBuf#type), [remainTime](/api/UnitBuf#remaintime), [model](/api/UnitBuf#model), [effectSrc](/api/UnitBuf#effectsrc), [duplicateType](/api/UnitBuf#duplicatetype), [Destroy()](/api/UnitBuf#destroy), [OnDestroy()](/api/UnitBuf#ondestroy), [MovementScale()](/api/UnitBuf#movementscale), [GetDamageFactor()](/api/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### KnightOfDespairBuf(KnightOfDespair)

```csharp
public KnightOfDespairBuf(KnightOfDespair knight)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `knight` | `Global.KnightOfDespair` |  |

## Fields

### knight

```csharp
public KnightOfDespair knight
```

#### Field Value

**Type:** Global.KnightOfDespair

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

### OnStageRelease()

```csharp
public override void OnStageRelease()
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

### OnUnitPanic()

```csharp
public override void OnUnitPanic()
```
