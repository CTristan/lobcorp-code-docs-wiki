---
uid: WorkerSprite.WorkerBasicSprite
canonical_path: /api/WorkerSprite/WorkerBasicSprite
---

# Class WorkerBasicSprite

**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerBasicSprite
```
Worker facial sprite...?

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerBasicSprite

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### WorkerBasicSprite()

```csharp
public WorkerBasicSprite()
```

## Fields

### all

```csharp
private List<Sprite> all
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{UnityEngine.Sprite}

### data

```csharp
private List<WorkerBasicSprite.ResourceData> data
```

#### Field Value

**Type:** System.Collections.Generic.List{WorkerSprite.WorkerBasicSprite.ResourceData}

### loadedData

```csharp
public List<SpriteResourceLoadData> loadedData
```
#INC


#### Field Value

**Type:** System.Collections.Generic.List{WorkerSprite.SpriteResourceLoadData}

### subRegion

```csharp
public BasicSpriteRegion subRegion
```
#INC


#### Field Value

**Type:** WorkerSprite.BasicSpriteRegion

## Methods

### GetAllSprites()

```csharp
public List<Sprite> GetAllSprites()
```
#INC


#### Returns

**Type:** System.Collections.Generic.List{UnityEngine.Sprite}

### GetData(long)

```csharp
public SpriteResourceLoadData GetData(long id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns

**Type:** WorkerSprite.SpriteResourceLoadData

### GetLastId()

```csharp
public int GetLastId()
```
#INC
#code-generated


#### Returns

**Type:** System.Int32

### GetRandomData(bool)

```csharp
public SpriteResourceLoadData GetRandomData(bool containCustom = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `containCustom` | `System.Boolean` |  |

#### Returns

**Type:** WorkerSprite.SpriteResourceLoadData

### GetRandomDataWithExclude(List<int>, bool)

```csharp
public SpriteResourceLoadData GetRandomDataWithExclude(List<int> excludeIds, bool containCustom = false)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `excludeIds` | `System.Collections.Generic.List{System.Int32}` |  |
| `containCustom` | `System.Boolean` |  |

#### Returns

**Type:** WorkerSprite.SpriteResourceLoadData

### GetResourceData(Sprite)

```csharp
public WorkerBasicSprite.ResourceData GetResourceData(Sprite sprite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sprite` | `UnityEngine.Sprite` |  |

#### Returns

**Type:** WorkerSprite.WorkerBasicSprite.ResourceData

### GetUniqueCustomData()

```csharp
public SpriteResourceLoadData GetUniqueCustomData()
```
#INC


#### Returns

**Type:** WorkerSprite.SpriteResourceLoadData
