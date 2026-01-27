---
uid: Global.SlimeGirlArmor
canonical_path: /api/Global/Armor/SlimeGirlArmor
---

# Class SlimeGirlArmor

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SlimeGirlArmor : EquipmentScriptBase
```

Script for [Melting Love](/api/Global/Misc/SlimeGirl)'s EGO Suit: Adoration.

When the user has the corresponding EGO Gift and is at $\leq$ 20% HP, isn't on cooldown, and takes more than 10 damage:
- Give them a red shield (100 hp, 3 seconds)
- Slow them to 30% movements speed for 3 seconds
- Play a slime noise

Has a 12 second cooldown.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/Misc/EquipmentScriptBase) → SlimeGirlArmor

## Inherited Members
[_model](/api/Global/Misc/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/Misc/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/Misc/EquipmentScriptBase#setmodel-equipmentmodel), [OnEquip(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onequip-unitmodel), [OnRelease()](/api/Global/Misc/EquipmentScriptBase#onrelease), [OnStageStart()](/api/Global/Misc/EquipmentScriptBase#onstagestart), [OnStageRelease()](/api/Global/Misc/EquipmentScriptBase#onstagerelease), [OnPrepareWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#oncancelweapon-unitmodel), [OnAttackStart(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onattackstart-unitmodel-unitmodel), [OnAttackEnd(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onattackend-unitmodel-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/Misc/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/Misc/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/Misc/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdamage-unitmodel), [GetBonus(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/Misc/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/Misc/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SlimeGirlArmor()

```csharp
public SlimeGirlArmor()
```

## Fields

### BARRIER_COOL_TIME

```csharp
private const float BARRIER_COOL_TIME = 12
```
#INC


#### Field Value

**Type:** System.Single

### BARRIER_TIME

```csharp
private const float BARRIER_TIME = 3
```
#INC


#### Field Value

**Type:** System.Single

### BARRIER_VALUE

```csharp
private const float BARRIER_VALUE = 100
```
#INC


#### Field Value

**Type:** System.Single

### barrierCoolTimer

```csharp
private Timer barrierCoolTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### DMG_CONDITION

```csharp
private const float DMG_CONDITION = 10
```
#INC


#### Field Value

**Type:** System.Single

### HP_CONDITION

```csharp
private const float HP_CONDITION = 0.2
```
#INC


#### Field Value

**Type:** System.Single

### SLIME_GIFT_ID

```csharp
private const int SLIME_GIFT_ID = 400063
```
#INC


#### Field Value

**Type:** System.Int32

## Methods

### CheckCondition(WorkerModel)

```csharp
private bool CheckCondition(WorkerModel owner)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.WorkerModel` |  |

#### Returns

**Type:** System.Boolean

### GiveBarrier(WorkerModel)

```csharp
private void GiveBarrier(WorkerModel owner)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.WorkerModel` |  |

### OnFixedUpdate()

```csharp
public override void OnFixedUpdate()
```
#INC


### OnTakeDamage(UnitModel, ref DamageInfo)

```csharp
public override bool OnTakeDamage(UnitModel actor, ref DamageInfo dmg)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean
