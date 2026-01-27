---
uid: Global.ArmorModel
canonical_path: /api/Global/Model/ArmorModel
---

# Class ArmorModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ArmorModel : EquipmentModel
```

Parent class for EGO Suits.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentModel](/api/Global/Model/EquipmentModel) → ArmorModel

## Inherited Members
[metaInfo](/api/Global/Model/EquipmentModel#metainfo), [instanceId](/api/Global/Model/EquipmentModel#instanceid), [_owner](/api/Global/Model/EquipmentModel#owner), [script](/api/Global/Model/EquipmentModel#script), [currentTarget](/api/Global/Model/EquipmentModel#currenttarget), [OnPrepareWeapon(UnitModel)](/api/Global/Model/EquipmentModel#onprepareweapon-unitmodel), [GetDamageFactor()](/api/Global/Model/EquipmentModel#getdamagefactor), [OnCancelWeapon(UnitModel)](/api/Global/Model/EquipmentModel#oncancelweapon-unitmodel), [OnEquip(UnitModel)](/api/Global/Model/EquipmentModel#onequip-unitmodel), [OnRelease()](/api/Global/Model/EquipmentModel#onrelease), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/Model/EquipmentModel#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/Model/EquipmentModel#ontakedamage-after-float-rwbptype), [CheckRequire(UnitModel)](/api/Global/Model/EquipmentModel#checkrequire-unitmodel), [GetBonus(UnitModel)](/api/Global/Model/EquipmentModel#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Model/EquipmentModel#getworkprobspecialbonus-unitmodel-skilltypeinfo), [owner](/api/Global/Model/EquipmentModel#owner), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ArmorModel()

```csharp
public ArmorModel()
```

## Methods

### GetDefense(UnitModel)

```csharp
public DefenseInfo GetDefense(UnitModel actor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.DefenseInfo

### GetDummyArmor()

```csharp
public static ArmorModel GetDummyArmor()
```
#INC


#### Returns

**Type:** Global.ArmorModel

### MakeArmor(EquipmentTypeInfo)

```csharp
public static ArmorModel MakeArmor(EquipmentTypeInfo info)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |

#### Returns

**Type:** Global.ArmorModel

### OnFixedUpdate()

```csharp
public override void OnFixedUpdate()
```
#INC
#code-generated

