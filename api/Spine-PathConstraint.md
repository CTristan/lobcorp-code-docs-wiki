# Class PathConstraint

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PathConstraint : IConstraint, IUpdatable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PathConstraint

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

### Apply()

```csharp
public void Apply()
```

### Update()

```csharp
public void Update()
```
