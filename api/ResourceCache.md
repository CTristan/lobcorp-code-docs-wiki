# Class ResourceCache

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResourceCache
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ResourceCache

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### ResourceCache()

```csharp
public ResourceCache()
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** UnityEngine.Texture2D

### InsertSpriteCache(string, Sprite)

```csharp
public void InsertSpriteCache(string name, Sprite sprite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `sprite` | `UnityEngine.Sprite` |  |

### InsertSpriteCache(string, Sprite[])

```csharp
public void InsertSpriteCache(string name, Sprite[] sprite)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `sprite` | `UnityEngine.Sprite[]` |  |

### LoadPrefab(string)

```csharp
public GameObject LoadPrefab(string name)
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `spriteNameList` | `System.String[]` |  |
| `finishCallback` | `Global.Callback` |  |

#### Returns

**Type:** System.Collections.IEnumerator
