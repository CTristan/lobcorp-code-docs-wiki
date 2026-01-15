---
uid: Spine.IkConstraintData
canonical_path: /api/Spine/IkConstraintData
---

# Class IkConstraintData

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class IkConstraintData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → IkConstraintData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### IkConstraintData(string)

```csharp
public IkConstraintData(string name)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

## Fields

### bendDirection

```csharp
internal int bendDirection
```

#### Field Value

**Type:** System.Int32

### bones

```csharp
internal List<BoneData> bones
```

#### Field Value

**Type:** System.Collections.Generic.List{Spine.BoneData}

### mix

```csharp
internal float mix
```

#### Field Value

**Type:** System.Single

### name

```csharp
internal string name
```

#### Field Value

**Type:** System.String

### order

```csharp
internal int order
```

#### Field Value

**Type:** System.Int32

### target

```csharp
internal BoneData target
```

#### Field Value

**Type:** Spine.BoneData

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
