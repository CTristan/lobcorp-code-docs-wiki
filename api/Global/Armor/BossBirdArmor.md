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

#### Field Value

**Type:** System.String

### _damageEffect_set

```csharp
private const string _damageEffect_set = "Effect/Creature/BossBird/BossBirdArmorHit_Set"
```

#### Field Value

**Type:** System.String

### _footEffect

```csharp
private GameObject _footEffect
```

#### Field Value

**Type:** UnityEngine.GameObject

### _footEffectSrc

```csharp
private const string _footEffectSrc = "Effect/Creature/BossBird/BossBirdArmorEffect"
```

#### Field Value

**Type:** System.String

### _nearDamage

```csharp
private DamageInfo _nearDamage
```

#### Field Value

**Type:** Global.DamageInfo

### _nearDamageFreq

```csharp
private const float _nearDamageFreq = 5
```

#### Field Value

**Type:** System.Single

### _nearDamageTimer

```csharp
private Timer _nearDamageTimer
```

#### Field Value

**Type:** Global.Timer

### _setDamage

```csharp
private static DamageInfo[] _setDamage
```

#### Field Value

**Type:** Global.DamageInfo[]

### _setOption

```csharp
private bool _setOption
```

#### Field Value

**Type:** System.Boolean

### _worker

```csharp
private WorkerModel _worker
```

#### Field Value

**Type:** Global.WorkerModel

## Methods

### ClearEffect()

```csharp
private void ClearEffect()
```

### GetDamageFactor()

```csharp
public override float GetDamageFactor()
```

#### Returns

**Type:** System.Single

### GetNearHostileUnit()

```csharp
private List<UnitModel> GetNearHostileUnit()
```

#### Returns

**Type:** System.Collections.Generic.List{UnitModel}

### Init()

```csharp
private void Init()
```

### LoadEffect()

```csharp
private void LoadEffect()
```

### MakeDamage(List<UnitModel>)

```csharp
private void MakeDamage(List<UnitModel> target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `System.Collections.Generic.List{UnitModel}` |  |

### MakeDamageEffect(UnitModel)

```csharp
private void MakeDamageEffect(UnitModel target)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### OnFixedUpdate()

```csharp
public override void OnFixedUpdate()
```

### OnStageRelease()

```csharp
public override void OnStageRelease()
```

### OnStageStart()

```csharp
public override void OnStageStart()
```

### SetActiveEffect(bool)

```csharp
private void SetActiveEffect(bool state)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |
