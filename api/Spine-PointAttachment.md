# Class PointAttachment

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PointAttachment : Attachment
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Attachment](/api/Spine-Attachment) → PointAttachment

## Inherited Members
[ToString()](/api/Spine-Attachment#tostring), [Name](/api/Spine-Attachment#name), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### PointAttachment(string)

```csharp
public PointAttachment(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

## Properties

### Rotation

```csharp
public float Rotation { get; set; }
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

### ComputeWorldPosition(Bone, out float, out float)

```csharp
public void ComputeWorldPosition(Bone bone, out float ox, out float oy)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |
| `ox` | `System.Single` |  |
| `oy` | `System.Single` |  |

### ComputeWorldRotation(Bone)

```csharp
public float ComputeWorldRotation(Bone bone)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `bone` | `Spine.Bone` |  |

#### Returns

**Type:** System.Single
