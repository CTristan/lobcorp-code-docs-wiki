---
uid: BinahBoss.BinahOverloadActivation
canonical_path: /api/BinahBoss/BinahOverloadActivation
---

# Class BinahOverloadActivation

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahOverloadActivation : BinahAction
```
[An Arbiter](/api/Global/Script/BinahCoreScript)'s current list of overloads she wants to do


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [BinahAction](/api/BinahBoss/BinahAction) → BinahOverloadActivation

## Inherited Members
[binah](/api/BinahBoss/BinahAction#binah), [actionState](/api/BinahBoss/BinahAction#actionstate), [_interrupt](/api/BinahBoss/BinahAction#interrupt), [SetInterruptAction(BinahAction)](/api/BinahBoss/BinahAction#setinterruptaction-binahaction), [ParamInit()](/api/BinahBoss/BinahAction#paraminit), [OnExecute()](/api/BinahBoss/BinahAction#onexecute), [OnEnd()](/api/BinahBoss/BinahAction#onend), [OnInterrupt()](/api/BinahBoss/BinahAction#oninterrupt), [EndAction()](/api/BinahBoss/BinahAction#endaction), [Interrupt()](/api/BinahBoss/BinahAction#interrupt), [CanTakeDamage()](/api/BinahBoss/BinahAction#cantakedamage), [OnGiveDamage()](/api/BinahBoss/BinahAction#ongivedamage), [OnAttackEnd()](/api/BinahBoss/BinahAction#onattackend), [OnAnimEventCalled(int)](/api/BinahBoss/BinahAction#onanimeventcalled-int), [Movable](/api/BinahBoss/BinahAction#movable), [Model](/api/BinahBoss/BinahAction#model), [AnimScript](/api/BinahBoss/BinahAction#animscript), [Animator](/api/BinahBoss/BinahAction#animator), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BinahOverloadActivation(BinahCoreScript, params OverloadType[])

```csharp
public BinahOverloadActivation(BinahCoreScript binah, params OverloadType[] types)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |
| `types` | `Global.OverloadType[]` |  |

## Fields

### overloads

```csharp
private List<BinahOverload> overloads
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{BinahBoss.BinahOverload}

## Methods

### OnStart()

```csharp
public override void OnStart()
```
#INC
#code-generated

