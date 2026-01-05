# Class MeshAttachment

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MeshAttachment : VertexAttachment
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Attachment](/api/Spine-Attachment) → [VertexAttachment](/api/Spine-VertexAttachment) → MeshAttachment

## Inherited Members
[ComputeWorldVertices(Slot, float[])](/api/Spine-VertexAttachment#computeworldvertices-slot-float), [ComputeWorldVertices(Slot, int, int, float[], int, int)](/api/Spine-VertexAttachment#computeworldvertices-slot-int-int-float-int-int), [Id](/api/Spine-VertexAttachment#id), [Bones](/api/Spine-VertexAttachment#bones), [Vertices](/api/Spine-VertexAttachment#vertices), [WorldVerticesLength](/api/Spine-VertexAttachment#worldverticeslength), [ToString()](/api/Spine-Attachment#tostring), [Name](/api/Spine-Attachment#name), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### MeshAttachment(string)

```csharp
public MeshAttachment(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

## Fields

### RendererObject

```csharp
public object RendererObject
```

#### Field Value

**Type:** System.Object

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

### Edges

```csharp
public int[] Edges { get; set; }
```

#### Property Value

**Type:** System.Int32[]

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

### HullLength

```csharp
public int HullLength { get; set; }
```

#### Property Value

**Type:** System.Int32

### InheritDeform

```csharp
public bool InheritDeform { get; set; }
```

#### Property Value

**Type:** System.Boolean

### ParentMesh

```csharp
public MeshAttachment ParentMesh { get; set; }
```

#### Property Value

**Type:** Spine.MeshAttachment

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

### RegionRotate

```csharp
public bool RegionRotate { get; set; }
```

#### Property Value

**Type:** System.Boolean

### RegionU

```csharp
public float RegionU { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionU2

```csharp
public float RegionU2 { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionUVs

```csharp
public float[] RegionUVs { get; set; }
```

#### Property Value

**Type:** System.Single[]

### RegionV

```csharp
public float RegionV { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionV2

```csharp
public float RegionV2 { get; set; }
```

#### Property Value

**Type:** System.Single

### RegionWidth

```csharp
public float RegionWidth { get; set; }
```

#### Property Value

**Type:** System.Single

### Triangles

```csharp
public int[] Triangles { get; set; }
```

#### Property Value

**Type:** System.Int32[]

### UVs

```csharp
public float[] UVs { get; set; }
```

#### Property Value

**Type:** System.Single[]

### Width

```csharp
public float Width { get; set; }
```

#### Property Value

**Type:** System.Single

## Methods

### ApplyDeform(VertexAttachment)

```csharp
public override bool ApplyDeform(VertexAttachment sourceAttachment)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sourceAttachment` | `Spine.VertexAttachment` |  |

#### Returns

**Type:** System.Boolean

### UpdateUVs()

```csharp
public void UpdateUVs()
```
