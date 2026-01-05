# Class UnitStatBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnitStatBuf : UnitBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/UnitBuf) → UnitStatBuf

## Inherited Members
[type](/api/UnitBuf#type), [remainTime](/api/UnitBuf#remaintime), [model](/api/UnitBuf#model), [effectSrc](/api/UnitBuf#effectsrc), [duplicateType](/api/UnitBuf#duplicatetype), [Init(UnitModel)](/api/UnitBuf#init-unitmodel), [FixedUpdate()](/api/UnitBuf#fixedupdate), [Destroy()](/api/UnitBuf#destroy), [OnDestroy()](/api/UnitBuf#ondestroy), [MovementScale()](/api/UnitBuf#movementscale), [OnUnitDie()](/api/UnitBuf#onunitdie), [OnUnitPanic()](/api/UnitBuf#onunitpanic), [OnStageRelease()](/api/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### UnitStatBuf(float)

```csharp
public UnitStatBuf(float time)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

### UnitStatBuf(float, UnitBufType)

```csharp
public UnitStatBuf(float time, UnitBufType type)
```

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

#### Field Value

**Type:** System.Single

### cubeSpeed

```csharp
public int cubeSpeed
```

#### Field Value

**Type:** System.Int32

### maxHp

```csharp
public int maxHp
```

#### Field Value

**Type:** System.Int32

### maxMental

```csharp
public int maxMental
```

#### Field Value

**Type:** System.Int32

### movementSpeed

```csharp
public float movementSpeed
```

#### Field Value

**Type:** System.Single

### primaryStat

```csharp
public WorkerPrimaryStatBonus primaryStat
```

#### Field Value

**Type:** Global.WorkerPrimaryStatBonus

### workProb

```csharp
public int workProb
```

#### Field Value

**Type:** System.Int32
