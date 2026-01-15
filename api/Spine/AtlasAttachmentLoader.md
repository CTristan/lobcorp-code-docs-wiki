---
uid: Spine.AtlasAttachmentLoader
canonical_path: /api/Spine/AtlasAttachmentLoader
---

# Class AtlasAttachmentLoader

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AtlasAttachmentLoader : AttachmentLoader
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → AtlasAttachmentLoader

## Implements
[AttachmentLoader](/api/Spine/AttachmentLoader)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### AtlasAttachmentLoader(params Atlas[])

```csharp
public AtlasAttachmentLoader(params Atlas[] atlasArray)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `atlasArray` | `Spine.Atlas[]` |  |

## Fields

### atlasArray

```csharp
private Atlas[] atlasArray
```

#### Field Value

**Type:** Spine.Atlas[]

## Methods

### FindRegion(string)

```csharp
public AtlasRegion FindRegion(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

#### Returns

**Type:** Spine.AtlasRegion

### NewBoundingBoxAttachment(Skin, string)

```csharp
public BoundingBoxAttachment NewBoundingBoxAttachment(Skin skin, string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `name` | `System.String` |  |

#### Returns

**Type:** Spine.BoundingBoxAttachment

### NewClippingAttachment(Skin, string)

```csharp
public ClippingAttachment NewClippingAttachment(Skin skin, string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `name` | `System.String` |  |

#### Returns

**Type:** Spine.ClippingAttachment

### NewMeshAttachment(Skin, string, string)

```csharp
public MeshAttachment NewMeshAttachment(Skin skin, string name, string path)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `name` | `System.String` |  |
| `path` | `System.String` |  |

#### Returns

**Type:** Spine.MeshAttachment

### NewPathAttachment(Skin, string)

```csharp
public PathAttachment NewPathAttachment(Skin skin, string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `name` | `System.String` |  |

#### Returns

**Type:** Spine.PathAttachment

### NewPointAttachment(Skin, string)

```csharp
public PointAttachment NewPointAttachment(Skin skin, string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `name` | `System.String` |  |

#### Returns

**Type:** Spine.PointAttachment

### NewRegionAttachment(Skin, string, string)

```csharp
public RegionAttachment NewRegionAttachment(Skin skin, string name, string path)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `name` | `System.String` |  |
| `path` | `System.String` |  |

#### Returns

**Type:** Spine.RegionAttachment
