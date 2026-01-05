# Class IkConstraintData

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class IkConstraintData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → IkConstraintData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### IkConstraintData(string)

```csharp
public IkConstraintData(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

## Properties

### BendDirection

```csharp
public int BendDirection { get; set; }
```

#### Property Value

**Type:** System.Int32

### Bones

```csharp
public List<BoneData> Bones { get; }
```

#### Property Value

**Type:** System.Collections.Generic.List{Spine.BoneData}

### Mix

```csharp
public float Mix { get; set; }
```

#### Property Value

**Type:** System.Single

### Name

```csharp
public string Name { get; }
```

#### Property Value

**Type:** System.String

### Order

```csharp
public int Order { get; set; }
```

#### Property Value

**Type:** System.Int32

### Target

```csharp
public BoneData Target { get; set; }
```

#### Property Value

**Type:** Spine.BoneData

## Methods

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
