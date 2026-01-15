---
uid: Spine.Unity.MaterialsTextureLoader
canonical_path: /api/Spine/Unity/MaterialsTextureLoader
---

# Class MaterialsTextureLoader

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MaterialsTextureLoader : TextureLoader
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → MaterialsTextureLoader

## Implements
[TextureLoader](/api/Spine/TextureLoader)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### MaterialsTextureLoader(AtlasAsset)

```csharp
public MaterialsTextureLoader(AtlasAsset atlasAsset)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `atlasAsset` | `Spine.Unity.AtlasAsset` |  |

## Fields

### atlasAsset

```csharp
private AtlasAsset atlasAsset
```

#### Field Value

**Type:** Spine.Unity.AtlasAsset

## Methods

### Load(AtlasPage, string)

```csharp
public void Load(AtlasPage page, string path)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `page` | `Spine.AtlasPage` |  |
| `path` | `System.String` |  |

### Unload(object)

```csharp
public void Unload(object texture)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `texture` | `System.Object` |  |
