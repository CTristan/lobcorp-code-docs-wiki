---
uid: BinahBoss.BinahIdle
canonical_path: /api/BinahBoss/BinahIdle
---

# Class BinahIdle

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahIdle : BinahAction
```

[An Arbiter](/api/Global/Script/BinahCoreScript)'s idle action.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [BinahAction](/api/BinahBoss/BinahAction) → BinahIdle

## Inherited Members
[binah](/api/BinahBoss/BinahAction#binah), [actionState](/api/BinahBoss/BinahAction#actionstate), [_interrupt](/api/BinahBoss/BinahAction#interrupt), [SetInterruptAction(BinahAction)](/api/BinahBoss/BinahAction#setinterruptaction-binahaction), [ParamInit()](/api/BinahBoss/BinahAction#paraminit), [OnInterrupt()](/api/BinahBoss/BinahAction#oninterrupt), [EndAction()](/api/BinahBoss/BinahAction#endaction), [Interrupt()](/api/BinahBoss/BinahAction#interrupt), [CanTakeDamage()](/api/BinahBoss/BinahAction#cantakedamage), [OnGiveDamage()](/api/BinahBoss/BinahAction#ongivedamage), [OnAttackEnd()](/api/BinahBoss/BinahAction#onattackend), [OnAnimEventCalled(int)](/api/BinahBoss/BinahAction#onanimeventcalled-int), [Movable](/api/BinahBoss/BinahAction#movable), [Model](/api/BinahBoss/BinahAction#model), [AnimScript](/api/BinahBoss/BinahAction#animscript), [Animator](/api/BinahBoss/BinahAction#animator), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BinahIdle(BinahCoreScript, float, bool)

```csharp
public BinahIdle(BinahCoreScript binah, float time, bool groggy = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |
| `time` | `System.Single` |  |
| `groggy` | `System.Boolean` |  |

## Fields

### _dutrationTimer

```csharp
private Timer _dutrationTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### isGroggy

```csharp
private bool isGroggy
```
#INC


#### Field Value

**Type:** System.Boolean

### time

```csharp
private float time
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### OnEnd()

```csharp
public override void OnEnd()
```
#INC


### OnExecute()

```csharp
public override void OnExecute()
```
#INC


### OnStart()

```csharp
public override void OnStart()
```
#INC
#code-generated

