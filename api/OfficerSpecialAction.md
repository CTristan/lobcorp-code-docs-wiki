# Class OfficerSpecialAction

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OfficerSpecialAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → OfficerSpecialAction

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### OfficerSpecialAction(int, string, int, string)

```csharp
public OfficerSpecialAction(int id, string nodeid, int animVal, string animParam)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |
| `nodeid` | `System.String` |  |
| `animVal` | `System.Int32` |  |
| `animParam` | `System.String` |  |

## Fields

### animParam

```csharp
public string animParam
```

#### Field Value

**Type:** System.String

### animVal

```csharp
public int animVal
```

#### Field Value

**Type:** System.Int32

### id

```csharp
public int id
```

#### Field Value

**Type:** System.Int32

### nodeId

```csharp
public string nodeId
```

#### Field Value

**Type:** System.String

### posData

```csharp
public List<OfficerSpecialAction.PosData> posData
```

#### Field Value

**Type:** System.Collections.Generic.List{OfficerSpecialAction.PosData}

### shouldMove

```csharp
public bool shouldMove
```

#### Field Value

**Type:** System.Boolean

## Methods

### GetNode()

```csharp
public MapNode GetNode()
```

#### Returns

**Type:** Global.MapNode

### GetPos()

```csharp
public OfficerSpecialAction.PosData GetPos()
```

#### Returns

**Type:** Global.OfficerSpecialAction.PosData
