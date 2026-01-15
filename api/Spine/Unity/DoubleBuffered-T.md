---
uid: Spine.Unity.DoubleBuffered`1
canonical_path: /api/Spine/Unity/DoubleBuffered-T
---

# Class DoubleBuffered<T>

**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DoubleBuffered<T> where T : new()
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → DoubleBuffered<T>

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DoubleBuffered()

```csharp
public DoubleBuffered()
```

## Fields

### a

```csharp
private readonly T a
```

#### Field Value

**Type:** {T}

### b

```csharp
private readonly T b
```

#### Field Value

**Type:** {T}

### usingA

```csharp
private bool usingA
```

#### Field Value

**Type:** System.Boolean

## Methods

### GetCurrent()

```csharp
public T GetCurrent()
```

#### Returns

**Type:** {T}

### GetNext()

```csharp
public T GetNext()
```

#### Returns

**Type:** {T}
