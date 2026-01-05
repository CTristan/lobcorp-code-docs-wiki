# Class ChaseAction

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChaseAction : GeburahAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahAction](/api/GeburahBoss-GeburahAction) → ChaseAction

## Inherited Members
[geburah](/api/GeburahBoss-GeburahAction#geburah), [actionState](/api/GeburahBoss-GeburahAction#actionstate), [SetInterruptAction(GeburahAction)](/api/GeburahBoss-GeburahAction#setinterruptaction-geburahaction), [EndAction()](/api/GeburahBoss-GeburahAction#endaction), [Interrupt()](/api/GeburahBoss-GeburahAction#interrupt), [CanTakeDamage()](/api/GeburahBoss-GeburahAction#cantakedamage), [Movable](/api/GeburahBoss-GeburahAction#movable), [Model](/api/GeburahBoss-GeburahAction#model), [Animator](/api/GeburahBoss-GeburahAction#animator), [AnimScript](/api/GeburahBoss-GeburahAction#animscript), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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
