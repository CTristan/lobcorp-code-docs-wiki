---
uid: Spine.SkeletonBinary
canonical_path: /api/Spine/SkeletonBinary
---

# Class SkeletonBinary

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkeletonBinary
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkeletonBinary

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### SkeletonBinary(AttachmentLoader)

```csharp
public SkeletonBinary(AttachmentLoader attachmentLoader)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `attachmentLoader` | `Spine.AttachmentLoader` |  |

### SkeletonBinary(params Atlas[])

```csharp
public SkeletonBinary(params Atlas[] atlasArray)
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

### BONE_ROTATE

```csharp
public const int BONE_ROTATE = 0
```

#### Field Value

**Type:** System.Int32

### BONE_SCALE

```csharp
public const int BONE_SCALE = 2
```

#### Field Value

**Type:** System.Int32

### BONE_SHEAR

```csharp
public const int BONE_SHEAR = 3
```

#### Field Value

**Type:** System.Int32

### BONE_TRANSLATE

```csharp
public const int BONE_TRANSLATE = 1
```

#### Field Value

**Type:** System.Int32

### buffer

```csharp
private byte[] buffer
```

#### Field Value

**Type:** System.Byte[]

### CURVE_BEZIER

```csharp
public const int CURVE_BEZIER = 2
```

#### Field Value

**Type:** System.Int32

### CURVE_LINEAR

```csharp
public const int CURVE_LINEAR = 0
```

#### Field Value

**Type:** System.Int32

### CURVE_STEPPED

```csharp
public const int CURVE_STEPPED = 1
```

#### Field Value

**Type:** System.Int32

### linkedMeshes

```csharp
private List<SkeletonJson.LinkedMesh> linkedMeshes
```

#### Field Value

**Type:** System.Collections.Generic.List{Spine.SkeletonJson.LinkedMesh}

### PATH_MIX

```csharp
public const int PATH_MIX = 2
```

#### Field Value

**Type:** System.Int32

### PATH_POSITION

```csharp
public const int PATH_POSITION = 0
```

#### Field Value

**Type:** System.Int32

### PATH_SPACING

```csharp
public const int PATH_SPACING = 1
```

#### Field Value

**Type:** System.Int32

### SLOT_ATTACHMENT

```csharp
public const int SLOT_ATTACHMENT = 0
```

#### Field Value

**Type:** System.Int32

### SLOT_COLOR

```csharp
public const int SLOT_COLOR = 1
```

#### Field Value

**Type:** System.Int32

### SLOT_TWO_COLOR

```csharp
public const int SLOT_TWO_COLOR = 2
```

#### Field Value

**Type:** System.Int32

### TransformModeValues

```csharp
public static readonly TransformMode[] TransformModeValues
```

#### Field Value

**Type:** Spine.TransformMode[]

## Properties

### Scale

```csharp
public float Scale { get; set; }
```

#### Property Value

**Type:** System.Single

## Methods

### GetVersionString(Stream)

```csharp
public static string GetVersionString(Stream input)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |

#### Returns

**Type:** System.String

### ReadAnimation(string, Stream, SkeletonData)

```csharp
private void ReadAnimation(string name, Stream input, SkeletonData skeletonData)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `input` | `System.IO.Stream` |  |
| `skeletonData` | `Spine.SkeletonData` |  |

### ReadAttachment(Stream, SkeletonData, Skin, int, string, bool)

```csharp
private Attachment ReadAttachment(Stream input, SkeletonData skeletonData, Skin skin, int slotIndex, string attachmentName, bool nonessential)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |
| `skeletonData` | `Spine.SkeletonData` |  |
| `skin` | `Spine.Skin` |  |
| `slotIndex` | `System.Int32` |  |
| `attachmentName` | `System.String` |  |
| `nonessential` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Attachment

### ReadBoolean(Stream)

```csharp
private static bool ReadBoolean(Stream input)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |

#### Returns

**Type:** System.Boolean

### ReadCurve(Stream, int, CurveTimeline)

```csharp
private void ReadCurve(Stream input, int frameIndex, CurveTimeline timeline)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |
| `frameIndex` | `System.Int32` |  |
| `timeline` | `Spine.CurveTimeline` |  |

### ReadFloat(Stream)

```csharp
private float ReadFloat(Stream input)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |

#### Returns

**Type:** System.Single

### ReadFloatArray(Stream, int, float)

```csharp
private float[] ReadFloatArray(Stream input, int n, float scale)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |
| `n` | `System.Int32` |  |
| `scale` | `System.Single` |  |

#### Returns

**Type:** System.Single[]

### ReadFully(Stream, byte[], int, int)

```csharp
private static void ReadFully(Stream input, byte[] buffer, int offset, int length)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |
| `buffer` | `System.Byte[]` |  |
| `offset` | `System.Int32` |  |
| `length` | `System.Int32` |  |

### ReadInt(Stream)

```csharp
private static int ReadInt(Stream input)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |

#### Returns

**Type:** System.Int32

### ReadSByte(Stream)

```csharp
private static sbyte ReadSByte(Stream input)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |

#### Returns

**Type:** System.SByte

### ReadShortArray(Stream)

```csharp
private int[] ReadShortArray(Stream input)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |

#### Returns

**Type:** System.Int32[]

### ReadSkeletonData(Stream)

```csharp
public SkeletonData ReadSkeletonData(Stream input)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |

#### Returns

**Type:** Spine.SkeletonData

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

### ReadSkin(Stream, SkeletonData, string, bool)

```csharp
private Skin ReadSkin(Stream input, SkeletonData skeletonData, string skinName, bool nonessential)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |
| `skeletonData` | `Spine.SkeletonData` |  |
| `skinName` | `System.String` |  |
| `nonessential` | `System.Boolean` |  |

#### Returns

**Type:** Spine.Skin

### ReadString(Stream)

```csharp
private string ReadString(Stream input)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |

#### Returns

**Type:** System.String

### ReadVarint(Stream, bool)

```csharp
private static int ReadVarint(Stream input, bool optimizePositive)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |
| `optimizePositive` | `System.Boolean` |  |

#### Returns

**Type:** System.Int32

### ReadVertices(Stream, int)

```csharp
private SkeletonBinary.Vertices ReadVertices(Stream input, int vertexCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `input` | `System.IO.Stream` |  |
| `vertexCount` | `System.Int32` |  |

#### Returns

**Type:** Spine.SkeletonBinary.Vertices
