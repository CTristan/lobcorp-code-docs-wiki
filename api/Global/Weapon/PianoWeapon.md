---
uid: Global.PianoWeapon
canonical_path: /api/Global/Weapon/PianoWeapon
---

# Class PianoWeapon

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PianoWeapon : EquipmentScriptBase
```

Script for [Il Pianto della Luna](/api/Global/Misc/Piano)'s EGO Weapon: Moonlight.

At a 15% chance, does a special attack which gives nearby employees a black [shield](/api/Global/UnitBuf/BarrierBuf) if it lands.

The shield has a damage value of 50 (same as bullet shields) and has a lifetime of 7.5 seconds (half that of bullet shields) #verify.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/Misc/EquipmentScriptBase) → PianoWeapon

## Inherited Members
[_model](/api/Global/Misc/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/Misc/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/Misc/EquipmentScriptBase#setmodel-equipmentmodel), [OnEquip(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onequip-unitmodel), [OnRelease()](/api/Global/Misc/EquipmentScriptBase#onrelease), [OnStageStart()](/api/Global/Misc/EquipmentScriptBase#onstagestart), [OnStageRelease()](/api/Global/Misc/EquipmentScriptBase#onstagerelease), [OnPrepareWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#oncancelweapon-unitmodel), [OnAttackEnd(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onattackend-unitmodel-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/Misc/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/Misc/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/Misc/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdamage-unitmodel), [OnFixedUpdate()](/api/Global/Misc/EquipmentScriptBase#onfixedupdate), [GetBonus(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/Misc/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/Misc/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PianoWeapon()

```csharp
public PianoWeapon()
```

## Fields

### _isSpecial

```csharp
private bool _isSpecial
```
#INC


#### Field Value

**Type:** System.Boolean

## Methods

### GiveBarrier()

```csharp
private void GiveBarrier()
```
#INC


### OnAttackStart(UnitModel, UnitModel)

```csharp
public override EquipmentScriptBase.WeaponDamageInfo OnAttackStart(UnitModel actor, UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.EquipmentScriptBase.WeaponDamageInfo

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
