# Class PriorityQueue<T>

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PriorityQueue<T> where T : IComparable<T>
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PriorityQueue<T>

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### PriorityQueue()

```csharp
public PriorityQueue()
```

## Methods

### Count()

```csharp
public int Count()
```

#### Returns

**Type:** System.Int32

### Dequeue()

```csharp
public T Dequeue()
```

#### Returns

**Type:** {T}

### Enqueue(T)

```csharp
public void Enqueue(T item)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `{T}` |  |

### IsConsistent()

```csharp
public bool IsConsistent()
```

#### Returns

**Type:** System.Boolean

### Peek()

```csharp
public T Peek()
```

#### Returns

**Type:** {T}

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
