# Class ColumnThrow

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ColumnThrow : BinahAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [BinahAction](/api/BinahBoss-BinahAction) → ColumnThrow

## Inherited Members
[binah](/api/BinahBoss-BinahAction#binah), [actionState](/api/BinahBoss-BinahAction#actionstate), [SetInterruptAction(BinahAction)](/api/BinahBoss-BinahAction#setinterruptaction-binahaction), [OnExecute()](/api/BinahBoss-BinahAction#onexecute), [EndAction()](/api/BinahBoss-BinahAction#endaction), [Interrupt()](/api/BinahBoss-BinahAction#interrupt), [CanTakeDamage()](/api/BinahBoss-BinahAction#cantakedamage), [Movable](/api/BinahBoss-BinahAction#movable), [Model](/api/BinahBoss-BinahAction#model), [AnimScript](/api/BinahBoss-BinahAction#animscript), [Animator](/api/BinahBoss-BinahAction#animator), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ColumnThrow(BinahCoreScript)

```csharp
public ColumnThrow(BinahCoreScript binah)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |

## Methods

### OnAnimEventCalled(int)

```csharp
public override void OnAnimEventCalled(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnAttackEnd()

```csharp
public override void OnAttackEnd()
```

### OnEnd()

```csharp
public override void OnEnd()
```

### OnGiveDamage()

```csharp
public override void OnGiveDamage()
```

### OnInterrupt()

```csharp
public override void OnInterrupt()
```

### OnStart()

```csharp
public override void OnStart()
```

### ParamInit()

```csharp
public override void ParamInit()
```
