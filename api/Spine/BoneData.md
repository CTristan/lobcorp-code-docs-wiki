---
uid: Spine.BoneData
canonical_path: /api/Spine/BoneData
---

# Class BoneData

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BoneData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BoneData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BoneData(int, string, BoneData)

```csharp
public BoneData(int index, string name, BoneData parent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `name` | `System.String` |  |
| `parent` | `Spine.BoneData` |  |

## Fields

### index

```csharp
internal int index
```

#### Field Value

**Type:** System.Int32

### length

```csharp
internal float length
```

#### Field Value

**Type:** System.Single

### name

```csharp
internal string name
```

#### Field Value

**Type:** System.String

### parent

```csharp
internal BoneData parent
```

#### Field Value

**Type:** Spine.BoneData

### rotation

```csharp
internal float rotation
```

#### Field Value

**Type:** System.Single

### scaleX

```csharp
internal float scaleX
```

#### Field Value

**Type:** System.Single

### scaleY

```csharp
internal float scaleY
```

#### Field Value

**Type:** System.Single

### shearX

```csharp
internal float shearX
```

#### Field Value

**Type:** System.Single

### shearY

```csharp
internal float shearY
```

#### Field Value

**Type:** System.Single

### transformMode

```csharp
internal TransformMode transformMode
```

#### Field Value

**Type:** Spine.TransformMode

### x

```csharp
internal float x
```

#### Field Value

**Type:** System.Single

### y

```csharp
internal float y
```

#### Field Value

**Type:** System.Single

## Properties

### Index

```csharp
public int Index { get; }
```

#### Property Value

**Type:** System.Int32

### Length

```csharp
public float Length { get; set; }
```

#### Property Value

**Type:** System.Single

### Name

```csharp
public string Name { get; }
```

#### Property Value

**Type:** System.String

### Parent

```csharp
public BoneData Parent { get; }
```

#### Property Value

**Type:** Spine.BoneData

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

### ShearX

```csharp
public float ShearX { get; set; }
```

#### Property Value

**Type:** System.Single

### ShearY

```csharp
public float ShearY { get; set; }
```

#### Property Value

**Type:** System.Single

### TransformMode

```csharp
public TransformMode TransformMode { get; set; }
```

#### Property Value

**Type:** Spine.TransformMode

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

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
