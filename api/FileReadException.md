# Class FileReadException

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FileReadException : Exception, ISerializable, _Exception
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Exception](https://learn.microsoft.com/dotnet/api/system.exception) → FileReadException

## Inherited Members
[GetBaseException()](https://learn.microsoft.com/dotnet/api/system.exception.getbaseexception), [GetObjectData(SerializationInfo, StreamingContext)](https://learn.microsoft.com/dotnet/api/system.exception.getobjectdata), [GetType()](https://learn.microsoft.com/dotnet/api/system.exception.gettype), [InnerException](https://learn.microsoft.com/dotnet/api/system.exception.innerexception), [HelpLink](https://learn.microsoft.com/dotnet/api/system.exception.helplink), [HResult](https://learn.microsoft.com/dotnet/api/system.exception.hresult), [Message](https://learn.microsoft.com/dotnet/api/system.exception.message), [Source](https://learn.microsoft.com/dotnet/api/system.exception.source), [StackTrace](https://learn.microsoft.com/dotnet/api/system.exception.stacktrace), [TargetSite](https://learn.microsoft.com/dotnet/api/system.exception.targetsite), [Data](https://learn.microsoft.com/dotnet/api/system.exception.data), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### FileReadException(Exception)

```csharp
public FileReadException(Exception exception)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `exception` | `System.Exception` |  |

## Fields

### fileName

```csharp
public string fileName
```

#### Field Value

**Type:** System.String

## Methods

### ToString()

```csharp
public override string ToString()
```

#### Returns

**Type:** System.String
