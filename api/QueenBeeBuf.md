# Class QueenBeeBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class QueenBeeBuf : UnitBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/UnitBuf) → QueenBeeBuf

## Inherited Members
[type](/api/UnitBuf#type), [remainTime](/api/UnitBuf#remaintime), [model](/api/UnitBuf#model), [effectSrc](/api/UnitBuf#effectsrc), [duplicateType](/api/UnitBuf#duplicatetype), [OnDestroy()](/api/UnitBuf#ondestroy), [OnUnitPanic()](/api/UnitBuf#onunitpanic), [OnStageRelease()](/api/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### QueenBeeBuf(QueenBee, bool)

```csharp
public QueenBeeBuf(QueenBee queen, bool isDirect)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `queen` | `Global.QueenBee` |  |
| `isDirect` | `System.Boolean` |  |

## Fields

### buzzSrc

```csharp
public const string buzzSrc = "creature/QueenBee/QueenBee_Infect_01"
```

#### Field Value

**Type:** System.String

### effectTime

```csharp
public const float effectTime = 1
```

#### Field Value

**Type:** System.Single

### src

```csharp
public const string src = "Effect/Creature/QueenBee/QueenBeeGenEffect"
```

#### Field Value

**Type:** System.String

## Methods

### AttachEffect(Transform)

```csharp
public void AttachEffect(Transform head)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `head` | `UnityEngine.Transform` |  |

### Destroy()

```csharp
public override void Destroy()
```

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

### MovementScale()

```csharp
public override float MovementScale()
```

#### Returns

**Type:** System.Single

### OnUnitDie()

```csharp
public override void OnUnitDie()
```
