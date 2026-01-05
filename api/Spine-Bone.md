# Class Bone

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Bone : IUpdatable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Bone

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Bone(BoneData, Skeleton, Bone)

```csharp
public Bone(BoneData data, Skeleton skeleton, Bone parent)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Spine.BoneData` |  |
| `skeleton` | `Spine.Skeleton` |  |
| `parent` | `Spine.Bone` |  |

## Fields

### yDown

```csharp
public static bool yDown
```

#### Field Value

**Type:** System.Boolean

## Properties

### A

```csharp
public float A { get; }
```

#### Property Value

**Type:** System.Single

### AppliedRotation

```csharp
public float AppliedRotation { get; set; }
```

#### Property Value

**Type:** System.Single

### AScaleX

```csharp
public float AScaleX { get; set; }
```

#### Property Value

**Type:** System.Single

### AScaleY

```csharp
public float AScaleY { get; set; }
```

#### Property Value

**Type:** System.Single

### AShearX

```csharp
public float AShearX { get; set; }
```

#### Property Value

**Type:** System.Single

### AShearY

```csharp
public float AShearY { get; set; }
```

#### Property Value

**Type:** System.Single

### AX

```csharp
public float AX { get; set; }
```

#### Property Value

**Type:** System.Single

### AY

```csharp
public float AY { get; set; }
```

#### Property Value

**Type:** System.Single

### B

```csharp
public float B { get; }
```

#### Property Value

**Type:** System.Single

### C

```csharp
public float C { get; }
```

#### Property Value

**Type:** System.Single

### Children

```csharp
public ExposedList<Bone> Children { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.Bone}

### D

```csharp
public float D { get; }
```

#### Property Value

**Type:** System.Single

### Data

```csharp
public BoneData Data { get; }
```

#### Property Value

**Type:** Spine.BoneData

### Parent

```csharp
public Bone Parent { get; }
```

#### Property Value

**Type:** Spine.Bone

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

### Skeleton

```csharp
public Skeleton Skeleton { get; }
```

#### Property Value

**Type:** Spine.Skeleton

### WorldRotationX

```csharp
public float WorldRotationX { get; }
```

#### Property Value

**Type:** System.Single

### WorldRotationY

```csharp
public float WorldRotationY { get; }
```

#### Property Value

**Type:** System.Single

### WorldScaleX

```csharp
public float WorldScaleX { get; }
```

#### Property Value

**Type:** System.Single

### WorldScaleY

```csharp
public float WorldScaleY { get; }
```

#### Property Value

**Type:** System.Single

### WorldToLocalRotationX

```csharp
public float WorldToLocalRotationX { get; }
```

#### Property Value

**Type:** System.Single

### WorldToLocalRotationY

```csharp
public float WorldToLocalRotationY { get; }
```

#### Property Value

**Type:** System.Single

### WorldX

```csharp
public float WorldX { get; }
```

#### Property Value

**Type:** System.Single

### WorldY

```csharp
public float WorldY { get; }
```

#### Property Value

**Type:** System.Single

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

### LocalToWorld(float, float, out float, out float)

```csharp
public void LocalToWorld(float localX, float localY, out float worldX, out float worldY)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `localX` | `System.Single` |  |
| `localY` | `System.Single` |  |
| `worldX` | `System.Single` |  |
| `worldY` | `System.Single` |  |

### LocalToWorldRotation(float)

```csharp
public float LocalToWorldRotation(float localRotation)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `localRotation` | `System.Single` |  |

#### Returns

**Type:** System.Single

### RotateWorld(float)

```csharp
public void RotateWorld(float degrees)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `degrees` | `System.Single` |  |

### SetToSetupPose()

```csharp
public void SetToSetupPose()
```

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String

### Update()

```csharp
public void Update()
```

### UpdateWorldTransform()

```csharp
public void UpdateWorldTransform()
```

### UpdateWorldTransform(float, float, float, float, float, float, float)

```csharp
public void UpdateWorldTransform(float x, float y, float rotation, float scaleX, float scaleY, float shearX, float shearY)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Single` |  |
| `y` | `System.Single` |  |
| `rotation` | `System.Single` |  |
| `scaleX` | `System.Single` |  |
| `scaleY` | `System.Single` |  |
| `shearX` | `System.Single` |  |
| `shearY` | `System.Single` |  |

### WorldToLocal(float, float, out float, out float)

```csharp
public void WorldToLocal(float worldX, float worldY, out float localX, out float localY)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worldX` | `System.Single` |  |
| `worldY` | `System.Single` |  |
| `localX` | `System.Single` |  |
| `localY` | `System.Single` |  |

### WorldToLocalRotation(float)

```csharp
public float WorldToLocalRotation(float worldRotation)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `worldRotation` | `System.Single` |  |

#### Returns

**Type:** System.Single
