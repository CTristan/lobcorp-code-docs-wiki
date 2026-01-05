# Class EquipmentTypeInfo

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EquipmentTypeInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EquipmentTypeInfo

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

#### Field Value

**Type:** System.String[]

### armorId

```csharp
public int armorId
```

#### Field Value

**Type:** System.Int32

### attachPos

```csharp
public string attachPos
```

#### Field Value

**Type:** System.String

### attachType

```csharp
public EGOgiftAttachType attachType
```

#### Field Value

**Type:** Global.EGOgiftAttachType

### attackSpeed

```csharp
public float attackSpeed
```

#### Field Value

**Type:** System.Single

### bonus

```csharp
public EGObonusInfo bonus
```

#### Field Value

**Type:** Global.EGObonusInfo

### damageInfos

```csharp
public DamageInfo[] damageInfos
```

#### Field Value

**Type:** Global.DamageInfo[]

### defenseInfo

```csharp
public DefenseInfo defenseInfo
```

#### Field Value

**Type:** Global.DefenseInfo

### EquipmentTypeInfo.no

```csharp
public string no
```

#### Field Value

**Type:** System.String

### grade

```csharp
public string grade
```

#### Field Value

**Type:** System.String

### icon

```csharp
public string icon
```

#### Field Value

**Type:** System.String

### id

```csharp
public int id
```

#### Field Value

**Type:** System.Int32

### localizeData

```csharp
public Dictionary<string, string> localizeData
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

### maxNum

```csharp
public int maxNum
```

#### Field Value

**Type:** System.Int32

### range

```csharp
public float range
```

#### Field Value

**Type:** System.Single

### requires

```csharp
public List<EgoRequire> requires
```

#### Field Value

**Type:** System.Collections.Generic.List{EgoRequire}

### script

```csharp
public string script
```

#### Field Value

**Type:** System.String

### specialWeaponAnim

```csharp
public string specialWeaponAnim
```

#### Field Value

**Type:** System.String

### splashInfo

```csharp
public SplashInfo splashInfo
```

#### Field Value

**Type:** Global.SplashInfo

### sprite

```csharp
public string sprite
```

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

#### Field Value

**Type:** Global.WeaponClassType

### weaponId

```csharp
public int weaponId
```

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

#### Returns

**Type:** Global.EquipmentTypeInfo

### GetDummyGiftInfo()

```csharp
public static EquipmentTypeInfo GetDummyGiftInfo()
```

#### Returns

**Type:** Global.EquipmentTypeInfo

### GetDummyInfo()

```csharp
public static EquipmentTypeInfo GetDummyInfo()
```

#### Returns

**Type:** Global.EquipmentTypeInfo

### GetLocalizedText(string, out string)

```csharp
public bool GetLocalizedText(string region, out string output)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dmg` | `Global.DamageInfo` |  |

#### Returns

**Type:** Global.EquipmentTypeInfo
