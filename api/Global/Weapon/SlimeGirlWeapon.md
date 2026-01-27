---
uid: Global.SlimeGirlWeapon
canonical_path: /api/Global/Weapon/SlimeGirlWeapon
---

# Class SlimeGirlWeapon

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SlimeGirlWeapon : EquipmentScriptBase
```

Script for [Melting Love](/api/Global/Misc/SlimeGirl)'s EGO Weapon: Adoration.

Instead of giving damage normally, shoots a projectile ([SlimeGirlWeaponProjectile](/api/Global/Misc/SlimeGirlWeaponProjectile) prefab) and plays a sound.

Checks if the projectile should hit[^1], and if it does, calculates damage[^2], creates the damage particle effect, and gives the target a slowing DOT debuff ([SlimeGirlWeaponDebuf](/api/Global/UnitBuf/SlimeGirlWeaponDebuf)). Also loads an effect prefab (SlimeGirlProjectileHitEffect) at the target.

[^1]: #inc verify that this code is NOT how other weapons check this

[^2]: Does not use WeaponModel's OnGiveDamage, and does not use the meta info in the equipment xml. Hard-coded to do base 22-44 black damage. #INC -- check if this has any other consequences


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/Misc/EquipmentScriptBase) → SlimeGirlWeapon

## Inherited Members
[_model](/api/Global/Misc/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/Misc/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/Misc/EquipmentScriptBase#setmodel-equipmentmodel), [OnEquip(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onequip-unitmodel), [OnRelease()](/api/Global/Misc/EquipmentScriptBase#onrelease), [OnStageStart()](/api/Global/Misc/EquipmentScriptBase#onstagestart), [OnStageRelease()](/api/Global/Misc/EquipmentScriptBase#onstagerelease), [OnPrepareWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#oncancelweapon-unitmodel), [OnAttackStart(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onattackstart-unitmodel-unitmodel), [OnAttackEnd(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onattackend-unitmodel-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/Misc/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/Misc/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/Misc/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdamage-unitmodel), [OnFixedUpdate()](/api/Global/Misc/EquipmentScriptBase#onfixedupdate), [GetBonus(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/Misc/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/Misc/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SlimeGirlWeapon()

```csharp
public SlimeGirlWeapon()
```

## Fields

### _dmgMax

```csharp
private const int _dmgMax = 44
```
#INC


#### Field Value

**Type:** System.Int32

### _dmgMin

```csharp
private const int _dmgMin = 22
```
#INC


#### Field Value

**Type:** System.Int32

### _dmgType

```csharp
private const RwbpType _dmgType = B
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _effectPos

```csharp
private Vector3 _effectPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### _projectileHitSrc

```csharp
private const string _projectileHitSrc = "Effect/Creature/SlimeGirl/SlimeGirlProjectileHitEffect"
```
#INC


#### Field Value

**Type:** System.String

### _projectileSrc

```csharp
private const string _projectileSrc = "Effect/Agent/SlimeGirlWeaponProjectile"
```
#INC


#### Field Value

**Type:** System.String

### slowRatio

```csharp
public const float slowRatio = 0.3
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### Dmg

```csharp
private static DamageInfo Dmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

## Methods

### CheckHit(UnitModel)

```csharp
public bool CheckHit(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### GiveDamage(UnitModel)

```csharp
private void GiveDamage(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### MakeEffect(Vector3, float)

```csharp
private GameObject MakeEffect(Vector3 pos, float scale)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** UnityEngine.GameObject

### OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)

```csharp
public override bool OnGiveDamage(UnitModel actor, UnitModel target, ref DamageInfo dmg)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean

### ShootProjectile()

```csharp
private void ShootProjectile()
```
#INC

