---
uid: Spine.Atlas
canonical_path: /api/Spine/Atlas
---

# Class Atlas

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Atlas : IEnumerable<AtlasRegion>, IEnumerable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Atlas

## Implements
[IEnumerable<AtlasRegion>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable-1), [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.ienumerable)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Atlas(List<AtlasPage>, List<AtlasRegion>)

```csharp
public Atlas(List<AtlasPage> pages, List<AtlasRegion> regions)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pages` | `System.Collections.Generic.List{Spine.AtlasPage}` |  |
| `regions` | `System.Collections.Generic.List{Spine.AtlasRegion}` |  |

### Atlas(TextReader, string, TextureLoader)

```csharp
public Atlas(TextReader reader, string dir, TextureLoader textureLoader)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `reader` | `System.IO.TextReader` |  |
| `dir` | `System.String` |  |
| `textureLoader` | `Spine.TextureLoader` |  |

## Fields

### pages

```csharp
private readonly List<AtlasPage> pages
```

#### Field Value

**Type:** System.Collections.Generic.List{Spine.AtlasPage}

### regions

```csharp
private List<AtlasRegion> regions
```

#### Field Value

**Type:** System.Collections.Generic.List{Spine.AtlasRegion}

### textureLoader

```csharp
private TextureLoader textureLoader
```

#### Field Value

**Type:** Spine.TextureLoader

## Methods

### Dispose()

```csharp
public void Dispose()
```

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

### FlipV()

```csharp
public void FlipV()
```

### GetEnumerator()

```csharp
public IEnumerator<AtlasRegion> GetEnumerator()
```

#### Returns

**Type:** System.Collections.Generic.IEnumerator{Spine.AtlasRegion}

### IEnumerable.GetEnumerator()

```csharp
IEnumerator IEnumerable.GetEnumerator()
```

#### Returns

**Type:** System.Collections.IEnumerator

### Load(TextReader, string, TextureLoader)

```csharp
private void Load(TextReader reader, string imagesDir, TextureLoader textureLoader)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `reader` | `System.IO.TextReader` |  |
| `imagesDir` | `System.String` |  |
| `textureLoader` | `Spine.TextureLoader` |  |

### ReadTuple(TextReader, string[])

```csharp
private static int ReadTuple(TextReader reader, string[] tuple)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `reader` | `System.IO.TextReader` |  |
| `tuple` | `System.String[]` |  |

#### Returns

**Type:** System.Int32

### ReadValue(TextReader)

```csharp
private static string ReadValue(TextReader reader)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `reader` | `System.IO.TextReader` |  |

#### Returns

**Type:** System.String
