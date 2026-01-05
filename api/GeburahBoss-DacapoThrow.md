# Class DacapoThrow

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DacapoThrow : GeburahAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahAction](/api/GeburahBoss-GeburahAction) → DacapoThrow

## Inherited Members
[geburah](/api/GeburahBoss-GeburahAction#geburah), [actionState](/api/GeburahBoss-GeburahAction#actionstate), [SetInterruptAction(GeburahAction)](/api/GeburahBoss-GeburahAction#setinterruptaction-geburahaction), [OnExecute()](/api/GeburahBoss-GeburahAction#onexecute), [EndAction()](/api/GeburahBoss-GeburahAction#endaction), [Interrupt()](/api/GeburahBoss-GeburahAction#interrupt), [CanTakeDamage()](/api/GeburahBoss-GeburahAction#cantakedamage), [Movable](/api/GeburahBoss-GeburahAction#movable), [Model](/api/GeburahBoss-GeburahAction#model), [Animator](/api/GeburahBoss-GeburahAction#animator), [AnimScript](/api/GeburahBoss-GeburahAction#animscript), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DacapoThrow(GeburahCoreScript)

```csharp
public DacapoThrow(GeburahCoreScript geburah)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |

## Fields

### _damage

```csharp
public static DamageInfo _damage
```

#### Field Value

**Type:** Global.DamageInfo

## Methods

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

### OnStart()

```csharp
public override void OnStart()
```

### OnThrowObject()

```csharp
public void OnThrowObject()
```

### ParamInit()

```csharp
public override void ParamInit()
```
