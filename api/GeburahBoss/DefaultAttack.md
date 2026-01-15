---
uid: GeburahBoss.DefaultAttack
canonical_path: /api/GeburahBoss/DefaultAttack
---

# Class DefaultAttack

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DefaultAttack : GeburahAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahAction](/api/GeburahBoss/GeburahAction) → DefaultAttack

## Inherited Members
[geburah](/api/GeburahBoss/GeburahAction#geburah), [_interrupt](/api/GeburahBoss/GeburahAction#interrupt), [actionState](/api/GeburahBoss/GeburahAction#actionstate), [SetInterruptAction(GeburahAction)](/api/GeburahBoss/GeburahAction#setinterruptaction-geburahaction), [EndAction()](/api/GeburahBoss/GeburahAction#endaction), [Interrupt()](/api/GeburahBoss/GeburahAction#interrupt), [CanTakeDamage()](/api/GeburahBoss/GeburahAction#cantakedamage), [Movable](/api/GeburahBoss/GeburahAction#movable), [Model](/api/GeburahBoss/GeburahAction#model), [Animator](/api/GeburahBoss/GeburahAction#animator), [AnimScript](/api/GeburahBoss/GeburahAction#animscript), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DefaultAttack(GeburahCoreScript, float, float, int)

```csharp
public DefaultAttack(GeburahCoreScript geburah, float front, float rear, int attackTypeMax = 3)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |
| `front` | `System.Single` |  |
| `rear` | `System.Single` |  |
| `attackTypeMax` | `System.Int32` |  |

### DefaultAttack(GeburahCoreScript, float, float, List<AttackProb>)

```csharp
public DefaultAttack(GeburahCoreScript geburah, float front, float rear, List<DefaultAttack.AttackProb> list)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |
| `front` | `System.Single` |  |
| `rear` | `System.Single` |  |
| `list` | `System.Collections.Generic.List{GeburahBoss.DefaultAttack.AttackProb}` |  |

## Fields

### _attackDist_front

```csharp
private float _attackDist_front
```

#### Field Value

**Type:** System.Single

### _attackDist_rear

```csharp
private float _attackDist_rear
```

#### Field Value

**Type:** System.Single

### _hasStructure

```csharp
private bool _hasStructure
```

#### Field Value

**Type:** System.Boolean

### _isAttacking

```csharp
private bool _isAttacking
```

#### Field Value

**Type:** System.Boolean

### _p1_dummy

```csharp
private static DefenseInfo _p1_dummy
```

#### Field Value

**Type:** Global.DefenseInfo

### _p2_dummy

```csharp
private static DefenseInfo _p2_dummy
```

#### Field Value

**Type:** Global.DefenseInfo

### attackType

```csharp
private int attackType
```

#### Field Value

**Type:** System.Int32

### damageType

```csharp
private DamageType damageType
```

#### Field Value

**Type:** GeburahBoss.DamageType

### list

```csharp
private List<DefaultAttack.AttackProb> list
```

#### Field Value

**Type:** System.Collections.Generic.List{GeburahBoss.DefaultAttack.AttackProb}

### maxAttackType

```csharp
private int maxAttackType
```

#### Field Value

**Type:** System.Int32

### maxProb

```csharp
private float maxProb
```

#### Field Value

**Type:** System.Single

## Properties

### IsAttacking

```csharp
public bool IsAttacking { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### OnAnimEventCalled(int)

```csharp
public void OnAnimEventCalled(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnAttackEnd()

```csharp
public void OnAttackEnd()
```

### OnDamage()

```csharp
public void OnDamage()
```

### OnEnd()

```csharp
public override void OnEnd()
```

### OnExecute()

```csharp
public override void OnExecute()
```

### OnStart()

```csharp
public override void OnStart()
```

### ParamInit()

```csharp
public override void ParamInit()
```

### SetAttackTypeMax(int)

```csharp
public void SetAttackTypeMax(int max)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `max` | `System.Int32` |  |
