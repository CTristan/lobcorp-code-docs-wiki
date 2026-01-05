# Class BinahAction

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BinahAction

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### BinahAction(BinahCoreScript)

```csharp
public BinahAction(BinahCoreScript binah)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |

## Fields

### actionState

```csharp
public BinahActionState actionState
```

#### Field Value

**Type:** BinahBoss.BinahActionState

### binah

```csharp
public BinahCoreScript binah
```

#### Field Value

**Type:** Global.BinahCoreScript

## Properties

### Animator

```csharp
public Animator Animator { get; }
```

#### Property Value

**Type:** UnityEngine.Animator

### AnimScript

```csharp
public BinahCoreAnim AnimScript { get; }
```

#### Property Value

**Type:** Global.BinahCoreAnim

### Model

```csharp
public CreatureModel Model { get; }
```

#### Property Value

**Type:** Global.CreatureModel

### Movable

```csharp
public MovableObjectNode Movable { get; }
```

#### Property Value

**Type:** Global.MovableObjectNode

## Methods

### CanTakeDamage()

```csharp
public virtual bool CanTakeDamage()
```

#### Returns

**Type:** System.Boolean

### EndAction()

```csharp
public virtual void EndAction()
```

### Interrupt()

```csharp
public virtual void Interrupt()
```

### OnAnimEventCalled(int)

```csharp
public virtual void OnAnimEventCalled(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnAttackEnd()

```csharp
public virtual void OnAttackEnd()
```

### OnEnd()

```csharp
public virtual void OnEnd()
```

### OnExecute()

```csharp
public virtual void OnExecute()
```

### OnGiveDamage()

```csharp
public virtual void OnGiveDamage()
```

### OnInterrupt()

```csharp
public virtual void OnInterrupt()
```

### OnStart()

```csharp
public virtual void OnStart()
```

### ParamInit()

```csharp
public virtual void ParamInit()
```

### SetInterruptAction(BinahAction)

```csharp
public virtual void SetInterruptAction(BinahAction action)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `BinahBoss.BinahAction` |  |
