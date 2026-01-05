# Class TransformConstraint

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TransformConstraint : IConstraint, IUpdatable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → TransformConstraint

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### TransformConstraint(TransformConstraintData, Skeleton)

```csharp
public TransformConstraint(TransformConstraintData data, Skeleton skeleton)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Spine.TransformConstraintData` |  |
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
public TransformConstraintData Data { get; }
```

#### Property Value

**Type:** Spine.TransformConstraintData

### Order

```csharp
public int Order { get; }
```

#### Property Value

**Type:** System.Int32

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
public Bone Target { get; set; }
```

#### Property Value

**Type:** Spine.Bone

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
