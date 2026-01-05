# Class SkeletonData

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SkeletonData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → SkeletonData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### SkeletonData()

```csharp
public SkeletonData()
```

## Properties

### Animations

```csharp
public ExposedList<Animation> Animations { get; set; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.Animation}

### Bones

```csharp
public ExposedList<BoneData> Bones { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.BoneData}

### DefaultSkin

```csharp
public Skin DefaultSkin { get; set; }
```

#### Property Value

**Type:** Spine.Skin

### Events

```csharp
public ExposedList<EventData> Events { get; set; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.EventData}

### Fps

```csharp
public float Fps { get; set; }
```

#### Property Value

**Type:** System.Single

### Hash

```csharp
public string Hash { get; set; }
```

#### Property Value

**Type:** System.String

### Height

```csharp
public float Height { get; set; }
```

#### Property Value

**Type:** System.Single

### IkConstraints

```csharp
public ExposedList<IkConstraintData> IkConstraints { get; set; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.IkConstraintData}

### ImagesPath

```csharp
public string ImagesPath { get; set; }
```

#### Property Value

**Type:** System.String

### Name

```csharp
public string Name { get; set; }
```

#### Property Value

**Type:** System.String

### PathConstraints

```csharp
public ExposedList<PathConstraintData> PathConstraints { get; set; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.PathConstraintData}

### Skins

```csharp
public ExposedList<Skin> Skins { get; set; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.Skin}

### Slots

```csharp
public ExposedList<SlotData> Slots { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.SlotData}

### TransformConstraints

```csharp
public ExposedList<TransformConstraintData> TransformConstraints { get; set; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.TransformConstraintData}

### Version

```csharp
public string Version { get; set; }
```

#### Property Value

**Type:** System.String

### Width

```csharp
public float Width { get; set; }
```

#### Property Value

**Type:** System.Single

## Methods

### FindAnimation(string)

```csharp
public Animation FindAnimation(string animationName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `animationName` | `System.String` |  |

#### Returns

**Type:** Spine.Animation

### FindBone(string)

```csharp
public BoneData FindBone(string boneName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `boneName` | `System.String` |  |

#### Returns

**Type:** Spine.BoneData

### FindBoneIndex(string)

```csharp
public int FindBoneIndex(string boneName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `boneName` | `System.String` |  |

#### Returns

**Type:** System.Int32

### FindEvent(string)

```csharp
public EventData FindEvent(string eventDataName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `eventDataName` | `System.String` |  |

#### Returns

**Type:** Spine.EventData

### FindIkConstraint(string)

```csharp
public IkConstraintData FindIkConstraint(string constraintName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraintName` | `System.String` |  |

#### Returns

**Type:** Spine.IkConstraintData

### FindPathConstraint(string)

```csharp
public PathConstraintData FindPathConstraint(string constraintName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraintName` | `System.String` |  |

#### Returns

**Type:** Spine.PathConstraintData

### FindPathConstraintIndex(string)

```csharp
public int FindPathConstraintIndex(string pathConstraintName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pathConstraintName` | `System.String` |  |

#### Returns

**Type:** System.Int32

### FindSkin(string)

```csharp
public Skin FindSkin(string skinName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skinName` | `System.String` |  |

#### Returns

**Type:** Spine.Skin

### FindSlot(string)

```csharp
public SlotData FindSlot(string slotName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotName` | `System.String` |  |

#### Returns

**Type:** Spine.SlotData

### FindSlotIndex(string)

```csharp
public int FindSlotIndex(string slotName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotName` | `System.String` |  |

#### Returns

**Type:** System.Int32

### FindTransformConstraint(string)

```csharp
public TransformConstraintData FindTransformConstraint(string constraintName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraintName` | `System.String` |  |

#### Returns

**Type:** Spine.TransformConstraintData

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
