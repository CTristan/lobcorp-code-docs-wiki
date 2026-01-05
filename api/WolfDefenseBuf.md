# Class WolfDefenseBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WolfDefenseBuf : UnitBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/UnitBuf) → WolfDefenseBuf

## Inherited Members
[type](/api/UnitBuf#type), [remainTime](/api/UnitBuf#remaintime), [model](/api/UnitBuf#model), [effectSrc](/api/UnitBuf#effectsrc), [duplicateType](/api/UnitBuf#duplicatetype), [Init(UnitModel)](/api/UnitBuf#init-unitmodel), [FixedUpdate()](/api/UnitBuf#fixedupdate), [Destroy()](/api/UnitBuf#destroy), [OnDestroy()](/api/UnitBuf#ondestroy), [MovementScale()](/api/UnitBuf#movementscale), [OnUnitDie()](/api/UnitBuf#onunitdie), [OnUnitPanic()](/api/UnitBuf#onunitpanic), [OnStageRelease()](/api/UnitBuf#onstagerelease), [GetDamageFactor()](/api/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### WolfDefenseBuf(float)

```csharp
public WolfDefenseBuf(float defenseFactor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `defenseFactor` | `System.Single` |  |

### WolfDefenseBuf(float, float)

```csharp
public WolfDefenseBuf(float defenseFactor, float lifeTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `defenseFactor` | `System.Single` |  |
| `lifeTime` | `System.Single` |  |

## Methods

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

### SetFactor(float)

```csharp
public void SetFactor(float factor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factor` | `System.Single` |  |
