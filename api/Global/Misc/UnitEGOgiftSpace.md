---
uid: Global.UnitEGOgiftSpace
canonical_path: /api/Global/Misc/UnitEGOgiftSpace
---

# Class UnitEGOgiftSpace

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnitEGOgiftSpace
```
Many methods to work with EGO gifts.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → UnitEGOgiftSpace

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UnitEGOgiftSpace()

```csharp
public UnitEGOgiftSpace()
```
#INC
#code-generated


## Fields

### addedGifts

```csharp
public List<EGOgiftModel> addedGifts
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{EGOgiftModel}

### displayState

```csharp
public Dictionary<int, bool> displayState
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Boolean}

### lockState

```csharp
public Dictionary<int, UnitEGOgiftSpace.GiftLockState> lockState
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,UnitEGOgiftSpace.GiftLockState}

### replacedGifts

```csharp
public List<EGOgiftModel> replacedGifts
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{EGOgiftModel}

### uniqueLock

```csharp
public static readonly long[] uniqueLock
```
#INC


#### Field Value

**Type:** System.Int64[]

## Methods

### AttachGift(UnitModel, EGOgiftModel)

```csharp
public void AttachGift(UnitModel owner, EGOgiftModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.UnitModel` |  |
| `model` | `Global.EGOgiftModel` |  |

### CountGifts()

```csharp
public int CountGifts()
```
#INC


#### Returns

**Type:** System.Int32

### GetBonus(UnitModel)

```csharp
public EGObonusInfo GetBonus(UnitModel actor)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.EGObonusInfo

### GetDamageFactor()

```csharp
public float GetDamageFactor()
```
#INC


#### Returns

**Type:** System.Single

### GetDisplayState(EGOgiftModel)

```csharp
public bool GetDisplayState(EGOgiftModel model)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EGOgiftModel` |  |

#### Returns

**Type:** System.Boolean

### GetLockState(EquipmentTypeInfo)

```csharp
public bool GetLockState(EquipmentTypeInfo info)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |

#### Returns

**Type:** System.Boolean

### GetLockStateUI(EquipmentTypeInfo)

```csharp
public bool GetLockStateUI(EquipmentTypeInfo info)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |

#### Returns

**Type:** System.Boolean

### GetRegionId(EquipmentTypeInfo)

```csharp
public static int GetRegionId(EquipmentTypeInfo info)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |

#### Returns

**Type:** System.Int32

### GetRegionName(EquipmentTypeInfo)

```csharp
public static string GetRegionName(EquipmentTypeInfo info)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |

#### Returns

**Type:** System.String

### GetRegionName(int)

```csharp
public static string GetRegionName(int regionIndex)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `regionIndex` | `System.Int32` |  |

#### Returns

**Type:** System.String

### GetSaveData()

```csharp
public Dictionary<string, object> GetSaveData()
```
#INC


#### Returns

**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)

```csharp
public float GetWorkProbSpecialBonus(UnitModel actor, SkillTypeInfo skill)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `skill` | `Global.SkillTypeInfo` |  |

#### Returns

**Type:** System.Single

### HasEquipment(int)

```csharp
public bool HasEquipment(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** System.Boolean

### IsUniqueLock(long)

```csharp
public static bool IsUniqueLock(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** System.Boolean

### LoadDataAndAttach(UnitModel, Dictionary<string, object>)

```csharp
public void LoadDataAndAttach(UnitModel owner, Dictionary<string, object> dic)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.UnitModel` |  |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### OnFixedUpdate()

```csharp
public void OnFixedUpdate()
```
#INC


### OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)

```csharp
public bool OnGiveDamage(UnitModel actor, UnitModel target, ref DamageInfo dmg)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** System.Boolean

### OnTakeDamage(UnitModel, ref DamageInfo)

```csharp
public void OnTakeDamage(UnitModel actor, ref DamageInfo dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### OnTakeDamage_After(float, RwbpType)

```csharp
public void OnTakeDamage_After(float value, RwbpType type)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |
| `type` | `Global.RwbpType` |  |

### OwnerHeal(bool, ref float)

```csharp
public void OwnerHeal(bool isMental, ref float amount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `isMental` | `System.Boolean` |  |
| `amount` | `System.Single` |  |

### ReleaseGift(EGOgiftModel)

```csharp
public void ReleaseGift(EGOgiftModel gift)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `gift` | `Global.EGOgiftModel` |  |

### SetDisplayState(EGOgiftModel, bool)

```csharp
public void SetDisplayState(EGOgiftModel model, bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EGOgiftModel` |  |
| `state` | `System.Boolean` |  |

### SetLockState(EGOgiftModel, bool)

```csharp
public void SetLockState(EGOgiftModel model, bool state)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.EGOgiftModel` |  |
| `state` | `System.Boolean` |  |
