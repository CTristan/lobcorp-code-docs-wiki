---
uid: Spine.SkeletonJson
canonical_path: /api/Spine/SkeletonJson
---

# Class SkeletonJson

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkeletonJson
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkeletonJson

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SkeletonJson(AttachmentLoader)

```csharp
public SkeletonJson(AttachmentLoader attachmentLoader)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attachmentLoader` | `Spine.AttachmentLoader` |  |

### SkeletonJson(params Atlas[])

```csharp
public SkeletonJson(params Atlas[] atlasArray)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `atlasArray` | `Spine.Atlas[]` |  |

## Fields

### attachmentLoader

```csharp
private AttachmentLoader attachmentLoader
```

#### Field Value

**Type:** Spine.AttachmentLoader

### linkedMeshes

```csharp
private List<SkeletonJson.LinkedMesh> linkedMeshes
```

#### Field Value

**Type:** System.Collections.Generic.List{Spine.SkeletonJson.LinkedMesh}

## Properties

### Scale

```csharp
public float Scale { get; set; }
```

#### Property Value

**Type:** System.Single

## Methods

### GetBoolean(Dictionary<string, object>, string, bool)

```csharp
private static bool GetBoolean(Dictionary<string, object> map, string name, bool defaultValue)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `map` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `name` | `System.String` |  |
| `defaultValue` | `System.Boolean` |  |

#### Returns

**Type:** System.Boolean

### GetFloat(Dictionary<string, object>, string, float)

```csharp
private static float GetFloat(Dictionary<string, object> map, string name, float defaultValue)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `map` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `name` | `System.String` |  |
| `defaultValue` | `System.Single` |  |

#### Returns

**Type:** System.Single

### GetFloatArray(Dictionary<string, object>, string, float)

```csharp
private static float[] GetFloatArray(Dictionary<string, object> map, string name, float scale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `map` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `name` | `System.String` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** System.Single[]

### GetInt(Dictionary<string, object>, string, int)

```csharp
private static int GetInt(Dictionary<string, object> map, string name, int defaultValue)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `map` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `name` | `System.String` |  |
| `defaultValue` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### GetIntArray(Dictionary<string, object>, string)

```csharp
private static int[] GetIntArray(Dictionary<string, object> map, string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `map` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `name` | `System.String` |  |

#### Returns

**Type:** System.Int32[]

### GetString(Dictionary<string, object>, string, string)

```csharp
private static string GetString(Dictionary<string, object> map, string name, string defaultValue)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `map` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `name` | `System.String` |  |
| `defaultValue` | `System.String` |  |

#### Returns

**Type:** System.String

### ReadAnimation(Dictionary<string, object>, string, SkeletonData)

```csharp
private void ReadAnimation(Dictionary<string, object> map, string name, SkeletonData skeletonData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `map` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `name` | `System.String` |  |
| `skeletonData` | `Spine.SkeletonData` |  |

### ReadAnimation_new(Dictionary<string, object>, string, SkeletonData)

```csharp
private void ReadAnimation_new(Dictionary<string, object> map, string name, SkeletonData skeletonData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `map` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `name` | `System.String` |  |
| `skeletonData` | `Spine.SkeletonData` |  |

### ReadAttachment(Dictionary<string, object>, Skin, int, string, SkeletonData)

```csharp
private Attachment ReadAttachment(Dictionary<string, object> map, Skin skin, int slotIndex, string name, SkeletonData skeletonData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `map` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `skin` | `Spine.Skin` |  |
| `slotIndex` | `System.Int32` |  |
| `name` | `System.String` |  |
| `skeletonData` | `Spine.SkeletonData` |  |

#### Returns

**Type:** Spine.Attachment

### ReadAttachment_new(Dictionary<string, object>, Skin, int, string, SkeletonData)

```csharp
private Attachment ReadAttachment_new(Dictionary<string, object> map, Skin skin, int slotIndex, string name, SkeletonData skeletonData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `map` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `skin` | `Spine.Skin` |  |
| `slotIndex` | `System.Int32` |  |
| `name` | `System.String` |  |
| `skeletonData` | `Spine.SkeletonData` |  |

#### Returns

**Type:** Spine.Attachment

### ReadCurve(Dictionary<string, object>, CurveTimeline, int)

```csharp
private static void ReadCurve(Dictionary<string, object> valueMap, CurveTimeline timeline, int frameIndex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `valueMap` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `timeline` | `Spine.CurveTimeline` |  |
| `frameIndex` | `System.Int32` |  |

### ReadSkeletonData(string)

```csharp
public SkeletonData ReadSkeletonData(string path)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `path` | `System.String` |  |

#### Returns

**Type:** Spine.SkeletonData

### ReadSkeletonData(TextReader)

```csharp
public SkeletonData ReadSkeletonData(TextReader reader)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `reader` | `System.IO.TextReader` |  |

#### Returns

**Type:** Spine.SkeletonData

### ReadVertices(Dictionary<string, object>, VertexAttachment, int)

```csharp
private void ReadVertices(Dictionary<string, object> map, VertexAttachment attachment, int verticesLength)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `map` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |
| `attachment` | `Spine.VertexAttachment` |  |
| `verticesLength` | `System.Int32` |  |

### ToColor(string, int, int)

```csharp
private static float ToColor(string hexString, int colorIndex, int expectedLength = 8)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `hexString` | `System.String` |  |
| `colorIndex` | `System.Int32` |  |
| `expectedLength` | `System.Int32` |  |

#### Returns

**Type:** System.Single
