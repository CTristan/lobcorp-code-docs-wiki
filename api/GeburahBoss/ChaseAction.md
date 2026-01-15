---
uid: GeburahBoss.ChaseAction
canonical_path: /api/GeburahBoss/ChaseAction
---

# Class ChaseAction

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChaseAction : GeburahAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahAction](/api/GeburahBoss/GeburahAction) → ChaseAction

## Inherited Members
[geburah](/api/GeburahBoss/GeburahAction#geburah), [_interrupt](/api/GeburahBoss/GeburahAction#interrupt), [actionState](/api/GeburahBoss/GeburahAction#actionstate), [SetInterruptAction(GeburahAction)](/api/GeburahBoss/GeburahAction#setinterruptaction-geburahaction), [EndAction()](/api/GeburahBoss/GeburahAction#endaction), [Interrupt()](/api/GeburahBoss/GeburahAction#interrupt), [CanTakeDamage()](/api/GeburahBoss/GeburahAction#cantakedamage), [Movable](/api/GeburahBoss/GeburahAction#movable), [Model](/api/GeburahBoss/GeburahAction#model), [Animator](/api/GeburahBoss/GeburahAction#animator), [AnimScript](/api/GeburahBoss/GeburahAction#animscript), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ChaseAction(GeburahCoreScript, float)

```csharp
public ChaseAction(GeburahCoreScript geburah, float approachDist)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |
| `approachDist` | `System.Single` |  |

### ChaseAction(GeburahCoreScript, MovableObjectNode, float, bool, bool)

```csharp
public ChaseAction(GeburahCoreScript geburah, MovableObjectNode movable, float approachDist, bool missEnabed = false, bool autoAttack = false)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |
| `movable` | `Global.MovableObjectNode` |  |
| `approachDist` | `System.Single` |  |
| `missEnabed` | `System.Boolean` |  |
| `autoAttack` | `System.Boolean` |  |

## Fields

### _arriveAttack

```csharp
private bool _arriveAttack
```

#### Field Value

**Type:** System.Boolean

### _cancelTimer

```csharp
private Timer _cancelTimer
```

#### Field Value

**Type:** Global.Timer

### _fail

```csharp
private bool _fail
```

#### Field Value

**Type:** System.Boolean

### _isArriveAttacking

```csharp
private bool _isArriveAttacking
```

#### Field Value

**Type:** System.Boolean

### _isAttacking

```csharp
private bool _isAttacking
```

#### Field Value

**Type:** System.Boolean

### _missWhenOtherPassage

```csharp
private bool _missWhenOtherPassage
```

#### Field Value

**Type:** System.Boolean

### approachDist

```csharp
private float approachDist
```

#### Field Value

**Type:** System.Single

### autoAttack

```csharp
private bool autoAttack
```

#### Field Value

**Type:** System.Boolean

### buf

```csharp
private GeburahChaseBuf buf
```

#### Field Value

**Type:** Global.GeburahChaseBuf

### currentDamageTargets

```csharp
private List<UnitModel> currentDamageTargets
```

#### Field Value

**Type:** System.Collections.Generic.List{UnitModel}

### movementBuf

```csharp
private MovementBuf movementBuf
```

#### Field Value

**Type:** GeburahBoss.MovementBuf

### speedFactor

```csharp
private float speedFactor
```

#### Field Value

**Type:** System.Single

### target

```csharp
private MovableObjectNode target
```

#### Field Value

**Type:** Global.MovableObjectNode

### targetAgent

```csharp
private AgentModel targetAgent
```

#### Field Value

**Type:** Global.AgentModel

### targetOldNode

```csharp
private MapNode targetOldNode
```

#### Field Value

**Type:** Global.MapNode

### tracking

```csharp
private bool tracking
```

#### Field Value

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

### OnArriveAttack()

```csharp
public void OnArriveAttack()
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
public void OnGiveDamage()
```

### OnStart()

```csharp
public override void OnStart()
```

### ParamInit()

```csharp
public override void ParamInit()
```
