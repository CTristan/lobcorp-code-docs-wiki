# Class TransformConstraintData

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TransformConstraintData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TransformConstraintData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### TransformConstraintData(string)

```csharp
public TransformConstraintData(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

## Properties

### Bones

```csharp
public ExposedList<BoneData> Bones { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.BoneData}

### Local

```csharp
public bool Local { get; set; }
```

#### Property Value

**Type:** System.Boolean

### Name

```csharp
public string Name { get; }
```

#### Property Value

**Type:** System.String

### OffsetRotation

```csharp
public float OffsetRotation { get; set; }
```

#### Property Value

**Type:** System.Single

### OffsetScaleX

```csharp
public float OffsetScaleX { get; set; }
```

#### Property Value

**Type:** System.Single

### OffsetScaleY

```csharp
public float OffsetScaleY { get; set; }
```

#### Property Value

**Type:** System.Single

### OffsetShearY

```csharp
public float OffsetShearY { get; set; }
```

#### Property Value

**Type:** System.Single

### OffsetX

```csharp
public float OffsetX { get; set; }
```

#### Property Value

**Type:** System.Single

### OffsetY

```csharp
public float OffsetY { get; set; }
```

#### Property Value

**Type:** System.Single

### Order

```csharp
public int Order { get; set; }
```

#### Property Value

**Type:** System.Int32

### Relative

```csharp
public bool Relative { get; set; }
```

#### Property Value

**Type:** System.Boolean

### RotateMix

```csharp
public float RotateMix { get; set; }
```

#### Property Value

**Type:** System.Single

### ScaleMix

```csharp
public float ScaleMix { get; set; }
```

#### Property Value

**Type:** System.Single

### ShearMix

```csharp
public float ShearMix { get; set; }
```

#### Property Value

**Type:** System.Single

### Target

```csharp
public BoneData Target { get; set; }
```

#### Property Value

**Type:** Spine.BoneData

### TranslateMix

```csharp
public float TranslateMix { get; set; }
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
