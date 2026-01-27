---
uid: Global.DeathAngelWeapon
canonical_path: /api/Global/Weapon/DeathAngelWeapon
---

# Class DeathAngelWeapon

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeathAngelWeapon : EquipmentScriptBase
```

Script for [WhiteNight](/api/Legacy/DeathAngel)'s EGO Weapon: Paradise Lost.

It's complicated.

Has a special AOE attack which gives a shield that negates all forms of damage. I think.
Heals on attack, and prevents all other healing except by damage.
Apparently slows the target on hit, too?

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/Misc/EquipmentScriptBase) → DeathAngelWeapon

## Inherited Members
[_model](/api/Global/Misc/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/Misc/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/Misc/EquipmentScriptBase#setmodel-equipmentmodel), [OnEquip(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onequip-unitmodel), [OnRelease()](/api/Global/Misc/EquipmentScriptBase#onrelease), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/Misc/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/Misc/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/Misc/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdamage-unitmodel), [GetBonus(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/Misc/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/Misc/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DeathAngelWeapon()

```csharp
public DeathAngelWeapon()
```

## Fields

### _barrierTime

```csharp
private const float _barrierTime = 10
```
#INC


#### Field Value

**Type:** System.Single

### _barrierValue

```csharp
private const float _barrierValue = 100
```
#INC


#### Field Value

**Type:** System.Single

### _dmgMax_1st

```csharp
private const int _dmgMax_1st = 20
```
#INC


#### Field Value

**Type:** System.Int32

### _dmgMax_2nd

```csharp
private const int _dmgMax_2nd = 23
```
#INC


#### Field Value

**Type:** System.Int32

### _dmgMax_3rd

```csharp
private const int _dmgMax_3rd = 28
```
#INC


#### Field Value

**Type:** System.Int32

### _dmgMin_1st

```csharp
private const int _dmgMin_1st = 16
```
#INC


#### Field Value

**Type:** System.Int32

### _dmgMin_2nd

```csharp
private const int _dmgMin_2nd = 19
```
#INC


#### Field Value

**Type:** System.Int32

### _dmgMin_3rd

```csharp
private const int _dmgMin_3rd = 22
```
#INC


#### Field Value

**Type:** System.Int32

### _dmgType

```csharp
private const RwbpType _dmgType = P
```
#INC


#### Field Value

**Type:** Global.RwbpType

### _effectConditionFirst

```csharp
private const int _effectConditionFirst = 2
```
#INC


#### Field Value

**Type:** System.Int32

### _effectConditionSecond

```csharp
private const int _effectConditionSecond = 6
```
#INC


#### Field Value

**Type:** System.Int32

### _effectSrc

```csharp
private const string _effectSrc = "Effect/Invoke/DamageInfo/DeathAngelWeaponeffect"
```
#INC


#### Field Value

**Type:** System.String

### _healMax

```csharp
private const float _healMax = 4
```
#INC


#### Field Value

**Type:** System.Single

### _healMin

```csharp
private const float _healMin = 2
```
#INC


#### Field Value

**Type:** System.Single

### _isBattle

```csharp
private bool _isBattle
```
#INC


#### Field Value

**Type:** System.Boolean

### _skillCoolTimeMax

```csharp
private const float _skillCoolTimeMax = 20
```
#INC


#### Field Value

**Type:** System.Single

### _skillCoolTimeMin

```csharp
private const float _skillCoolTimeMin = 20
```
#INC


#### Field Value

**Type:** System.Single

### _skillEffect

```csharp
private GameObject _skillEffect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### _trailSrc

```csharp
private const string _trailSrc = "Effect/Agent/DeathAngelWeaponTrail"
```
#INC


#### Field Value

**Type:** System.String

### _whiteNight

```csharp
private bool _whiteNight
```
#INC


#### Field Value

**Type:** System.Boolean

### atkInit

```csharp
private bool atkInit
```
#INC


#### Field Value

**Type:** System.Boolean

### isSpecial

```csharp
private bool isSpecial
```
#INC


#### Field Value

**Type:** System.Boolean

### skillCoolTimer

```csharp
private Timer skillCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### trailPos

```csharp
private readonly Vector3 trailPos
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### trailRot

```csharp
private readonly Vector3 trailRot
```
#INC


#### Field Value

**Type:** UnityEngine.Vector3

### worker

```csharp
private WorkerModel worker
```
#INC


#### Field Value

**Type:** Global.WorkerModel

## Properties

### Dmg_1st

```csharp
private static DamageInfo Dmg_1st { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### Dmg_2nd

```csharp
private static DamageInfo Dmg_2nd { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### Dmg_3rd

```csharp
private static DamageInfo Dmg_3rd { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### HealValue

```csharp
private static float HealValue { get; }
```

#### Property Value

**Type:** System.Single

### skillCoolTime

```csharp
private static float skillCoolTime { get; }
```

#### Property Value

**Type:** System.Single

## Methods

### ClearEffect()

```csharp
private void ClearEffect()
```
#INC


### GetBarrier()

```csharp
private void GetBarrier()
```
#INC


### GetTargets()

```csharp
private List<UnitModel> GetTargets()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### GiveDamage(UnitModel, int)

```csharp
private void GiveDamage(UnitModel target, int cnt)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `cnt` | `System.Int32` |  |

### IsHostile(UnitModel)

```csharp
private bool IsHostile(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### LoadEffect()

```csharp
private void LoadEffect()
```
#INC


### MakeEffect(UnitModel, int)

```csharp
private void MakeEffect(UnitModel target, int cnt)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `cnt` | `System.Int32` |  |

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

### OnCancelWeapon(UnitModel)

```csharp
public override void OnCancelWeapon(UnitModel actor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnFixedUpdate()

```csharp
public override void OnFixedUpdate()
```
#INC


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

### OnPrepareWeapon(UnitModel)

```csharp
public override void OnPrepareWeapon(UnitModel actor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnStageRelease()

```csharp
public override void OnStageRelease()
```
#INC


### OnStageStart()

```csharp
public override void OnStageStart()
```
#INC
#code-generated


### SetEffectActive(bool)

```csharp
private void SetEffectActive(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetNextAttackType()

```csharp
private void SetNextAttackType()
```
#INC

