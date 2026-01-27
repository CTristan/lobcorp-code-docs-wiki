---
uid: Global.EquipmentTypeInfo
canonical_path: /api/Global/Info/EquipmentTypeInfo
---

# Class EquipmentTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EquipmentTypeInfo
```
Holds information about whether an [EGO](/api/Global/Model/EquipmentModel) is a weapon, suit, or something special, as well as a mix of information for all types of EGO.

Holds defense information, weapon class type, weapon damage information, gift stat bonuses, name, description, special effect description, grade, and max amount craftable.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EquipmentTypeInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EquipmentTypeInfo()

```csharp
public EquipmentTypeInfo()
```

## Fields

### animationNames

```csharp
public string[] animationNames
```
#INC


#### Field Value

**Type:** System.String[]

### armorId

```csharp
public int armorId
```
#INC


#### Field Value

**Type:** System.Int32

### attachPos

```csharp
public string attachPos
```
#INC


#### Field Value

**Type:** System.String

### attachType

```csharp
public EGOgiftAttachType attachType
```
#INC


#### Field Value

**Type:** Global.EGOgiftAttachType

### attackSpeed

```csharp
public float attackSpeed
```
#INC


#### Field Value

**Type:** System.Single

### bonus

```csharp
public EGObonusInfo bonus
```
#INC


#### Field Value

**Type:** Global.EGObonusInfo

### damageInfos

```csharp
public DamageInfo[] damageInfos
```
#INC


#### Field Value

**Type:** Global.DamageInfo[]

### defenseInfo

```csharp
public DefenseInfo defenseInfo
```
#INC


#### Field Value

**Type:** Global.DefenseInfo

### EquipmentTypeInfo.no

```csharp
public string no
```
#INC


#### Field Value

**Type:** System.String

### grade

```csharp
public string grade
```
#INC


#### Field Value

**Type:** System.String

### icon

```csharp
public string icon
```
#INC


#### Field Value

**Type:** System.String

### id

```csharp
public int id
```
#INC


#### Field Value

**Type:** System.Int32

### localizeData

```csharp
public Dictionary<string, string> localizeData
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

### maxNum

```csharp
public int maxNum
```
#INC


#### Field Value

**Type:** System.Int32

### range

```csharp
public float range
```
#INC


#### Field Value

**Type:** System.Single

### requires

```csharp
public List<EgoRequire> requires
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{EgoRequire}

### script

```csharp
public string script
```
#INC


#### Field Value

**Type:** System.String

### specialWeaponAnim

```csharp
public string specialWeaponAnim
```
#INC


#### Field Value

**Type:** System.String

### splashInfo

```csharp
public SplashInfo splashInfo
```
#INC


#### Field Value

**Type:** Global.SplashInfo

### sprite

```csharp
public string sprite
```
#INC


#### Field Value

**Type:** System.String

### type

```csharp
public EquipmentTypeInfo.EquipmentType type
```

#### Field Value

**Type:** Global.EquipmentTypeInfo.EquipmentType

### weaponClassType

```csharp
public WeaponClassType weaponClassType
```
#INC


#### Field Value

**Type:** Global.WeaponClassType

### weaponId

```csharp
public int weaponId
```
#INC


#### Field Value

**Type:** System.Int32

## Properties

### AttachRegion

```csharp
public EGOgiftAttachRegion AttachRegion { get; }
```

#### Property Value

**Type:** Global.EGOgiftAttachRegion

### damageInfo

```csharp
public DamageInfo damageInfo { get; }
```

#### Property Value

**Type:** Global.DamageInfo

### Description

```csharp
public string Description { get; }
```

#### Property Value

**Type:** System.String

### EquipmentTypeInfo.No

```csharp
public string No { get; }
```

#### Property Value

**Type:** System.String

### Grade

```csharp
public RiskLevel Grade { get; }
```

#### Property Value

**Type:** Global.RiskLevel

### MaxNum

```csharp
public int MaxNum { get; }
```

#### Property Value

**Type:** System.Int32

### Name

```csharp
public string Name { get; }
```

#### Property Value

**Type:** System.String

### SpecialDesc

```csharp
public string SpecialDesc { get; }
```

#### Property Value

**Type:** System.String

## Methods

### GetDummyArmorInfo()

```csharp
public static EquipmentTypeInfo GetDummyArmorInfo()
```
#INC


#### Returns

**Type:** Global.EquipmentTypeInfo

### GetDummyGiftInfo()

```csharp
public static EquipmentTypeInfo GetDummyGiftInfo()
```
#INC


#### Returns

**Type:** Global.EquipmentTypeInfo

### GetDummyInfo()

```csharp
public static EquipmentTypeInfo GetDummyInfo()
```
#INC
#code-generated


#### Returns

**Type:** Global.EquipmentTypeInfo

### GetLocalizedText(string, out string)

```csharp
public bool GetLocalizedText(string region, out string output)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `region` | `System.String` |  |
| `output` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### MakeWeaponInfoByDamageInfo(DamageInfo)

```csharp
public static EquipmentTypeInfo MakeWeaponInfoByDamageInfo(DamageInfo dmg)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** Global.EquipmentTypeInfo
