---
uid: Global.LadyLookingAtWallWeapon
canonical_path: /api/Global/Weapon/LadyLookingAtWallWeapon
---

# Class LadyLookingAtWallWeapon

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class LadyLookingAtWallWeapon : EquipmentScriptBase
```

Script for [The Lady Facing the Wall](/api/Global/Misc/LadyLookingAtWall)'s EGO Weapon: Screaming Wedge.

On attack, randomly damages the user for 5 SP at a 50% chance if their fortitude and prudence are both less than 3.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/Misc/EquipmentScriptBase) → LadyLookingAtWallWeapon

## Inherited Members
[_model](/api/Global/Misc/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/Misc/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/Misc/EquipmentScriptBase#setmodel-equipmentmodel), [OnRelease()](/api/Global/Misc/EquipmentScriptBase#onrelease), [OnStageStart()](/api/Global/Misc/EquipmentScriptBase#onstagestart), [OnStageRelease()](/api/Global/Misc/EquipmentScriptBase#onstagerelease), [OnPrepareWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#oncancelweapon-unitmodel), [OnAttackStart(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onattackstart-unitmodel-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/Misc/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/Misc/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/Misc/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdamage-unitmodel), [OnFixedUpdate()](/api/Global/Misc/EquipmentScriptBase#onfixedupdate), [GetBonus(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/Misc/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/Misc/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### LadyLookingAtWallWeapon()

```csharp
public LadyLookingAtWallWeapon()
```

## Fields

### _AMOUNT_DECREASE_MENTAL

```csharp
private readonly float _AMOUNT_DECREASE_MENTAL
```
#INC


#### Field Value

**Type:** System.Single

### _backDmgState

```csharp
private bool _backDmgState
```
#INC


#### Field Value

**Type:** System.Boolean

### _CONDITION_FORTITUDE_LEVEL

```csharp
private readonly int _CONDITION_FORTITUDE_LEVEL
```
#INC


#### Field Value

**Type:** System.Int32

### _CONDITION_PRUDENCE_LEVEL

```csharp
private readonly int _CONDITION_PRUDENCE_LEVEL
```
#INC


#### Field Value

**Type:** System.Int32

### _LOG_STATE

```csharp
private readonly bool _LOG_STATE
```
#INC


#### Field Value

**Type:** System.Boolean

### _PROB_DECREASE_MENTAL

```csharp
private readonly float _PROB_DECREASE_MENTAL
```
#INC


#### Field Value

**Type:** System.Single

## Methods

### OnAttackEnd(UnitModel, UnitModel)

```csharp
public override void OnAttackEnd(UnitModel actor, UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |

### OnEquip(UnitModel)

```csharp
public override void OnEquip(UnitModel actor)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)

```csharp
public override bool OnGiveDamage(UnitModel actor, UnitModel target, ref DamageInfo dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean

### PrintLog(string)

```csharp
private void PrintLog(string s)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `s` | `System.String` |  |
