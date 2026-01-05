# Class PathConstraintData

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PathConstraintData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PathConstraintData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### PathConstraintData(string)

```csharp
public PathConstraintData(string name)
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

### Order

```csharp
public int Order { get; set; }
```

#### Property Value

**Type:** System.Int32

### Position

```csharp
public float Position { get; set; }
```

#### Property Value

**Type:** System.Single

### PositionMode

```csharp
public PositionMode PositionMode { get; set; }
```

#### Property Value

**Type:** Spine.PositionMode

### RotateMix

```csharp
public float RotateMix { get; set; }
```

#### Property Value

**Type:** System.Single

### RotateMode

```csharp
public RotateMode RotateMode { get; set; }
```

#### Property Value

**Type:** Spine.RotateMode

### Spacing

```csharp
public float Spacing { get; set; }
```

#### Property Value

**Type:** System.Single

### SpacingMode

```csharp
public SpacingMode SpacingMode { get; set; }
```

#### Property Value

**Type:** Spine.SpacingMode

### Target

```csharp
public SlotData Target { get; set; }
```

#### Property Value

**Type:** Spine.SlotData

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
