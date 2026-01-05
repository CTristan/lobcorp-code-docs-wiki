# Class Notice

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Notice
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Notice

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Properties

### instance

```csharp
public static Notice instance { get; }
```

#### Property Value

**Type:** Global.Notice

## Methods

### Observe(string, IObserver)

```csharp
public void Observe(string notice, IObserver observer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `observer` | `Global.IObserver` |  |

### Observe(string, NoticeReciever)

```csharp
public int Observe(string notice, NoticeReciever observer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `observer` | `Global.NoticeReciever` |  |

#### Returns

**Type:** System.Int32

### Remove(string, int)

```csharp
public void Remove(string notice, int noticeId)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `noticeId` | `System.Int32` |  |

### Remove(string, IObserver)

```csharp
public void Remove(string notice, IObserver observer)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `observer` | `Global.IObserver` |  |

### Send(string, params object[])

```csharp
public void Send(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |
