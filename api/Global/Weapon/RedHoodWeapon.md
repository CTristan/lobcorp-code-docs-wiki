---
uid: Global.RedHoodWeapon
canonical_path: /api/Global/Weapon/RedHoodWeapon
---

# Class RedHoodWeapon

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RedHoodWeapon : EquipmentScriptBase
```

Script for [Little Red](/api/Global/IOBserver/RedHood)'s EGO Weapon: Crimson Scar.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/Misc/EquipmentScriptBase) → RedHoodWeapon

## Inherited Members
[_model](/api/Global/Misc/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/Misc/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/Misc/EquipmentScriptBase#setmodel-equipmentmodel), [OnEquip(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onequip-unitmodel), [OnRelease()](/api/Global/Misc/EquipmentScriptBase#onrelease), [OnStageRelease()](/api/Global/Misc/EquipmentScriptBase#onstagerelease), [OnPrepareWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#oncancelweapon-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [GetReinforcementDmg()](/api/Global/Misc/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/Misc/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/Misc/EquipmentScriptBase#getdamagefactor), [GetBonus(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/Misc/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/Misc/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RedHoodWeapon()

```csharp
public RedHoodWeapon()
```

## Fields

### _attackBuf

```csharp
private const float _attackBuf = 1.5
```
#INC


#### Field Value

**Type:** System.Single

### _defaultRange

```csharp
private const int _defaultRange = 3
```
#INC


#### Field Value

**Type:** System.Int32

### _effect_src

```csharp
private const string _effect_src = "Effect/Agent/RedHoodWeaponAura"
```
#INC


#### Field Value

**Type:** System.String

### _gun_fire

```csharp
private const string _gun_fire = "Effect/Agent/RedHoodWeaponGunFire"
```
#INC


#### Field Value

**Type:** System.String

### _skillHpRatio

```csharp
private const float _skillHpRatio = 0.5
```
#INC


#### Field Value

**Type:** System.Single

### _specialProb

```csharp
private const float _specialProb = 0.3
```
#INC


#### Field Value

**Type:** System.Single

### _specialRange

```csharp
private const int _specialRange = 15
```
#INC


#### Field Value

**Type:** System.Int32

### aura

```csharp
private GameObject aura
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### defaultInfo

```csharp
private SplashInfo defaultInfo
```
#INC


#### Field Value

**Type:** Global.SplashInfo

### isSpecial

```csharp
private bool isSpecial
```
#INC


#### Field Value

**Type:** System.Boolean

### specialInfo

```csharp
private SplashInfo specialInfo
```
#INC


#### Field Value

**Type:** Global.SplashInfo

### worker

```csharp
private WorkerModel worker
```
#INC


#### Field Value

**Type:** Global.WorkerModel

## Properties

### isRaged

```csharp
private bool isRaged { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### AttachEffect()

```csharp
private GameObject AttachEffect()
```
#INC


#### Returns

**Type:** UnityEngine.GameObject

### GetDamage(int)

```csharp
private DamageInfo GetDamage(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** Global.DamageInfo

### GetDamage(UnitModel)

```csharp
public override DamageInfo GetDamage(UnitModel actor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.DamageInfo

### Init()

```csharp
private void Init()
```
#INC


### MakeGunFire()

```csharp
private void MakeGunFire()
```
#INC


### OnAnimCalled(int)

```csharp
public void OnAnimCalled(int i)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

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

### OnFixedUpdate()

```csharp
public override void OnFixedUpdate()
```
#INC


### OnStageStart()

```csharp
public override void OnStageStart()
```
#INC
#code-generated


### OnTakeDamage_After(float, RwbpType)

```csharp
public override bool OnTakeDamage_After(float value, RwbpType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |
| `type` | `Global.RwbpType` |  |

#### Returns

**Type:** System.Boolean

### RemoveEffect()

```csharp
private void RemoveEffect()
```
#INC


### SetNextAttackType()

```csharp
private void SetNextAttackType()
```
#INC

