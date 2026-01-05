# Class SkeletonRendererInstruction

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine-Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkeletonRendererInstruction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkeletonRendererInstruction

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SkeletonRendererInstruction()

```csharp
public SkeletonRendererInstruction()
```

## Fields

### attachments

```csharp
public readonly ExposedList<Attachment> attachments
```

#### Field Value

**Type:** Spine.ExposedList{Spine.Attachment}

### hasActiveClipping

```csharp
public bool hasActiveClipping
```

#### Field Value

**Type:** System.Boolean

### immutableTriangles

```csharp
public bool immutableTriangles
```

#### Field Value

**Type:** System.Boolean

### rawVertexCount

```csharp
public int rawVertexCount
```

#### Field Value

**Type:** System.Int32

### submeshInstructions

```csharp
public readonly ExposedList<SubmeshInstruction> submeshInstructions
```

#### Field Value

**Type:** Spine.ExposedList{Spine.Unity.SubmeshInstruction}

## Methods

### Clear()

```csharp
public void Clear()
```

### Dispose()

```csharp
public void Dispose()
```

### GeometryNotEqual(SkeletonRendererInstruction, SkeletonRendererInstruction)

```csharp
public static bool GeometryNotEqual(SkeletonRendererInstruction a, SkeletonRendererInstruction b)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Spine.Unity.SkeletonRendererInstruction` |  |
| `b` | `Spine.Unity.SkeletonRendererInstruction` |  |

#### Returns

**Type:** System.Boolean

### Set(SkeletonRendererInstruction)

```csharp
public void Set(SkeletonRendererInstruction other)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `other` | `Spine.Unity.SkeletonRendererInstruction` |  |

### SetWithSubset(ExposedList<SubmeshInstruction>, int, int)

```csharp
public void SetWithSubset(ExposedList<SubmeshInstruction> instructions, int startSubmesh, int endSubmesh)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instructions` | `Spine.ExposedList{Spine.Unity.SubmeshInstruction}` |  |
| `startSubmesh` | `System.Int32` |  |
| `endSubmesh` | `System.Int32` |  |
