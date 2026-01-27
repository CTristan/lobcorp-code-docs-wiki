---
uid: Global.MagicalGirlWeapon
canonical_path: /api/Global/Weapon/MagicalGirlWeapon
---

# Class MagicalGirlWeapon

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MagicalGirlWeapon : EquipmentScriptBase
```

Script for [Queen of Hatred](/api/Global/IOBserver/MagicalGirl)'s EGO Weapon: In the Name of Love and Hate.

Sends stars of a random type of damage (.3/.3/.3/.1 flying. Damages hostile things, panicked workers, and abnormalities, and heals other controllable workers. (Ignores uncontrollable workers.)

Healing heals the corresponding HP or SP for the damage type, with Pale damage healing percentile HP.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/Misc/EquipmentScriptBase) → MagicalGirlWeapon

## Inherited Members
[_model](/api/Global/Misc/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/Misc/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/Misc/EquipmentScriptBase#setmodel-equipmentmodel), [OnEquip(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onequip-unitmodel), [OnRelease()](/api/Global/Misc/EquipmentScriptBase#onrelease), [OnStageStart()](/api/Global/Misc/EquipmentScriptBase#onstagestart), [OnStageRelease()](/api/Global/Misc/EquipmentScriptBase#onstagerelease), [OnPrepareWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#oncancelweapon-unitmodel), [OnAttackStart(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onattackstart-unitmodel-unitmodel), [OnAttackEnd(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onattackend-unitmodel-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/Misc/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/Misc/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/Misc/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdamage-unitmodel), [OnFixedUpdate()](/api/Global/Misc/EquipmentScriptBase#onfixedupdate), [GetBonus(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/Misc/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/Misc/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MagicalGirlWeapon()

```csharp
public MagicalGirlWeapon()
```

## Fields

### _bDmgMax

```csharp
private const float _bDmgMax = 8
```
#INC


#### Field Value

**Type:** System.Single

### _bDmgMin

```csharp
private const float _bDmgMin = 5
```
#INC


#### Field Value

**Type:** System.Single

### _bHealMax

```csharp
private const float _bHealMax = 3
```
#INC


#### Field Value

**Type:** System.Single

### _bHealMin

```csharp
private const float _bHealMin = 2
```
#INC


#### Field Value

**Type:** System.Single

### _bProb

```csharp
private const float _bProb = 0.3
```
#INC


#### Field Value

**Type:** System.Single

### _effectPos

```csharp
private Vector3 _effectPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### _pDmgMax

```csharp
private const float _pDmgMax = 8
```
#INC


#### Field Value

**Type:** System.Single

### _pDmgMin

```csharp
private const float _pDmgMin = 5
```
#INC


#### Field Value

**Type:** System.Single

### _pHealMax

```csharp
private const float _pHealMax = 3
```
#INC


#### Field Value

**Type:** System.Single

### _pHealMin

```csharp
private const float _pHealMin = 2
```
#INC


#### Field Value

**Type:** System.Single

### _projectileSrc

```csharp
private const string _projectileSrc = "Effect/Agent/MagicalGirlWeaponProjectile_"
```
#INC


#### Field Value

**Type:** System.String

### _rDmgMax

```csharp
private const float _rDmgMax = 8
```
#INC


#### Field Value

**Type:** System.Single

### _rDmgMin

```csharp
private const float _rDmgMin = 5
```
#INC


#### Field Value

**Type:** System.Single

### _rHealMax

```csharp
private const float _rHealMax = 3
```
#INC


#### Field Value

**Type:** System.Single

### _rHealMin

```csharp
private const float _rHealMin = 2
```
#INC


#### Field Value

**Type:** System.Single

### _rProb

```csharp
private const float _rProb = 0.3
```
#INC


#### Field Value

**Type:** System.Single

### _wDmgMax

```csharp
private const float _wDmgMax = 8
```
#INC


#### Field Value

**Type:** System.Single

### _wDmgMin

```csharp
private const float _wDmgMin = 5
```
#INC


#### Field Value

**Type:** System.Single

### _wHealMax

```csharp
private const float _wHealMax = 3
```
#INC


#### Field Value

**Type:** System.Single

### _wHealMin

```csharp
private const float _wHealMin = 2
```
#INC


#### Field Value

**Type:** System.Single

### _wProb

```csharp
private const float _wProb = 0.3
```
#INC


#### Field Value

**Type:** System.Single

## Properties

### bDmg

```csharp
private static DamageInfo bDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### bHealValue

```csharp
private static float bHealValue { get; }
```

#### Property Value

**Type:** System.Single

### bValue

```csharp
private static float bValue { get; }
```

#### Property Value

**Type:** System.Single

### pDmg

```csharp
private static DamageInfo pDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### pHealValue

```csharp
private static float pHealValue { get; }
```

#### Property Value

**Type:** System.Single

### pValue

```csharp
private static float pValue { get; }
```

#### Property Value

**Type:** System.Single

### rDmg

```csharp
private static DamageInfo rDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### rHealValue

```csharp
private static float rHealValue { get; }
```

#### Property Value

**Type:** System.Single

### rValue

```csharp
private static float rValue { get; }
```

#### Property Value

**Type:** System.Single

### wDmg

```csharp
private static DamageInfo wDmg { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### wHealValue

```csharp
private static float wHealValue { get; }
```

#### Property Value

**Type:** System.Single

### wValue

```csharp
private static float wValue { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### CheckHit(UnitModel, RwbpType)

```csharp
public bool CheckHit(UnitModel target, RwbpType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `type` | `Global.RwbpType` |  |

#### Returns

**Type:** System.Boolean

### GiveDamage(UnitModel, RwbpType)

```csharp
private void GiveDamage(UnitModel target, RwbpType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `type` | `Global.RwbpType` |  |

### Heal(WorkerModel, RwbpType)

```csharp
private void Heal(WorkerModel worker, RwbpType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |
| `type` | `Global.RwbpType` |  |

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

