---
uid: Global.Notice
canonical_path: /api/Global/Misc/Notice
---

# Class Notice

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Notice
```
Class for registering, de-registering, and notifying [observers](/api/Global/Misc/IObserver) of various kinds.



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Notice

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### Notice()

```csharp
private Notice()
```
#INC
#code-generated


## Fields

### _instance

```csharp
private static Notice _instance
```
#INC


#### Field Value

**Type:** Global.Notice

### lastNoticeId

```csharp
private int lastNoticeId
```
#INC


#### Field Value

**Type:** System.Int32

### noticeList

```csharp
private Dictionary<string, List<IObserver>> noticeList
```
#INC


#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{IObserver}}

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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `observer` | `Global.IObserver` |  |

### Observe(string, NoticeReciever)

```csharp
public int Observe(string notice, NoticeReciever observer)
```
#INC


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
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `noticeId` | `System.Int32` |  |

### Remove(string, IObserver)

```csharp
public void Remove(string notice, IObserver observer)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `observer` | `Global.IObserver` |  |

### Send(string, params object[])

```csharp
public void Send(string notice, params object[] param)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |
