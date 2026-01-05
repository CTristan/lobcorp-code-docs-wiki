# Class SkeletonJson

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkeletonJson
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkeletonJson

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

## Properties

### Scale

```csharp
public float Scale { get; set; }
```

#### Property Value

**Type:** System.Single

## Methods

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
