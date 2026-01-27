---
uid: Global.DoorObjectModel
canonical_path: /api/Global/Model/DoorObjectModel
---

# Class DoorObjectModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DoorObjectModel : ObjectModelBase
```
A door between two [rooms](/api/Global/Model/PassageObjectModel).
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [ObjectModelBase](/api/Global/Object/ObjectModelBase) → DoorObjectModel

## Inherited Members
[position](/api/Global/Object/ObjectModelBase#position), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DoorObjectModel(string, string, PassageObjectModel, MapNode)

```csharp
public DoorObjectModel(string id, string type, PassageObjectModel passage, MapNode node)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |
| `type` | `System.String` |  |
| `passage` | `Global.PassageObjectModel` |  |
| `node` | `Global.MapNode` |  |

## Fields

### autoCloseCount

```csharp
private float autoCloseCount
```
#INC


#### Field Value

**Type:** System.Single

### closed

```csharp
private bool closed
```
#INC


#### Field Value

**Type:** System.Boolean

### connectedDoor

```csharp
private DoorObjectModel connectedDoor
```
#INC


#### Field Value

**Type:** Global.DoorObjectModel

### hp

```csharp
public int hp
```
#INC


#### Field Value

**Type:** System.Int32

### id

```csharp
private string id
```
#INC


#### Field Value

**Type:** System.String

### node

```csharp
public MapNode node
```
#INC


#### Field Value

**Type:** Global.MapNode

### openMotion

```csharp
public bool openMotion
```
#INC


#### Field Value

**Type:** System.Boolean

### openProgress

```csharp
private float openProgress
```
#INC


#### Field Value

**Type:** System.Single

### passage

```csharp
private PassageObjectModel passage
```
#INC


#### Field Value

**Type:** Global.PassageObjectModel

### tryOpenCounter

```csharp
private float tryOpenCounter
```
#INC


#### Field Value

**Type:** System.Single

### type

```csharp
public string type
```
#INC


#### Field Value

**Type:** System.String

## Methods

### Close()

```csharp
public void Close()
```
#INC


### Connect(DoorObjectModel)

```csharp
public void Connect(DoorObjectModel door)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `door` | `Global.DoorObjectModel` |  |

### FixedUpdate()

```csharp
public void FixedUpdate()
```
#INC


### GetId()

```csharp
public string GetId()
```
#INC


#### Returns

**Type:** System.String

### IsClosed()

```csharp
public bool IsClosed()
```
#INC


#### Returns

**Type:** System.Boolean

### OnObjectPassed()

```csharp
public void OnObjectPassed()
```
#INC


### Open()

```csharp
public void Open()
```
#INC


### TryOpen()

```csharp
public void TryOpen()
```
#INC

