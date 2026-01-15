---
uid: Spine.ExposedList`1
canonical_path: /api/Spine/ExposedList-T
---

# Class ExposedList<T>

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ExposedList<T> : IEnumerable<T>, IEnumerable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ExposedList<T>

## Implements
[IEnumerable<T>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable-1), [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.ienumerable)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### ExposedList()

```csharp
public ExposedList()
```

### ExposedList(IEnumerable<T>)

```csharp
public ExposedList(IEnumerable<T> collection)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `collection` | `System.Collections.Generic.IEnumerable{{T}}` |  |

### ExposedList(int)

```csharp
public ExposedList(int capacity)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `capacity` | `System.Int32` |  |

### ExposedList(T[], int)

```csharp
internal ExposedList(T[] data, int size)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `{T}[]` |  |
| `size` | `System.Int32` |  |

## Fields

### Count

```csharp
public int Count
```

#### Field Value

**Type:** System.Int32

### DefaultCapacity

```csharp
private const int DefaultCapacity = 4
```

#### Field Value

**Type:** System.Int32

### EmptyArray

```csharp
private static readonly T[] EmptyArray
```

#### Field Value

**Type:** {T}[]

### Items

```csharp
public T[] Items
```

#### Field Value

**Type:** {T}[]

### version

```csharp
private int version
```

#### Field Value

**Type:** System.Int32

## Properties

### Capacity

```csharp
public int Capacity { get; set; }
```

#### Property Value

**Type:** System.Int32

## Methods

### Add(T)

```csharp
public void Add(T item)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `{T}` |  |

### AddCollection(ICollection<T>)

```csharp
private void AddCollection(ICollection<T> collection)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `collection` | `System.Collections.Generic.ICollection{{T}}` |  |

### AddEnumerable(IEnumerable<T>)

```csharp
private void AddEnumerable(IEnumerable<T> enumerable)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `enumerable` | `System.Collections.Generic.IEnumerable{{T}}` |  |

### AddRange(IEnumerable<T>)

```csharp
public void AddRange(IEnumerable<T> collection)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `collection` | `System.Collections.Generic.IEnumerable{{T}}` |  |

### BinarySearch(int, int, T, IComparer<T>)

```csharp
public int BinarySearch(int index, int count, T item, IComparer<T> comparer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `count` | `System.Int32` |  |
| `item` | `{T}` |  |
| `comparer` | `System.Collections.Generic.IComparer{{T}}` |  |

#### Returns

**Type:** System.Int32

### BinarySearch(T)

```csharp
public int BinarySearch(T item)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `{T}` |  |

#### Returns

**Type:** System.Int32

### BinarySearch(T, IComparer<T>)

```csharp
public int BinarySearch(T item, IComparer<T> comparer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `{T}` |  |
| `comparer` | `System.Collections.Generic.IComparer{{T}}` |  |

#### Returns

**Type:** System.Int32

### CheckCollection(IEnumerable<T>)

```csharp
private void CheckCollection(IEnumerable<T> collection)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `collection` | `System.Collections.Generic.IEnumerable{{T}}` |  |

### CheckIndex(int)

