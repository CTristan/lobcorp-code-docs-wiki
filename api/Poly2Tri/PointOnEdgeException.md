---
uid: Poly2Tri.PointOnEdgeException
canonical_path: /api/Poly2Tri/PointOnEdgeException
---

# Class PointOnEdgeException

**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PointOnEdgeException : NotImplementedException, ISerializable, _Exception
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Exception](https://learn.microsoft.com/dotnet/api/system.exception) → [SystemException](https://learn.microsoft.com/dotnet/api/system.systemexception) → [NotImplementedException](https://learn.microsoft.com/dotnet/api/system.notimplementedexception) → PointOnEdgeException

## Implements
[ISerializable](https://learn.microsoft.com/dotnet/api/system.runtime.serialization.iserializable), [_Exception](https://learn.microsoft.com/dotnet/api/system.runtime.interopservices._exception)

## Inherited Members
[Result](https://learn.microsoft.com/dotnet/api/system.notimplementedexception.result), [trace_ips](https://learn.microsoft.com/dotnet/api/system.exception.trace_ips), [inner_exception](https://learn.microsoft.com/dotnet/api/system.exception.inner_exception), [message](https://learn.microsoft.com/dotnet/api/system.exception.message), [help_link](https://learn.microsoft.com/dotnet/api/system.exception.help_link), [class_name](https://learn.microsoft.com/dotnet/api/system.exception.class_name), [stack_trace](https://learn.microsoft.com/dotnet/api/system.exception.stack_trace), [_remoteStackTraceString](https://learn.microsoft.com/dotnet/api/system.exception._remotestacktracestring), [remote_stack_index](https://learn.microsoft.com/dotnet/api/system.exception.remote_stack_index), [hresult](https://learn.microsoft.com/dotnet/api/system.exception.hresult), [source](https://learn.microsoft.com/dotnet/api/system.exception.source), [_data](https://learn.microsoft.com/dotnet/api/system.exception._data), [SetMessage(string)](https://learn.microsoft.com/dotnet/api/system.exception.setmessage), [SetStackTrace(string)](https://learn.microsoft.com/dotnet/api/system.exception.setstacktrace), [GetBaseException()](https://learn.microsoft.com/dotnet/api/system.exception.getbaseexception), [GetObjectData(SerializationInfo, StreamingContext)](https://learn.microsoft.com/dotnet/api/system.exception.getobjectdata), [ToString()](https://learn.microsoft.com/dotnet/api/system.exception.tostring), [FixRemotingException()](https://learn.microsoft.com/dotnet/api/system.exception.fixremotingexception), [GetFullNameForStackTrace(StringBuilder, MethodBase)](https://learn.microsoft.com/dotnet/api/system.exception.getfullnameforstacktrace), [GetType()](https://learn.microsoft.com/dotnet/api/system.exception.gettype), [InnerException](https://learn.microsoft.com/dotnet/api/system.exception.innerexception), [HelpLink](https://learn.microsoft.com/dotnet/api/system.exception.helplink), [HResult](https://learn.microsoft.com/dotnet/api/system.exception.hresult), [ClassName](https://learn.microsoft.com/dotnet/api/system.exception.classname), [Message](https://learn.microsoft.com/dotnet/api/system.exception.message), [Source](https://learn.microsoft.com/dotnet/api/system.exception.source), [StackTrace](https://learn.microsoft.com/dotnet/api/system.exception.stacktrace), [TargetSite](https://learn.microsoft.com/dotnet/api/system.exception.targetsite), [Data](https://learn.microsoft.com/dotnet/api/system.exception.data), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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
