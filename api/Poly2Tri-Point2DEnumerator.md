# Class Point2DEnumerator

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Point2DEnumerator : IEnumerator<Point2D>, IEnumerator, IDisposable
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Point2DEnumerator

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### Point2DEnumerator(IList<Point2D>)

```csharp
public Point2DEnumerator(IList<Point2D> points)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `points` | `System.Collections.Generic.IList{Poly2Tri.Point2D}` |  |

## Fields

### mPoints

```csharp
protected IList<Point2D> mPoints
```

#### Field Value

**Type:** System.Collections.Generic.IList{Poly2Tri.Point2D}

### position

```csharp
protected int position
```

#### Field Value

**Type:** System.Int32

## Properties

### Current

```csharp
public Point2D Current { get; }
```

#### Property Value

**Type:** Poly2Tri.Point2D

## Methods

### MoveNext()

```csharp
public bool MoveNext()
```

#### Returns

**Type:** System.Boolean

### Reset()

```csharp
public void Reset()
```
