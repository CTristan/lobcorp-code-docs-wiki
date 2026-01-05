# Class EGOgiftModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EGOgiftModel : EquipmentModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentModel](/api/EquipmentModel) → EGOgiftModel

## Inherited Members
[metaInfo](/api/EquipmentModel#metainfo), [instanceId](/api/EquipmentModel#instanceid), [script](/api/EquipmentModel#script), [currentTarget](/api/EquipmentModel#currenttarget), [OnFixedUpdate()](/api/EquipmentModel#onfixedupdate), [OnPrepareWeapon(UnitModel)](/api/EquipmentModel#onprepareweapon-unitmodel), [GetDamageFactor()](/api/EquipmentModel#getdamagefactor), [OnCancelWeapon(UnitModel)](/api/EquipmentModel#oncancelweapon-unitmodel), [OnEquip(UnitModel)](/api/EquipmentModel#onequip-unitmodel), [OnRelease()](/api/EquipmentModel#onrelease), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/EquipmentModel#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/EquipmentModel#ontakedamage-after-float-rwbptype), [CheckRequire(UnitModel)](/api/EquipmentModel#checkrequire-unitmodel), [GetBonus(UnitModel)](/api/EquipmentModel#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/EquipmentModel#getworkprobspecialbonus-unitmodel-skilltypeinfo), [owner](/api/EquipmentModel#owner), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### EGOgiftModel()

```csharp
public EGOgiftModel()
```

## Methods

### GetDummyGift()

```csharp
public static EGOgiftModel GetDummyGift()
```

#### Returns

**Type:** Global.EGOgiftModel

### MakeGift(EquipmentTypeInfo)

```csharp
public static EGOgiftModel MakeGift(EquipmentTypeInfo info)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |

#### Returns

**Type:** Global.EGOgiftModel
