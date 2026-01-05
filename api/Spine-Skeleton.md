# Class Skeleton

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Skeleton
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Skeleton

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Skeleton(SkeletonData)

```csharp
public Skeleton(SkeletonData data)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Spine.SkeletonData` |  |

## Properties

### A

```csharp
public float A { get; set; }
```

#### Property Value

**Type:** System.Single

### B

```csharp
public float B { get; set; }
```

#### Property Value

**Type:** System.Single

### Bones

```csharp
public ExposedList<Bone> Bones { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.Bone}

### Data

```csharp
public SkeletonData Data { get; }
```

#### Property Value

**Type:** Spine.SkeletonData

### DrawOrder

```csharp
public ExposedList<Slot> DrawOrder { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.Slot}

### FlipX

```csharp
public bool FlipX { get; set; }
```

#### Property Value

**Type:** System.Boolean

### FlipY

```csharp
public bool FlipY { get; set; }
```

#### Property Value

**Type:** System.Boolean

### G

```csharp
public float G { get; set; }
```

#### Property Value

**Type:** System.Single

### IkConstraints

```csharp
public ExposedList<IkConstraint> IkConstraints { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.IkConstraint}

### PathConstraints

```csharp
public ExposedList<PathConstraint> PathConstraints { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.PathConstraint}

### R

```csharp
public float R { get; set; }
```

#### Property Value

**Type:** System.Single

### RootBone

```csharp
public Bone RootBone { get; }
```

#### Property Value

**Type:** Spine.Bone

### Skin

```csharp
public Skin Skin { get; set; }
```

#### Property Value

**Type:** Spine.Skin

### Slots

```csharp
public ExposedList<Slot> Slots { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.Slot}

### Time

```csharp
public float Time { get; set; }
```

#### Property Value

**Type:** System.Single

### TransformConstraints

```csharp
public ExposedList<TransformConstraint> TransformConstraints { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.TransformConstraint}

### UpdateCacheList

```csharp
public ExposedList<IUpdatable> UpdateCacheList { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.IUpdatable}

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

### FindBone(string)

```csharp
public Bone FindBone(string boneName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `boneName` | `System.String` |  |

#### Returns

**Type:** Spine.Bone

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

### FindIkConstraint(string)

```csharp
public IkConstraint FindIkConstraint(string constraintName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraintName` | `System.String` |  |

#### Returns

**Type:** Spine.IkConstraint

### FindPathConstraint(string)

```csharp
public PathConstraint FindPathConstraint(string constraintName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraintName` | `System.String` |  |

#### Returns

**Type:** Spine.PathConstraint

### FindSlot(string)

```csharp
public Slot FindSlot(string slotName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotName` | `System.String` |  |

#### Returns

**Type:** Spine.Slot

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
public TransformConstraint FindTransformConstraint(string constraintName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `constraintName` | `System.String` |  |

#### Returns

**Type:** Spine.TransformConstraint

### GetAttachment(int, string)

```csharp
public Attachment GetAttachment(int slotIndex, string attachmentName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotIndex` | `System.Int32` |  |
| `attachmentName` | `System.String` |  |

#### Returns

**Type:** Spine.Attachment

### GetAttachment(string, string)

```csharp
public Attachment GetAttachment(string slotName, string attachmentName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotName` | `System.String` |  |
| `attachmentName` | `System.String` |  |

#### Returns

**Type:** Spine.Attachment

### GetBounds(out float, out float, out float, out float, ref float[])

```csharp
public void GetBounds(out float x, out float y, out float width, out float height, ref float[] vertexBuffer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `x` | `System.Single` |  |
| `y` | `System.Single` |  |
| `width` | `System.Single` |  |
| `height` | `System.Single` |  |
| `vertexBuffer` | `System.Single[]` |  |

### SetAttachment(string, string)

```csharp
public void SetAttachment(string slotName, string attachmentName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slotName` | `System.String` |  |
| `attachmentName` | `System.String` |  |

### SetBonesToSetupPose()

```csharp
public void SetBonesToSetupPose()
```

### SetSkin(Skin)

```csharp
public void SetSkin(Skin newSkin)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `newSkin` | `Spine.Skin` |  |

### SetSkin(string)

```csharp
public void SetSkin(string skinName)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `skinName` | `System.String` |  |

### SetSlotsToSetupPose()

```csharp
public void SetSlotsToSetupPose()
```

### SetToSetupPose()

```csharp
public void SetToSetupPose()
```

### Update(float)

```csharp
public void Update(float delta)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `delta` | `System.Single` |  |

### UpdateCache()

```csharp
public void UpdateCache()
```

### UpdateWorldTransform()

```csharp
public void UpdateWorldTransform()
```
