# Class IkConstraint

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class IkConstraint : IConstraint, IUpdatable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → IkConstraint

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### IkConstraint(IkConstraintData, Skeleton)

```csharp
public IkConstraint(IkConstraintData data, Skeleton skeleton)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `Spine.IkConstraintData` |  |
| `skeleton` | `Spine.Skeleton` |  |

## Properties

### BendDirection

```csharp
public int BendDirection { get; set; }
```

#### Property Value

**Type:** System.Int32

### Bones

```csharp
public ExposedList<Bone> Bones { get; }
```

#### Property Value

**Type:** Spine.ExposedList{Spine.Bone}

### Data

```csharp
public IkConstraintData Data { get; }
```

#### Property Value

**Type:** Spine.IkConstraintData

### Mix

```csharp
public float Mix { get; set; }
```

#### Property Value

**Type:** System.Single

### Order

```csharp
public int Order { get; }
```

#### Property Value

**Type:** System.Int32

### Target

```csharp
public Bone Target { get; set; }
```

#### Property Value

**Type:** Spine.Bone

## Methods

### Apply()

```csharp
public void Apply()
```

### Apply(Bone, Bone, float, float, int, float)

```csharp
public static void Apply(Bone parent, Bone child, float targetX, float targetY, int bendDir, float alpha)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `parent` | `Spine.Bone` |  |
| `child` | `Spine.Bone` |  |
| `targetX` | `System.Single` |  |
| `targetY` | `System.Single` |  |
| `bendDir` | `System.Int32` |  |
| `alpha` | `System.Single` |  |

### Apply(Bone, float, float, float)

```csharp
public static void Apply(Bone bone, float targetX, float targetY, float alpha)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `targetX` | `System.Single` |  |
| `targetY` | `System.Single` |  |
| `alpha` | `System.Single` |  |

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
