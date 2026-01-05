# Class MovementBuf

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MovementBuf : UnitBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/UnitBuf) → MovementBuf

## Inherited Members
[type](/api/UnitBuf#type), [remainTime](/api/UnitBuf#remaintime), [model](/api/UnitBuf#model), [effectSrc](/api/UnitBuf#effectsrc), [duplicateType](/api/UnitBuf#duplicatetype), [Init(UnitModel)](/api/UnitBuf#init-unitmodel), [Destroy()](/api/UnitBuf#destroy), [OnDestroy()](/api/UnitBuf#ondestroy), [OnUnitDie()](/api/UnitBuf#onunitdie), [OnUnitPanic()](/api/UnitBuf#onunitpanic), [OnStageRelease()](/api/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### MovementBuf(float)

```csharp
public MovementBuf(float factor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factor` | `System.Single` |  |

### MovementBuf(float, float)

```csharp
public MovementBuf(float factor, float lifeTime)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `factor` | `System.Single` |  |
| `lifeTime` | `System.Single` |  |

## Methods

### FixedUpdate()

```csharp
public override void FixedUpdate()
```

### MovementScale()

```csharp
public override float MovementScale()
```

#### Returns

**Type:** System.Single
