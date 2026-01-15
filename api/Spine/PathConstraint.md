---
uid: Spine.PathConstraint
canonical_path: /api/Spine/PathConstraint
---

# Class PathConstraint

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PathConstraint : IConstraint, IUpdatable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PathConstraint

## Implements
[IConstraint](/api/Spine/IConstraint), [IUpdatable](/api/Spine/IUpdatable)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### PathConstraint(PathConstraintData, Skeleton)

```csharp
public PathConstraint(PathConstraintData data, Skeleton skeleton)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Spine.PathConstraintData` |  |
| `skeleton` | `Spine.Skeleton` |  |

## Fields

### AFTER

```csharp
private const int AFTER = -3
```

#### Field Value

**Type:** System.Int32

### BEFORE

```csharp
private const int BEFORE = -2
```

#### Field Value

**Type:** System.Int32

### bones

```csharp
internal ExposedList<Bone> bones
```

#### Field Value

**Type:** Spine.ExposedList{Spine.Bone}

### curves

```csharp
internal ExposedList<float> curves
```

#### Field Value

**Type:** Spine.ExposedList{System.Single}

### data

```csharp
internal PathConstraintData data
```

#### Field Value

**Type:** Spine.PathConstraintData

### Epsilon

```csharp
private const float Epsilon = 1E-05
```

#### Field Value

**Type:** System.Single

### lengths

```csharp
internal ExposedList<float> lengths
```

#### Field Value

**Type:** Spine.ExposedList{System.Single}

### NONE

```csharp
private const int NONE = -1
```

#### Field Value

**Type:** System.Int32

### position

```csharp
internal float position
```

#### Field Value

**Type:** System.Single

### positions

```csharp
internal ExposedList<float> positions
```

#### Field Value

**Type:** Spine.ExposedList{System.Single}

### rotateMix

```csharp
internal float rotateMix
```

#### Field Value

**Type:** System.Single

### segments

```csharp
internal float[] segments
```

#### Field Value

**Type:** System.Single[]

### spaces

```csharp
internal ExposedList<float> spaces
```

#### Field Value

**Type:** Spine.ExposedList{System.Single}

### spacing

```csharp
internal float spacing
```

#### Field Value

**Type:** System.Single

### target

```csharp
internal Slot target
```

#### Field Value

**Type:** Spine.Slot

### translateMix

```csharp
internal float translateMix
```

#### Field Value

**Type:** System.Single

### world

```csharp
internal ExposedList<float> world
```

#### Field Value

**Type:** Spine.ExposedList{System.Single}

## Properties

### Bones

```csharp
public ExposedList<Bone> Bones { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.Bone}

### Data

```csharp
public PathConstraintData Data { get; }
```

#### Property Value

**Type:** Spine.PathConstraintData

### Order

```csharp
public int Order { get; }
```

#### Property Value

**Type:** System.Int32

### Position

```csharp
public float Position { get; set; }
```

#### Property Value

**Type:** System.Single

### RotateMix

```csharp
public float RotateMix { get; set; }
```

#### Property Value

**Type:** System.Single

### Spacing

```csharp
public float Spacing { get; set; }
```

#### Property Value

**Type:** System.Single

### Target

```csharp
public Slot Target { get; set; }
```

#### Property Value

**Type:** Spine.Slot

### TranslateMix

```csharp
public float TranslateMix { get; set; }
```

#### Property Value

**Type:** System.Single

## Methods

### AddAfterPosition(float, float[], int, float[], int)

```csharp
private static void AddAfterPosition(float p, float[] temp, int i, float[] output, int o)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `System.Single` |  |
| `temp` | `System.Single[]` |  |
| `i` | `System.Int32` |  |
| `output` | `System.Single[]` |  |
| `o` | `System.Int32` |  |

### AddBeforePosition(float, float[], int, float[], int)

```csharp
private static void AddBeforePosition(float p, float[] temp, int i, float[] output, int o)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `System.Single` |  |
| `temp` | `System.Single[]` |  |
| `i` | `System.Int32` |  |
| `output` | `System.Single[]` |  |
| `o` | `System.Int32` |  |

### AddCurvePosition(float, float, float, float, float, float, float, float, float, float[], int, bool)

```csharp
private static void AddCurvePosition(float p, float x1, float y1, float cx1, float cy1, float cx2, float cy2, float x2, float y2, float[] output, int o, bool tangents)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `p` | `System.Single` |  |
| `x1` | `System.Single` |  |
| `y1` | `System.Single` |  |
| `cx1` | `System.Single` |  |
| `cy1` | `System.Single` |  |
| `cx2` | `System.Single` |  |
| `cy2` | `System.Single` |  |
| `x2` | `System.Single` |  |
| `y2` | `System.Single` |  |
| `output` | `System.Single[]` |  |
| `o` | `System.Int32` |  |
| `tangents` | `System.Boolean` |  |

### Apply()

```csharp
public void Apply()
```

### ComputeWorldPositions(PathAttachment, int, bool, bool, bool)

```csharp
private float[] ComputeWorldPositions(PathAttachment path, int spacesCount, bool tangents, bool percentPosition, bool percentSpacing)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `path` | `Spine.PathAttachment` |  |
| `spacesCount` | `System.Int32` |  |
| `tangents` | `System.Boolean` |  |
| `percentPosition` | `System.Boolean` |  |
| `percentSpacing` | `System.Boolean` |  |

#### Returns

**Type:** System.Single[]

### Update()

```csharp
public void Update()
```
