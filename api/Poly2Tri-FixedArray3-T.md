# Struct FixedArray3<T>

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public struct FixedArray3<T> : IEnumerable<T>, IEnumerable where T : class
```

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.valuetype.equals), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.valuetype.gethashcode), [ToString()](https://learn.microsoft.com/dotnet/api/system.valuetype.tostring), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Fields

### _0

```csharp
public T _0
```

#### Field Value

**Type:** {T}

### _1

```csharp
public T _1
```

#### Field Value

**Type:** {T}

### _2

```csharp
public T _2
```

#### Field Value

**Type:** {T}

## Properties

### this[int]

```csharp
public T this[int index] { get; set; }
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Property Value

**Type:** {T}

## Methods

### Clear()

```csharp
public void Clear()
```

### Clear(T)

```csharp
public void Clear(T value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `{T}` |  |

### Contains(T)

```csharp
public bool Contains(T value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `{T}` |  |

#### Returns

**Type:** System.Boolean

### GetEnumerator()

```csharp
public IEnumerator<T> GetEnumerator()
```

#### Returns

**Type:** System.Collections.Generic.IEnumerator{{T}}

### IndexOf(T)

```csharp
public int IndexOf(T value)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `{T}` |  |

#### Returns

**Type:** System.Int32
