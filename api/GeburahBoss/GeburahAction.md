---
uid: GeburahBoss.GeburahAction
canonical_path: /api/GeburahBoss/GeburahAction
---

# Class GeburahAction

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GeburahAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GeburahAction

## Derived
[BloodyTreeThrow](/api/GeburahBoss/BloodyTreeThrow), [ChaseAction](/api/GeburahBoss/ChaseAction), [DacapoMimicriThrow](/api/GeburahBoss/DacapoMimicriThrow), [DacapoThrow](/api/GeburahBoss/DacapoThrow), [DangoAttackAction](/api/GeburahBoss/DangoAttackAction), [DefaultAttack](/api/GeburahBoss/DefaultAttack), [GeburahIdle](/api/GeburahBoss/GeburahIdle), [GreedyTelepeort](/api/GeburahBoss/GreedyTelepeort), [GreedyThrow](/api/GeburahBoss/GreedyThrow), [MoveNodeAction](/api/GeburahBoss/MoveNodeAction)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### GeburahAction(GeburahCoreScript)

```csharp
public GeburahAction(GeburahCoreScript geburah)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |

## Fields

### _interrupt

```csharp
private GeburahAction _interrupt
```

#### Field Value

**Type:** GeburahBoss.GeburahAction

### actionState

```csharp
public GeburahActionState actionState
```

#### Field Value

**Type:** GeburahBoss.GeburahActionState

### geburah

```csharp
public GeburahCoreScript geburah
```

#### Field Value

**Type:** Global.GeburahCoreScript

## Properties

### Animator

```csharp
public Animator Animator { get; }
```

#### Property Value

**Type:** UnityEngine.Animator

### AnimScript

```csharp
public GeburahCoreAnim AnimScript { get; }
```

#### Property Value

**Type:** Global.GeburahCoreAnim

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

### OnEnd()

```csharp
public virtual void OnEnd()
```

### OnExecute()

```csharp
public virtual void OnExecute()
```

### OnStart()

```csharp
public virtual void OnStart()
```

### ParamInit()

```csharp
public virtual void ParamInit()
```

### SetInterruptAction(GeburahAction)

```csharp
public virtual void SetInterruptAction(GeburahAction action)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `GeburahBoss.GeburahAction` |  |
