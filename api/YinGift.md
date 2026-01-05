# Class YinGift

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class YinGift : EquipmentScriptBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/EquipmentScriptBase) → YinGift

## Inherited Members
[MAX_REINFORCEMENT_LEVEL](/api/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/EquipmentScriptBase#setmodel-equipmentmodel), [OnEquip(UnitModel)](/api/EquipmentScriptBase#onequip-unitmodel), [OnRelease()](/api/EquipmentScriptBase#onrelease), [OnStageStart()](/api/EquipmentScriptBase#onstagestart), [OnStageRelease()](/api/EquipmentScriptBase#onstagerelease), [OnPrepareWeapon(UnitModel)](/api/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/EquipmentScriptBase#oncancelweapon-unitmodel), [OnAttackStart(UnitModel, UnitModel)](/api/EquipmentScriptBase#onattackstart-unitmodel-unitmodel), [OnAttackEnd(UnitModel, UnitModel)](/api/EquipmentScriptBase#onattackend-unitmodel-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/EquipmentScriptBase#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [GetReinforcementDmg()](/api/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/EquipmentScriptBase#getdamage-unitmodel), [OnFixedUpdate()](/api/EquipmentScriptBase#onfixedupdate), [GetBonus(UnitModel)](/api/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/EquipmentScriptBase#model), [reinforcementLevel](/api/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### YinGift()

```csharp
public YinGift()
```

## Methods

### OnTakeDamage(UnitModel, ref DamageInfo)

```csharp
public override bool OnTakeDamage(UnitModel actor, ref DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean

### OnTakeDamage_After(float, RwbpType)

```csharp
public override bool OnTakeDamage_After(float value, RwbpType type)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |
| `type` | `Global.RwbpType` |  |

#### Returns

**Type:** System.Boolean
