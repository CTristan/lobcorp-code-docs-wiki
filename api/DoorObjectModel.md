# Class DoorObjectModel

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DoorObjectModel : ObjectModelBase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [ObjectModelBase](/api/ObjectModelBase) → DoorObjectModel

## Inherited Members
[position](/api/ObjectModelBase#position), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

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

### hp

```csharp
public int hp
```

#### Field Value

**Type:** System.Int32

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
