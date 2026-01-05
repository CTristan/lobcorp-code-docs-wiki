# Class BinahIdle

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahIdle : BinahAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [BinahAction](/api/BinahBoss-BinahAction) → BinahIdle

## Inherited Members
[binah](/api/BinahBoss-BinahAction#binah), [actionState](/api/BinahBoss-BinahAction#actionstate), [SetInterruptAction(BinahAction)](/api/BinahBoss-BinahAction#setinterruptaction-binahaction), [ParamInit()](/api/BinahBoss-BinahAction#paraminit), [OnInterrupt()](/api/BinahBoss-BinahAction#oninterrupt), [EndAction()](/api/BinahBoss-BinahAction#endaction), [Interrupt()](/api/BinahBoss-BinahAction#interrupt), [CanTakeDamage()](/api/BinahBoss-BinahAction#cantakedamage), [OnGiveDamage()](/api/BinahBoss-BinahAction#ongivedamage), [OnAttackEnd()](/api/BinahBoss-BinahAction#onattackend), [OnAnimEventCalled(int)](/api/BinahBoss-BinahAction#onanimeventcalled-int), [Movable](/api/BinahBoss-BinahAction#movable), [Model](/api/BinahBoss-BinahAction#model), [AnimScript](/api/BinahBoss-BinahAction#animscript), [Animator](/api/BinahBoss-BinahAction#animator), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BinahIdle(BinahCoreScript, float, bool)

```csharp
public BinahIdle(BinahCoreScript binah, float time, bool groggy = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |
| `time` | `System.Single` |  |
| `groggy` | `System.Boolean` |  |

## Methods

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
