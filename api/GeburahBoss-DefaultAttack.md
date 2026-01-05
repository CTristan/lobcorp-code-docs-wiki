# Class DefaultAttack

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DefaultAttack : GeburahAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahAction](/api/GeburahBoss-GeburahAction) → DefaultAttack

## Inherited Members
[geburah](/api/GeburahBoss-GeburahAction#geburah), [actionState](/api/GeburahBoss-GeburahAction#actionstate), [SetInterruptAction(GeburahAction)](/api/GeburahBoss-GeburahAction#setinterruptaction-geburahaction), [EndAction()](/api/GeburahBoss-GeburahAction#endaction), [Interrupt()](/api/GeburahBoss-GeburahAction#interrupt), [CanTakeDamage()](/api/GeburahBoss-GeburahAction#cantakedamage), [Movable](/api/GeburahBoss-GeburahAction#movable), [Model](/api/GeburahBoss-GeburahAction#model), [Animator](/api/GeburahBoss-GeburahAction#animator), [AnimScript](/api/GeburahBoss-GeburahAction#animscript), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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
