# Class RedShoesAttractedWeapon

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RedShoesAttractedWeapon : EquipmentScriptBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/EquipmentScriptBase) → RedShoesAttractedWeapon

## Inherited Members
[MAX_REINFORCEMENT_LEVEL](/api/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/EquipmentScriptBase#setmodel-equipmentmodel), [OnRelease()](/api/EquipmentScriptBase#onrelease), [OnStageStart()](/api/EquipmentScriptBase#onstagestart), [OnStageRelease()](/api/EquipmentScriptBase#onstagerelease), [OnPrepareWeapon(UnitModel)](/api/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/EquipmentScriptBase#oncancelweapon-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/EquipmentScriptBase#getdamage-unitmodel), [OnFixedUpdate()](/api/EquipmentScriptBase#onfixedupdate), [GetBonus(UnitModel)](/api/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/EquipmentScriptBase#model), [reinforcementLevel](/api/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### RedShoesAttractedWeapon()

```csharp
public RedShoesAttractedWeapon()
```

## Methods

### OnAttackEnd(UnitModel, UnitModel)

```csharp
public override void OnAttackEnd(UnitModel actor, UnitModel target)
```

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

### OnEquip(UnitModel)

```csharp
public override void OnEquip(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)

```csharp
public override bool OnGiveDamage(UnitModel actor, UnitModel target, ref DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean

### OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)

```csharp
public override void OnGiveDamageAfter(UnitModel actor, UnitModel target, DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |
