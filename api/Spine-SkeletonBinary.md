# Class SkeletonBinary

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkeletonBinary
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkeletonBinary

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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
