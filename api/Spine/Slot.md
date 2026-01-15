---
uid: Spine.Slot
canonical_path: /api/Spine/Slot
---

# Class Slot

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Slot
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Slot

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Extension Methods
- [SetAttachmentToSetupPose(Slot)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_SetAttachmentToSetupPose_Spine_Slot_)
- [SetColorToSetupPose(Slot)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_SetColorToSetupPose_Spine_Slot_)
- [SetColor(Slot, Color)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_SetColor_Spine_Slot_UnityEngine_Color_)
- [SetColor(Slot, Color32)](Spine.Unity.SkeletonExtensions.html#Spine_Unity_SkeletonExtensions_SetColor_Spine_Slot_UnityEngine_Color32_)

## Constructors

### Slot(SlotData, Bone)

```csharp
public Slot(SlotData data, Bone bone)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Spine.SlotData` |  |
| `bone` | `Spine.Bone` |  |

## Fields

### a

```csharp
internal float a
```

#### Field Value

**Type:** System.Single

### attachment

```csharp
internal Attachment attachment
```

#### Field Value

**Type:** Spine.Attachment

### attachmentTime

```csharp
internal float attachmentTime
```

#### Field Value

**Type:** System.Single

### attachmentVertices

```csharp
internal ExposedList<float> attachmentVertices
```

#### Field Value

**Type:** Spine.ExposedList{System.Single}

### b

```csharp
internal float b
```

#### Field Value

**Type:** System.Single

### b2

```csharp
internal float b2
```

#### Field Value

**Type:** System.Single

### bone

```csharp
internal Bone bone
```

#### Field Value

**Type:** Spine.Bone

### data

```csharp
internal SlotData data
```

#### Field Value

**Type:** Spine.SlotData

### g

```csharp
internal float g
```

#### Field Value

**Type:** System.Single

### g2

```csharp
internal float g2
```

#### Field Value

**Type:** System.Single

### hasSecondColor

```csharp
internal bool hasSecondColor
```

#### Field Value

**Type:** System.Boolean

### r

```csharp
internal float r
```

#### Field Value

**Type:** System.Single

### r2

```csharp
internal float r2
```

#### Field Value

**Type:** System.Single

## Properties

### A

```csharp
public float A { get; set; }
```

#### Property Value

**Type:** System.Single

### Attachment

```csharp
public Attachment Attachment { get; set; }
```

#### Property Value

**Type:** Spine.Attachment

### AttachmentTime

```csharp
public float AttachmentTime { get; set; }
```

#### Property Value

**Type:** System.Single

### AttachmentVertices

```csharp
public ExposedList<float> AttachmentVertices { get; set; }
```

#### Property Value

**Type:** Spine.ExposedList{System.Single}

### B

```csharp
public float B { get; set; }
```

#### Property Value

**Type:** System.Single

### B2

```csharp
public float B2 { get; set; }
```

#### Property Value

**Type:** System.Single

### Bone

```csharp
public Bone Bone { get; }
```

#### Property Value

**Type:** Spine.Bone

### Data

```csharp
public SlotData Data { get; }
```

#### Property Value

**Type:** Spine.SlotData

### G

```csharp
public float G { get; set; }
```

#### Property Value

**Type:** System.Single

### G2

```csharp
public float G2 { get; set; }
```

#### Property Value

**Type:** System.Single

### HasSecondColor

```csharp
public bool HasSecondColor { get; set; }
```

#### Property Value

**Type:** System.Boolean

### R

```csharp
public float R { get; set; }
```

#### Property Value

**Type:** System.Single

### R2

```csharp
public float R2 { get; set; }
```

#### Property Value

**Type:** System.Single

### Skeleton

```csharp
public Skeleton Skeleton { get; }
```

#### Property Value

**Type:** Spine.Skeleton

## Methods

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
