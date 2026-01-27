---
uid: Global.LookAtMeArmor
canonical_path: /api/Global/Armor/LookAtMeArmor
---

# Class LookAtMeArmor

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class LookAtMeArmor : EquipmentScriptBase
```

Script for [Schadenfreude](/api/Global/Misc/LookAtMe)'s EGO Suit: Gaze.

Increases attack speed by 10 while the equipped agent is in the camera.

Also, changes the defenses to 0.8 / 0.5 / 0.8 / 1.5 (hard-coded!) while in the camera.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/Misc/EquipmentScriptBase) → LookAtMeArmor

## Inherited Members
[_model](/api/Global/Misc/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/Misc/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/Misc/EquipmentScriptBase#setmodel-equipmentmodel), [OnRelease()](/api/Global/Misc/EquipmentScriptBase#onrelease), [OnPrepareWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#oncancelweapon-unitmodel), [OnAttackStart(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onattackstart-unitmodel-unitmodel), [OnAttackEnd(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onattackend-unitmodel-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/Misc/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/Misc/EquipmentScriptBase#addreinforcementlevel-int), [GetDamageFactor()](/api/Global/Misc/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdamage-unitmodel), [GetBonus(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/Misc/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/Misc/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### LookAtMeArmor()

```csharp
public LookAtMeArmor()
```

## Fields

### _justiceBuf

```csharp
private const int _justiceBuf = 10
```
#INC


#### Field Value

**Type:** System.Int32

### cameraSensor

```csharp
private GameObject cameraSensor
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### cameraUtil

```csharp
private CreatureCameraUtil cameraUtil
```

#### Field Value

**Type:** CreatureCameraUtil.CreatureCameraUtil

### owner

```csharp
private WorkerModel owner
```
#INC


#### Field Value

**Type:** Global.WorkerModel

## Methods

### GetDefense(UnitModel)

```csharp
public override DefenseInfo GetDefense(UnitModel actor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.DefenseInfo

### IsInCamera()

```csharp
private bool IsInCamera()
```
#INC


#### Returns

**Type:** System.Boolean

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

### OnFixedUpdate()

```csharp
public override void OnFixedUpdate()
```
#INC


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


### RemoveCamera()

```csharp
private void RemoveCamera()
```
#INC


### SetCamera()

```csharp
private void SetCamera()
```
#INC

