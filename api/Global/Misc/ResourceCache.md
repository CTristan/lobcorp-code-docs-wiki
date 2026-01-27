---
uid: Global.ResourceCache
canonical_path: /api/Global/Misc/ResourceCache
---

# Class ResourceCache

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResourceCache
```
Loads and caches textures, sprites, prefabs, and sprite arrays.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ResourceCache

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ResourceCache()

```csharp
public ResourceCache()
```

## Fields

### _instance

```csharp
private static ResourceCache _instance
```
#INC


#### Field Value

**Type:** Global.ResourceCache

### loadingCount

```csharp
private int loadingCount
```
#INC


#### Field Value

**Type:** System.Int32

### multipleSpriteCache

```csharp
private Dictionary<string, Sprite[]> multipleSpriteCache
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,UnityEngine.Sprite[]}

### prefabCache

```csharp
private Dictionary<string, GameObject> prefabCache
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,UnityEngine.GameObject}

### spriteCache

```csharp
private Dictionary<string, Sprite> spriteCache
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,UnityEngine.Sprite}

### textureCache

```csharp
private Dictionary<string, Texture2D> textureCache
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,UnityEngine.Texture2D}

## Properties

### instance

```csharp
public static ResourceCache instance { get; }
```

#### Property Value

**Type:** Global.ResourceCache

### isLoadingDone

```csharp
public bool isLoadingDone { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### GetMultipleSprite(string)

```csharp
public Sprite[] GetMultipleSprite(string name)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Sprite[]

### GetSprite(string)

```csharp
public Sprite GetSprite(string name)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Sprite

### GetTexture(string)

```csharp
public Texture2D GetTexture(string name)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Texture2D

### Init()

```csharp
private void Init()
```
#INC
#code-generated


### InsertSpriteCache(string, Sprite)

```csharp
public void InsertSpriteCache(string name, Sprite sprite)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `sprite` | `UnityEngine.Sprite` |  |

### InsertSpriteCache(string, Sprite[])

```csharp
public void InsertSpriteCache(string name, Sprite[] sprite)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `sprite` | `UnityEngine.Sprite[]` |  |

### LoadPrefab(string)

```csharp
public GameObject LoadPrefab(string name)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** UnityEngine.GameObject

### LoadSprites(string[], Callback)

```csharp
public IEnumerator LoadSprites(string[] spriteNameList, Callback finishCallback)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spriteNameList` | `System.String[]` |  |
| `finishCallback` | `Global.Callback` |  |

#### Returns

**Type:** System.Collections.IEnumerator
