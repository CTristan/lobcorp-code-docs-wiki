---
uid: BinahBoss.BladeWaveThrow
canonical_path: /api/BinahBoss/BladeWaveThrow
---

# Class BladeWaveThrow

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BladeWaveThrow : BinahAction
```
[An Arbiter](/api/Global/Script/BinahCoreScript)'s melee action (ouch!)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [BinahAction](/api/BinahBoss/BinahAction) → BladeWaveThrow

## Inherited Members
[binah](/api/BinahBoss/BinahAction#binah), [actionState](/api/BinahBoss/BinahAction#actionstate), [_interrupt](/api/BinahBoss/BinahAction#interrupt), [SetInterruptAction(BinahAction)](/api/BinahBoss/BinahAction#setinterruptaction-binahaction), [OnExecute()](/api/BinahBoss/BinahAction#onexecute), [OnInterrupt()](/api/BinahBoss/BinahAction#oninterrupt), [EndAction()](/api/BinahBoss/BinahAction#endaction), [Interrupt()](/api/BinahBoss/BinahAction#interrupt), [CanTakeDamage()](/api/BinahBoss/BinahAction#cantakedamage), [Movable](/api/BinahBoss/BinahAction#movable), [Model](/api/BinahBoss/BinahAction#model), [AnimScript](/api/BinahBoss/BinahAction#animscript), [Animator](/api/BinahBoss/BinahAction#animator), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BladeWaveThrow(BinahCoreScript)

```csharp
public BladeWaveThrow(BinahCoreScript binah)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |

## Fields

### DamageInfo

```csharp
private DamageInfo DamageInfo
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### type

```csharp
private RwbpType type
```
#INC


#### Field Value

**Type:** Global.RwbpType

## Methods

### OnAnimEventCalled(int)

```csharp
public override void OnAnimEventCalled(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnAttackEnd()

```csharp
public override void OnAttackEnd()
```
#INC


### OnEnd()

```csharp
public override void OnEnd()
```
#INC


### OnGiveDamage()

```csharp
public override void OnGiveDamage()
```
#INC


### OnStart()

```csharp
public override void OnStart()
```
#INC


### ParamInit()

```csharp
public override void ParamInit()
```
#INC
#code-generated

