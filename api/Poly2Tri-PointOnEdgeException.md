# Class PointOnEdgeException

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PointOnEdgeException : NotImplementedException, ISerializable, _Exception
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Exception](https://learn.microsoft.com/dotnet/api/system.exception) → [SystemException](https://learn.microsoft.com/dotnet/api/system.systemexception) → [NotImplementedException](https://learn.microsoft.com/dotnet/api/system.notimplementedexception) → PointOnEdgeException

## Inherited Members
[GetBaseException()](https://learn.microsoft.com/dotnet/api/system.exception.getbaseexception), [GetObjectData(SerializationInfo, StreamingContext)](https://learn.microsoft.com/dotnet/api/system.exception.getobjectdata), [ToString()](https://learn.microsoft.com/dotnet/api/system.exception.tostring), [GetType()](https://learn.microsoft.com/dotnet/api/system.exception.gettype), [InnerException](https://learn.microsoft.com/dotnet/api/system.exception.innerexception), [HelpLink](https://learn.microsoft.com/dotnet/api/system.exception.helplink), [HResult](https://learn.microsoft.com/dotnet/api/system.exception.hresult), [Message](https://learn.microsoft.com/dotnet/api/system.exception.message), [Source](https://learn.microsoft.com/dotnet/api/system.exception.source), [StackTrace](https://learn.microsoft.com/dotnet/api/system.exception.stacktrace), [TargetSite](https://learn.microsoft.com/dotnet/api/system.exception.targetsite), [Data](https://learn.microsoft.com/dotnet/api/system.exception.data), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### PointOnEdgeException(string, TriangulationPoint, TriangulationPoint, TriangulationPoint)

```csharp
public PointOnEdgeException(string message, TriangulationPoint a, TriangulationPoint b, TriangulationPoint c)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `message` | `System.String` |  |
| `a` | `Poly2Tri.TriangulationPoint` |  |
| `b` | `Poly2Tri.TriangulationPoint` |  |
| `c` | `Poly2Tri.TriangulationPoint` |  |

## Fields

### A

```csharp
public readonly TriangulationPoint A
```

#### Field Value

**Type:** Poly2Tri.TriangulationPoint

### B

```csharp
public readonly TriangulationPoint B
```

#### Field Value

**Type:** Poly2Tri.TriangulationPoint

### C

```csharp
public readonly TriangulationPoint C
```

#### Field Value

**Type:** Poly2Tri.TriangulationPoint
