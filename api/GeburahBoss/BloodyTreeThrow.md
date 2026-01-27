---
uid: GeburahBoss.BloodyTreeThrow
canonical_path: /api/GeburahBoss/BloodyTreeThrow
---

# Class BloodyTreeThrow

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BloodyTreeThrow : GeburahAction
```

Action for [The Red Mist](/api/Global/Script/GeburahCoreScript)'s [Heaven](/api/Global/Weapon/BloodyTreeWeapon) throw attack (WATCH OUT)



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahAction](/api/GeburahBoss/GeburahAction) → BloodyTreeThrow

## Inherited Members
[geburah](/api/GeburahBoss/GeburahAction#geburah), [_interrupt](/api/GeburahBoss/GeburahAction#interrupt), [actionState](/api/GeburahBoss/GeburahAction#actionstate), [SetInterruptAction(GeburahAction)](/api/GeburahBoss/GeburahAction#setinterruptaction-geburahaction), [OnExecute()](/api/GeburahBoss/GeburahAction#onexecute), [EndAction()](/api/GeburahBoss/GeburahAction#endaction), [Interrupt()](/api/GeburahBoss/GeburahAction#interrupt), [Movable](/api/GeburahBoss/GeburahAction#movable), [Model](/api/GeburahBoss/GeburahAction#model), [Animator](/api/GeburahBoss/GeburahAction#animator), [AnimScript](/api/GeburahBoss/GeburahAction#animscript), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BloodyTreeThrow(GeburahCoreScript, bool)

```csharp
public BloodyTreeThrow(GeburahCoreScript geburah, bool isPhaseShift = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |
| `isPhaseShift` | `System.Boolean` |  |

## Fields

### _damage

```csharp
public static DamageInfo _damage
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### _isPhaseShift

```csharp
private bool _isPhaseShift
```
#INC


#### Field Value

**Type:** System.Boolean

### throwDirection

```csharp
private UnitDirection throwDirection
```
#INC


#### Field Value

**Type:** Global.UnitDirection

## Methods

### CanTakeDamage()

```csharp
public override bool CanTakeDamage()
```
#INC


#### Returns

**Type:** System.Boolean

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

