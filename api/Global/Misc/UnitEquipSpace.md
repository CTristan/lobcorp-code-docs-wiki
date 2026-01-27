---
uid: Global.UnitEquipSpace
canonical_path: /api/Global/Misc/UnitEquipSpace
---

# Class UnitEquipSpace

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnitEquipSpace
```
Holds and manages the equipment of a [unit](/api/Global/Model/UnitModel).

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → UnitEquipSpace

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### UnitEquipSpace()

```csharp
public UnitEquipSpace()
```

## Fields

### armor

```csharp
public ArmorModel armor
```
#INC


#### Field Value

**Type:** Global.ArmorModel

### gifts

```csharp
public UnitEGOgiftSpace gifts
```
#INC


#### Field Value

**Type:** Global.UnitEGOgiftSpace

### kitCreature

```csharp
public CreatureModel kitCreature
```
#INC


#### Field Value

**Type:** Global.CreatureModel

### weapon

```csharp
public WeaponModel weapon
```
#INC


#### Field Value

**Type:** Global.WeaponModel

## Methods

### GetBonus(UnitModel)

```csharp
public EGObonusInfo GetBonus(UnitModel actor)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

#### Returns

**Type:** Global.EGObonusInfo

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
