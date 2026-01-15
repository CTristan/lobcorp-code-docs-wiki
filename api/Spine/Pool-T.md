---
uid: Spine.Pool`1
canonical_path: /api/Spine/Pool-T
---

# Class Pool<T>

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Pool<T> where T : class, new()
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Pool<T>

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Pool(int, int)

```csharp
public Pool(int initialCapacity = 16, int max = 2147483647)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `initialCapacity` | `System.Int32` |  |
| `max` | `System.Int32` |  |

## Fields

### freeObjects

```csharp
private readonly Stack<T> freeObjects
```

#### Field Value

**Type:** System.Collections.Generic.Stack{{T}}

### max

```csharp
public readonly int max
```

#### Field Value

**Type:** System.Int32

## Properties

### Count

```csharp
public int Count { get; }
```

#### Property Value

**Type:** System.Int32

### Peak

```csharp
public int Peak { get; private set; }
```

#### Property Value

**Type:** System.Int32

## Methods

### Clear()

```csharp
public void Clear()
```

### Free(T)

```csharp
public void Free(T obj)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `obj` | `{T}` |  |

### Obtain()

```csharp
public T Obtain()
```

#### Returns

**Type:** {T}

### Reset(T)

```csharp
protected void Reset(T obj)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `obj` | `{T}` |  |
