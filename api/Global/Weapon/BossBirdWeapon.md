---
uid: Global.BossBirdWeapon
canonical_path: /api/Global/Weapon/BossBirdWeapon
---

# Class BossBirdWeapon

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BossBirdWeapon : EquipmentScriptBase
```
Script for [Apocalypse Bird](/api/Global/Misc/BossBird)'s EGO Weapon: Twilight. Does all types of damage.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/Misc/EquipmentScriptBase) → BossBirdWeapon

## Inherited Members
[_model](/api/Global/Misc/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/Misc/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/Misc/EquipmentScriptBase#setmodel-equipmentmodel), [OnEquip(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onequip-unitmodel), [OnRelease()](/api/Global/Misc/EquipmentScriptBase#onrelease), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/Misc/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/Misc/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/Misc/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdamage-unitmodel), [GetBonus(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/Misc/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/Misc/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BossBirdWeapon()

```csharp
public BossBirdWeapon()
```

## Fields

### _closeTimer

```csharp
private AutoTimer _closeTimer
```
#INC


#### Field Value

**Type:** Global.AutoTimer

### _isBattle

```csharp
private bool _isBattle
```
#INC


#### Field Value

**Type:** System.Boolean

### _isSpecialAttack

```csharp
private bool _isSpecialAttack
```
#INC


#### Field Value

**Type:** System.Boolean

### _skillCoolTime

```csharp
private const float _skillCoolTime = 60
```
#INC


#### Field Value

**Type:** System.Single

### _skillCoolTimer

```csharp
private Timer _skillCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _skillEffect

```csharp
private GameObject _skillEffect
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

### effectSrc

```csharp
private const string effectSrc = "Effect/Creature/BigBird/BossBirdWeaponEffect"
```
#INC


#### Field Value

**Type:** System.String

### normalDamageAry

```csharp
private static int[] normalDamageAry
```
#INC


#### Field Value

**Type:** System.Int32[]

### skillInfo

```csharp
private SplashInfo skillInfo
```
#INC


#### Field Value

**Type:** Global.SplashInfo

### specialDamageAry

```csharp
private static int[] specialDamageAry
```
#INC


#### Field Value

**Type:** System.Int32[]

### worker

```csharp
private WorkerModel worker
```
#INC


#### Field Value

**Type:** Global.WorkerModel

## Methods

### ClearEffect()

```csharp
private void ClearEffect()
```
#INC


### CloseSkill()

```csharp
public void CloseSkill()
```
#INC


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

### Init()

```csharp
private void Init()
```
#INC


### LoadEffect()

```csharp
private void LoadEffect()
```
#INC


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
