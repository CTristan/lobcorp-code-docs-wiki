---
uid: Global.CreatureSpecialDamageTable
canonical_path: /api/Global/Misc/CreatureSpecialDamageTable
---

# Class CreatureSpecialDamageTable

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureSpecialDamageTable
```
Holds the damage values of abnormality damage outside of work damage (e.g., breaching attack damages). Only used by some abnormalities:
- [Big and Will be Bad Wolf](/api/Global/IOBserver/BigBadWolf)
- [Fragment of the Universe](/api/Global/Misc/Cosmos)
- [Laetitia's friend](/api/Global/Misc/LittleWitchMonster)
- [Green Dawn](/api/Global/Machine/MachineDawn)
- [Little Red Riding Hooded Mercenary](/api/Global/IOBserver/RedHood)
- [The Silent Orchestra](/api/Global/Misc/SilentOrchestra)
- [Forsaken Murderer](/api/Global/Misc/StraitJacket)



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureSpecialDamageTable

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CreatureSpecialDamageTable()

```csharp
public CreatureSpecialDamageTable()
```

## Fields

### _specialWeaponInfos

```csharp
private Dictionary<string, EquipmentTypeInfo> _specialWeaponInfos
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,EquipmentTypeInfo}

## Methods

### GetList()

```csharp
public List<DamageInfo> GetList()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{DamageInfo}

### GetSpecialDamage(string)

```csharp
public DamageInfo GetSpecialDamage(string id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns

**Type:** Global.DamageInfo

### GetSpecialWeapon(string)

```csharp
public EquipmentTypeInfo GetSpecialWeapon(string id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns

**Type:** Global.EquipmentTypeInfo

### Init(Dictionary<string, EquipmentTypeInfo>)

```csharp
public void Init(Dictionary<string, EquipmentTypeInfo> infos)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `infos` | `System.Collections.Generic.Dictionary{System.String,EquipmentTypeInfo}` |  |
