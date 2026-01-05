# Class EightColumn

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EightColumn : BinahAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [BinahAction](/api/BinahBoss-BinahAction) → EightColumn

## Inherited Members
[binah](/api/BinahBoss-BinahAction#binah), [actionState](/api/BinahBoss-BinahAction#actionstate), [SetInterruptAction(BinahAction)](/api/BinahBoss-BinahAction#setinterruptaction-binahaction), [OnInterrupt()](/api/BinahBoss-BinahAction#oninterrupt), [EndAction()](/api/BinahBoss-BinahAction#endaction), [Interrupt()](/api/BinahBoss-BinahAction#interrupt), [CanTakeDamage()](/api/BinahBoss-BinahAction#cantakedamage), [Movable](/api/BinahBoss-BinahAction#movable), [Model](/api/BinahBoss-BinahAction#model), [AnimScript](/api/BinahBoss-BinahAction#animscript), [Animator](/api/BinahBoss-BinahAction#animator), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### EightColumn(BinahCoreScript)

```csharp
public EightColumn(BinahCoreScript binah)
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

### OnCancel()

```csharp
public void OnCancel()
```

### OnEnd()

```csharp
public override void OnEnd()
```

### OnExecute()

```csharp
public override void OnExecute()
```

### OnGiveDamage()

```csharp
public override void OnGiveDamage()
```

### OnShoot()

```csharp
public void OnShoot()
```

### OnStart()

```csharp
public override void OnStart()
```

### ParamInit()

```csharp
public override void ParamInit()
```
