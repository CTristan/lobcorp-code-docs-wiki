---
uid: Global.BossBirdArmor
canonical_path: /api/Global/Armor/BossBirdArmor
---

# Class BossBirdArmor

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BossBirdArmor : EquipmentScriptBase
```

Script for [Apocalypse Bird](/api/Global/Misc/BossBird)'s EGO Suit: Twilight. Does some damage to enemies in the room, I think. #INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/Misc/EquipmentScriptBase) → BossBirdArmor

## Inherited Members
[_model](/api/Global/Misc/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/Misc/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/Misc/EquipmentScriptBase#setmodel-equipmentmodel), [OnEquip(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onequip-unitmodel), [OnRelease()](/api/Global/Misc/EquipmentScriptBase#onrelease), [OnPrepareWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/Misc/EquipmentScriptBase#oncancelweapon-unitmodel), [OnAttackStart(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onattackstart-unitmodel-unitmodel), [OnAttackEnd(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onattackend-unitmodel-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/Misc/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/Misc/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/Misc/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/Misc/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdefense-unitmodel), [GetDamage(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getdamage-unitmodel), [GetBonus(UnitModel)](/api/Global/Misc/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Misc/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/Misc/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/Misc/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/Misc/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BossBirdArmor()

```csharp
public BossBirdArmor()
```

## Fields

### _damageEffect

```csharp
private const string _damageEffect = "Effect/Creature/BossBird/BossBirdArmorHit"
```
#INC


#### Field Value

**Type:** System.String

### _damageEffect_set

```csharp
private const string _damageEffect_set = "Effect/Creature/BossBird/BossBirdArmorHit_Set"
```
#INC


#### Field Value

**Type:** System.String

### _footEffect

```csharp
private GameObject _footEffect
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### _footEffectSrc

```csharp
private const string _footEffectSrc = "Effect/Creature/BossBird/BossBirdArmorEffect"
```
#INC


#### Field Value

**Type:** System.String

### _nearDamage

```csharp
private DamageInfo _nearDamage
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### _nearDamageFreq

```csharp
private const float _nearDamageFreq = 5
```
#INC


#### Field Value

**Type:** System.Single

### _nearDamageTimer

```csharp
private Timer _nearDamageTimer
```
#INC


#### Field Value

**Type:** Global.Timer

### _setDamage

```csharp
private static DamageInfo[] _setDamage
```
#INC


#### Field Value

**Type:** Global.DamageInfo[]

### _setOption

```csharp
private bool _setOption
```
#INC


#### Field Value

**Type:** System.Boolean

### _worker

```csharp
private WorkerModel _worker
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


### GetDamageFactor()

```csharp
public override float GetDamageFactor()
```
#INC


#### Returns

**Type:** System.Single

### GetNearHostileUnit()

```csharp
private List<UnitModel> GetNearHostileUnit()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

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


### MakeDamage(List<UnitModel>)

```csharp
private void MakeDamage(List<UnitModel> target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `System.Collections.Generic.List{UnitModel}` |  |

### MakeDamageEffect(UnitModel)

```csharp
private void MakeDamageEffect(UnitModel target)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

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
#code-generated


### SetActiveEffect(bool)

```csharp
private void SetActiveEffect(bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |
