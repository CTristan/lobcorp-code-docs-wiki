---
uid: WorkerSprite.WorkerClothesSprite
canonical_path: /api/WorkerSprite/WorkerClothesSprite
---

# Class WorkerClothesSprite

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerClothesSprite : WorkerEquipmentSprite
```

Map between int and sprite resource data?

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [WorkerEquipmentSprite](/api/WorkerSprite/WorkerEquipmentSprite) → WorkerClothesSprite

## Inherited Members
[subRegion](/api/WorkerSprite/WorkerEquipmentSprite#subregion), [loadedData](/api/WorkerSprite/WorkerEquipmentSprite#loadeddata), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerClothesSprite()

```csharp
public WorkerClothesSprite()
```

## Fields

### lib

```csharp
public Dictionary<int, SpriteResourceLoadData> lib
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.Int32,WorkerSprite.SpriteResourceLoadData}

## Methods

### GetData(int)

```csharp
public SpriteResourceLoadData GetData(int id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

#### Returns

**Type:** WorkerSprite.SpriteResourceLoadData

### Init()

```csharp
public void Init()
```
#INC
#code-generated

