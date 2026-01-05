# Class Atlas

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Atlas : IEnumerable<AtlasRegion>, IEnumerable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Atlas

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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
