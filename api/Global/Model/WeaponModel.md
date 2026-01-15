---
uid: Global.WeaponModel
canonical_path: /api/Global/Model/WeaponModel
---

# Class WeaponModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WeaponModel : EquipmentModel
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentModel](/api/Global/Model/EquipmentModel) → WeaponModel

## Inherited Members
[metaInfo](/api/Global/Model/EquipmentModel#metainfo), [instanceId](/api/Global/Model/EquipmentModel#instanceid), [_owner](/api/Global/Model/EquipmentModel#owner), [script](/api/Global/Model/EquipmentModel#script), [currentTarget](/api/Global/Model/EquipmentModel#currenttarget), [OnPrepareWeapon(UnitModel)](/api/Global/Model/EquipmentModel#onprepareweapon-unitmodel), [GetDamageFactor()](/api/Global/Model/EquipmentModel#getdamagefactor), [OnCancelWeapon(UnitModel)](/api/Global/Model/EquipmentModel#oncancelweapon-unitmodel), [OnEquip(UnitModel)](/api/Global/Model/EquipmentModel#onequip-unitmodel), [OnRelease()](/api/Global/Model/EquipmentModel#onrelease), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/Model/EquipmentModel#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/Model/EquipmentModel#ontakedamage-after-float-rwbptype), [CheckRequire(UnitModel)](/api/Global/Model/EquipmentModel#checkrequire-unitmodel), [GetBonus(UnitModel)](/api/Global/Model/EquipmentModel#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Model/EquipmentModel#getworkprobspecialbonus-unitmodel-skilltypeinfo), [owner](/api/Global/Model/EquipmentModel#owner), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WeaponModel()

```csharp
public WeaponModel()
```

## Fields

### _currentDamageInfos

```csharp
private Queue<DamageInfo> _currentDamageInfos
```

#### Field Value

**Type:** System.Collections.Generic.Queue{DamageInfo}

### fireEffectRunned

```csharp
private bool fireEffectRunned
```

#### Field Value

**Type:** System.Boolean

### remainDelay

```csharp
public float remainDelay
```

#### Field Value

**Type:** System.Single

## Methods

### GetDamage(UnitModel)

```csharp
public DamageInfo GetDamage(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.DamageInfo

### GetDir(UnitModel, UnitModel)

```csharp
public UnitDirection GetDir(UnitModel attacker, UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.UnitDirection

### GetDummyWeapon()

```csharp
public static WeaponModel GetDummyWeapon()
```

#### Returns

**Type:** Global.WeaponModel

### GetOfficerWeapon()

```csharp
public static WeaponModel GetOfficerWeapon()
```

#### Returns

**Type:** Global.WeaponModel

### InRange(UnitModel, UnitModel)

```csharp
public bool InRange(UnitModel actor, UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.Boolean

### InRangeDirectionalAtDamageTime(UnitModel, UnitModel, float)

```csharp
public bool InRangeDirectionalAtDamageTime(UnitModel actor, UnitModel target, float addedRange)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |
| `addedRange` | `System.Single` |  |

#### Returns

**Type:** System.Boolean

### InvokeEffect(UnitModel, DamageInfo, UnitDirection)

```csharp
public void InvokeEffect(UnitModel unit, DamageInfo damageInfo, UnitDirection dir)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |
| `damageInfo` | `Global.DamageInfo` |  |
| `dir` | `Global.UnitDirection` |  |

### MakeWeapon(EquipmentTypeInfo)

```csharp
public static WeaponModel MakeWeapon(EquipmentTypeInfo info)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |

#### Returns

**Type:** Global.WeaponModel

### OnAttack(UnitModel, UnitModel)

```csharp
public string OnAttack(UnitModel actor, UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |

#### Returns

**Type:** System.String

### OnEndAttackCycle()

```csharp
public void OnEndAttackCycle()
```

### OnFixedUpdate()

```csharp
public override void OnFixedUpdate()
```

### OnGiveDamage(UnitModel)

```csharp
public void OnGiveDamage(UnitModel actor)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
