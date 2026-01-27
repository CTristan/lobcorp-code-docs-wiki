---
uid: BinahBoss.BlackThron
canonical_path: /api/BinahBoss/BlackThron
---

# Class BlackThron

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BlackThron : BinahAction
```
[An Arbiter](/api/Global/Script/BinahCoreScript)'s black fog attack


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [BinahAction](/api/BinahBoss/BinahAction) → BlackThron

## Inherited Members
[binah](/api/BinahBoss/BinahAction#binah), [actionState](/api/BinahBoss/BinahAction#actionstate), [_interrupt](/api/BinahBoss/BinahAction#interrupt), [SetInterruptAction(BinahAction)](/api/BinahBoss/BinahAction#setinterruptaction-binahaction), [OnExecute()](/api/BinahBoss/BinahAction#onexecute), [OnInterrupt()](/api/BinahBoss/BinahAction#oninterrupt), [EndAction()](/api/BinahBoss/BinahAction#endaction), [Interrupt()](/api/BinahBoss/BinahAction#interrupt), [CanTakeDamage()](/api/BinahBoss/BinahAction#cantakedamage), [Movable](/api/BinahBoss/BinahAction#movable), [Model](/api/BinahBoss/BinahAction#model), [AnimScript](/api/BinahBoss/BinahAction#animscript), [Animator](/api/BinahBoss/BinahAction#animator), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BlackThron(BinahCoreScript, int, bool)

```csharp
public BlackThron(BinahCoreScript binah, int maxCount, bool invokeOverload = true)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `binah` | `Global.BinahCoreScript` |  |
| `maxCount` | `System.Int32` |  |
| `invokeOverload` | `System.Boolean` |  |

## Fields

### blackThorn

```csharp
private List<BinahProjectile> blackThorn
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{BinahBoss.BinahProjectile}

### invokeOverload

```csharp
private bool invokeOverload
```
#INC


#### Field Value

**Type:** System.Boolean

### maxCount

```csharp
private int maxCount
```
#INC


#### Field Value

**Type:** System.Int32

## Methods

### GenThorn()

```csharp
private void GenThorn()
```
#INC


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

