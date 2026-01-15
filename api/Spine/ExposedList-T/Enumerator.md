---
uid: Spine.ExposedList`1.Enumerator
canonical_path: /api/Spine/ExposedList-T/Enumerator
---

# Struct ExposedList<T>.Enumerator

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public struct ExposedList<T>.Enumerator : IEnumerator<T>, IDisposable, IEnumerator
```

## Implements
[IEnumerator<T>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerator-1), [IDisposable](https://learn.microsoft.com/dotnet/api/system.idisposable), [IEnumerator](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.valuetype.equals), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.valuetype.gethashcode), [ToString()](https://learn.microsoft.com/dotnet/api/system.valuetype.tostring), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Enumerator(ExposedList<T>)

```csharp
internal Enumerator(ExposedList<T> l)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `l` | `Spine.ExposedList`1` |  |

## Fields

### current

```csharp
private T current
```

#### Field Value

**Type:** {T}

### l

```csharp
private ExposedList<T> l
```

#### Field Value

**Type:** Spine.ExposedList`1

### next

```csharp
private int next
```

#### Field Value

**Type:** System.Int32

### ver

```csharp
private int ver
```

#### Field Value

**Type:** System.Int32

## Properties

### Current

```csharp
public T Current { get; }
```

#### Property Value

**Type:** {T}

### IEnumerator.Current

```csharp
object IEnumerator.Current { get; }
```

#### Property Value

**Type:** System.Object

## Methods

### Dispose()

```csharp
public void Dispose()
```

### IEnumerator.Reset()

```csharp
void IEnumerator.Reset()
```

### MoveNext()

```csharp
public bool MoveNext()
```

#### Returns

**Type:** System.Boolean

### VerifyState()

```csharp
private void VerifyState()
```
