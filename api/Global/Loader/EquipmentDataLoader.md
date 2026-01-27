---
uid: Global.EquipmentDataLoader
canonical_path: /api/Global/Loader/EquipmentDataLoader
---

# Class EquipmentDataLoader

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class EquipmentDataLoader
```
Class which loads static data about [EGO](/api/Global/Model/EquipmentModel).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EquipmentDataLoader

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### EquipmentDataLoader()

```csharp
public EquipmentDataLoader()
```

## Methods

### CheckNamedDir(DirectoryInfo, string)

```csharp
public static DirectoryInfo CheckNamedDir(DirectoryInfo dir, string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `dir` | `System.IO.DirectoryInfo` |  |
| `name` | `System.String` |  |

#### Returns

**Type:** System.IO.DirectoryInfo

### ConvertToDamageInfo(XmlNode)

```csharp
public static DamageInfo ConvertToDamageInfo(XmlNode damageNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damageNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.DamageInfo

### ConvertToRWBP(string)

```csharp
public static RwbpType ConvertToRWBP(string text)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

#### Returns

**Type:** Global.RwbpType

### ConvertToWeaponClassType(string)

```csharp
public static WeaponClassType ConvertToWeaponClassType(string text)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |

#### Returns

**Type:** Global.WeaponClassType

### Load()

```csharp
public void Load()
```
#INC
#code-generated


### LoadArmor(EquipmentTypeInfo, XmlNode)

```csharp
public EquipmentTypeInfo LoadArmor(EquipmentTypeInfo info, XmlNode equipNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |
| `equipNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.EquipmentTypeInfo

### LoadEGOgift(EquipmentTypeInfo, XmlNode)

```csharp
public void LoadEGOgift(EquipmentTypeInfo info, XmlNode equipNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |
| `equipNode` | `System.Xml.XmlNode` |  |

### LoadEquips(XmlDocument)

```csharp
public Dictionary<int, EquipmentTypeInfo> LoadEquips(XmlDocument document)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `document` | `System.Xml.XmlDocument` |  |

#### Returns

**Type:** System.Collections.Generic.Dictionary{System.Int32,EquipmentTypeInfo}

### LoadWeapon(EquipmentTypeInfo, XmlNode)

```csharp
public EquipmentTypeInfo LoadWeapon(EquipmentTypeInfo info, XmlNode equipNode)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |
| `equipNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.EquipmentTypeInfo
