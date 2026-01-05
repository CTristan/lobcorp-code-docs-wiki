# Class BinahJusticeDebuf

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahJusticeDebuf : UnitStatBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/UnitBuf) → [UnitStatBuf](/api/UnitStatBuf) → BinahJusticeDebuf

## Inherited Members
[primaryStat](/api/UnitStatBuf#primarystat), [maxHp](/api/UnitStatBuf#maxhp), [maxMental](/api/UnitStatBuf#maxmental), [cubeSpeed](/api/UnitStatBuf#cubespeed), [workProb](/api/UnitStatBuf#workprob), [movementSpeed](/api/UnitStatBuf#movementspeed), [attackSpeed](/api/UnitStatBuf#attackspeed), [type](/api/UnitBuf#type), [remainTime](/api/UnitBuf#remaintime), [model](/api/UnitBuf#model), [effectSrc](/api/UnitBuf#effectsrc), [duplicateType](/api/UnitBuf#duplicatetype), [Destroy()](/api/UnitBuf#destroy), [MovementScale()](/api/UnitBuf#movementscale), [OnUnitPanic()](/api/UnitBuf#onunitpanic), [OnStageRelease()](/api/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BinahJusticeDebuf(float)

```csharp
public BinahJusticeDebuf(float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

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

### SetReduceValue(float)

```csharp
public void SetReduceValue(float val)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |
