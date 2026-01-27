---
uid: Global.FileReadException
canonical_path: /api/Global/Misc/FileReadException
---

# Class FileReadException

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FileReadException : Exception, ISerializable, _Exception
```

Exception through when a file could not be read. Thrown only by [SaveUtil](/api/Global/Misc/SaveUtil).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Exception](https://learn.microsoft.com/dotnet/api/system.exception) → FileReadException

## Implements
[ISerializable](https://learn.microsoft.com/dotnet/api/system.runtime.serialization.iserializable), [_Exception](https://learn.microsoft.com/dotnet/api/system.runtime.interopservices._exception)

## Inherited Members
[trace_ips](https://learn.microsoft.com/dotnet/api/system.exception.trace_ips), [inner_exception](https://learn.microsoft.com/dotnet/api/system.exception.inner_exception), [message](https://learn.microsoft.com/dotnet/api/system.exception.message), [help_link](https://learn.microsoft.com/dotnet/api/system.exception.help_link), [class_name](https://learn.microsoft.com/dotnet/api/system.exception.class_name), [stack_trace](https://learn.microsoft.com/dotnet/api/system.exception.stack_trace), [_remoteStackTraceString](https://learn.microsoft.com/dotnet/api/system.exception._remotestacktracestring), [remote_stack_index](https://learn.microsoft.com/dotnet/api/system.exception.remote_stack_index), [hresult](https://learn.microsoft.com/dotnet/api/system.exception.hresult), [source](https://learn.microsoft.com/dotnet/api/system.exception.source), [_data](https://learn.microsoft.com/dotnet/api/system.exception._data), [SetMessage(string)](https://learn.microsoft.com/dotnet/api/system.exception.setmessage), [SetStackTrace(string)](https://learn.microsoft.com/dotnet/api/system.exception.setstacktrace), [GetBaseException()](https://learn.microsoft.com/dotnet/api/system.exception.getbaseexception), [GetObjectData(SerializationInfo, StreamingContext)](https://learn.microsoft.com/dotnet/api/system.exception.getobjectdata), [FixRemotingException()](https://learn.microsoft.com/dotnet/api/system.exception.fixremotingexception), [GetFullNameForStackTrace(StringBuilder, MethodBase)](https://learn.microsoft.com/dotnet/api/system.exception.getfullnameforstacktrace), [GetType()](https://learn.microsoft.com/dotnet/api/system.exception.gettype), [InnerException](https://learn.microsoft.com/dotnet/api/system.exception.innerexception), [HelpLink](https://learn.microsoft.com/dotnet/api/system.exception.helplink), [HResult](https://learn.microsoft.com/dotnet/api/system.exception.hresult), [ClassName](https://learn.microsoft.com/dotnet/api/system.exception.classname), [Message](https://learn.microsoft.com/dotnet/api/system.exception.message), [Source](https://learn.microsoft.com/dotnet/api/system.exception.source), [StackTrace](https://learn.microsoft.com/dotnet/api/system.exception.stacktrace), [TargetSite](https://learn.microsoft.com/dotnet/api/system.exception.targetsite), [Data](https://learn.microsoft.com/dotnet/api/system.exception.data), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### FileReadException(Exception)

```csharp
public FileReadException(Exception exception)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `exception` | `System.Exception` |  |

## Fields

### basicExceptionInfo

```csharp
private Exception basicExceptionInfo
```
#INC


#### Field Value

**Type:** System.Exception

### fileName

```csharp
public string fileName
```
#INC


#### Field Value

**Type:** System.String

## Methods

### ToString()

```csharp
public override string ToString()
```
#INC
#code-generated


#### Returns

**Type:** System.String
