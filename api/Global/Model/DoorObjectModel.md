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

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [ObjectModelBase](/api/Global/Object/ObjectModelBase) → DoorObjectModel

## Inherited Members
[position](/api/Global/Object/ObjectModelBase#position), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### DoorObjectModel(string, string, PassageObjectModel, MapNode)

```csharp
public DoorObjectModel(string id, string type, PassageObjectModel passage, MapNode node)
```

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

#### Field Value

**Type:** System.Single

### closed

```csharp
private bool closed
```

#### Field Value

**Type:** System.Boolean

### connectedDoor

```csharp
private DoorObjectModel connectedDoor
```

#### Field Value

**Type:** Global.DoorObjectModel

### hp

```csharp
public int hp
```

#### Field Value

**Type:** System.Int32

### id

```csharp
private string id
```

#### Field Value

**Type:** System.String

### node

```csharp
public MapNode node
```

#### Field Value

**Type:** Global.MapNode

### openMotion

```csharp
public bool openMotion
```

#### Field Value

**Type:** System.Boolean

### openProgress

```csharp
private float openProgress
```

#### Field Value

**Type:** System.Single

### passage

```csharp
private PassageObjectModel passage
```

#### Field Value

**Type:** Global.PassageObjectModel

### tryOpenCounter

```csharp
private float tryOpenCounter
```

#### Field Value

**Type:** System.Single

### type

```csharp
public string type
```

#### Field Value

**Type:** System.String

## Methods

### Close()

```csharp
public void Close()
```

### Connect(DoorObjectModel)

```csharp
public void Connect(DoorObjectModel door)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `door` | `Global.DoorObjectModel` |  |

### FixedUpdate()

```csharp
public void FixedUpdate()
```

### GetId()

```csharp
public string GetId()
```

#### Returns

**Type:** System.String

### IsClosed()

```csharp
public bool IsClosed()
```

#### Returns

**Type:** System.Boolean

### OnObjectPassed()

```csharp
public void OnObjectPassed()
```

### Open()

```csharp
public void Open()
```

### TryOpen()

```csharp
public void TryOpen()
```
