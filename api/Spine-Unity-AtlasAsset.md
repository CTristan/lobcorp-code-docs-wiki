# Class AtlasAsset

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine-Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AtlasAsset : ScriptableObject
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [ScriptableObject](#) → AtlasAsset

## Inherited Members
[SetDirty()](#), [CreateInstance(string)](https://learn.microsoft.com/dotnet/api/system.string), [CreateInstance(Type)](https://learn.microsoft.com/dotnet/api/system.type), [CreateInstance<T>()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### AtlasAsset()

```csharp
public AtlasAsset()
```

## Fields

### atlas

```csharp
protected Atlas atlas
```

#### Field Value

**Type:** Spine.Atlas

### atlasFile

```csharp
public TextAsset atlasFile
```

#### Field Value

**Type:** UnityEngine.TextAsset

### atlasFile_string

```csharp
public string atlasFile_string
```

#### Field Value

**Type:** System.String

### materials

```csharp
public Material[] materials
```

#### Field Value

**Type:** UnityEngine.Material[]

## Properties

### IsLoaded

```csharp
public bool IsLoaded { get; }
```

#### Property Value

**Type:** System.Boolean

## Methods

### Clear()

```csharp
public virtual void Clear()
```

### CreateRuntimeInstance(string, Material[], bool)

```csharp
public static AtlasAsset CreateRuntimeInstance(string atlasText, Material[] materials, bool initialize)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `atlasText` | `System.String` |  |
| `materials` | `UnityEngine.Material[]` |  |
| `initialize` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Unity.AtlasAsset

### CreateRuntimeInstance(string, Texture2D[], Material, bool)

```csharp
public static AtlasAsset CreateRuntimeInstance(string atlasText, Texture2D[] textures, Material materialPropertySource, bool initialize)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `atlasText` | `System.String` |  |
| `textures` | `UnityEngine.Texture2D[]` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |
| `initialize` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Unity.AtlasAsset

### CreateRuntimeInstance(string, Texture2D[], Shader, bool)

```csharp
public static AtlasAsset CreateRuntimeInstance(string atlasText, Texture2D[] textures, Shader shader, bool initialize)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `atlasText` | `System.String` |  |
| `textures` | `UnityEngine.Texture2D[]` |  |
| `shader` | `UnityEngine.Shader` |  |
| `initialize` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Unity.AtlasAsset

### CreateRuntimeInstance(TextAsset, Material[], bool)

```csharp
public static AtlasAsset CreateRuntimeInstance(TextAsset atlasText, Material[] materials, bool initialize)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `atlasText` | `UnityEngine.TextAsset` |  |
| `materials` | `UnityEngine.Material[]` |  |
| `initialize` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Unity.AtlasAsset

### CreateRuntimeInstance(TextAsset, Texture2D[], Material, bool)

```csharp
public static AtlasAsset CreateRuntimeInstance(TextAsset atlasText, Texture2D[] textures, Material materialPropertySource, bool initialize)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `atlasText` | `UnityEngine.TextAsset` |  |
| `textures` | `UnityEngine.Texture2D[]` |  |
| `materialPropertySource` | `UnityEngine.Material` |  |
| `initialize` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Unity.AtlasAsset

### CreateRuntimeInstance(TextAsset, Texture2D[], Shader, bool)

```csharp
public static AtlasAsset CreateRuntimeInstance(TextAsset atlasText, Texture2D[] textures, Shader shader, bool initialize)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `atlasText` | `UnityEngine.TextAsset` |  |
| `textures` | `UnityEngine.Texture2D[]` |  |
| `shader` | `UnityEngine.Shader` |  |
| `initialize` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Unity.AtlasAsset

### GenerateMesh(string, Mesh, out Material, float)

```csharp
public Mesh GenerateMesh(string name, Mesh mesh, out Material material, float scale = 0.01)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `mesh` | `UnityEngine.Mesh` |  |
| `material` | `UnityEngine.Material` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** UnityEngine.Mesh

### GetAtlas()

```csharp
public virtual Atlas GetAtlas()
```

#### Returns

**Type:** Spine.Atlas

### GetAtlas_string()

```csharp
public virtual Atlas GetAtlas_string()
```

#### Returns

**Type:** Spine.Atlas
