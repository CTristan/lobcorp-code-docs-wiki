---
uid: Global.Notice.CallbackObserver
canonical_path: /api/Global/IOBserver/NoticeCallbackObserver
---

# Class Notice.CallbackObserver

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
private class Notice.CallbackObserver : IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Notice.CallbackObserver

## Implements
[IObserver](/api/Global/Misc/IObserver)

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### CallbackObserver(int, NoticeReciever)

```csharp
public CallbackObserver(int noticeId, NoticeReciever callback)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `noticeId` | `System.Int32` |  |
| `callback` | `Global.NoticeReciever` |  |

## Fields

### callback

```csharp
public NoticeReciever callback
```

#### Field Value

**Type:** Global.NoticeReciever

### noticeId

```csharp
public int noticeId
```

#### Field Value

**Type:** System.Int32

## Methods

### OnNotice(string, params object[])

```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |
