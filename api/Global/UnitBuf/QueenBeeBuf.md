---
uid: Global.QueenBeeBuf
canonical_path: /api/Global/UnitBuf/QueenBeeBuf
---

# Class QueenBeeBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class QueenBeeBuf : UnitBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → QueenBeeBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [OnUnitPanic()](/api/Global/Misc/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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

### buzz

```csharp
private SoundEffectPlayer buzz
```

#### Field Value

**Type:** Global.SoundEffectPlayer

### buzzSrc

```csharp
public const string buzzSrc = "creature/QueenBee/QueenBee_Infect_01"
```

#### Field Value

**Type:** System.String

### damageTickTimer

```csharp
private Timer damageTickTimer
```

#### Field Value

**Type:** Global.Timer

### effect

```csharp
private GameObject effect
```

#### Field Value

**Type:** UnityEngine.GameObject

### effectTime

```csharp
public const float effectTime = 1
```

#### Field Value

**Type:** System.Single

### effectTimer

```csharp
private AutoTimer effectTimer
```

#### Field Value

**Type:** Global.AutoTimer

### fixedY

```csharp
private const float fixedY = 2
```

#### Field Value

**Type:** System.Single

### isDirect

```csharp
private bool isDirect
```

#### Field Value

**Type:** System.Boolean

### queen

```csharp
private QueenBee queen
```

#### Field Value

**Type:** Global.QueenBee

### speedFactor

```csharp
private const float speedFactor = 0.5
```

#### Field Value

**Type:** System.Single

### src

```csharp
public const string src = "Effect/Creature/QueenBee/QueenBeeGenEffect"
```

#### Field Value

**Type:** System.String

### tickDamage

```csharp
private const float tickDamage = 8
```

#### Field Value

**Type:** System.Single

### tickDmg

```csharp
private DamageInfo tickDmg
```

#### Field Value

**Type:** Global.DamageInfo

### tickTime

```csharp
private const float tickTime = 2
```

#### Field Value

**Type:** System.Single

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

### MakeChild()

```csharp
private void MakeChild()
```

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
