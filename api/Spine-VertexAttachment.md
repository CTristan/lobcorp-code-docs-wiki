# Class VertexAttachment

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class VertexAttachment : Attachment
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Attachment](/api/Spine-Attachment) → VertexAttachment

## Inherited Members
[ToString()](/api/Spine-Attachment#tostring), [Name](/api/Spine-Attachment#name), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### VertexAttachment(string)

```csharp
public VertexAttachment(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

## Properties

### Bones

```csharp
public int[] Bones { get; set; }
```

#### Property Value

**Type:** System.Int32[]

### Id

```csharp
public int Id { get; }
```

#### Property Value

**Type:** System.Int32

### Vertices

```csharp
public float[] Vertices { get; set; }
```

#### Property Value

**Type:** System.Single[]

### WorldVerticesLength

```csharp
public int WorldVerticesLength { get; set; }
```

#### Property Value

**Type:** System.Int32

## Methods

### ApplyDeform(VertexAttachment)

```csharp
public virtual bool ApplyDeform(VertexAttachment sourceAttachment)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `sourceAttachment` | `Spine.VertexAttachment` |  |

#### Returns

**Type:** System.Boolean

### ComputeWorldVertices(Slot, float[])

```csharp
public void ComputeWorldVertices(Slot slot, float[] worldVertices)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Spine.Slot` |  |
| `worldVertices` | `System.Single[]` |  |

### ComputeWorldVertices(Slot, int, int, float[], int, int)

```csharp
public void ComputeWorldVertices(Slot slot, int start, int count, float[] worldVertices, int offset, int stride = 2)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slot` | `Spine.Slot` |  |
| `start` | `System.Int32` |  |
| `count` | `System.Int32` |  |
| `worldVertices` | `System.Single[]` |  |
| `offset` | `System.Int32` |  |
| `stride` | `System.Int32` |  |
