---
uid: Global.YoungPrinceSporeBuf
canonical_path: /api/Global/UnitBuf/YoungPrinceSporeBuf
---

# Class YoungPrinceSporeBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class YoungPrinceSporeBuf : UnitBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Misc/UnitBuf) → YoungPrinceSporeBuf

## Inherited Members
[type](/api/Global/Misc/UnitBuf#type), [remainTime](/api/Global/Misc/UnitBuf#remaintime), [model](/api/Global/Misc/UnitBuf#model), [effectSrc](/api/Global/Misc/UnitBuf#effectsrc), [duplicateType](/api/Global/Misc/UnitBuf#duplicatetype), [OnDestroy()](/api/Global/Misc/UnitBuf#ondestroy), [MovementScale()](/api/Global/Misc/UnitBuf#movementscale), [OnStageRelease()](/api/Global/Misc/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Misc/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### YoungPrinceSporeBuf(YoungPrince)

```csharp
public YoungPrinceSporeBuf(YoungPrince yp)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `yp` | `Global.YoungPrince` |  |

## Fields

### _tickDamageMax

```csharp
private const int _tickDamageMax = 3
```

#### Field Value

**Type:** System.Int32

### _tickDamageMin

```csharp
private const int _tickDamageMin = 1
```

#### Field Value

**Type:** System.Int32

### damageTickTimer

```csharp
private Timer damageTickTimer
```

#### Field Value

**Type:** Global.Timer

### defaultRemain

```csharp
private const float defaultRemain = 10
```

#### Field Value

**Type:** System.Single

### prince

```csharp
private YoungPrince prince
```

#### Field Value

**Type:** Global.YoungPrince

### spore

```csharp
private GameObject spore
```

#### Field Value

**Type:** UnityEngine.GameObject

### tickTime

```csharp
private const float tickTime = 2
```

#### Field Value

**Type:** System.Single

### worker

```csharp
private WorkerModel worker
```

#### Field Value

**Type:** Global.WorkerModel

## Properties

### tickDamage

```csharp
private static int tickDamage { get; }
```

#### Property Value

**Type:** System.Int32

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

### OnUnitDie()

```csharp
public override void OnUnitDie()
```

### OnUnitPanic()

```csharp
public override void OnUnitPanic()
```

### RemoveSpore()

```csharp
public void RemoveSpore()
```
