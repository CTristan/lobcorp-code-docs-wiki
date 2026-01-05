# Class RedHoodBleedBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RedHoodBleedBuf : UnitBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/UnitBuf) → RedHoodBleedBuf

## Inherited Members
[type](/api/UnitBuf#type), [remainTime](/api/UnitBuf#remaintime), [model](/api/UnitBuf#model), [effectSrc](/api/UnitBuf#effectsrc), [duplicateType](/api/UnitBuf#duplicatetype), [Destroy()](/api/UnitBuf#destroy), [MovementScale()](/api/UnitBuf#movementscale), [OnUnitPanic()](/api/UnitBuf#onunitpanic), [OnStageRelease()](/api/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### RedHoodBleedBuf(RedHood)

```csharp
public RedHoodBleedBuf(RedHood redHood)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `redHood` | `Global.RedHood` |  |

## Fields

### _additionalSrc

```csharp
public const string _additionalSrc = "Effect/Creature/RedHood/Redhood_AdditionalDamage"
```

#### Field Value

**Type:** System.String

### _effectSrc

```csharp
public const string _effectSrc = "Effect/Creature/RedHood/Redhood_Bleed"
```

#### Field Value

**Type:** System.String

### CurrentStackCount

```csharp
public int CurrentStackCount
```

#### Field Value

**Type:** System.Int32

### effect

```csharp
public GameObject effect
```

#### Field Value

**Type:** UnityEngine.GameObject

### MaxStackCount

```csharp
public const int MaxStackCount = 3
```

#### Field Value

**Type:** System.Int32

### RedHood

```csharp
public RedHood RedHood
```

#### Field Value

**Type:** Global.RedHood

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

### OnRedHoodAttacked(bool, int)

```csharp
public void OnRedHoodAttacked(bool isRanged, int stackCount = 1)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isRanged` | `System.Boolean` |  |
| `stackCount` | `System.Int32` |  |

### OnSetCount()

```csharp
public void OnSetCount()
```

### OnUnitDie()

```csharp
public override void OnUnitDie()
```

### TakeAdditionalDamage()

```csharp
public void TakeAdditionalDamage()
```
