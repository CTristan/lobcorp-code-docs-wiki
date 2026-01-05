# Class RegionAttachment

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RegionAttachment : Attachment
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Attachment](/api/Spine-Attachment) → RegionAttachment

## Inherited Members
[ToString()](/api/Spine-Attachment#tostring), [Name](/api/Spine-Attachment#name), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### RegionAttachment(string)

```csharp
public RegionAttachment(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

## Fields

### BLX

```csharp
public const int BLX = 0
```

#### Field Value

**Type:** System.Int32

### BLY

```csharp
public const int BLY = 1
```

#### Field Value

**Type:** System.Int32

### BRX

```csharp
public const int BRX = 6
```

#### Field Value

**Type:** System.Int32

### BRY

```csharp
public const int BRY = 7
```

#### Field Value

**Type:** System.Int32

### RendererObject

```csharp
public object RendererObject
```

#### Field Value

**Type:** System.Object

### ULX

```csharp
public const int ULX = 2
```

#### Field Value

**Type:** System.Int32

### ULY

```csharp
public const int ULY = 3
```

#### Field Value

**Type:** System.Int32

### URX

```csharp
public const int URX = 4
```

#### Field Value

**Type:** System.Int32

### URY

```csharp
public const int URY = 5
```

#### Field Value

**Type:** System.Int32

## Properties

### A

```csharp
public float A { get; set; }
```

#### Property Value

**Type:** System.Single

### B

```csharp
public float B { get; set; }
```

#### Property Value

**Type:** System.Single

### G

```csharp
public float G { get; set; }
```

#### Property Value

**Type:** System.Single

### Height

```csharp
public float Height { get; set; }
```

#### Property Value

**Type:** System.Single

### Offset

```csharp
public float[] Offset { get; }
```

#### Property Value

**Type:** System.Single[]

### Path

```csharp
public string Path { get; set; }
```

#### Property Value

**Type:** System.String

### R

```csharp
public float R { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionHeight

```csharp
public float RegionHeight { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionOffsetX

```csharp
public float RegionOffsetX { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionOffsetY

```csharp
public float RegionOffsetY { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionOriginalHeight

```csharp
public float RegionOriginalHeight { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionOriginalWidth

```csharp
public float RegionOriginalWidth { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionWidth

```csharp
public float RegionWidth { get; set; }
```

#### Property Value

**Type:** System.Single

### Rotation

```csharp
public float Rotation { get; set; }
```

#### Property Value

**Type:** System.Single

### ScaleX

```csharp
public float ScaleX { get; set; }
```

#### Property Value

**Type:** System.Single

### ScaleY

```csharp
public float ScaleY { get; set; }
```

#### Property Value

**Type:** System.Single

### UVs

```csharp
public float[] UVs { get; }
```

#### Property Value

**Type:** System.Single[]

### Width

```csharp
public float Width { get; set; }
```

#### Property Value

**Type:** System.Single

### X

```csharp
public float X { get; set; }
```

#### Property Value

**Type:** System.Single

### Y

```csharp
public float Y { get; set; }
```

#### Property Value

**Type:** System.Single

## Methods

### ComputeWorldVertices(Bone, float[], int, int)

```csharp
public void ComputeWorldVertices(Bone bone, float[] worldVertices, int offset, int stride = 2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `worldVertices` | `System.Single[]` |  |
| `offset` | `System.Int32` |  |
| `stride` | `System.Int32` |  |

### SetUVs(float, float, float, float, bool)

```csharp
public void SetUVs(float u, float v, float u2, float v2, bool rotate)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `u` | `System.Single` |  |
| `v` | `System.Single` |  |
| `u2` | `System.Single` |  |
| `v2` | `System.Single` |  |
| `rotate` | `System.Boolean` |  |

### UpdateOffset()

```csharp
public void UpdateOffset()
```
