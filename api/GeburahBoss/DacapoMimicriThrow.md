---
uid: GeburahBoss.DacapoMimicriThrow
canonical_path: /api/GeburahBoss/DacapoMimicriThrow
---

# Class DacapoMimicriThrow

**Namespace:** [GeburahBoss](/api/GeburahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DacapoMimicriThrow : GeburahAction
```

Action for when [The Red Mist](/api/Global/Script/GeburahCoreScript) throws [Da Capo](/api/Global/Misc/SilentOrchestra) and [Mimicry](/api/Global/Weapon/NothingWeapon) at the start of phase 3.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [GeburahAction](/api/GeburahBoss/GeburahAction) → DacapoMimicriThrow

## Inherited Members
[geburah](/api/GeburahBoss/GeburahAction#geburah), [_interrupt](/api/GeburahBoss/GeburahAction#interrupt), [actionState](/api/GeburahBoss/GeburahAction#actionstate), [SetInterruptAction(GeburahAction)](/api/GeburahBoss/GeburahAction#setinterruptaction-geburahaction), [OnStart()](/api/GeburahBoss/GeburahAction#onstart), [OnExecute()](/api/GeburahBoss/GeburahAction#onexecute), [EndAction()](/api/GeburahBoss/GeburahAction#endaction), [Interrupt()](/api/GeburahBoss/GeburahAction#interrupt), [Movable](/api/GeburahBoss/GeburahAction#movable), [Model](/api/GeburahBoss/GeburahAction#model), [Animator](/api/GeburahBoss/GeburahAction#animator), [AnimScript](/api/GeburahBoss/GeburahAction#animscript), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DacapoMimicriThrow(GeburahCoreScript)

```csharp
public DacapoMimicriThrow(GeburahCoreScript geburah)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `geburah` | `Global.GeburahCoreScript` |  |

## Fields

### _r_damage

```csharp
public static DamageInfo _r_damage
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### _w_damage

```csharp
public static DamageInfo _w_damage
```
#INC


#### Field Value

**Type:** Global.DamageInfo

## Methods

### CanTakeDamage()

```csharp
public override bool CanTakeDamage()
```
#INC


#### Returns

**Type:** System.Boolean

### MakeProjectile(ProjectileType, Transform, UnitDirection, DamageInfo, Vector2, Vector3)

```csharp
private void MakeProjectile(ProjectileType type, Transform tr, UnitDirection direction, DamageInfo damage, Vector2 size, Vector3 rotation)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `GeburahBoss.ProjectileType` |  |
| `tr` | `UnityEngine.Transform` |  |
| `direction` | `Global.UnitDirection` |  |
| `damage` | `Global.DamageInfo` |  |
| `size` | `UnityEngine.Vector2` |  |
| `rotation` | `UnityEngine.Vector3` |  |

### MakeWeaponAppear()

```csharp
private void MakeWeaponAppear()
```
#INC


### OnAnimEventCalled(int)

```csharp
public void OnAnimEventCalled(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnEnd()

```csharp
public override void OnEnd()
```
#INC


### OnThrow()

```csharp
public void OnThrow()
```
#INC


### ParamInit()

```csharp
public override void ParamInit()
```
#INC
#code-generated