```csharp
private void CheckIndex(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### CheckMatch(Predicate<T>)

```csharp
private static void CheckMatch(Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `match` | `System.Predicate{{T}}` |  |

### CheckRange(int, int)

```csharp
private void CheckRange(int index, int count)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `count` | `System.Int32` |  |

### Clear(bool)

```csharp
public void Clear(bool clearArray = true)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `clearArray` | `System.Boolean` |  |

### Contains(T)

```csharp
public bool Contains(T item)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `{T}` |  |

#### Returns

**Type:** System.Boolean

### ConvertAll<TOutput>(Converter<T, TOutput>)

```csharp
public ExposedList<TOutput> ConvertAll<TOutput>(Converter<T, TOutput> converter)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `converter` | `System.Converter{{T},{TOutput}}` |  |

#### Returns

**Type:** Spine.ExposedList{{TOutput}}

### CopyTo(int, T[], int, int)

```csharp
public void CopyTo(int index, T[] array, int arrayIndex, int count)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `array` | `{T}[]` |  |
| `arrayIndex` | `System.Int32` |  |
| `count` | `System.Int32` |  |

### CopyTo(T[])

```csharp
public void CopyTo(T[] array)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `array` | `{T}[]` |  |

### CopyTo(T[], int)

```csharp
public void CopyTo(T[] array, int arrayIndex)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `array` | `{T}[]` |  |
| `arrayIndex` | `System.Int32` |  |

### EnsureCapacity(int)

```csharp
public void EnsureCapacity(int min)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `min` | `System.Int32` |  |

### Exists(Predicate<T>)

```csharp
public bool Exists(Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** System.Boolean

### Find(Predicate<T>)

```csharp
public T Find(Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** {T}

### FindAll(Predicate<T>)

```csharp
public ExposedList<T> FindAll(Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** Spine.ExposedList`1

### FindAllList(Predicate<T>)

```csharp
private ExposedList<T> FindAllList(Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** Spine.ExposedList`1

### FindIndex(int, int, Predicate<T>)

```csharp
public int FindIndex(int startIndex, int count, Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `startIndex` | `System.Int32` |  |
| `count` | `System.Int32` |  |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** System.Int32

### FindIndex(int, Predicate<T>)

```csharp
public int FindIndex(int startIndex, Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `startIndex` | `System.Int32` |  |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** System.Int32

### FindIndex(Predicate<T>)

```csharp
public int FindIndex(Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** System.Int32

### FindLast(Predicate<T>)

```csharp
public T FindLast(Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** {T}

### FindLastIndex(int, int, Predicate<T>)

```csharp
public int FindLastIndex(int startIndex, int count, Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `startIndex` | `System.Int32` |  |
| `count` | `System.Int32` |  |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** System.Int32

### FindLastIndex(int, Predicate<T>)

```csharp
public int FindLastIndex(int startIndex, Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `startIndex` | `System.Int32` |  |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** System.Int32

### FindLastIndex(Predicate<T>)

```csharp
public int FindLastIndex(Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** System.Int32

### ForEach(Action<T>)

```csharp
public void ForEach(Action<T> action)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `action` | `System.Action{{T}}` |  |

### GetEnumerator()

```csharp
public ExposedList<T>.Enumerator GetEnumerator()
```

#### Returns

**Type:** Spine.ExposedList`1.Enumerator

### GetIndex(int, int, Predicate<T>)

```csharp
private int GetIndex(int startIndex, int count, Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `startIndex` | `System.Int32` |  |
| `count` | `System.Int32` |  |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** System.Int32

### GetLastIndex(int, int, Predicate<T>)

```csharp
private int GetLastIndex(int startIndex, int count, Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `startIndex` | `System.Int32` |  |
| `count` | `System.Int32` |  |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** System.Int32

### GetRange(int, int)

```csharp
public ExposedList<T> GetRange(int index, int count)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `count` | `System.Int32` |  |

#### Returns

**Type:** Spine.ExposedList`1

### GrowIfNeeded(int)

```csharp
public void GrowIfNeeded(int newCount)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `newCount` | `System.Int32` |  |

### IEnumerable.GetEnumerator()

```csharp
IEnumerator IEnumerable.GetEnumerator()
```

#### Returns

**Type:** System.Collections.IEnumerator

### IEnumerable<T>.GetEnumerator()

```csharp
IEnumerator<T> IEnumerable<T>.GetEnumerator()
```

#### Returns

**Type:** System.Collections.Generic.IEnumerator{{T}}

### IndexOf(T)

```csharp
public int IndexOf(T item)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `{T}` |  |

#### Returns

**Type:** System.Int32

### IndexOf(T, int)

```csharp
public int IndexOf(T item, int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `{T}` |  |
| `index` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### IndexOf(T, int, int)

```csharp
public int IndexOf(T item, int index, int count)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `{T}` |  |
| `index` | `System.Int32` |  |
| `count` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### Insert(int, T)

```csharp
public void Insert(int index, T item)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `item` | `{T}` |  |

### InsertCollection(int, ICollection<T>)

```csharp
private void InsertCollection(int index, ICollection<T> collection)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `collection` | `System.Collections.Generic.ICollection{{T}}` |  |

### InsertEnumeration(int, IEnumerable<T>)

```csharp
private void InsertEnumeration(int index, IEnumerable<T> enumerable)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `enumerable` | `System.Collections.Generic.IEnumerable{{T}}` |  |

### InsertRange(int, IEnumerable<T>)

```csharp
public void InsertRange(int index, IEnumerable<T> collection)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `collection` | `System.Collections.Generic.IEnumerable{{T}}` |  |

### LastIndexOf(T)

```csharp
public int LastIndexOf(T item)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `{T}` |  |

#### Returns

**Type:** System.Int32

### LastIndexOf(T, int)

```csharp
public int LastIndexOf(T item, int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `{T}` |  |
| `index` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### LastIndexOf(T, int, int)

```csharp
public int LastIndexOf(T item, int index, int count)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `{T}` |  |
| `index` | `System.Int32` |  |
| `count` | `System.Int32` |  |

#### Returns

**Type:** System.Int32

### Pop()

```csharp
public T Pop()
```

#### Returns

**Type:** {T}

### Remove(T)

```csharp
public bool Remove(T item)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `item` | `{T}` |  |

#### Returns

**Type:** System.Boolean

### RemoveAll(Predicate<T>)

```csharp
public int RemoveAll(Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** System.Int32

### RemoveAt(int)

```csharp
public void RemoveAt(int index)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### RemoveRange(int, int)

```csharp
public void RemoveRange(int index, int count)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `count` | `System.Int32` |  |

### Resize(int)

```csharp
public ExposedList<T> Resize(int newSize)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `newSize` | `System.Int32` |  |

#### Returns

**Type:** Spine.ExposedList`1

### Reverse()

```csharp
public void Reverse()
```

### Reverse(int, int)

```csharp
public void Reverse(int index, int count)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `count` | `System.Int32` |  |

### Shift(int, int)

```csharp
private void Shift(int start, int delta)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `start` | `System.Int32` |  |
| `delta` | `System.Int32` |  |

### Sort()

```csharp
public void Sort()
```

### Sort(Comparison<T>)

```csharp
public void Sort(Comparison<T> comparison)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `comparison` | `System.Comparison{{T}}` |  |

### Sort(IComparer<T>)

```csharp
public void Sort(IComparer<T> comparer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `comparer` | `System.Collections.Generic.IComparer{{T}}` |  |

### Sort(int, int, IComparer<T>)

```csharp
public void Sort(int index, int count, IComparer<T> comparer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `count` | `System.Int32` |  |
| `comparer` | `System.Collections.Generic.IComparer{{T}}` |  |

### ToArray()

```csharp
public T[] ToArray()
```

#### Returns

**Type:** {T}[]

### TrimExcess()

```csharp
public void TrimExcess()
```

### TrueForAll(Predicate<T>)

```csharp
public bool TrueForAll(Predicate<T> match)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `match` | `System.Predicate{{T}}` |  |

#### Returns

**Type:** System.Boolean
