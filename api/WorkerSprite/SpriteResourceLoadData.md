---
uid: WorkerSprite.SpriteResourceLoadData
canonical_path: /api/WorkerSprite/SpriteResourceLoadData
---

# Class SpriteResourceLoadData

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpriteResourceLoadData
```
Information required to find and load a sprite resource


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SpriteResourceLoadData

## Derived
[AtlasLoadData](/api/WorkerSprite/AtlasLoadData), [SpriteLoadData](/api/WorkerSprite/SpriteLoadData)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SpriteResourceLoadData()

```csharp
public SpriteResourceLoadData()
```

## Fields

### count

```csharp
public int count
```
#INC


#### Field Value

**Type:** System.Int32

### id

```csharp
public int id
```
#INC


#### Field Value

**Type:** System.Int32

### isCredit

```csharp
public bool isCredit
```
#INC


#### Field Value

**Type:** System.Boolean

### isCustom

```csharp
public bool isCustom
```
#INC


#### Field Value

**Type:** System.Boolean

### src

```csharp
public string src
```
#INC


#### Field Value

**Type:** System.String

### type

```csharp
public SpriteResourceType type
```
#INC


#### Field Value

**Type:** WorkerSprite.SpriteResourceType

## Methods

### GetRandomSprite()

```csharp
public virtual Sprite GetRandomSprite()
```
#INC


#### Returns

**Type:** UnityEngine.Sprite

### GetSprite(int)

```csharp
public virtual Sprite GetSprite(int index)
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
public virtual void LoadSprite()
```
#INC
#code-generated

