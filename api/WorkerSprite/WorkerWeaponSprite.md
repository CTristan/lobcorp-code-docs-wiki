---
uid: WorkerSprite.WorkerWeaponSprite
canonical_path: /api/WorkerSprite/WorkerWeaponSprite
---

# Class WorkerWeaponSprite

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerWeaponSprite : WorkerEquipmentSprite
```

Has a list of weapons and the associated sprites, and methods for grabbing them


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [WorkerEquipmentSprite](/api/WorkerSprite/WorkerEquipmentSprite) → WorkerWeaponSprite

## Inherited Members
[subRegion](/api/WorkerSprite/WorkerEquipmentSprite#subregion), [loadedData](/api/WorkerSprite/WorkerEquipmentSprite#loadeddata), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerWeaponSprite()

```csharp
public WorkerWeaponSprite()
```

## Fields

### database

```csharp
public Dictionary<int, WorkerWeaponSprite.WeaponDatabase> database
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,WorkerSprite.WorkerWeaponSprite.WeaponDatabase}

### lib

```csharp
public Dictionary<int, List<SpriteResourceLoadData>> lib
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.List{WorkerSprite.SpriteResourceLoadData}}

## Methods

### GetData(int)

```csharp
public List<SpriteResourceLoadData> GetData(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** System.Collections.Generic.List{WorkerSprite.SpriteResourceLoadData}

### GetDb(int)

```csharp
public WorkerWeaponSprite.WeaponDatabase GetDb(int id)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** WorkerSprite.WorkerWeaponSprite.WeaponDatabase

### Init()

```csharp
public void Init()
```
#INC
#code-generated

