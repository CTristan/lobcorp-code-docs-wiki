# Class Slot

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Slot
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Slot

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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
