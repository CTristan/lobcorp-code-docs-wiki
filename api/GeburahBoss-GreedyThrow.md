# Class GreedyThrow

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GreedyThrow : GeburahAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahAction](/api/GeburahBoss-GeburahAction) → GreedyThrow

## Inherited Members
[geburah](/api/GeburahBoss-GeburahAction#geburah), [actionState](/api/GeburahBoss-GeburahAction#actionstate), [SetInterruptAction(GeburahAction)](/api/GeburahBoss-GeburahAction#setinterruptaction-geburahaction), [EndAction()](/api/GeburahBoss-GeburahAction#endaction), [Interrupt()](/api/GeburahBoss-GeburahAction#interrupt), [CanTakeDamage()](/api/GeburahBoss-GeburahAction#cantakedamage), [Movable](/api/GeburahBoss-GeburahAction#movable), [Model](/api/GeburahBoss-GeburahAction#model), [Animator](/api/GeburahBoss-GeburahAction#animator), [AnimScript](/api/GeburahBoss-GeburahAction#animscript), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### GreedyThrow(GeburahCoreScript, int)

```csharp
public GreedyThrow(GeburahCoreScript geburah, int passageCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |
| `passageCount` | `System.Int32` |  |

## Fields

### speedValue

```csharp
public const float speedValue = 32
```

#### Field Value

**Type:** System.Single

## Methods

### MakePortal(Vector3)

```csharp
public Animator MakePortal(Vector3 pos)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |

#### Returns

**Type:** UnityEngine.Animator

### OnAttackEnd()

```csharp
public void OnAttackEnd()
```

### OnEnd()

```csharp
public override void OnEnd()
```

### OnEventCalled(int)

```csharp
public void OnEventCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

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
