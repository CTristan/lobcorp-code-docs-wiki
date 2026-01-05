# Class UnitBuf

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnitBuf
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → UnitBuf

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### UnitBuf()

```csharp
public UnitBuf()
```

## Fields

### duplicateType

```csharp
public BufDuplicateType duplicateType
```

#### Field Value

**Type:** Global.BufDuplicateType

### effectSrc

```csharp
public string effectSrc
```

#### Field Value

**Type:** System.String

### model

```csharp
public UnitModel model
```

#### Field Value

**Type:** Global.UnitModel

### remainTime

```csharp
public float remainTime
```

#### Field Value

**Type:** System.Single

### type

```csharp
public UnitBufType type
```

#### Field Value

**Type:** Global.UnitBufType

## Methods

### Destroy()

```csharp
public virtual void Destroy()
```

### FixedUpdate()

```csharp
public virtual void FixedUpdate()
```

### GetDamageFactor()

```csharp
public virtual float GetDamageFactor()
```

#### Returns

**Type:** System.Single

### GetDamageFactor(UnitModel, DamageInfo)

```csharp
public virtual float GetDamageFactor(UnitModel target, DamageInfo info)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `info` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Single

### GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)

```csharp
public virtual float GetWorkProbSpecialBonus(UnitModel actor, SkillTypeInfo skill)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `skill` | `Global.SkillTypeInfo` |  |

#### Returns

**Type:** System.Single

### Init(UnitModel)

```csharp
public virtual void Init(UnitModel model)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

### MovementScale()

```csharp
public virtual float MovementScale()
```

#### Returns

**Type:** System.Single

### OnDestroy()

```csharp
public virtual void OnDestroy()
```

### OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)

```csharp
public virtual bool OnGiveDamage(UnitModel actor, UnitModel target, ref DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean

### OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)

```csharp
public virtual void OnGiveDamageAfter(UnitModel actor, UnitModel target, DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### OnStageRelease()

```csharp
public virtual void OnStageRelease()
```

### OnTakeDamage(UnitModel, DamageInfo)

```csharp
public virtual float OnTakeDamage(UnitModel attacker, DamageInfo damageInfo)
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
public virtual void OnUnitDie()
```

### OnUnitPanic()

```csharp
public virtual void OnUnitPanic()
```
