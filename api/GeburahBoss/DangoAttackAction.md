---
uid: GeburahBoss.DangoAttackAction
canonical_path: /api/GeburahBoss/DangoAttackAction
---

# Class DangoAttackAction

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DangoAttackAction : GeburahAction
```

Action for [The Red Mist](/api/Global/Script/GeburahCoreScript) using [Smile](/api/Global/Weapon/DangoCreatureWeapon) attack (ouchie!!)

If 'isPhaseShift' is true (for the end of her third phase), destroys Smile and is scary.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahAction](/api/GeburahBoss/GeburahAction) → DangoAttackAction

## Inherited Members
[geburah](/api/GeburahBoss/GeburahAction#geburah), [_interrupt](/api/GeburahBoss/GeburahAction#interrupt), [actionState](/api/GeburahBoss/GeburahAction#actionstate), [SetInterruptAction(GeburahAction)](/api/GeburahBoss/GeburahAction#setinterruptaction-geburahaction), [OnStart()](/api/GeburahBoss/GeburahAction#onstart), [OnExecute()](/api/GeburahBoss/GeburahAction#onexecute), [EndAction()](/api/GeburahBoss/GeburahAction#endaction), [Interrupt()](/api/GeburahBoss/GeburahAction#interrupt), [Movable](/api/GeburahBoss/GeburahAction#movable), [Model](/api/GeburahBoss/GeburahAction#model), [Animator](/api/GeburahBoss/GeburahAction#animator), [AnimScript](/api/GeburahBoss/GeburahAction#animscript), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DangoAttackAction(GeburahCoreScript, bool)

```csharp
public DangoAttackAction(GeburahCoreScript geburah, bool isPhaseShift)
```
#INC


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
#INC


#### Field Value

**Type:** Global.DamageInfo

### _damageEffect

```csharp
private const string _damageEffect = "GeburahDangoDamage"
```
#INC


#### Field Value

**Type:** System.String

### _effect

```csharp
private GameObject _effect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### _isPhaseShift

```csharp
private bool _isPhaseShift
```
#INC


#### Field Value

**Type:** System.Boolean

### _p_damage

```csharp
public static DamageInfo _p_damage
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### _stunEffect

```csharp
private const string _stunEffect = "GeburahDangoStun"
```
#INC


#### Field Value

**Type:** System.String

### curDamage

```csharp
private DamageInfo curDamage
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### stunbuf

```csharp
private List<StunBuf> stunbuf
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{StunBuf}

## Methods

### AddStunBuf()

```csharp
public void AddStunBuf()
```
#INC


### CanTakeDamage()

```csharp
public override bool CanTakeDamage()
```
#INC


#### Returns

**Type:** System.Boolean

### ClearStunBuf()

```csharp
public void ClearStunBuf()
```
#INC


### DangoFirstDamage()

```csharp
public void DangoFirstDamage()
```
#INC


### GetTargets()

```csharp
private List<UnitModel> GetTargets()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### OnAttackEnd()

```csharp
public void OnAttackEnd()
```
#INC


### OnDamage()

```csharp
public void OnDamage()
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

### ParamInit()

```csharp
public override void ParamInit()
```
#INC
#code-generated

