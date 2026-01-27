---
uid: GeburahBoss.DacapoThrow
canonical_path: /api/GeburahBoss/DacapoThrow
---

# Class DacapoThrow

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DacapoThrow : GeburahAction
```

Action for [The Red Mist](/api/Global/Script/GeburahCoreScript) to throw [Da Capo](/api/Global/Misc/SilentOrchestra).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahAction](/api/GeburahBoss/GeburahAction) → DacapoThrow

## Inherited Members
[geburah](/api/GeburahBoss/GeburahAction#geburah), [_interrupt](/api/GeburahBoss/GeburahAction#interrupt), [actionState](/api/GeburahBoss/GeburahAction#actionstate), [SetInterruptAction(GeburahAction)](/api/GeburahBoss/GeburahAction#setinterruptaction-geburahaction), [OnExecute()](/api/GeburahBoss/GeburahAction#onexecute), [EndAction()](/api/GeburahBoss/GeburahAction#endaction), [Interrupt()](/api/GeburahBoss/GeburahAction#interrupt), [CanTakeDamage()](/api/GeburahBoss/GeburahAction#cantakedamage), [Movable](/api/GeburahBoss/GeburahAction#movable), [Model](/api/GeburahBoss/GeburahAction#model), [Animator](/api/GeburahBoss/GeburahAction#animator), [AnimScript](/api/GeburahBoss/GeburahAction#animscript), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DacapoThrow(GeburahCoreScript)

```csharp
public DacapoThrow(GeburahCoreScript geburah)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |

## Fields

### _damage

```csharp
public static DamageInfo _damage
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### targetSefira

```csharp
private Sefira targetSefira
```
#INC


#### Field Value

**Type:** Global.Sefira

## Methods

### MoveToDest()

```csharp
private void MoveToDest()
```
#INC


### OnAttackEnd()

```csharp
public void OnAttackEnd()
```
#INC


### OnEnd()

```csharp
public override void OnEnd()
```
#INC


### OnEventCalled(int)

```csharp
public void OnEventCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnStart()

```csharp
public override void OnStart()
```
#INC


### OnThrowObject()

```csharp
public void OnThrowObject()
```
#INC


### ParamInit()

```csharp
public override void ParamInit()
```
#INC
#code-generated

