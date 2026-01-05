# Class DangoAttackAction

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DangoAttackAction : GeburahAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahAction](/api/GeburahBoss-GeburahAction) → DangoAttackAction

## Inherited Members
[geburah](/api/GeburahBoss-GeburahAction#geburah), [actionState](/api/GeburahBoss-GeburahAction#actionstate), [SetInterruptAction(GeburahAction)](/api/GeburahBoss-GeburahAction#setinterruptaction-geburahaction), [OnStart()](/api/GeburahBoss-GeburahAction#onstart), [OnExecute()](/api/GeburahBoss-GeburahAction#onexecute), [EndAction()](/api/GeburahBoss-GeburahAction#endaction), [Interrupt()](/api/GeburahBoss-GeburahAction#interrupt), [Movable](/api/GeburahBoss-GeburahAction#movable), [Model](/api/GeburahBoss-GeburahAction#model), [Animator](/api/GeburahBoss-GeburahAction#animator), [AnimScript](/api/GeburahBoss-GeburahAction#animscript), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### DangoAttackAction(GeburahCoreScript, bool)

```csharp
public DangoAttackAction(GeburahCoreScript geburah, bool isPhaseShift)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |
| `isPhaseShift` | `System.Boolean` |  |

## Fields

### _b_damage

```csharp
public static DamageInfo _b_damage
```

#### Field Value

**Type:** Global.DamageInfo

### _p_damage

```csharp
public static DamageInfo _p_damage
```

#### Field Value

**Type:** Global.DamageInfo

## Methods

### AddStunBuf()

```csharp
public void AddStunBuf()
```

### CanTakeDamage()

```csharp
public override bool CanTakeDamage()
```

#### Returns

**Type:** System.Boolean

### ClearStunBuf()

```csharp
public void ClearStunBuf()
```

### DangoFirstDamage()

```csharp
public void DangoFirstDamage()
```

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

### OnEventCalled(int)

```csharp
public void OnEventCalled(int i)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### ParamInit()

```csharp
public override void ParamInit()
```
