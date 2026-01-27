---
uid: WorkerSprite.AtlasLoadData
canonical_path: /api/WorkerSprite/AtlasLoadData
---

# Class AtlasLoadData

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AtlasLoadData : SpriteResourceLoadData
```

Information for loading from an Atlas (aka sprite sheet)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SpriteResourceLoadData](/api/WorkerSprite/SpriteResourceLoadData) → AtlasLoadData

## Inherited Members
[src](/api/WorkerSprite/SpriteResourceLoadData#src), [id](/api/WorkerSprite/SpriteResourceLoadData#id), [type](/api/WorkerSprite/SpriteResourceLoadData#type), [count](/api/WorkerSprite/SpriteResourceLoadData#count), [isCustom](/api/WorkerSprite/SpriteResourceLoadData#iscustom), [isCredit](/api/WorkerSprite/SpriteResourceLoadData#iscredit), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AtlasLoadData()

```csharp
public AtlasLoadData()
```
#INC


## Fields

### sprites

```csharp
public List<Sprite> sprites
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Sprite}

## Properties

### Count

```csharp
public int Count { get; }
```

#### Property Value

**Type:** System.Int32

## Methods

### GetRandomSprite()

```csharp
public override Sprite GetRandomSprite()
```
#INC


#### Returns

**Type:** UnityEngine.Sprite

### GetSprite(int)

```csharp
public override Sprite GetSprite(int index)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns

**Type:** UnityEngine.Sprite

### LoadSprite()

```csharp
public override void LoadSprite()
```
#INC
#code-generated

